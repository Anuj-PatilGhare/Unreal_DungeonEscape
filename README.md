# 🏰 Dungeon Escape | Unreal Engine 5 | C++ & Blueprints
> First-Person Puzzle Adventure :
>

Dungeon Escape is a first-person puzzle adventure built in **Unreal
Engine 5** using **native C++** and **Blueprint Visual Scripting**. The
project demonstrates modular gameplay programming through reusable Actor
Components, interactive puzzle mechanics, and environment-driven
exploration.

------------------------------------------------------------------------

# 📖 Project Overview

Dungeon Escape was developed to explore Unreal Engine's Gameplay
Framework while applying object-oriented programming principles to
practical gameplay systems.

Instead of embedding gameplay logic directly inside actors, the project
follows a **component-based architecture**, allowing systems such as
movement, triggers, and interactions to be reused across multiple
gameplay objects.


The environment was assembled using the Medieval Dungeon Asset Pack
from the Fab Marketplac , while the gameplay mechanics---including
interaction, inventory, trigger logic, lock & key puzzles, and moving
objects---were implemented using custom C++ classes and Blueprint
integration.

---
# 📂 Repository Information

To keep this repository lightweight, only the **source code**,
**Blueprints**, **configuration files**, and project resources are
included.

The complete Unreal Engine project contains several gigabytes of
content, including assets, textures, meshes, and materials from the Fab
Marketplace.

A complete project archive is available below.

------------------------------------------------------------------------

# 📦 Complete Project Download

**🔗 Google Drive :** *(https://drive.google.com/file/d/1RATXYCcPCi23Hq8OFPwfEFTSO52wE1H8/view?usp=sharing)*

The archive includes:

-   ✅ Complete Unreal Engine Project
-   ✅ Content Folder
-   ✅ C++ Source Code
-   ✅ Blueprint Files
-   ✅ Config Files
-   ✅ Project Settings

------------------------------------------------------------------------

# 🎥 Gameplay Video

📺 **Watch Gameplay :** *(https://drive.google.com/drive/folders/18itgnrsHb370QMGyq6W8TscWyGyKXPXL?usp=sharing)*

------------------------------------------------------------------------

# 🎯 Gameplay Objective

Explore the dungeon and solve environmental puzzles by:

-   🔑 Collecting keys
-   🚪 Unlocking matching doors
-   🔘 Activating pressure plates
-   🚧 Triggering moving platforms and mechanisms
-   🧩 Solving environmental puzzles
-   🏁 Escaping the dungeon

------------------------------------------------------------------------

# ✨ Key Features

-   🎮 First-person exploration
-   💻 Native C++ gameplay systems
-   🔷 Blueprint configurable actors
-   🚪 Lock & Key puzzle system
-   🎒 Item collection & inventory
-   🔘 Pressure plate mechanics
-   🚧 Reusable moving platform & door system
-   🤝 Custom interaction system
-   🌍 Medieval dungeon environment
-   ⚡ Enhanced Input integration

------------------------------------------------------------------------

 🤝 Interaction System ::

Implemented using **Sphere Sweep Tracing** to detect nearby interactable
objects.<br>
Supports: - Collectable items - Locks - Future interactable actors


🎒 Inventory System ::

A lightweight inventory stores collected key names using a dynamic
array.br>
Features: - Key collection - Inventory validation - Key removal after
use - Puzzle progression

🔐 Lock & Key System ::

Reusable lock actors manage puzzle progression.br>
Features: - Named key matching - Insert/remove keys - Lock state
management - Trigger activation - Visual key placement

🔘 Trigger Component ::

Custom trigger component built from `UBoxComponent`.br>
Responsibilities: - Overlap detection - Pressure plate logic - Activator
counting - Trigger state management - Communication with movement
components

 🚧 Mover Component ::

Reusable Actor Component controlling movement.br>
Features: - Configurable movement offset - Adjustable movement time -
Delta Time interpolation - Automatic return movement - Smooth actor
transitions


------------------------------------------------------------------------

# 📸 Screenshots


Screenshot 1 :

Game Mechanics Testing :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_4.png)

Screenshot 2 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_5.png)

Screenshot 3 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_6.png)

Screenshot 4 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_7.png)

Screenshot 5 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_8.png)

Screenshot 6 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_9.png)

Screenshot 7 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_10.png)

Screenshot 8 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_11.png)

Screenshot 9 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_12.png)

Screenshot 10 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_13.png)

Screenshot 11 :
![Description](https://github.com/Anuj-PatilGhare/Unreal_DungeonEscape/blob/b5be5220d0f7861df96c9be2307e16407306ebd9/Images/ScreenShot_14.png)

------------------------------------------------------------------------

# 🌍 Environment Design

The environment was created using the **Medieval Dungeon Asset Pack**
from the **Fab Marketplace**.

The level features:

-   Medieval corridors
-   Puzzle rooms
-   Locked pathways
-   Interactive mechanisms
-   Pressure plates
-   Atmospheric lighting
-   Exploration-focused level progression

------------------------------------------------------------------------
# 🏗️ Architecture

``` text
Player
   │
Enhanced Input
   │
Interact
   │
Sphere Sweep Trace
   │
Collectable / Lock
   │
Trigger Component
   │
Mover Component
   │
Door / Platform
```

The gameplay architecture follows **Composition over Inheritance**,
keeping systems modular, reusable, and easy to extend.

------------------------------------------------------------------------

# 💻 Technical Highlights

-   Custom Actor Components
-   Gameplay Framework
-   Enhanced Input
-   Collision Detection
-   Sphere Sweep Trace
-   Event-driven Gameplay
-   Blueprint Exposure with `UPROPERTY`
-   Blueprint Callable Functions
-   Object-Oriented Programming
-   Modular System Design

------------------------------------------------------------------------

# 📚 Unreal Engine Concepts

-   Gameplay Framework
-   Actor Components
-   Enhanced Input
-   Collision & Overlap Events
-   Sphere Sweep Trace
-   Actor Communication
-   Blueprint Integration
-   Delta Time
-   Level Design

------------------------------------------------------------------------
# 📦 Assets Used

## Environment

-   Medieval Dungeon Asset Pack *(Fab Marketplace)*
-   Unreal Engine First Person Template
-   Custom C++ Components
-   Blueprint Actors

------------------------------------------------------------------------

# 🚀 Getting Started

1.  Download the complete project.
2.  Extract the ZIP archive.
3.  Open the `.uproject` file in Unreal Engine 5.
4.  Build if prompted.
5.  Press **Play** to explore the dungeon.

------------------------------------------------------------------------

# 🔮 Future Improvements

-   Enemy AI
-   Save & Load System
-   Audio & Music
-   Additional Puzzle Mechanics
-   UI & Objectives
-   More Dungeon Levels
-   Performance Optimization

------------------------------------------------------------------------

# 👨‍💻 Author

**Anuj Patilghare**

This project demonstrates my experience with **Unreal Engine 5**, **C++
gameplay programming**, **Blueprint integration**, and **component-based
architecture**, with a focus on building reusable and maintainable
gameplay systems.
