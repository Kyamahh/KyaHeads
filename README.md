# KyaHeads

KyaHeads is a Minecraft plugin that allows players to obtain other players' heads directly in-game. It is designed to be used alongside KyaCORE and **does not work without it**.

---

## Features

- Configurable automatic head drops: choose whether a player's head drops as an item when they are killed.  
- Connects to the NameMC API to fetch up-to-date player information.  
- Safe handling of commands and permissions.

---

## Requirements

- **Minecraft:** 1.19.x - 1.21.x  
- **Server:** Spigot / Bukkit / Paper  
- **Java:** 17+  
- **Dependency:** KyaCORE installed and running

---

## Installation

1. Make sure the latest version of **KyaCORE** is installed on your server.  
2. Download the latest version of `KyaHeads.jar` from the [Releases](https://github.com/Kyamahh/KyaHeads/releases) page.  
3. Place the file in your server's `/plugins` folder.  
4. Restart the server.  
5. Configure the plugin in the `config.yml` file to enable or disable automatic head drops.

---

## Commands

| Command | Description |
|---------|------------|
| `/kyaheads give <nick>` | Gives the head of the specified player. |

---

## Configuration

In the `config.yml` file, you can set:  

```yaml
auto-drop-heads: true # true = heads drop on player death, false = disabled
