
**PREVIEW:**

![spotify1](https://user-images.githubusercontent.com/57992120/149266534-dd6c48b6-c156-40bb-ac0d-9e5c4310d136.png)

---
**FOR THOSE WHO DONT HAVE SPICEFY YET:**
- Spicetify Download: https://github.com/khanhas/spicetify-cli
- Youtube Tutorial: https://www.youtube.com/watch?v=PoSidNiRu-g

---

⚠️️**DONT FORGET TO DOWNLOAD THE ZIP FILE AND IMPORT IT TO THE `THEMES` FOLDER IN `.SPICEFIY`**⚠️️
![unknown](https://user-images.githubusercontent.com/57992120/149071826-9db637c3-20cc-497f-ae94-e6f597e91b47.png)

---

- If you want to have the image header on a playlist, move the `Comfy.js` file to the `Extensions` folder and do:
```
spicetify config extensions Comfy.js
```

*(The image header changes depending on the banner of the selected song)*

---
**!!ALL OF THE TEXT BELOW IS WRITTEN BY THE ORIGINAL CREATOR: NYRI4 https://github.com/NYRI4/Comfy-spicetify!!**
---
### 📥 Installation

Go into your **Windows Powershell** and type :
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
