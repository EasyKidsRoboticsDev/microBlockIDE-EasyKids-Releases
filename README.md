# microBlock IDE EasyKids Releases

[Download installers](https://github.com/EasyKidsRoboticsDev/microBlockIDE-EasyKids-Releases/releases) | [Build status](https://github.com/EasyKidsRoboticsDev/microBlockIDE-EasyKids-Releases/actions)

The workflow checks for new application versions hourly and publishes Windows installers and unsigned Intel/Apple Silicon macOS DMGs with automatic update metadata.

## Initial setup required

The source repository is private. Source checkout is configured with SOURCE_READ_KEY, a dedicated read-only SSH deploy key limited to the source repository. Unsigned macOS DMGs are built automatically without Apple certificates and installed manually. Optional signed macOS automatic updates require Apple signing/notarization secrets and MACOS_RELEASE_ENABLED=true.

Maintainers: see [the setup guide in the private source repository](https://github.com/EasyKidsRoboticsDev/microBlockIDE-EasyKids-Edition-Online/blob/main/DESKTOP-RELEASES.md). No access tokens belong in the installed app.
