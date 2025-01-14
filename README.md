# DISCLAIMER: The official [JooonAddons](https://github.com/JooonAddons/JooonAddons) repository contains malicious software and is highly not recommended.

Welcome to the GitHub page for **JooonAddons**! This is a secure and polished fork of JooonAddons, designed to enhance your **Hypixel Skyblock** experience. It offers support for **The Dojo**, **The Harp**, **Fishing**, **Experiments**, and more, all while ensuring safety by removing malicious scripts for a smoother and more secure gameplay journey.

## What's New in JooonAddons:

- **Unified Module**: 
  - **DojoHelper** and **MelodyMod** have been merged into a single module for improved performance and easier updates.
  
- **Malicious Script Removal**: 
  - All harmful scripts from the original JooonAddons have been completely removed, ensuring a safe and smooth gaming experience.

- **Expanded Feature Support**:
  - Support for various Skyblock features, including **The Dojo**, **The Harp**, **Fishing**, and **Experiments**.

- **Improved Stability**: 
  - Significant optimizations for smoother gameplay with reduced bugs and interruptions.

- **Polished Interface**: 
  - A cleaner, more user-friendly interface to enhance your experience.

---

### Features:

- **The Dojo**: Take on The Dojo in a secure and smooth experience.
- **The Harp**: MelodyMod’s functions are now part of the unified module.
- **Fishing**: Enhanced fishing experience with optimized support.
- **Experiments**: Streamlined support for Skyblock experiments.

