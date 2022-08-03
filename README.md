# My shell dotfiles

Set-up for the Windows PowerShell prompt with [Oh My Posh](https://github.com/JanDeDobbeleer/oh-my-posh) and [Scoop](https://github.com/ScoopInstaller/Scoop).

For a tutorial on how to configure the patched [nerd fonts](https://github.com/ryanoasis/nerd-fonts) and a UNIX-like transparent / acrylic background, check out the [devaslife](https://www.youtube.com/watch?v=5-aK2_WwrmM) YouTube video.

## Content
* Powershell .config
* Bash .config (to be updated)

## How to Use

## PowerShell setup

Scoop installation (for admin installation check out [this](https://github.com/ScoopInstaller/Install#for-admin)):

```
iwr -useb get.scoop.sh | iex
```

Installing Git:

```
winget install -e --id Git.Git
```

Installing Neovim with Scoop:

```
scoop install neovim gcc
```

Setting up the custom profile as the CurrentUserCurrentHost profile (for further details about profile, visit the [Microsoft website](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_profiles?view=powershell-7.2)):

```
vim $PROFILE.CurrentUserCurrentHost
```

Modify the profile adding this command:

```
$env:USERPROFILE\.config\powershell\my_profile.ps1
```

## Bash setup

(to be updated)