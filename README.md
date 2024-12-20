# PulseAudio Profile Toggle

A simple bash script to toggle between PulseAudio audio profiles. This script helps fix audio lag issues in Linux by switching between Analog Stereo Duplex and Analog Stereo Output profiles.

## Problem it Solves

Sometimes in Linux, YouTube videos may lag when using certain audio profiles. This script provides a quick way to toggle between:
- Analog Stereo Duplex
- Analog Stereo Output

## Prerequisites

Make sure you have the following installed:
```bash
sudo pacman -S pulseaudio pavucontrol
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/pulseaudio-profile-toggle.git
```

2. Make the script executable:
```bash
chmod +x toggle-audio
```

3. Move the script to your bin directory:
```bash
mv toggle-audio ~/bin/
```

## Usage

Just run the command from anywhere in your terminal:
```bash
toggle-audio
```

The script will:
1. Detect your current audio profile
2. Toggle between Analog Stereo Duplex and Analog Stereo Output
3. Display the change it made

## Output Example

```bash
Detected current profile: 'output:analog-stereo+input:analog-stereo'
Switching from Duplex to Output...
Switched to Analog Stereo Output
```

## Troubleshooting

If you encounter any issues:

1. Make sure PulseAudio is running:
```bash
pulseaudio --check
```

2. Check your sound card:
```bash
pactl list cards short
```

3. Verify PulseAudio profiles:
```bash
pactl list cards | grep -A50 "Active Profile:"
```

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