For more information, check out the [JooonAddons repository](https://github.com/JooonAddons/JooonAddons).

---

## Installation Guide

To install **JooonAddons**, follow the steps below:

### Prerequisites:
1. **Minecraft Java Edition**: Ensure you are using the **Java Edition** of Minecraft, as this mod is not compatible with other versions.
2. **Minecraft Forge**: Download and install **Minecraft Forge** (version 1.8.9 or higher) for the mod to work correctly.
   - You can download Forge from the official website: [Forge Download](https://files.minecraftforge.net/).

### Steps:
1. **Download the Latest Release**:
   - Navigate to the [Releases page](https://github.com/Krithiv-7/JooonAddons/releases) and download the latest version of the **JooonAddons** mod.
   
2. **Install Forge**:
   - If you haven’t already, download and install Minecraft Forge for your desired Minecraft version.
   - Run the Minecraft launcher and select the Forge profile to ensure it’s installed correctly.

3. **Install the Mod**:
   - Locate your Minecraft installation folder. You can find it in:
     - **Windows**: `%AppData%/.minecraft`
     - **macOS**: `~/Library/Application Support/minecraft`
     - **Linux**: `~/.minecraft`
   - Open the **mods** folder. If it doesn’t exist, create a folder named `mods`.
   - Place the downloaded **JooonAddons** `.jar` file into the **mods** folder.

4. **Launch Minecraft**:
   - Open the Minecraft Launcher, select the Forge profile, and click **Play**.
   - The mod should now be successfully installed and ready to use.


If you encounter any issues or need further assistance, feel free to check the issues section or open a new issue in the [GitHub repository](https://github.com/Krithiv-7/JooonAddons).

---

## Why Use This Version of JooonAddons?

### Reasons to Use

- **Enhanced Security**: Unlike the official version, this fork has been thoroughly cleaned and is free from any malicious scripts or harmful code that could compromise your account or system.
- **Stable and Safe**: This version is free from the vulnerabilities found in the official repository. It provides a safer gameplay experience without the risk of potential account bans.
- **Tested and Clean**: All features in this version are tested and safe to use, providing a smooth experience without the issues found in the official version.

### Reasons Not to Use the Official JooonAddons

- **Malicious Software**: The official JooonAddons repository contains harmful scripts that could jeopardize your system or account. These scripts can lead to serious security risks, including data theft or account compromise.
- **Pre-release Versions**: Any pre-release versions available in our repository are directly copied from the official JooonAddons repository. These versions are not recommended for use, as they may contain bugs or untested features that can lead to issues or security vulnerabilities. It is strongly advised to avoid using any pre-release versions.
- **Account Risk**: Using the official version of JooonAddons exposes you to the risk of getting your account banned. Malicious scripts and unverified code can lead to violations of the game’s terms of service, resulting in account penalties or bans.
- **Lack of Support**: The official repository lacks proper support or updates, meaning you are on your own if any issues arise. This fork, however, ensures that you are using a secure, stable, and well-maintained version with ongoing improvements.

---

## How to Test Whether Minecraft Jars Have RATs or Not

### Testing for Malicious Code in Minecraft Jars

1. **Check for Suspicious Code in the JAR File**:
    - Use a decompiler like **JD-GUI** or **CFR** to open the Minecraft JAR file.
    - Inspect the code for any suspicious methods or obfuscated code that seems unusual. RATs often hide their operations in complex or encrypted code blocks.
    - Look for code related to **network communication**, **file manipulation**, or **remote control** which could be indicative of malicious activity.

2. **Use an Antivirus or Malware Scanner**:
    - Run the Minecraft JAR through an **antivirus software** that specializes in detecting trojans, RATs, and other malicious code.
    - Tools like **Bitdefender** or **Malwarebytes** may detect RATs if they're included in the JAR.
    - Ensure the antivirus is up-to-date to catch new types of malicious software.

3. **Check for Unusual File Operations**:
    - If the JAR file interacts with files or directories outside the Minecraft directory (such as writing to system files or executing unknown scripts), it could be a sign of malicious behavior.
    - Check whether the JAR tries to alter important system files or access unauthorized files.

4. **Monitor Network Activity**:
    - Run the Minecraft JAR on a controlled environment (like a virtual machine) and monitor its network traffic using tools such as **Wireshark** or **Fiddler**.
    - If the JAR tries to establish outgoing connections to unfamiliar IP addresses or servers, it's a red flag that it could be communicating with a remote server (which is characteristic of RATs).

5. **Check for Unexpected Permissions**:
    - If you notice the JAR is requesting elevated permissions (like administrator access), it's important to be cautious.
    - A legitimate Minecraft mod or JAR should not require such permissions unless it’s performing specific tasks like installing libraries or modifying Minecraft itself.

6. **Compare with Official Sources**:
    - Compare the code of your Minecraft JAR with the official, trusted version from Mojang or reputable sources.
    - If there are significant discrepancies, such as additional classes or code that shouldn’t be there, it could indicate malicious intent.
    - Always ensure you are downloading Minecraft JAR files from trusted sources and double-check against trusted platforms like **CurseForge** or **Spigot** for mods.

7. **Use Online Services to Scan for RATs**:
    - There are online services that allow you to upload JAR files to scan for RATs and malware. Services like **VirusTotal** can scan the file with multiple antivirus engines to provide a broader check for malicious content.
    - This is a quick way to determine if the JAR file has been flagged by any antivirus engines.

### Before using any mod **(INCLUDING THIS ONE)**, ensure its safety by scanning it with trusted tools. Here are some recommendations to check mods before installation:

- **[IsThisARat](https://isthisarat.com/)**: Identify malicious mods quickly.
- **[RatterScanner](https://discord.com/invite/E9uUFdjP5A)**: A community-driven resource for mod safety.
- **[RatRater](https://ktibow.github.io/RatRater/)**: A specialized tool for assessing mod safety.

Always verify mods before adding them to your game to protect your account and data.

### Why This Matters

Running Minecraft mods or JAR files that are compromised with RATs or malicious scripts can put your system, account, and personal data at risk. These malicious files may:
- Capture your login credentials for Minecraft or other accounts.
- Use your machine as a botnet or for other illegal activities.
- Corrupt your game data, causing crashes or gameplay issues.

Always ensure you are downloading files from trusted sources and perform the checks mentioned above to ensure your Minecraft experience remains safe and enjoyable.


---

## Important Notice

Please be aware that the official JooonAddons repository is **NOT SAFE** and **I DO NOT APPROVE** of using any of the content from it. The repository contains malicious software that could harm your system or compromise your account.

Additionally, **pre-release versions** available in the official repository are **NOT to be used**. These versions are still in development and are likely to contain vulnerabilities or other issues. I strongly discourage anyone from using any pre-release versions, as they could cause serious problems with your gameplay or system.

If you choose to use the official mod or pre-release versions, and something goes wrong—such as your account being banned or your system getting compromised—I am **NOT RESPONSIBLE** for any consequences that may occur. Use at your own risk!
