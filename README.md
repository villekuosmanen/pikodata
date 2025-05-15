# Pikodata
Data Studio for LeRobot Datasets

[Join the Discord!](https://discord.gg/8QvvCpQtJq)

Private Beta - expect bugs!

Known issues:
1. Not optimised for first render - if it needs to download datasets locally (datasets stored in default LeRobot directory, `~/.cache/huggingface/lerobot` on Linux the app looks like it has frozen even though it is waiting for data to load. I recommend downloading the datasets you use to the cache first, or using very fast internet.
2. Deleting frames takes a long time - be patient while it loads!
2. Deleting frames won't work without an `ffmpeg` installation.

## Installation

You will need to have `ffmpeg` and the `libsvtav1` encoder available.

### Linux

You will need to start Pikodata from the command line with a compatible `ffmpeg` installation. I suggest using an existing LeRobot conda environment.
```
conda activate lerobot
pikodata
```
or
```
conda create -n pikodata python=3.10
conda activate pikodata
conda install ffmpeg -c conda-forge
pikodata
```

**AppImage** (currently not available as the file is too large to upload on github)
- Download the latest `Pikodata-x.x.x.AppImage` file from the releases page
- Make it executable: `chmod +x Pikodata-x.x.x.AppImage`
- Run it directly: `./Pikodata-x.x.x.AppImage`
- Optionally, move it to a location in your `PATH` for easier access


**DEB package** (For Debian/Ubuntu-based distributions):

Download the latest `pikodata_x.x.x_amd64.deb` file
Install using `apt`:
`sudo apt install ./pikodata_x.x.x_amd64.deb`
or `dpkg`
`sudo dpkg -i ./pikodata_x.x.x_amd64.deb`

Launch from your applications menu or run pikodata in terminal


**RPM package** (For Fedora/RHEL-based distributions):

Download the latest `pikodata-x.x.x.x86_64.rpm` file
Install using `dnf` or `yum`:
`sudo dnf install ./pikodata-x.x.x.x86_64.rpm`
or
`sudo yum install ./pikodata-x.x.x.x86_64.rpm`

Launch from your applications menu or run pikodata in terminal

### MacOS

First install `ffmpeg`:
```
brew install ffmpeg 
```

- Download the latest `Pikodata-x.x.x.dmg` file from the releases page.
  - For Apple Silicon (M1 processor and above) download the `arm64.dmg` version. 
- Open the DMG file
- Drag the Pikodata icon to the Applications folder
- Close the DMG window
- Open Pikodata from your Applications folder
