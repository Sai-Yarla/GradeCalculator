# 📊 Grade Calculator

A beautiful, organic-designed grade calculator web application that helps students calculate weighted averages, determine final exam requirements, and compute GPA with ease.

---

## ✨ Features

### 🧮 Three Calculators
1. **Grade Calculator** — Calculate weighted averages from assignments, homework, exams, and coursework  
2. **Final Grade Calculator** — Find the grade needed on a final exam to hit a target course grade  
3. **GPA Calculator** — Compute weighted GPA using courses with different credit hours  

### ⚡ Smart Functionality
- 📊 Real-time calculations  
- 💾 Save & load multiple calculations (localStorage)  
- 📁 Manage saved calculations (view, load, delete)  
- 📄 Open multiple scenarios in new tabs  
- 🎛️ Adjustable decimal precision (1–4 places)  
- ➕ Dynamic rows for grades and courses  
- 📱 Fully responsive (desktop, tablet, mobile)  

---

## 🎨 Design System

### 🌿 Organic / Natural Philosophy
Inspired by:
- **Forest floors** — Moss greens, earth browns  
- **Clay pottery** — Warm terracotta tones  
- **Paper textures** — Subtle grain overlays  
- **Handcrafted aesthetics** — Soft curves, blob shapes, asymmetry  

### 🎨 Color Palette
| Role | Color |
|------|-------|
| Primary (Moss Green) | `#5D7052` |
| Secondary (Terracotta) | `#C18C5D` |
| Background | `#FDFCF8` |
| Foreground | `#2C2C24` |
| Accent | `#E6DCCD` |
| Muted | `#F0EBE5` |

### ✍️ Typography
- **Headings**: Fraunces (serif)  
- **Body**: Nunito (sans-serif)  
- **Scaling**: Responsive `clamp()` sizing  

### 🖼️ Visual Details
- Soft colored shadows (no harsh black)
- Organic blob-style border radii
- 3% opacity noise texture overlay
- Smooth 300–500ms transitions
- Pill-shaped buttons and inputs (50px radius)

---

## 🚀 Quick Start

### Opening the App
1. Download or clone the repository  
2. Open `index.html` in a modern browser  
3. Start calculating  

---

## 🧑‍🏫 Usage Guide

### Grade Calculator
1. Open **Grade Calculator** tab  
2. Enter grades (%) and weights (%)  
3. Add or remove rows as needed  
4. View weighted average instantly  
5. Set a target and calculate additional grade needed  

### Final Grade Calculator
1. Open **Final Grade Calculator** tab  
2. **Optional**: Toggle **Live Updates** for real-time calculations as you type  
3. Enter current grade and target grade  
4. Enter current + final exam weights (must total 100%)  
5. If Live Updates is OFF, click the button to calculate  
6. View required final exam grade  
   - **Live Updates enabled**: Results update instantly as you change values  
   - **Live Updates disabled**: Click button to calculate on demand  

### GPA Calculator
1. Open **GPA Calculator** tab  
2. Enter course name, grade, and credit hours  
3. Add courses as needed  
4. View GPA and total credits  

---

## 💾 Saving & Loading

### Save
1. Click **💾 Save Current**  
2. Name your calculation  
3. Save to browser storage  

### Load / Delete
1. Click **📁 Manage Saves**  
2. Load or delete any saved calculation  

### Multi-Scenario
- Use **📄 Open New Tab** for side-by-side comparisons  

---

## 📐 How the Math Works

### Weighted Average
```text
(w₁×g₁ + w₂×g₂ + … + wₙ×gₙ) / (w₁ + w₂ + … + wₙ)
