# Contributing to ModCenterSFS

Thank you for contributing to the SCAN Mod Database.

This repository stores mods that can be installed automatically using SCAN.

---

# 🚀 How to Add a Mod

Follow this EXACT process:

## 1. Download your mod
- The mod must be in `.zip` format

## 2. Create a folder
The folder name must match your mod name:

`TYPE/YourModName/`

Example:

`Parts/MyCoolMod/`

## 3. Add required files

Inside the folder:
```
YourModName/
├── YourModName.zip 
└── mod.json
```

## 4. Create mod.json

Example:

```json
{
  "name": "MyCoolMod",
  "author": "YourName",
  "version": "1.0.0",
  "type": "DLL",
  "description": "Describe your mod"
}
```

## 📦 Zip Structure Rules (VERY IMPORTANT)

✅ DLL / .pack mods

Zip must contain ONLY the file:

```
MyCoolMod.zip 
  └── mod.dll
```

OR 

```
MyCoolMod.zip 
 └── mod.pack
 ```

✔ No folders allowed

✅ Texture / Solar mods

Zip can contain folders:

```
MyCoolMod.zip
  └── SolarSystem/
```

```
MyCoolMod.zip
  └── Textures/
```

✔ Keep original structure
✔ Do NOT modify anything

❌ Invalid structure 

```
MyCoolMod.zip 
 └── MyCoolMod/ 
     └── mod.dll
```

❌ Nested folders are NOT allowed

## 📁 Types

Use ONLY these values in "type":

mod 
parts 
texture 
solar 

## ⚠️ Rules

Folder name = mod name 
Zip name = mod name 
Must include mod.json 
No broken or incomplete mods 
No invalid zip structure 

## 🔄 Final Step

Open a Pull Request with your mod.

## 🎯 Goal

Make mods easy to install using SCAN.

Your contribution helps build a reliable mod ecosystem.
