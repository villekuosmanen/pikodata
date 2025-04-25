# Pikodata
Data Studio for LeRobot Datasets

Private Beta - expect bugs!

## Installation

### Linux

**AppImage**
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


RPM package (For Fedora/RHEL-based distributions):

Download the latest `pikodata-x.x.x.x86_64.rpm` file
Install using `dnf` or `yum`:
`sudo dnf install ./pikodata-x.x.x.x86_64.rpm`
or
`sudo yum install ./pikodata-x.x.x.x86_64.rpm`

Launch from your applications menu or run pikodata in terminal



macOS

Download the latest `Pikodata-x.x.x.dmg` file from the releases page
Open the DMG file
Drag the Pikodata icon to the Applications folder
Close the DMG window
Open Pikodata from your Applications folder
On first launch, you may need to right-click the app and select "Open" to bypass macOS security warnings

Troubleshooting on macOS
If you see "App is damaged and can't be opened" message:

Open System Preferences → Security & Privacy
Click the "Open Anyway" button that appears
If the button doesn't appear, try running: `xattr -cr /Applications/Pikodata.app` in Terminal
