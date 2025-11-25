# Porcelain & Azure (青花汝窯) - Obsidian CSS Snippet

A custom CSS snippet for [Obsidian.md](https://obsidian.md/), inspired by the aesthetics of traditional Chinese ceramics. This theme blends the serenity of **Ru Ware (Ru Kiln)** with the classic contrast of **Blue and White Porcelain**.

## 🎨 Design Philosophy

This styling focuses on texture, depth, and a calm reading environment.

### ☀️ Light Mode: "Ru Foundation, Blue Application"
* **Base:** Modeled after the "Ru Kiln" (Celadon) aesthetic. Soft, off-white backgrounds (`#F2F7F7`) with a hint of warmth, avoiding harsh pure whites.
* **Text:** Deep Prussian Blue (`#1A2F45`) for bold text, resembling ink on paper.
* **Accents:** Gradient headers inspired by the varying shades of cobalt blue found in Blue & White porcelain.

### 🌙 Dark Mode: "Blue Ocean, Ru Stars"
* **Base:** A deep, immersive navy (`#0F1626`) representing the ocean depth.
* **Text:** Pale Cyan and "Sand Gold" (`#DCD0B3`) for bold text, ensuring high legibility without eye strain.
* **Accents:** Teals and Cyans that glow like stars or phosphorescence against the dark background.

## ✨ Key Features

### 1. "Glazed" 3D Callouts
Callouts have been redesigned to feel like physical objects with a "glazed" ceramic texture.
* **Subtle Bulge:** A combination of inner highlights and outer shadows creates a gentle, rounded 3D effect.
* **Tactile Feel:** They float slightly above the page, with distinct styling for Light (translucent glaze) and Dark (deep glass) modes.

### 2. Refined Typography & Hierarchy
* **Gradient Headers:** H1 through H3 feature subtle color gradients (Cobalt to Blue-Grey).
* **Underglaze Red Accents:** Uses a distinct "Seal Red" (`#B22222`) for strong emphasis, horizontal rules (`hr`), and brackets (`[[ ]]`), creating a classic "Red & Black/Blue" contrast.
* **Lists:** Harmonized bullet points and numbers in the main accent color.

### 3. UI & UX Improvements
* **MacOS Scrollbar Fix:** Custom slim scrollbars that float elegantly, fixing the default bulky MacOS appearance.
* **Checkbox Micro-interactions:** Clean, solid borders with muted text for completed tasks.
* **Graph View:** Colors synchronized with the theme palette for a cohesive look.

## 🛠️ Installation

1. Download the `porcelain-azure.css` file (or copy the code).
2. Open your Obsidian vault folder.
3. Navigate to `.obsidian/snippets/`.
4. Paste the file there.
5. Open Obsidian **Settings** > **Appearance**.
6. Under **CSS Snippets**, toggle on `porcelain-azure`.

## ⚙️ Customization

The CSS is heavily commented and uses CSS Variables (Custom Properties) for easy tweaking. You can find the palette definitions at the top of the file:

```css
/* Example Variable Structure */
.theme-light {
  --user-bg-white: #F2F7F7;      /* Background */
  --user-accent-main: #346c9c;   /* Main Blue */
  --user-accent-strong: #B22222; /* Red Accent */
}