# XanFetch

XanFetch is a command-line system information utility for Windows written in PowerShell.

![XanFetch](https://github.com/xanmoy/xanfetch/blob/main/assets/xanfetch.png)

## Overview

XanFetch provides an easy way to gather system information on Windows systems directly from the command line. It displays various details about the system, including OS version, CPU, GPU, memory usage, disk usage, network status, and more.

## Features

- Displays system information such as OS version, CPU, GPU, memory usage, etc.
- Option to display a pixelated image of the XanFetch logo.
- Ability to download a configuration template.
- Support for displaying information without any image or logo.
- Detailed help message available for reference.

## Usage

XanFetch can be used with various options:

- `-image`: Display a pixelated image instead of the usual logo. (Imagemagick required)
- `-genconf`: Download a configuration template. (Internet connection required)
- `-noimage`: Do not display any image or logo; display information only.
- `-help`: Display help message.

## Requirements

- PowerShell 5+
- Imagemagick (optional, required for image display)

## Installation

1. Clone or download the XanFetch repository.
2. Ensure PowerShell 5+ is installed on your system.
3. Optionally, install Imagemagick if you want to display the pixelated image.

## Usage Example

```powershell
# Display system information with the XanFetch logo
.\XanFetch.ps1

# Display system information without the logo
.\XanFetch.ps1 -noimage

# Download a configuration template
.\XanFetch.ps1 -genconf

## Credits

- **Author:** [xanmoy](https://github.com/xanmoy)
- **Project URL:** [https://github.com/xanmoy/xanfetch](https://github.com/xanmoy/xanfetch)

## License

This project is licensed under the [MIT License](LICENSE).


This README.md now includes the License and Credit sections. Feel free to use it for your project!
