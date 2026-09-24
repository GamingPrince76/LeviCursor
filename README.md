LeviCursor

Introduction

LeviCursor is a native mouse-cursor mod for Minecraft Bedrock on Android, made for "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid).

It provides a customizable cursor for Minecraft when using a mouse through LeviLauncher, replacing the default cursor appearance with a custom cursor image.

LeviCursor is distributed as a ready-to-install ".levipack" package through GitHub Releases.

Features

- Custom mouse cursor for Minecraft Bedrock
- Native Android mod built for LeviLauncher
- ARM64 ("arm64-v8a") support
- Custom cursor image
- Configurable cursor hotspot
- Simple ".levipack" installation
- Lightweight and focused on cursor customization

System Requirements

- Android 9 or newer
- 64-bit ARM device ("arm64-v8a")
- "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid)
- A compatible Minecraft Bedrock version

Compatibility

The current release targets:

- Minecraft Bedrock: "1.26.5X.X"
- Architecture: "arm64-v8a"
- Platform: Android
- Launcher: LeviLauncher

Minecraft compatibility can vary between releases. Check the release information before installing an older or newer version.

Installation

1. Install "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid).
2. Download the latest "LeviCursor.levipack" from the "Releases" (../../releases) page.
3. Import the ".levipack" through LeviLauncher's mod manager.
4. Enable LeviCursor.
5. Launch Minecraft through LeviLauncher.

Once enabled, LeviCursor applies the custom cursor when the Minecraft activity is running.

Configuration

LeviCursor includes a cursor configuration file:

{
  "cursor": "arrow.png",
  "hotspot_x": 2,
  "hotspot_y": 2
}

Configuration options

Option| Description
"cursor"| Cursor image used by LeviCursor
"hotspot_x"| Horizontal cursor hotspot
"hotspot_y"| Vertical cursor hotspot

The hotspot determines which point of the cursor image is treated as the actual pointer position.

Releases

The latest version is available from the GitHub Releases page:

"Download LeviCursor" (../../releases/latest)

Current release:

v0.1.0

Package:

levicursor-0.1.0-arm64-v8a.levipack

Project Structure

The distributed package contains the files required by LeviLauncher to load LeviCursor, including the native library, manifest, resources, and configuration.

The development source is maintained separately and is not included in the public distribution repository.

Usage Guidelines

LeviCursor is intended for use with Minecraft Bedrock through LeviLauncher.

Do not use LeviCursor or LeviLauncher to violate Mojang or Microsoft's user agreements.

Disclaimer: LeviCursor, its author, and contributors are not responsible for bans, damages, data loss, or other issues resulting from the use of this software. Use it at your own risk and in accordance with Minecraft's terms of service.

Credits & Acknowledgements

LeviCursor is made by GamingPrince76.

Built for "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid).

Thanks to the LeviLauncher and LeviModHub projects for providing the ecosystem used to distribute and run native Android mods.

Contact

Report Issues: Open an issue in this GitHub repository.

For bugs or compatibility problems, please include:

- LeviCursor version
- Minecraft Bedrock version
- LeviLauncher version
- Android version
- Device architecture
- A description of the problem

License

LeviCursor is distributed as a compiled native mod.

The public repository contains the distribution package and project information. The development source code is maintained privately.
