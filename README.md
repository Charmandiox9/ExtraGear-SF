# ExtraGear (1.21.X Edition) ⚔️🛡️

[![Java 21](https://img.shields.io/badge/Java-21-orange.svg?style=flat-square&logo=openjdk)](https://adoptium.net/)
[![Paper 1.21.X](https://img.shields.io/badge/Paper-1.21.X-blue.svg?style=flat-square&logo=curseforge)](https://papermc.io/)
[![Slimefun4](https://img.shields.io/badge/Slimefun4-RC--37%2B-brightgreen.svg?style=flat-square)](https://github.com/Slimefun/Slimefun4)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square)](LICENSE)
[![CI & Release](https://img.shields.io/badge/GitHub_Actions-CI_%26_Release-blueviolet.svg?style=flat-square&logo=githubactions)](.github/workflows/build-and-release.yml)

**ExtraGear** is a classic combat and equipment addon for **[Slimefun 4](https://github.com/Slimefun/Slimefun4)**. It expands your arsenal by introducing custom enchanted swords and protective armor sets forged from Slimefun ingots, alloys, and magical components.

This version has been completely refactored and modernized for **Minecraft / Paper / Purpur 1.21.X** running on **Java 21**, with full binary compatibility for the latest **Slimefun4 builds (RC-37+ / SlimefunCore build 2708+)**.

---

## 🌟 Features

- 🗡️ **Custom Metal & Alloy Swords:** Craft specialized blades using Enhanced Crafting Tables (Copper, Tin, Silver, Aluminum, Lead, Zinc, Magnesium, Steel, Bronze, Duralumin, Billon, Brass, Damascus Steel, Hardened Metal, Reinforced Alloy, Ferrosilicon, Gilded Iron, Cobalt, and more).
- 🛡️ **Modular Armor Sets:** Forge custom Helmets, Chestplates, Leggings, and Boots in the Armor Forge.
- ✨ **Tiered Enchantments:** Equipment comes pre-enchanted with custom combat modifiers (Sharpness, Smite, Bane of Arthropods, Blast Protection, Protection, and Unbreaking) balanced to match metal tiers.
- 🔬 **Slimefun Research System:** Integrates into the Slimefun guide book with unlockable research trees and recipe previews.
- 🛡️ **Zero `VerifyError` / Modern Dough Compatibility:** Native internal `CustomItemStack` implementation to prevent runtime bytecode classloader errors.
- ⚡ **Paper 1.21.X & Java 21 Toolchain:** Built with modern PaperMC APIs, Gradle (Kotlin DSL), ShadowJar, and `run-paper` test server integration.

---

## 🗡️ Equipment & Enchantment Overview

| Material / Alloy | Weapons & Armor | Built-in Enchantments |
| :--- | :--- | :--- |
| **Copper** | Sword, Armor Set (Leather-base) | Smite II / Blast Protection II |
| **Tin** | Sword, Armor Set (Iron-base) | Sharpness I / Blast Protection III |
| **Silver** | Sword, Armor Set (Iron-base) | Sharpness II / Protection II |
| **Aluminum** | Sword, Armor Set (Iron-base) | Bane of Arthropods III / Blast Protection II, Unbreaking II |
| **Lead** | Sword, Armor Set (Iron-base) | Sharpness III, Unbreaking VIII / Protection III, Unbreaking VIII |
| **Zinc** | Sword, Armor Set (Iron-base) | Sharpness II / Protection III |
| **Magnesium** | Sword, Armor Set (Iron-base) | Sharpness II, Unbreaking V / Protection II, Unbreaking V |
| **Steel** | Sword, Armor Set (Iron-base) | Sharpness V, Unbreaking VI / Protection III, Unbreaking IV |
| **Bronze** | Sword | Sharpness III, Unbreaking VI |
| **Duralumin** | Sword | Sharpness III, Unbreaking VI |
| **Billon** | Sword | Sharpness IV, Unbreaking V |
| **Brass** | Sword | Smite IV, Unbreaking VI |
| **Damascus Steel** | Sword | Sharpness VI, Unbreaking VII |
| **Hardened Metal** | Sword | Sharpness VII, Unbreaking X |
| **Reinforced Alloy**| Sword | Sharpness VIII, Unbreaking VIII |
| **Ferrosilicon** | Sword | Smite VIII, Unbreaking IV |
| **Gilded Iron** | Sword (Gold-base) | Bane of Arthropods VIII, Unbreaking X |
| **Cobalt** | Sword, Armor Set (Iron-base) | Sharpness VII, Unbreaking VII / Protection VII, Unbreaking VII |

---

## 📋 Requirements

| Requirement | Supported Version |
| :--- | :--- |
| **Server Software** | [Paper](https://papermc.io/), [Purpur](https://purpurmc.org/) (1.21, 1.21.1, 1.21.3, 1.21.4+) |
| **Java Runtime** | Java 21 (LTS) or higher |
| **Core Dependency** | [Slimefun 4](https://github.com/Slimefun/Slimefun4) / [SlimefunCore](https://modrinth.com/plugin/slimefuncore) (RC-37 / build 2708+) |

---

## 🚀 Installation

1. Download the latest `ExtraGear.jar` from the **[Releases](https://github.com/Charmandiox9/ExtraGear-SF/releases)** tab.
2. Place `Slimefun4.jar` and `ExtraGear.jar` inside your server's `plugins/` directory.
3. Start or restart your server.

---

## 🛠️ Building and Testing Locally

### 📦 Building the Plugin Jar

```bash
# Windows
.\gradlew.bat build

# Linux / macOS
chmod +x gradlew
./gradlew build
```

The resulting shaded JAR file will be located at `build/libs/ExtraGear-1.21.0-SNAPSHOT.jar`.

### 🎮 Running the Local Test Server

You can launch a self-contained Paper 1.21.4 test server with Slimefun and ExtraGear loaded in one command:

```bash
# Windows
.\gradlew.bat runServer

# Linux / macOS
./gradlew runServer
```

---

## 📜 Credits & Attribution

- **Original Creator & Concept:** [TheBusyBiscuit](https://github.com/TheBusyBiscuit) — creator of Slimefun and the original ExtraGear addon.
- **1.21.X Modernization & Compatibility Maintenance:** [Charmandiox9](https://github.com/Charmandiox9)
- **Slimefun Community:** Thanks to all contributors to the [Slimefun4](https://github.com/Slimefun/Slimefun4) ecosystem.

---

## 📄 License

This project is open-source and licensed under the [GNU General Public License v3.0](LICENSE).
