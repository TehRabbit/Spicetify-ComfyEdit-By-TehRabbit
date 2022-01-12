**PREVIEW:**

![ab0ec9bb-b2bd-4a38-a727-c0f99de2bd14](https://user-images.githubusercontent.com/57992120/149066086-a83c7e5e-0da7-4990-911f-17a1e4a5bc99.jpg)

---
⚠️️**DONT FORGET TO DOWNLOAD THE ZIP FILE AND IMPORT IT TO THE "THEMES" FOLDER IN ".SPICEFIY"**⚠️️

*- If you want to have the image header on a playlist, move the "Comfy.js" file to the "Extensions" folder and do:*
``` spicetify config extensions Comfy.js
```

---
**!!ALL OF THE TEXT BELOW IS WRITTEN BY THE ORIGINAL CREATOR: NYRI4 https://github.com/NYRI4/Comfy-spicetify!!**

### 📥 Installation

Go into your `Themes` folder in `.spicetify` then do :
```sh
git clone https://github.com/NYRI4/Comfy-spicetify
```

#### Windows
In **Powershell**:
```powershell
spicetify config current_theme Comfy-spicetify
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

#### macOS and Linux
In **Bash**:
```bash
spicetify config current_theme Comfy-spicetify
spicetify config inject_css 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

If you want to have the image header on a playlist, move the `Comfy.js` file to the `Extensions` folder and do :

#### Windows
In **Powershell**:
```powershell
cd "$(spicetify -c | Split-Path)\Themes\Comfy-spicetify"
Copy-Item Comfy.js ..\..\Extensions
spicetify config extensions Comfy.js
spicetify apply
```

#### macOS and Linux
In **Bash**:
```bash
cd "$(dirname "$(spicetify -c)")/Themes/Comfy-spicetify"
mkdir -p ../../Extensions
cp Comfy.js ../../Extensions/.
spicetify config extensions Comfy.js
spicetify apply
```

### ⚠️️ Warning

---

The theme part is now updating itself for users using the version of Spicetify equals or greater than `2.8.2`, however, for the extesnion part if you have issues with it : 

1. Go [here](https://nyri4.github.io/Comfy-spicetify/Comfy.js)
2. Copy the whole code (sorry for the flashbang)
3. Go into the Spicetify extension folder
4. Open the `Comfy.js` file, paste the code and **save it**
4. Afterwards, in a terminal, run `spicetify apply`
5. Enjoy !

For the users that don't want to update Spicetify to the newest version, do the same with [this](https://nyri4.github.io/Comfy-spicetify/Comfy.js) and paste it in the `user.css` replacing the `@import`.
