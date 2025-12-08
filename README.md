<img width="1560" height="866" alt="image" src="https://github.com/user-attachments/assets/d7540926-0b0c-42d1-aa62-9873c167af37" />
***

# GTA SA FXP Editor

A simple browser tool to edit **GTA: San Andreas** particle files (`.fxp`). It lets you tweak effects and see changes instantly without restarting the game every time.

## ✅ What it does
* **Instant Preview:** See your particles move and change color in real-time.
* **Full Editing:** Change every property (Speed, Life, Color, Size, etc.) using a timeline table.
* **Texture Support:** Load your local `.png` images to see the actual textures on the particles.
* **Fixes Files:** Automatically fixes common errors in FXP files (like duplicate LENGTH lines) when saving.
* **Easy Export:** Copy the file content to your clipboard or save as `.fxp`.

## 🚀 How to use
1.  **Open:** Click **File > Open FXP** and pick your file. .fxs(single PArticle System) is also supported.
2.  **Textures:** Click **Load Textures** and select the *folder* where your .png images are.
3.  **Edit:** Click items in the tree (left) and change values in the table (bottom).
    * Use the **+** button on the timeline to add keyframes.
    * Use the **+** button in the tree to add new Emitters or Info blocks.
4.  **Save:** Click **File > Save FXP** or **Copy to Clipboard**.

## ⚠️ Known Issues & Limitations
* **Rendering:** This is a web preview. It is **not** 1:1 with the game engine. Always check the final result in GTA.
* **Visuals:** `FLAT` and `DIR` (directional) particles do not render correctly yet.
* **Trails:** Ribbon trails are experimental and may look glitchy.

## 📝 Planned Features
* **Single Effect Export:** Save just one System/Effect instead of the whole file.
* **Copy/Paste:** Ability to copy Systems and Info blocks between emitters.


<img width="1152" height="1051" alt="image" src="https://github.com/user-attachments/assets/d5fa0322-bf41-489f-924d-538423b41c27" />
<img width="750" height="196" alt="image" src="https://github.com/user-attachments/assets/163356ef-0444-4173-93c6-ebdc5a943c85" />
