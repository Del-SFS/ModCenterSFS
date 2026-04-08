
## 🚀 SCAN | SFS Comprehensive Archive Network ##
Central Repository: ModCenterSFS
This is the official repository powering SCAN, the automated mod manager for Spaceflight Simulator. We centralize metadata and download links here to ensure the community always has access to the latest mod versions.

## 📂 The ModCenterSFS Project ##
ModCenterSFS is more than just a folder of files; it is a dynamic database in JSON format.

repo.json: The "brain" of the project. It contains the list of all active mod links.

Individual .json files: Each mod has its own configuration file containing:

Current version.

Direct download link.

Required dependencies.

Technical description.

## 🖥️ The SCAN Software ##
SCAN is a smart installer developed in Python that reads this repository in real-time to automate your game setup.

## 🛠️ Key Features ##
Auto-Update: Automatically checks for new mod versions every time you launch the app.

Smart Folder Mapping: SCAN knows exactly where each file belongs:
| Mod Type | SFS Destination |
| :--- | :--- |
| DLL | /Mods |
| Parts | /Custom Assets/Parts |
| Textures | /Custom Assets/Texture Packs |
| Solar Systems | /Spaceflight Simulator_Data/Custom Solar Systems |
---
👨‍💻 Credits and Development
Lead Developer: Del

Platform: Spaceflight Simulator (PC Version) of Spaceflight Simulator is a registered trademark of **Stefo Mai Morojna**.
