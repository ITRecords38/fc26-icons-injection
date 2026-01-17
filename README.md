![FC26 Icons Injection Pack](releases/release_1.0.png)


Heroes & Icons player injection for EA SPORTS FC 26 using Live Editor (Lua API)


This repository provides a complete Heroes & Icons player injection pack for FC 26, designed for use with FC 26 Live Editor.

All players are generated from official EA database data, using safe fictive player IDs to avoid any database overwrite or conflict.

The project follows the same philosophy as my previous FC25 work:
👉 https://github.com/ITRecords38/fc25-icons-injection


✅ Features

One .lua file per player

Players sorted by revision:

Debut Icon

Champion Icon

Heroes

DB-safe fictive player IDs

Correct real EA Player ID used for:

real_playerid

headassetid

Players start their career at 18 years old

Fully injected:

Nationality

Height

Weight

Preferred foot

Full stats, traits, workrates, skill moves & weak foot

Automatic name insertion (editedplayernames)

Compatible with FC 26 Live Editor – CreatePlayer API

No crashes / no desktop return (fully tested)


## 📂 Structure

lua_players_by_revision/
├─ Heroes/
│ ├─ 18814_Papin.lua
│ ├─ 5454_Lizarazu.lua
│ └─ ...
│
├─ Champion_Icon/
│ └─ ...
│
└─ Debut_Icon/
└─ ...



🛠 Requirements

EA SPORTS FC 26 (PC)

FC 26 Live Editor

Lua scripts enabled


▶️ Usage

Extract the ZIP

Place the folders inside your Live Editor lua directory

Load the scripts via Live Editor


Players will appear as Free Agents

