# [WIP] Linsama's OpenWrt Build

This repository contains the configurations and workflows for building custom OpenWrt firmware for x86 and Raspberry Pi 3 platforms. It includes integrations for various packages like Passwall2 and UU Game Booster.

## Structure

- `/.github/workflows/` - Contains GitHub Actions workflows for automated builds.
- `/config/` - Custom configuration files, including the `.config` file for OpenWrt builds.
- `/files/` - Additional files for the firmware.
- `/patches/` - Patches for the OpenWrt source.

## Building

The build process is automated using GitHub Actions. Pushes or merges to the main branch trigger the workflow.

## Custom Configuration

- The `.config` file in the `/config/` directory specifies the packages and settings for the build.
- Update this file to change the build configuration.

## Contributions

Contributions are welcome. Please submit pull requests with a detailed description of your changes or enhancements.

## License

MIT License
