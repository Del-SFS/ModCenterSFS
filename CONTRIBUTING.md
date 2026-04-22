# 🤝 Contributing to ModCenterSFS

Thank you for contributing to **SCAN (SFS Comprehensive Archive Network)**.

This repository is designed to be **machine-readable**, so all submissions must strictly follow the required format.


## ⚡ Quick Start (2 minutes)

1. Download a mod
2. Create a folder with the mod name
3. Add:
   - ModName.zip (ONLY mod files)
   - mod.json
4. Zip the folder
5. Open a Pull Request

You're done.


# 📦 Mod Submission Workflow #

Follow this process exactly to ensure your mod works correctly with SCAN.

### 1. Download the Mod

Download the mod in its original `.zip` format.

### 2. Validate the Mod ZIP

The mod `.zip` must contain ONLY the mod files.

### ✅ Correct structure:

```
Mod/
├──Mod.zip
├──mod.json
```
then compress the folder with mod.zip and mod.json

### 3. Create a Mod Folder 

Create a folder using the mod name

`ModName/`

### 4. Create mod.json 

Inside the folder, create a file named:

**mod.json**
standard:

```
{
    "nome": "ModName",
    "autor": "Author",
    "versao": "1.0.0",
    "descricao": "Description",
    "tipo": "DLL / Parts / Texture / System",
    "dependencias": [],
    "conflitos": [],
    "download": "URL",
    "tamanho": "MB"
}
```

### 5. Add Files

Place both files inside the folder:

```
ModName/
 ├── ModName.zip
 └── mod.json
 ```

### 6. Final Packaging ##

Compress the folder into a final `.zip`:

```
ModName.zip
 ├── ModName.zip
 └── mod.json
```

### 📌 Final Structure Summary

```
FinalFile.zip 
 ├── ModName.zip 
 |   └──mod.dll .pack etc... 
 └── mod.json  
 ```

## 🚀 How to Submit

Fork the repository on GitHub

```
# Fork the repository on GitHub

git clone https://github.com/YOUR-USERNAME/ModCenterSFS
cd ModCenterSFS

# Add your mod

git add .
git commit -m "Add ModName"
git push origin main
```

Then open a Pull Request on GitHub.

**📌 Rules**

Follow the required structure strictly
Ensure mod.json is valid
Do not upload broken or incomplete mods
Avoid duplicate submissions

## 🧠 Notes ##

SCAN depends on correct formatting.

Invalid submissions may be rejected automatically.

## 💡 Need Help? ##

contact the [Del](DelDoSFS@outlook.com)

👨‍💻 Maintained by ***Del***
