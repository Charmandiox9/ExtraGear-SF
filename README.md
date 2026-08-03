# ExtraGear ⚔️🛡️

> **Modernized for Paper & Purpur 1.21.X / Java 21+**  
> Slimefun4 Addon that introduces enchanted weapons and custom armor sets forged from Slimefun metals, alloys, and magical components.

---

## 🌟 Features

- 🗡️ **Custom Swords**: Adds unique swords for each Slimefun ingot and alloy (Copper, Tin, Silver, Aluminum, Lead, Zinc, Magnesium, Steel, Bronze, Duralumin, Billon, Brass, Damascus Steel, Hardened Metal, Reinforced Alloy, Ferrosilicon, Gilded Iron, Cobalt, etc.).
- 🛡️ **Full Armor Sets**: Helmets, Chestplates, Leggings, and Boots craftable in the Armor Forge.
- ✨ **Custom Enchantments**: Weapons and armor sets come pre-enchanted with tailored effects (Sharpness, Smite, Bane of Arthropods, Blast Protection, Protection, Unbreaking) scaled by metal tier.
- 🔬 **Slimefun Researches**: Seamless integration into the Slimefun guide book with categorized research nodes and recipe previews.
- ⚡ **1.21.4 & Java 21 Ready**: Native Paper API 1.21.4 support, zero `VerifyError` issues, and modern compilation toolchain.

---

## 📋 Requirements

- **Server Software:** [Paper](https://papermc.io/) or [Purpur](https://purpurmc.org/) for **Minecraft 1.21.X**
- **Java:** **Java 21** or newer
- **Dependency:** [Slimefun4](https://github.com/Slimefun/Slimefun4) / [SlimefunCore](https://modrinth.com/plugin/slimefuncore) (Build 2708+ / RC-37+ compatible)

---

## 🚀 Building from Source

To compile the plugin using Gradle:

```bash
# Windows
.\gradlew.bat clean build

# Linux / macOS
./gradlew clean build
```

The compiled JAR file with shaded dependencies will be generated in `build/libs/ExtraGear-1.21.0-SNAPSHOT.jar`.

---

## 🧪 Local Testing

You can spin up an integrated test server with Paper 1.21.4 and Slimefun loaded:

```bash
.\gradlew.bat runServer
```

---

## 📄 License

This project is licensed under the [GPL-3.0 License](LICENSE).
