<div align="center">

<img src="https://imgur.com/a/idJiXwU" width="100%" alt="BackAsk Banner"/>

<br><br>

# BackAsk

### Modern Backpack System for Paper & Spigot

A modern inventory management plugin built for Minecraft servers, providing a complete backpack ecosystem with virtual storage, advanced search, favorites, workstations and fully customizable interfaces.

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

<a id="overview"></a>
# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/markdown/markdown-original.svg" width="24" height="24"/> Overview

**BackAsk** is a complete backpack solution designed for modern Minecraft servers.

Instead of adding only extra inventory space, BackAsk introduces an entire inventory management ecosystem focused on usability, organization, and performance.

Every feature has been designed from scratch with scalability and maintainability in mind, making the plugin suitable for survival, economy, RPG, and large network servers.

The plugin focuses on reducing inventory clutter while giving players instant access to tools that are frequently used during gameplay.

---

<div align="center">

## Architecture

</div>

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

<a id="highlights"></a>
# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original.svg" width="24" height="24"/> Highlights

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

<div align="center">

## Plugin Philosophy

</div>

BackAsk follows four main design principles:

| Principle | Goal |
|-----------|------|
| **Simplicity** | Easy to use without sacrificing functionality |
| **Performance** | Low CPU and memory usage |
| **Customization** | Extensive configuration support |
| **Stability** | Reliable behavior in production environments |

---

<div align="center">

## Key Advantages

</div>

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

<div align="center">

## Designed For

</div>

| Server Type | Recommended |
|--------------|:-----------:|
| Survival | ✔ |
| SMP | ✔ |
| Economy | ✔[cite: 1] |
| RPG | ✔[cite: 1] |
| SkyBlock | ✔[cite: 1] |
| Prison | ✔[cite: 1] |
| Lifesteal | ✔[cite: 1] |
| Network Servers | ✔[cite: 1] |

---

<div align="center">

## Technology Stack

</div>

| Technology | Purpose |
|------------|---------|
| **Java 21** | Core language[cite: 1] |
| **Gradle** | Build system[cite: 1] |
| **Paper API** | Primary platform[cite: 1] |
| **Spigot API** | Compatibility layer[cite: 1] |

---

<div align="center">

## Development Goals

</div>

BackAsk has been developed with emphasis on:[cite: 1]
- Clean architecture & modular systems[cite: 1]
- Maintainable source code & modern Java practices[cite: 1]
- Production stability & efficient inventory processing[cite: 1]
- Full compatibility with current Minecraft releases[cite: 1]
- Intuitive player experience[cite: 1]

---

<a id="features"></a>
# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/labs/labs-original.svg" width="24" height="24"/> Features

BackAsk provides a complete inventory ecosystem instead of a simple backpack. Every module has been designed to work independently while integrating seamlessly with the rest of the plugin.[cite: 1]

### Backpack System
Players receive a virtual backpack that can be opened anywhere, allowing safe storage without requiring physical containers. Storage is persistent and automatically synchronized.[cite: 1]
* Virtual backpack inventory with configurable sizes.[cite: 1]
* Persistent player storage with automatic save system.[cite: 1]
* Smart slot handling and lightweight implementation.[cite: 1]

### Smart Search
Quickly locate any item inside the backpack. The search engine filters inventory contents in real time without requiring additional menus.[cite: 1]
* Supports filtering by Material Name, Custom Display Name, Partial Text, and is Case Insensitive.[cite: 1]

### Favorites
Mark important items to avoid losing track of them. Favorite items remain highlighted regardless of inventory organization and are protected during stack sorting.[cite: 1]

### Trash System
Safely dispose of unwanted items. Instead of deleting items immediately, BackAsk stores them temporarily, allowing recovery before permanent removal. Includes history tracking and timestamp management.[cite: 1]

### Virtual Workstations
Access crafting utilities directly from the backpack interface or via commands. Supported virtual stations include: Crafting Table, Stonecutter, Smithing Table, Loom, Cartography Table, and Grindstone.[cite: 1]

### Stack Management
Automatically organize inventory contents. Merge stacks, sort materials, compact inventory, and fill empty spaces while preserving your favorite items.[cite: 1]

### Modern GUI
Every interface features a modern layout, responsive buttons, decorative borders, configurable titles, placeholder support, animations, and clean navigation.[cite: 1]

---

<a id="compatibility"></a>
# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ie10/ie10-original.svg" width="24" height="24"/> Compatibility

BackAsk officially supports the latest Paper and Spigot releases.[cite: 1]

| Software | Support |
|----------|:-------:|
| Paper | ✔[cite: 1] |
| Spigot | ✔[cite: 1] |

### Minecraft Versions
Supports versions **1.21 up to 26.2** (including 1.21.x, 1.22, 1.23, 1.24, 1.25, 26.1, and 26.2).[cite: 1]

### Requirements & Dependencies
* **Java:** 21 or newer[cite: 1]
* **RAM:** 512 MB minimum (2 GB+ recommended)[cite: 1]
* **Server Software:** Paper or Spigot[cite: 1]
* **External Dependencies:** Designed to run with **zero** external runtime dependencies. Support for **PlaceholderAPI** is optional and automatically enabled if present.[cite: 1]

---

<a id="installation"></a>
# <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/putty/putty-original.svg" width="24" height="24"/> Installation

### 1. Download
Download the latest release from the Releases page.[cite: 1]
```text
BackAsk-x.x.x.jar
