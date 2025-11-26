# VTAB - Visual Test Automation Builder

**Public Release Repository**

This repository contains public releases of VTAB (Visual Test Automation Builder), a visual test automation tool for creating automated UI tests through a node-based interface.

## Download Latest Release

Visit the [Releases](../../releases) page to download the latest version of VTAB.

## What is VTAB?

VTAB is a powerful visual test automation tool that allows you to create automated UI tests without writing code. Using a drag-and-drop node-based interface, you can build complex test workflows visually.

### Key Features

- **Visual Node-Based Editor**: Create tests by connecting nodes on an infinite canvas
- **Computer Vision**: Detect and interact with UI elements using image matching
- **AI-Powered Verification**: Use GPT-4o Vision for intelligent text verification
- **Real-Time Execution**: Run tests and see results immediately
- **Professional Reports**: Generate detailed HTML execution reports
- **Dark Theme Interface**: Modern, eye-friendly UI

## Installation

1. Download the latest `VTAB_Setup.exe` from the [Releases](../../releases) page
2. Run the installer
3. Follow the installation wizard
4. Launch VTAB from the Start Menu

### System Requirements

- **OS**: Windows 10 or Windows 11 (64-bit)
- **RAM**: 4 GB minimum, 8 GB recommended
- **Disk Space**: 500 MB
- **Display**: 1280x720 minimum resolution

## Getting Started

1. Launch VTAB
2. Create a new project
3. Drag nodes from the Node Library onto the canvas
4. Connect nodes to create your test flow
5. Click Execute to run your test

## Security & Verification

All releases include SHA256 checksums for verification. To verify your download:

**PowerShell:**
```powershell
Get-FileHash VTAB_Setup.exe -Algorithm SHA256
```

**Command Prompt:**
```cmd
certutil -hashfile VTAB_Setup.exe SHA256
```

Compare the output with the `.sha256` file included in the release.

## Release Notes

Each release includes:
- Installer executable (VTAB_Setup.exe)
- SHA256 checksum file
- README with installation instructions
- Release notes describing changes

## Support

For questions, issues, or feature requests, please open an issue in this repository.

## License

See the LICENSE file included with each release for licensing information.

## About This Repository

This is a **public release-only repository**. The source code is maintained in a private repository. This repository exists solely to provide public access to VTAB releases while keeping the source code private.

Releases are automatically copied from the private repository to this public repository when published.

---

**Note**: This repository does not contain source code. For security and support inquiries, please use the Issues tab.
