# windows-setup

How do I setup my Windows

## Prerequisites

You must be running Windows 10 version 2004 and higher (Build 19041 and higher) or Windows 11.

> **Note**\
> To check you Windows version and build number, press <kbd>Win + R</kbd>, type `winver`, select **OK**. You can update to the latest Windows version by selecting **Start** > **Settings** > **Windows Update** > **Check for updates**.

If you're running an older build, or just prefer not to use the install command and would like step-by-step directions, see [WSL manual installation steps for older versions](https://docs.microsoft.com/en-us/windows/wsl/install-manual).

## Essential tools and configurations

_Please follow these steps below in order._

### Windows Terminal

Install the [Windows Terminal from the Microsoft Store](https://aka.ms/terminal). This allows you to always be on the latest version when we release new builds with automatic upgrades.

### Windows Subsystem for Linux (WSL)

Install the [Ubuntu from the Microsoft Store](https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV).

Ubuntu is always the latest LTS version of Ubuntu. When new LTS versions are released, Ubuntu can be upgraded from the command line by using:

```sh
sudo do-release-upgrade
```

## License

CC0-1.0
