# Dino-Deluxe
A real-time strategy (RTS) game built in **Unity**, where players grow and command dinosaur factions to gather resources, battle for doniance, and conquer the world.

This project is currently in early development and is being built collaboratively using **Unity**, **GitHub**, and **Trello**.

---

## 🎮 Project Goals

- Classic RTS-style gameplay 
- Dinosaur-based factions and units
- Resource gathering and base building
- AI-controlled enemies
- Expandable tech trees and upgrades

---

## 🛠 Tech Stack

- **Engine:** Unity 6.3 LTS
- **Language:** C#
- **Rendering:** Universal Render Pipeline (URP)
- **Version Control:** Git + GitHub
- **Project Management:** Trello

---

## 📁 Project Structure
Assets/
 ├─ Art/
 ├─ Audio/
 ├─ Prefabs/
 ├─ Scripts/
 ├─ Scenes/
 ├─ ScriptableObjects/
 └─ UI/

#### Folder Notes
- `Assets/` → All art, prefabs, scripts, scenes, and UI
- `Packages/` → Unity packages and dependencies
- `ProjectSettings/` → Project-wide settings (input, layers, URP, etc.)
- `.gitignore` → Git ignore settings for Unity temp files
- `.gitattributes` → Git LFS and merge settings

---

## 🚀 Project Setup + Getting Started (For New Developers)

### 1️⃣ Prerequisites
- Git installed
- Unity Hub installed
- **Unity 6.3 LTS** installed via Unity Hub

> ⚠️ Make sure you are using Unity Version 6.3 LTS


### 2️⃣ Clone the Repository
```bash
git clone https://github.com/viperfirestorm/Dino-Deluxe.git
cd Dino-Deluxe
```


### 3️⃣ Install Git LFS (Large File Support)
```bash
git lfs install
```


### 4️⃣ Open the Project in Unity
1. Open **Unity Hub → Projects → Add**
2. Navigate to the cloned `Dino-Deluxe` folder
3. Click **Select Folder → Add**
4. Click the project to open it

> Unity will import all assets. This may take a few minutes.


### 5️⃣ Verify Setup
- Make sure these folders appear in the Project window:
  - `Assets/`
  - `Packages/`
  - `ProjectSettings/`
- Open `Scenes/Gameplay.unity` to verify it loads correctly.


### 6️⃣ Pull Latest Changes Before Working
Before making any changes:

```bash
git pull origin main
git lfs pull