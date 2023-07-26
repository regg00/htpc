![Stack](/.eraser/xfMkifrLBtIdyb8BkUnb___t2NVDJhO8DYC2968H5wuLk8FNe52___---figure---jdFwSpgYTMGO9mFR8dhfW---figure---p3XwtDueP8KcS-dOOeLCzg.png "Stack")

<img src="./docs/icon.png" height="200">

# htpc

A HTPC stack built with docker-compose

## Why it exists

I got tired of managing multiple HTPC apps. With Docker and Docker Compose, it's easier than ever to create a complete stack or migrate an existing one to a new server.

## Installing this module

This module is available in [PowerShell Gallery](https://www.powershellgallery.com/packages/PSPsat):

```powershell
PS C:\> Install-Module ChocoMan
```

Or, download it from here and save all of the files somewhere in your `$PSModulePath`.

## Before you start

Before using this package, you need to make sure that Chocolatey is installed on your device.

You can valide this with the `choco --version` command.

```powershell
PS C:\> choco --version
2.1.0
```

You can also install it using this module with the `Install-Choco` command.

```powershell
PS C:\> Install-Choco
Chocolatey v2.1.0 installed
```

## Using the module

First things first, you need to import it `Import-Module ChocoMan`

### Functions

Here's the status of each functions:

| Command                                                    | Status             | Notes                                                                              |
| ---------------------------------------------------------- | ------------------ | ---------------------------------------------------------------------------------- |
| [Get-ChocoApiKey](./Docs/Get-ChocoApiKey.md)               | :white_check_mark: | Retrieves, saves or deletes an API key for a particular source                     |
| [Get-ChocoConfig ](./Docs/Get-ChocoConfig.md)              | :white_check_mark: | Retrieves the chocolatey configuration                                             |
| [Get-ChocoFeature ](./Docs/Get-ChocoFeature.md)            | :white_check_mark: | Retrieves the chocolatey features                                                  |
| [Get-ChocoOutdated](./Docs/Get-ChocoOutdated.md)           | :white_check_mark: | Get the list of outdated chocolatey packages.                                      |
| [Get-ChocoPackage](./Docs/Get-ChocoPackage.md)             | :white_check_mark: | Get a specific locally installed chocolatey package.                               |
| [Get-ChocoSources](./Docs/Get-ChocoSources.md)             | :white_check_mark: | Get the list of chocolatey sources.                                                |
| [Get-ChocoVersion](./Docs/Get-ChocoVersion.md)             | :white_check_mark: | Get the version of chocolatey.                                                     |
| [Set-ChocoApiKey](./Docs/Set-ChocoApikey.md)               | :white_check_mark: | Edit API keys                                                                      |
| [Search-ChocoPackage](./Docs/Search-ChocoPackage.md)       | :white_check_mark: | Search for a chocolatey package.                                                   |
| [Add-ChocoApiKey](./Docs/Set-ChocoApiKey.md)               | :white_check_mark: | Adds a new API. Aliases to Set-ChocoApiKey. keuy                                   |
| [Add-ChocoSource ](./Docs/Add-ChocoSource.md)              | :white_check_mark: | Adds a new chocolatey source                                                       |
| [Install-Choco](./Docs/Install-Choco.md)                   | :white_check_mark: | Install chocolatey.                                                                |
| [Install-ChocoPackage](./Docs/Install-ChocoPackage.md)     | :white_check_mark: | Installs a chocolatey package.                                                     |
| [Uninstall-ChocoPackage](./Docs/Uninstall-ChocoPackage.md) | :white_check_mark: | Uninstalls a chocolatey package.                                                   |
| New-ChocoPackage                                           | :soon:             | Generates files necessary for a chocolatey package from a template                 |
| Build-ChocoPackage                                         | :soon:             | Packages nuspec, scripts, and other Chocolatey package resources into a nupkg file |
| Publish-ChocoPackage                                       | :soon:             | Pushes a compiled nupkg to a source                                                |

## What else can I do?
