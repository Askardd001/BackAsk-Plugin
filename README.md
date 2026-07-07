<div align="center">

<img src="https://cdn.discordapp.com/attachments/1503890704043348098/1524135852140134460/banner-removebg-preview.png?ex=6a4ea5a0&is=6a4d5420&hm=b3dadd4ad966e8d5f4233ba7e2fb436c84728ace8c1da1e615ce6ecee238926b&" width="100%" alt="BackAsk Banner"/>

<br><br>

# BackAsk

### Modern Backpack System for Paper & Spigot

A modern inventory management plugin built for Minecraft servers, providing a complete backpack ecosystem with virtual storage, advanced search, favorites, workstations and fully customizable interfaces.

<p>
<a href="https://github.com/Askardd001">
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=22&duration=3000&pause=1000&color=3B82F6&center=true&vCenter=true&width=700&lines=By+Askardd;Java;Minecraft+Plugin;V2.0.0"/>
</a>
</p>

<br>

<img src="https://img.shields.io/github/v/release/Askardd001/BackAsk-Plugin?style=for-the-badge">
<img src="https://img.shields.io/badge/Minecraft-1.21.x%20%E2%86%92%2026.2-5EAF4E?style=for-the-badge">
<img src="https://img.shields.io/badge/Java-21+-F89820?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Paper-Supported-FFFFFF?style=for-the-badge">
<img src="https://img.shields.io/badge/Spigot-Supported-F47B20?style=for-the-badge">
<img src="https://img.shields.io/github/license/Askardd001/BackAsk-Plugin?style=for-the-badge">

<br><br>

<table>
  <tr>
    <td align="center"><a href="#overview">Overview</a></td>
    <td align="center"><a href="#highlights">Highlights</a></td>
    <td align="center"><a href="#features">Features</a></td>
    <td align="center"><a href="#compatibility">Compatibility</a></td>
    <td align="center"><a href="#installation">Installation</a></td>
    <td align="center"><a href="#configuration">Configuration</a></td>
    <td align="center"><a href="#commands">Commands</a></td>
    <td align="center"><a href="#permissions">Permissions</a></td>
  </tr>
</table>

</div>

---

<div id="overview"></div>

# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/markdown/markdown-original.svg" width="24" height="24"/> Overview

**BackAsk** is a complete backpack solution designed for modern Minecraft servers.

Instead of adding only extra inventory space, BackAsk introduces an entire inventory management ecosystem focused on usability, organization, and performance.

Every feature has been designed from scratch with scalability and maintainability in mind, making the plugin suitable for survival, economy, RPG, and large network servers.

The plugin focuses on reducing inventory clutter while giving players instant access to tools that are frequently used during gameplay.

---

## Architecture

| Component | Description |
|------------|-------------|
| **Backpack Engine** | Persistent player storage |
| **Search Engine** | Instant item lookup |
| **Favorites Manager** | Favorite item system |
| **Trash System** | Safe item deletion and recovery |
| **Workstations** | Virtual crafting utilities |
| **GUI Engine** | Fully configurable inventories |
| **Configuration Loader** | Automatic configuration management |
| **Storage Layer** | Efficient player data persistence |

---

<div id="highlights"></div>

# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="24" height="24"/> Highlights

<table>
<tr>
<td width="50%">

### Performance
Designed to minimize unnecessary allocations and inventory scans. Optimized algorithms ensure fast searches and smooth interaction even with large backpacks.

</td>
<td width="50%">

### Clean Design
Modern graphical interfaces with configurable layouts. Supports custom textures, lore, and titles through configuration files.

</td>
</tr>
<tr>
<td>

### Flexible
Every major system can be enabled, disabled, or customized independently. Ideal for servers with different gameplay styles.

</td>
<td>

### Lightweight
Runs without unnecessary dependencies while maintaining low memory usage. Compatible with long-running production servers.

</td>
</tr>
</table>

---

## Plugin Philosophy

BackAsk follows four main design principles:

| Principle | Goal |
|-----------|------|
| **Simplicity** | Easy to use without sacrificing functionality |
| **Performance** | Low CPU and memory usage |
| **Customization** | Extensive configuration support |
| **Stability** | Reliable behavior in production environments |

---

## Key Advantages

<table>
<tr>
<th align="left">Inventory Management</th>
<th align="left">Server Administration</th>
</tr>
<tr>
<td>

• Persistent backpack storage  
• Fast item organization  
• Favorites support  
• Smart search  
• Stack optimization  
• Trash recovery  

</td>
<td>

• Easy installation  
• Lightweight architecture  
• Clean configuration files  
• Modern codebase  
• Production ready  
• Minimal maintenance  

</td>
</tr>
</table>

---

## Designed For

| Server Type | Recommended |
|--------------|:-----------:|
| Survival | ✔ |
| SMP | ✔ |
| Economy | ✔ |
| RPG | ✔ |
| SkyBlock | ✔ |
| Prison | ✔ |
| Lifesteal | ✔ |
| Network Servers | ✔ |

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| **Java 21** | Core language |
| **Gradle** | Build system |
| **Paper API** | Primary platform |
| **Spigot API** | Compatibility layer |

---

## Development Goals

BackAsk has been developed with emphasis on:
- Clean architecture & modular systems
- Maintainable source code & modern Java practices
- Production stability & efficient inventory processing
- Full compatibility with current Minecraft releases
- Intuitive player experience

---

<div id="features"></div>

# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="24" height="24"/> Features

BackAsk provides a complete inventory ecosystem instead of a simple backpack. Every module has been designed to work independently while integrating seamlessly with the rest of the plugin.

