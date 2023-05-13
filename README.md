# Broadcom Wireless Driver Installation Script

This Bash script automates the process of removing the `broadcom-wl` package and setting up the necessary configuration files for installing the Broadcom wireless driver on Arch Linux or Arch-based distributions like Manjaro. It performs the following actions:

- Removes existing `broadcom-wl` package.
- Creates and edits the `broadcom-wl-dkms.conf` file with the required blacklist entries.
- Installs `linux-headers` and `broadcom-wl-dkms` packages.
- Regenerates the initramfs.

## Prerequisites

- Arch Linux or Arch-based distribution (e.g., Manjaro).
- `pacman` package manager.
- Administrative (root) privileges.

## Usage

1. Clone or download this repository.

2. Open a terminal and navigate to the repository directory.

3. Make the script executable by running the following command:

    **chmod +x broadcom-wl-setup.sh**

4. Run the script with root privileges:

    **sudo ./broadcom-wl-setup.sh**

Please ensure that you understand the script and its implications before running it. Review the script contents and modify it if necessary to fit your specific requirements or system configuration.

## License

This script is provided under the [MIT License](LICENSE).

Feel free to contribute to this repository by submitting pull requests or opening issues if you encounter any problems.
