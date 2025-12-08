# Style Guide - Mystery Shack Website
## 1. Color Palette 
### Primary Colors Used
| Name | Value | Usage |
|------|-------|-------|
| **Dark Brown (translucent)** |`rgba(91,51,14,0.9)` | Navbar background, hero/history labels |
| **Light Gold** | `#d2b48c` | Borders, accents, quote borders, history image border |
| **Higlight Gold** | `#ffd700` | Link hover color, nav underline hover |
| **Off-White** | `#fffaf0` | Navigation link default text |
| **Alice Blue** | `aliceblue` | Headings, footer text, hero/history blocks |
| **Overlay Black** | `rgba(0,0,0,0.6)` | Image hover overlay |

### Some Supporting Colors/Backgrounds

- Drop-shadow glow: `rgba(255,215,0,0.4-0.9)`
- Black (text shadows, outlines)
- Gravity Falls wallpaper (background image)

---

## 2. Typography

### Global Font
font-family: Arial, sans-serif;

### Headings

- **H1**
   - Color: `aliceblue`
   - Size: `48px`
   - Text-shadow: `2px 2px 8px black`
   - Padding-left: `10%

## 3. Layout Structure

### Navigation Bar

- Sticky (`position: sticky; top: 0`)
- Background: `rgba(91,51,14,0.9)`
- Box shadow: `0 4px 12px rgba(0,0,0,0.6)`
- Bottom border: `3px solid #d2b48c`
- Link hover effects:
  - Gold underline animation
  - Gold hover color (`#ffd700`)
  - Slight scale transform

 ### Image Grid Layout

 display: grid;
 grid-template-columns: repeat(3,1fr);
 gap: 20px;
 width: 90%;
 max-width: 1000px;
 margin: 0 auto;
 
## 4. Components

### Hero Section
- centered heading and paragraph
- Brown translucent text blocks

### History Section
- Styled Headers and paragraphs
- Images:
  - Border: `5px solid #d2b48c`
  - Shadow: `0 4px 12px rgba(0,0,0,0.7)`
  - Centered
 
### Footer
- Text Color: `aliceblue`
- Form uses the default browser styling

### Quote Bar

- Black translucent background
- Gold borders on top and bottom
- A hover glow effect added

---

## 5. Hover and Animation

### Navigation hover
- Gold text color
- Animated underline
- Transform scale effect

### Lantern Animation
- Flickering glow using `drop-shadow`
- Opacity changes from 0.85 to 1
- Has a 3-second loop

## 6. Visuals

### Global Background
- Gravity Falls wallpaper
  `Images/wallpaper_gravityfalls.png`

### Page Images
- PNG/JPG character & shop images
- Staff grid images:
  - Hover zoom
  - Fade-in overlay
- History image:
   - Gold border
   - Shadow

### Lantern

- Fixed bottom-right position
- Flicker animation
- File:
  `Images/pngimg.com - lantern_PNG1.png`

---

## 7. Tone and Mood

- **Funny and Playful**
- **Leans into tourist-trap/cabin in the woods vibe**
- **References some of the lore from Gravity Falls and the setting**
- **Intentionally chaotic and all over the place**
- **Silly, mysterious, and fun (on brand with the series)**
