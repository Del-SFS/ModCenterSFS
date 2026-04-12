# 🤝 Contributing to ModCenterSFS

Thanks for your interest in contributing to **ModCenterSFS**!  
This repository powers the SCAN system for managing mods in Spaceflight Simulator.

We welcome all contributions — from adding new mods to improving the structure of the project.

---

# 📦 Ways to Contribute

You can help in several ways:

- ➕ Add new mods
- 🐞 Fix broken mod entries
- 🔧 Improve JSON structure
- 📚 Improve documentation
- 💡 Suggest new features for SCAN

# 🔀 Contribution Workflow

1. Fork the repository  
2. Create a new branch:
   ```bash
   git checkout -b my-feature
3. Make your changes

4. Commit:
```bash
git commit -m "Add: new mod or improvement"

```
5. Push to your fork:
```
git push origin my-feature
```
6. Open a Pull Request

# ➕ Adding a New Mod #
📁 Step 1: Create the file

Create a new .json file inside:
```
Mods/
```
🧾 Step 2: Follow the standard format
```
{
  "nome": "Mod Name",
  "autor": "Author",
  "versao": "1.0.0",
  "descricao": "Short description",
  "tipo": "Parts / DLL / Texture / System",
  "dependencias": [],
  "conflitos": [],
  "download": "Direct download link",
  "tamanho": "File size (MB)"
}
```
✅ Step 3: Validate your mod

Before submitting, ensure:

- ✔ JSON is valid (no syntax errors)
- ✔ Download link works
- ✔ Version is correct
- ✔ Dependencies are listed (if any)
- ✔ No duplicate mods exist

# ⚠️ Rules & Guidelines
Do NOT submit broken or fake links
Keep formatting clean and consistent
Use clear and accurate descriptions
Avoid duplicate entries
Respect other contributors' work

# 🐞 Reporting Issues

If you find a problem, please open an Issue and include:

- Mod name
- Description of the issue
- Screenshot (if possible)
- Suggested fix (optional)

# 💡 Suggesting Features
Have an idea for SCAN or the repo?

Open an Issue with:

- Feature description
- Use case
- Optional implementation idea

# 🧠 Development Notes
This repo acts as a JSON-based mod database
SCAN reads repo.json to install mods
Structure consistency is critical
- 👨‍💻 Code of Conduct
- Be respectful
- Be constructive
- Help others learn
- 🚀 Final Notes

Even small contributions matter.
By contributing, you help improve the entire Spaceflight Simulator modding community.

**Thanks for being part of the project 💙** *del*
