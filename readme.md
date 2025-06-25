# Realme GT7 Pro Speed Kernel Manifest

This repository contains the kernel manifest files for the Realme GT7 Pro Speed device.

## Overview

The manifest file (realme_GT7pro-Speed.xml) defines the required Git repositories and their specific revisions needed to build the kernel for the Realme GT7 Pro Speed device.

## Structure

- `realme_GT7pro-Speed.xml`: Main manifest file that contains repository references and project configurations

## Usage

1. Initialize repo:
```bash
repo init -u https://github.com/your-repo/kernel_manifest -b master
```

2. Sync the repositories:
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

## License

This project follows the licensing terms of the original kernel source code and included components.
