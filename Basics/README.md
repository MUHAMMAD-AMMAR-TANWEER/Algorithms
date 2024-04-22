# Installing and Troubleshooting Go 1.22

### Installation on Windows:

1. Download the Go installer for Windows from [here](https://go.dev/dl/go1.22.2.windows-amd64.msi).
2. Once the MSI file is downloaded, double-click on it to run the installer.
3. Follow the on-screen instructions in the installer wizard.
4. Choose the installation location and click "Install" to begin the installation process.
5. After installation is complete, you can verify the installation by opening a command prompt or terminal.

### Verifying Installation

To check if Go is installed properly, follow these steps:

1. Open Command Prompt or PowerShell.
2. Type the following command

`go version`

You will see the following output.

`go version go1.22.2 windows/amd64`

## Installation on macOS

1. Download the Go installer for macOS from the [here](https://go.dev/dl/go1.22.2.darwin-amd64.pkg).
2. Open the package file you downloaded and follow the prompts to install Go.
3. The package installs the Go distribution to `/usr/local/go`.
4. The package should automatically add the `/usr/local/go/bin` directory to your PATH environment variable. If not, you may need to add it manually.
5. Restart any open Terminal sessions for the changes to take effect.

## Verifying Installation

To check if Go is installed properly, follow these steps:

1. Open Terminal.
2. Type the following command:

`go version`

You will see the something like below.

` go version go1.22.2 darwin/amd64`
