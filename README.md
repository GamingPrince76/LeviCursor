# LeviCursor

## Introduction

LeviCursor is a native mouse cursor mod for Minecraft Bedrock on Android, made for "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid). It provides a customizable mouse cursor while playing Minecraft through LeviLauncher.

The mod is designed to be lightweight and simple to install, with the distributed build packaged as a ".levipack" for Android ARM64 devices.

## Features

- Native C++20 mod built for LeviLauncher and Preloader
- Custom mouse cursor for Minecraft Bedrock
- Custom cursor image
- Configurable cursor hotspot
- Automatic cursor application while Minecraft is running
- ARM64 ("arm64-v8a") support
- Distributed as a ready-to-install ".levipack"
- Designed specifically for LeviLauncher on Android

## System Requirements

- Android 9 or newer
- 64-bit ARM device ("arm64-v8a")
- "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid)
- A Minecraft Bedrock version supported by the LeviCursor release you are using

## Installation

1. Install LeviLauncher.
2. Download the latest "LeviCursor.levipack" release.
3. Import the package through LeviLauncher's mod manager.
4. Enable LeviCursor.
5. Launch Minecraft through LeviLauncher.

## Configuration

LeviCursor includes a cursor configuration file:

{
  "cursor": "arrow.png",
  "hotspot_x": 2,
  "hotspot_y": 2
}

#Configuration Options

- "cursor" — cursor image used by LeviCursor.
- "hotspot_x" — horizontal hotspot position.
- "hotspot_y" — vertical hotspot position.

The hotspot determines the point within the cursor image that represents the actual pointer position.

## Compatibility

Current target: Minecraft Bedrock "1.26.5X.X"

Platform: Android

Architecture: "arm64-v8a"

Launcher: LeviLauncher

Minecraft native compatibility can vary between game versions. Use a LeviCursor release that matches the Minecraft version you are running.

## Releases

The latest compiled LeviCursor package is available from the "Releases" (../../releases) page.

The current release is v0.1.0.

## Package:

"levicursor-0.1.0-arm64-v8a.levipack"

Project Structure

The distributed LeviCursor package contains the files required by LeviLauncher:

- Native library
- LeviLauncher manifest
- Cursor resources
- Cursor configuration

The development source code is maintained privately and is not included in the public distribution repository.

## Usage Guidelines

Do not use LeviCursor or LeviLauncher to violate Mojang or Microsoft's user agreements.

## Disclaimer: The author of LeviCursor is not responsible for bans, damages, data loss, or other issues arising from the use of this software. Use it at your own risk and in accordance with Minecraft's terms of service.

Credits & Acknowledgements

LeviCursor is made by GamingPrince76.

Built for "LeviLauncher" (https://github.com/LiteLDev/LeviLaunchroid).

Thanks to the LeviLauncher and LeviModHub projects for providing the ecosystem used to run and distribute native Android mods.

## Contact

Report Issues: Open an issue in this GitHub repository.

When reporting an issue, include:

- LeviCursor version
- Minecraft Bedrock version
- LeviLauncher version
- Android version
- Device architecture
- Description of the problem

## License

LeviCursor is distributed as a compiled native mod.

The public repository contains the compiled distribution package and project documentation. The development source code is maintained privately.
