# 🧩 Quick Texture Baker

**Quick Texture Baker** is a lightweight ![Blender 5.1+](https://img.shields.io/badge/Blender-5.1%2B-orange?logo=blender) add-on designed for artists, modders, and developers who want to **create and bake textures quickly** without navigating deep into Blender’s shader or render settings.

It automates **image texture node creation** and **diffuse baking** for the selected mesh, making it perfect for both manual workflows and automated 3D pipelines.

---

## 🖼️ Preview

![Quick Texture Baker Demo](./preview.gif)
_(Example: Baking a texture in seconds using the Quick Texture Baker panel)_

---

## ✨ Features

- 🖼️ **Create Image Texture Nodes** — Instantly create a new texture node and assign a 1024×1024 image.
- 🔥 **One-Click Baking** — Bake the selected mesh’s material directly to the chosen image (Diffuse only).
- ⚙️ **Automatic Setup** — Automatically configures render engine (Cycles) and bake settings.
- 🧠 **Smart Handling** — Detects missing materials, existing images, and prevents bake errors.
- 🎨 **Ideal For:** Model preparation, character baking, or texture export pipelines.

---

## 🧩 Installation (In Blender)

1. Click this button to download the add-on ZIP:  
   [![Download Add-on](https://img.shields.io/badge/⬇️%20Download%20Addon-ZIP-blue?style=for-the-badge&logo=github)](https://github.com/Sudhanshu-Ambastha/Quick-Texture-Baker/releases/download/V-1.1.0/QUICK-TEXTURE-BAKER.zip)

2. Go to **Edit → Preferences → Add-ons → Install** 3. Select the downloaded **`.zip` file** 4. Enable ✅ **Quick Texture Baker** in the add-ons list

---

## 🚀 Usage

1. **Select an object** that has a material applied
2. Open **Sidebar → Quick Texture Baker** (in the **3D Viewport**)
3. Enter a **Texture Name** (e.g., `Body`, `Hand`, etc.)
4. Click **Create Texture Node** — a new image texture node is created and linked automatically
5. Click **Bake to Texture (Diffuse)** — the add-on will automatically:
   - Switch the render engine to **Cycles** - Set the bake type to **Diffuse** - Disable **Direct** and **Indirect** lighting
   - Bake to the **selected image texture node**

✅ The baked texture will appear in the **Image Editor** and be stored in **Blender’s image data** list.

---

## 📜 License

This add-on is released under the **GNU General Public License v3.0 (GPLv3)**.  
See the [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE) for details.

**© 2026 Sudhanshu Ambastha**
