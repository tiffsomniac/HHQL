# Home Headquarters Launcher

A cross-platform launcher for PlayStation Home on RPCS3 emulator.

## Features

- Launch PlayStation Home in online mode
- Browse the item catalogue
- View announcements and events
- Customizable theme with accent colors

## Installation

### Windows

1. Download the latest release from the releases page
2. Extract the ZIP file to your preferred location
3. Run `HHQ_Launcher.exe`

## Configuration

### Path Settings

The launcher needs to know where your RPCS3 executable is.

- **RPCS3 Path**: Path to the RPCS3 executable

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

- If RPCS3 fails to start, make sure it has executable permissions:
  ```bash
  chmod +x /path/to/rpcs3
  ```
- You may need to run with sudo if RPCS3 requires elevated permissions

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
