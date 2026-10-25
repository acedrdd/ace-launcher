# Ace Launcher
A Minecraft: Bedrock Edition launcher for Android, with mod support and a built-in FPS optimizer for low-end devices.
Ace Launcher lets you run your own licensed copy of Minecraft Bedrock, manage multiple game versions, and load native .levipack mods. It ships with Volt, an FPS optimizer made to help weak phones run the game smoother and cooler.
Features
Mod loading: import .levipack native modules, switch them on or off, and reorder them.
Volt FPS optimizer (v2.3.2):
Frame cap: 0 for unlimited, or 60, 90 or 120 to reduce heat and tearing
Chunk level of detail
Culling of chunks behind you and of distant entities
Paced chunk rebuilds to avoid stutter
Frame-spike detection
Multiple game versions: keep several Minecraft versions, each with its own settings and data.
Worlds and resource packs: import, export and back up.
Accounts: manage more than one Xbox account.
Ace look: dark neon-mint theme and a lightning-bolt icon.
Requirements
Android 9.0 or newer
An ARM64 (arm64-v8a) phone
2 GB or more of RAM recommended, and about 2 GB of free storage
A licensed copy of Minecraft Bedrock from Google Play. Volt targets Bedrock 1.26.52.
Install
Download AceLauncher-debug.apk from the latest build under Actions → Artifacts.
Allow "Install unknown apps" for your browser or file manager, then install the APK.
Open Ace Launcher and import your Minecraft APK. You need to own the game.
Using Volt
Create or select a game version.
Open Mods → Import and choose bundled-mods/Ace-Volt-2.3.2.levipack.
Switch Volt on and launch the game.
Adjust Volt's options in the in-game mod menu.
Tips for weak phones: use a frame cap of 30–60, turn on chunk level of detail and entity culling, and lower the game's render distance.
Building
The project builds automatically with GitHub Actions. Upload AceLauncher2.zip and .github/workflows/build.yml to a repository, then open Actions and wait for the green check. The APK appears under Artifacts. To build locally, use Android Studio with JDK 21, the Android SDK, and NDK r28.
Credits and legal
Based on LeviLaunchroid by LiteLDev, under the Apache-2.0 license. The original license is kept.
Volt is by DrukisMC.
Ace Launcher is unofficial and not affiliated with Mojang or Microsoft. Minecraft is a trademark of Mojang. You must own a legitimate copy of the game. Do not use this with pirated copies. Mods are used at your own risk.
