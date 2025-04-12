# Home Headquarters Launcher


# HHQ Launcher

A cross-platform launcher for PlayStation Home on RPCS3 emulator.

## Features

- Launch PlayStation Home in both online and offline modes
- Browse the item catalogue
- View announcements and events
- Customizable theme with accent colors
- Cross-platform support for Windows and Linux

## Installation

### Windows

1. Download the latest release from the releases page
2. Extract the ZIP file to your preferred location
3. Run `HHQ_Launcher.exe`

### Linux

1. Download the latest release from the releases page
2. Extract the archive to your preferred location
3. Make the launcher executable:
   ```bash
   chmod +x HHQ_Launcher
   ```
4. Run the launcher:
   ```bash
   ./HHQ_Launcher
   ```

## Configuration

### Path Settings

The launcher needs to know where your RPCS3 executable and game files are located:

- **RPCS3 Path**: Path to the RPCS3 executable
- **Offline Game Path**: Path to the offline version of PlayStation Home
- **Online Game Path**: Path to the online version of PlayStation Home
- **Postinstall.sql Path**: Path to the postinstall.sql file 

### Default Paths

#### Windows
- RPCS3: `F:\PSHomeStuff\RPCS3\rpcs3.exe`
- Offline Game: `C:\psh_devhdd0\dev_hdd0\GAME\NPIA00010`
- Online Game: `F:\PSHomeStuff\RPCS3\dev_hdd0\game\NPIA00005`

#### Linux
- RPCS3: `~/.config/rpcs3/rpcs3`
- Offline Game: `~/.config/rpcs3/dev_hdd0/GAME/NPIA00010`
- Online Game: `~/.config/rpcs3/dev_hdd0/game/NPIA00005`

## Building from Source

### Prerequisites

- Python 3.8 or higher
- PyInstaller
- Required Python packages (install with `pip install -r requirements.txt`)

### Building

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the build script:
   ```bash
   python build.py
   ```
4. The executable will be created in the `dist` directory

## Troubleshooting

### Windows

- If the launcher fails to start RPCS3, try running it with administrator privileges
- Make sure all paths in the settings are correct

### Linux

- If the launcher can't find the font, it will fall back to Arial
- If RPCS3 fails to start, make sure it has executable permissions:
  ```bash
  chmod +x /path/to/rpcs3
  ```
- You may need to run with sudo if RPCS3 requires elevated permissions

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
