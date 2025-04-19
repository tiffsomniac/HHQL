
![image](https://github.com/user-attachments/assets/265c6b78-99ad-42cf-9eb5-393f62dac68f)

 Home Headquarters Launcher

A dedicated launcher for PlayStation Home that simplifies RPCS3 / Home Headquarters setup.
##

##  Key Features

 Game Management
- Quickly open RPCS3 and Home Headquarters in the press of a button 
- RPCS3 Configuration Assistance
- Firmware Auto Installation 
- Input Handler Configuration (DualSense, DualShock 4, XInput, Keyboard)

### Content Discovery
- Item catalogue
- Event announcements 
- News updates
- Player count 
- Event calendar

### Customization
- Favorite Color Setting

### System Features
- Update notifications
- Automatic path detection
- Error handling

## 🚀 Getting Started

### Windows Installation
1. Download the latest release from the [releases page](https://github.com/tiffsomniac/HHQL/releases)
2. Extract the ZIP file to your preferred location
3. Run `HHQLauncher.exe`

### Linux Installation
1. Download the latest release
2. Extract the archive
3. Make executable: `chmod +x HHQLauncher`
4. Run: `./HHQLauncher`

## ⚙️ Configuration

### Needs to be done outside of launcher
- RPCN Account Creation
- RPCS3 Custom Input Binds (for now)

### Default Locations

#### Windows
```
RPCS3: C:\RPCS3\rpcs3.exe
Game: C:\RPCS3\dev_hdd0\game\NPIA00005
```

#### Linux
```
RPCS3: ~/.config/rpcs3/rpcs3
Game: ~/.config/rpcs3/dev_hdd0/game/NPIA00005
```

## 🛠️ Development

### Prerequisites
- Python 3.8+
- Required packages: `pip install -r requirements.txt`

### Building from Source
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run build script: `python build.py`
4. Find executable in `dist` directory

## 🔍 Troubleshooting

### Common Solutions
- Run as administrator for path-related issues
- Check RPCS3 configuration if game fails to launch
- Ensure you have a valid RPCN account in the launcher via Network settings
- Verify firmware installation if experiencing black screens
- Ensure correct input handler is selected 

### Linux-Specific
- Set executable permissions: `chmod +x /path/to/rpcs3`
- May require sudo for certain operations

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