### Backpack System
Players receive a virtual backpack that can be opened anywhere, allowing safe storage without requiring physical containers. Storage is persistent and automatically synchronized.
* Virtual backpack inventory with configurable sizes.
* Persistent player storage with automatic save system.
* Smart slot handling and lightweight implementation.

### Smart Search
Quickly locate any item inside the backpack. The search engine filters inventory contents in real time without requiring additional menus.
* Supports filtering by Material Name, Custom Display Name, Partial Text, and is Case Insensitive.

### Favorites
Mark important items to avoid losing track of them. Favorite items remain highlighted regardless of inventory organization and are protected during stack sorting.

### Trash System
Safely dispose of unwanted items. Instead of deleting items immediately, BackAsk stores them temporarily, allowing recovery before permanent removal. Includes history tracking and timestamp management.

### Virtual Workstations
Access crafting utilities directly from the backpack interface or via commands. Supported virtual stations include: Crafting Table, Stonecutter, Smithing Table, Loom, Cartography Table, and Grindstone.

### Stack Management
Automatically organize inventory contents. Merge stacks, sort materials, compact inventory, and fill empty spaces while preserving your favorite items.

### Modern GUI
Every interface features a modern layout, responsive buttons, decorative borders, configurable titles, placeholder support, animations, and clean navigation.

---

<div id="compatibility"></div>

# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gradle/gradle-original.svg" width="24" height="24"/> Compatibility

BackAsk officially supports the latest Paper and Spigot releases.

| Software | Support |
|----------|:-------:|
| Paper | ✔ |
| Spigot | ✔ |

### Minecraft Versions
Supports versions **1.21 up to 26.2** (including 1.21.x, 1.22, 1.23, 1.24, 1.25, 26.1, and 26.2).

### Requirements & Dependencies
* **Java:** 21 or newer
* **RAM:** 512 MB minimum (2 GB+ recommended)
* **Server Software:** Paper or Spigot
* **External Dependencies:** Designed to run with **zero** external runtime dependencies. Support for **PlaceholderAPI** is optional and automatically enabled if present.

---

<div id="installation"></div>

# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/putty/putty-original.svg" width="24" height="24"/> Installation

### 1. Download
Download the latest release from the Releases page.
```text
BackAsk-x.x.x.jar

## 2. Stop the Server

Always stop your server before installing or updating plugins.

---

## 3. Install

Move the JAR file into your server's `plugins` directory.

```text
server/
└── plugins/
    └── BackAsk.jar
```

---

## 4. Start the Server

Start the server normally.

BackAsk will automatically generate its folders and configuration files.

---

# Configuration

All plugin files are generated automatically after the first startup inside:

```text
plugins/
└── BackAsk/
    ├── config.yml          # Main plugin settings
    ├── storage.yml         # Storage & data retention options
    ├── language.yml        # Active language configuration
    ├── menus.yml           # Custom GUI layouts and titles
    ├── sounds.yml          # Custom sound effects
    ├── lang/
    │   ├── en_us.yml
    │   ├── es_es.yml
    │   └── pt_br.yml
    └── data/
```

No recompilation is required after changing the configuration.

Most settings can be reloaded instantly in-game.

---

# Commands

| Command | Description |
|---------|-------------|
| `/backpack` | Opens the main BackAsk menu |
| `/backpack reload` | Reloads all plugin configuration files |
| `/bp` | Opens the Backpack interface |
| `/bau` | Opens the Virtual Backpack |
| `/enderchest` | Opens the Virtual Ender Chest |
| `/lixeira` | Opens the Trash system |
| `/mesa` | Opens the Virtual Crafting Table |
| `/bigorna` | Opens the Virtual Anvil |
| `/encantamentos` | Opens the Virtual Enchanting Table |
| `/rebolo` | Opens the Grindstone |
| `/talhar` | Opens the Smithing Table |
| `/cartografia` | Opens the Cartography Table |
| `/ferraria` | Opens the Smithing Table |
| `/tear` | Opens the Loom |

---

# Permissions

BackAsk includes a flexible permission system for controlling access to features, backpack sizes, and administrative commands.

For the complete list of permission nodes, see:

```text
PERMISSIONS.md
```

---

# PlaceholderAPI

BackAsk automatically supports PlaceholderAPI when it is installed.

Example placeholders:

```text
%backask_backpack_size%
%backask_backpack_slots%
%backask_storage_items%
%backask_trash_items%
```

---

# Frequently Asked Questions

### Does BackAsk replace vanilla inventories?

No.

Everything is virtual, independent, and secure.

### Is PlaceholderAPI required?

No.

PlaceholderAPI support is completely optional.

### Can I customize every menu?

Yes.

Every inventory layout, title, icon, and decoration can be customized in `menus.yml`.

### Does it support custom textures?

Yes.

BackAsk fully supports custom GUI icons and resource-pack based textures, including the exclusive DevTools icon set bundled with the plugin.

---

# Roadmap

Current goals for future versions:

- More PlaceholderAPI expansions
- Additional developer hooks
- More backpack upgrades
- New virtual utilities
- Advanced GUI animations
- Expanded language support
- Improved public API documentation

---

# API

BackAsk provides a public API for developers.

```java
BackAskAPI api = BackAskAPI.get();

api.openBackpack(player);
api.openTrash(player);
api.openStorage(player);
```

More examples and documentation are available in:

```text
API.md
```

---

# License

This project is licensed under the **MIT License**.

You are free to use, modify, fork, and distribute this project provided the original license is included.

See:

```text
LICENSE
```

---

# Credits

Developed and maintained by **BPA**.

BackAsk makes use of the following open-source projects:

- PaperMC
- PlaceholderAPI

### Custom Assets

The DevTools icon set included with BackAsk was custom designed exclusively for this project and is not part of Minecraft or any third-party resource pack.

Special thanks to the Minecraft server development community for their continuous contributions.
