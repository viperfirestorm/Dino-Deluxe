# Dino-Deluxe — Developer Tips

Welcome to **Dino-Deluxe**! This guide provides helpful tips for new developers joining the project. Follow these to make your workflow smoother and avoid common pitfalls.

---

## ⚙️ Git & Version Control

- **Pull before you push:** Always run
```bash
git pull origin main
git lfs pull


---
before starting work. This ensures you have the latest changes and assets.

Commit small changes often — avoid huge bulk commits.

Do NOT commit temporary or local files:
Library/
Temp/
Obj/
Build/
Builds/
Logs/
MemoryCaptures/
UserSettings/
.DS_Store
*.csproj
*.sln

---

.

🗂 Unity Project Tips

Unity Version: Use Unity 6.3 LTS only. Other versions may break prefabs or scenes.

Version Control Settings in Unity:

Edit → Project Settings → Version Control → Visible Meta Files

Edit → Project Settings → Editor → Asset Serialization → Force Text

Recommended Folder Organization (inside Assets/):

Assets/
 ├─ Art/
 ├─ Audio/
 ├─ Prefabs/
 ├─ Scripts/
 ├─ Scenes/
 ├─ ScriptableObjects/
 └─ UI/

Scenes & Prefabs: Save often. Unity tracks changes via .meta and .prefab files.