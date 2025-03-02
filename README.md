# SwitchEmuTutorial
This is a private repo for users to delve into Nintendo Switch Emulation with multiplayer support for games like Mario Kart 8 Deluxe.

# Yuzu Setup Guide

This guide will help you set up Yuzu, a Nintendo Switch emulator, on your PC. Ensure you own the games and have legally dumped them from your Nintendo Switch.

## Prerequisites

Before you begin, make sure you have the following:

- A compatible operating system (Windows, Linux, or macOS)
- A powerful enough PC (Check the [Yuzu requirements] for details)
- Your legally dumped Nintendo Switch games
- Any necessary firmware files and product keys extracted from your Switch

## Step 1: Download Yuzu

1. Visit this link: https://yuzu-emulator.net/download.
2. Download the latest version suitable for your operating system.

## Step 2: Install Yuzu

### On Windows:

1. Run the downloaded `.exe` file.
2. Follow the prompts in the installation wizard.
3. Select the installation directory and complete the installation.

### On Linux:

1. Open your terminal.
2. Follow the installation instructions on the Yuzu website, which may include adding a PPA or building from source.

## Step 3: Configure Yuzu

1. Launch Yuzu after installation.
2. Go to `File` > `Open Yuzu Folder`. This will open the directory where Yuzu stores its configuration files.
3. Create the following folders if they do not exist:
   - `games`: For your dumped Switch games.
   - `keys`: For product keys and firmware files.

### Adding Games

1. Copy your dumped game files into the `games` folder.
2. In Yuzu, go to `File` > `Add New Game Directory`.
3. Select the `games` folder where you placed your dumped games.

### Setting Up Firmware and Product Keys

1. **Obtain Firmware and Keys**:
   - Use the `Lockpick_RCM` tool on your Switch to extract the firmware and keys. Instructions can be found in the Lockpick_RCM documentation.
   - You will need the `prod.keys` and `title.keys` files.

   - Placeholder for firmware and keys download:
   - Firmware: https://darthsternie.net/switch-firmwares/
   - Keys: https://prodkeys.net/latest-switch-firmwares-v3/

2. **Copy Keys to Yuzu**:
   - Place the `prod.keys` and `title.keys` files into the `keys` folder you created.
   - Ensure the file names are correct: `prod.keys` must be named exactly as such.

3. **Add Firmware**:
   - Download the latest firmware files from a trusted source or directly from your Switch.
   - Place the firmware files into the `keys` folder as well.

## Step 4: Configure Controllers

### For PS4 / PS5 Controller

1. Connect your controller to your PC via USB or Bluetooth.
2. Open Yuzu and go to `Emulation` > `Configure`.
3. Navigate to the `Controls` tab.
4. Under `Input Device`, select `DualShock 4`.
5. Map the buttons according to your preference.

### For Xbox Controller

1. Connect your Xbox controller to your PC via USB or Bluetooth.
2. Open Yuzu and go to `Emulation` > `Configure`.
3. Navigate to the `Controls` tab.
4. Under `Input Device`, select `Xbox 360 Controller` or `Xbox One Controller`, depending on your model.
5. Map the buttons according to your preference.

## Step 5: Adjust Settings

1. Go to `Emulation` > `Configure`.
2. Adjust the settings according to your PC specifications and game requirements. Key areas to focus on include:
   - Graphics
   - Audio
   - Controls

## Step 6: Start Playing

1. Select a game from the Yuzu library.
2. Click `Play` to start your game.

## Troubleshooting

- Check the [Yuzu Compatibility List] for information on game performance.
- Visit the Yuzu [Discord server] for community support.

## Conclusion

You are now ready to enjoy your Nintendo Switch games on your PC using Yuzu! Remember to keep your software updated for the best experience.


