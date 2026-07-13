# 🏰 Dungeon Escape

> **First-Person Puzzle Adventure \| Unreal Engine 5 \| C++ &
> Blueprints**

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

The environment was assembled using the **Medieval Dungeon Asset Pack**
from the **Fab Marketplace**, while the gameplay mechanics---including
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

**🔗 Google Drive:** *(Add your download link here.)*

The archive includes:

-   ✅ Complete Unreal Engine Project
-   ✅ Content Folder
-   ✅ C++ Source Code
-   ✅ Blueprint Files
-   ✅ Config Files
-   ✅ Project Settings

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

# ⚙️ Gameplay Systems

## 🎮 First-Person Controller

-   Enhanced Input System
-   Character movement
-   Jump mechanics
-   Mouse look
-   Interaction input

## 🤝 Interaction System

Implemented using **Sphere Sweep Tracing** to detect nearby interactable
objects.

Supports: - Collectable items - Locks - Future interactable actors

## 🎒 Inventory System

A lightweight inventory stores collected key names using a dynamic
array.

Features: - Key collection - Inventory validation - Key removal after
use - Puzzle progression

## 🔐 Lock & Key System

Reusable lock actors manage puzzle progression.

Features: - Named key matching - Insert/remove keys - Lock state
management - Trigger activation - Visual key placement

## 🔘 Trigger Component

Custom trigger component built from `UBoxComponent`.

Responsibilities: - Overlap detection - Pressure plate logic - Activator
counting - Trigger state management - Communication with movement
components

## 🚧 Mover Component

Reusable Actor Component controlling movement.

Features: - Configurable movement offset - Adjustable movement time -
Delta Time interpolation - Automatic return movement - Smooth actor
transitions

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

# 🔷 Blueprint Integration

Blueprints are used to:

-   Configure gameplay actors
-   Set movement values
-   Assign trigger references
-   Build reusable level actors
-   Assemble gameplay scenes
-   Rapidly iterate level design

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

# 🛠️ Technologies Used

  Technology        Purpose
  ----------------- ------------------------
  Unreal Engine 5   Game Engine
  C++               Gameplay Programming
  Blueprints        Gameplay Configuration
  Enhanced Input    Player Controls
  Visual Studio     Development
  Git & GitHub      Version Control

------------------------------------------------------------------------

# 📦 Assets Used

## Environment

-   Medieval Dungeon Asset Pack *(Fab Marketplace)*

## Character

-   Unreal Engine First Person Template

## Gameplay

-   Custom C++ Components
-   Blueprint Actors

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

# 📈 Skills Demonstrated

-   Unreal Engine Gameplay Programming
-   Native C++ Development
-   Blueprint & C++ Integration
-   Component-Based Architecture
-   Interactive Puzzle Systems
-   Inventory Management
-   Trigger Systems
-   Lock & Key Mechanics
-   Problem Solving
-   Git Version Control

------------------------------------------------------------------------

# 📸 Screenshots


## 🏰 Dungeon Entrance

![Dungeon Entrance](Images/DungeonEntrance.png)

## 🔑 Key Collection

![Key Collection](Images/KeyCollection.png)

## 🚪 Door Mechanism

![Door](Images/DoorSystem.png)

## 🔘 Pressure Plate

![Pressure Plate](Images/PressurePlate.png)

## 🚧 Moving Platform

![Platform](Images/MovingPlatform.png)

------------------------------------------------------------------------

# 🎥 Gameplay Video

📺 **Watch Gameplay:** *(Add your YouTube or Google Drive link here.)*

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

Associate Developer \| Unreal Engine Developer

This project demonstrates my experience with **Unreal Engine 5**, **C++
gameplay programming**, **Blueprint integration**, and **component-based
architecture**, with a focus on building reusable and maintainable
gameplay systems.
