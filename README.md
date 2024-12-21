# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.# Audio Profile Toggle Script

A bash script to automatically toggle between audio output profiles (Duplex/Output) on system startup and reboot.

## Features

- Toggle between Duplex and Output audio profiles
- Enable/disable automatic toggling on system startup
- Enable/disable automatic toggling on system reboot
- Verification of profile changes
- Detailed status messages and error handling

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audio-profile-toggle
```

2. Make the script executable:
```bash
chmod +x toggle-audio-profile.sh
```

3. (Optional) Move the script to a directory in your PATH:
```bash
sudo cp toggle-audio-profile.sh /usr/local/bin/toggle-audio-profile
```

## Usage

### Basic Usage
```bash
./toggle-audio-profile.sh
```
This will toggle between Duplex and Output profiles once.

### Enable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -s
```

- For reboot only:
```bash
./toggle-audio-profile.sh -r
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -sr
```

### Disable Auto-toggle
- For startup only:
```bash
./toggle-audio-profile.sh -es
```

- For reboot only:
```bash
./toggle-audio-profile.sh -er
```

- For both startup and reboot:
```bash
./toggle-audio-profile.sh -esr
```

### Help
```bash
./toggle-audio-profile.sh -h
```

## Troubleshooting

If the script isn't working as expected:

1. Check the systemd service status:
```bash
systemctl --user status toggle-audio.service
```

2. Check the current audio profile:
```bash
pactl list cards | grep -A10 "Card #46"
```

3. Verify the autostart files:
```bash
ls -l ~/.config/systemd/user/toggle-audio.service
ls -l ~/.config/autostart/toggle-audio.desktop
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.
