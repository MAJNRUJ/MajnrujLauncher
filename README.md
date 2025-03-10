<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/program_info/cz.majnruj.MajnrujLauncher.logo-darkmode.svg">
  <source media="(prefers-color-scheme: light)" srcset="/program_info/cz.majnruj.MajnrujLauncher.logo.svg">
  <img alt="MAJNRUJ Launcher" src="/program_info/cz.majnruj.MajnrujLauncher.logo.svg" width="40%">
</picture>
</p>

<p align="center">
  MAJNRUJ Launcher is a custom launcher for Minecraft that is (not yet) tailored for MAJNRUJ network.<br />
  <br />This is a <b>fork</b> of the Prism Launcher and is <b>not</b> endorsed by it.
</p>

## Disclaimer
There are no plans to deviate from Prism Launcher, so we will still be pulling commits from them. You can use their wiki, etc. It will not become obsolete.<br />
<br />
This project is not ready yet and it will take a while. You should wait for non-pre-release build. Pre-release builds are highly unstable (You can't even connect your Microsoft account now, until we get access to Minecraft Auth, if we ever get it.). <br />
<br />
For testing purposes and no access to Minecraft Auth you can create offline account, even when verified account is not present. **Piracy will not be tolerated, buy the game.**

## Installation

- Grab suitable distributon from [Releases](https://github.com/MAJNRUJ/MajnrujLauncher/releases). 
  > If you're unsure which one to choose, then you are probably using Windows on amd64 (x86_64) architecture. In that case, download: **MajnrujLauncher-Windows-MSVC-Setup-xxx.exe**
- Last build status can be found in the [GitHub Actions](https://github.com/MAJNRUJ/MajnrujLauncher/actions) tab.

## Community & Support

Feel free to create a GitHub issue if you find a bug or want to suggest a new feature. We have multiple community spaces where other community members can help you:

- **Our Discord server:**

[![Prism Launcher Discord server](https://discordapp.com/api/guilds/792768473964740608/widget.png?style=banner3)](https://discord.gg/K8Tt5F5STH)
## Translations

The translation effort for Prism Launcher is hosted on [Weblate](https://hosted.weblate.org/projects/prismlauncher/launcher/) and information about translating Prism Launcher is available at <https://github.com/PrismLauncher/Translations>.

**Even though this is a fork, translations are still relevant. We are not planning to deviate from Prism Launcher.**

## Building

If you want to build MAJNRUJ Launcher yourself, you are free to follow Prism Launcher's build instructions:

- [Windows](https://prismlauncher.org/wiki/development/build-instructions/windows/)
- [Linux](https://prismlauncher.org/wiki/development/build-instructions/linux/)
- [MacOS](https://prismlauncher.org/wiki/development/build-instructions/macos/)
- [OpenBSD](https://prismlauncher.org/wiki/development/build-instructions/openbsd/)

## Thank you, Prism Launcher

Let's take a moment to thank everyone who contributed in any way to the development of Prism Launcher and made their work available to everyone. <br />This launcher wouldn't come to life without their efforts, support them -> [Become Prism Launcher's backer](https://opencollective.com/prismlauncher).

## Forking/Redistributing/Custom builds policy

You are free to fork, redistribute and provide custom builds as long as you follow the terms of the [license](LICENSE) (this is a legal responsibility), and if you made code changes rather than just packaging a custom build, please do the following as a basic courtesy:

- Make it clear that your fork is not MAJNRUJ Launcher and is not endorsed by or affiliated with the MAJNRUJ Launcher project (<https://majnruj.cz/launcher>).
- Go through [CMakeLists.txt](CMakeLists.txt) and change MAJNRUJ Launcher's API keys to your own or set them to empty strings (`""`) to disable them (this way the program will still compile but the functionality requiring those keys will be disabled).

If you have any questions or want any clarification on the above conditions please make an issue and ask us.

If you are just building MAJNRUJ Launcher for your distribution, please make sure to set the `Launcher_BUILD_PLATFORM` to a slug representing your distribution. Examples are `archlinux`, `fedora` and `nixpkgs`.

Note that if you build this software without removing the provided API keys in [CMakeLists.txt](CMakeLists.txt) you are accepting the following terms and conditions:

- [Microsoft Identity Platform Terms of Use](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
- [CurseForge 3rd Party API Terms and Conditions](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

If you do not agree with these terms and conditions, then remove the associated API keys from the [CMakeLists.txt](CMakeLists.txt) file by setting them to an empty string (`""`).

## License [![https://github.com/MAJNRUJ/MajnrujLauncher/blob/develop/LICENSE](https://img.shields.io/github/license/MAJNRUJ/MajnrujLauncher?label=License&logo=gnu&color=C4282D)](LICENSE)

All launcher code is available under the GPL-3.0-only license.

The logo and related assets are under the CC BY-SA 4.0 license.
