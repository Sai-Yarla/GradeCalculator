# ðŸ“Š Grade Calculator

A beautiful, organic-designed grade calculator web application that helps students calculate weighted averages, determine final exam requirements, and compute GPA with ease.

## âœ¨ Features

### Three Powerful Calculators
1. **Grade Calculator** - Calculate weighted average grades from multiple assignments, homework, exams, and other coursework
2. **Final Grade Calculator** - Determine what grade you need on your final exam to reach your target course grade
3. **GPA Calculator** - Calculate weighted GPA based on courses with different credit hours or points

### Smart Functionality
- ðŸ“Š **Real-time Calculations** - Results update as you enter data
- ðŸ’¾ **Save & Load** - Save multiple calculations with custom names to browser storage
- ðŸ“ **Manage Saves** - View all saved calculations, load them, or delete them
- ðŸ“„ **Open New Tabs** - Calculate multiple scenarios simultaneously in separate browser tabs
- ðŸŽ›ï¸ **Decimal Precision** - Choose 1-4 decimal places for result accuracy
- âž• **Dynamic Rows** - Add or remove grades/courses as needed
- ðŸ“± **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices

## ðŸŽ¨ Design System

### Organic / Natural Design Philosophy
The interface embraces a warm, natural aesthetic inspired by:
- **Forest floors** - Moss greens and earth browns
- **Clay pottery** - Warm terracotta tones
- **Paper texture** - Subtle grain overlay
- **Handcrafted feel** - Organic blob shapes, soft curves, and asymmetric design

### Color Palette
- **Primary (Moss Green)**: `#5D7052` - Main accent and interactive elements
- **Secondary (Terracotta)**: `#C18C5D` - Complementary warm tone
- **Background**: `#FDFCF8` - Soft off-white rice paper
- **Foreground**: `#2C2C24` - Deep loam charcoal text
- **Accent**: `#E6DCCD` - Sand/beige highlight
- **Muted**: `#F0EBE5` - Stone gray secondary tone

### Typography
- **Headings**: Fraunces (serif) - Warm, old-world character with modern softness
- **Body**: Nunito (sans-serif) - Clean with rounded terminals matching organic shapes
- **Scale**: Responsive sizing with clamp() for fluid scaling

### Visual Features
- **Soft Shadows** - Colored shadows with moss or clay tints instead of harsh black
- **Organic Shapes** - Complex border-radius values create natural blob shapes
- **Texture Overlay** - Subtle noise pattern at 3% opacity for paper-like quality
- **Smooth Interactions** - All transitions use 300-500ms durations for natural feel
- **Rounded Pills** - All buttons and inputs use 50px border-radius for warmth

## ðŸš€ Quick Start

### Opening the Calculator
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. Start calculating!

### Basic Usage

#### Grade Calculator
1. Click on the "Grade Calculator" tab
2. Enter your assignments, grades (%), and weights (%)
3. Click "Add Assignment" to add more rows
4. View your weighted average in the results section
5. Set a target average and click "Calculate Additional Grade" to see what you need

#### Final Grade Calculator
1. Click on the "Final Grade Calculator" tab
2. Enter your current grade (%)
3. Set your target grade (%)
4. Specify current and final exam weights (should total 100%)
5. Click "Calculate Final Exam Grade Needed"
6. See the exact grade required on your final exam

#### GPA Calculator
1. Click on the "GPA Calculator" tab
2. Enter course names, grades (%), and credit hours
3. Click "Add Course" to add more courses
4. View your weighted GPA and total credits

### Saving & Loading Calculations

**Save Current Calculation:**
1. Click the "ðŸ’¾ Save Current" button
2. Enter a name (e.g., "Fall 2024 Semester")
3. Click "Save"

**Load Saved Calculation:**
1. Click the "ðŸ“ Manage Saves" button
2. View all saved calculations with timestamps
3. Click "Load" next to any calculation to restore it
4. Click "Delete" to remove a saved calculation

**Open New Tab:**
- Click "ðŸ“„ Open New Tab" to calculate multiple scenarios simultaneously

## ðŸ“ How the Math Works

### Weighted Grade Calculation
```
Weighted Average = (wâ‚Ã—gâ‚ + wâ‚‚Ã—gâ‚‚ + ... wâ‚™Ã—gâ‚™) / (wâ‚ + wâ‚‚ + ... wâ‚™)
```

**Example:**
- Math (Grade 85, Weight 3) = 85 Ã— 3 = 255
- English (Grade 90, Weight 3) = 90 Ã— 3 = 270
- Science (Grade 88, Weight 4) = 88 Ã— 4 = 352
- **Total**: (255 + 270 + 352) / (3 + 3 + 4) = 877 / 10 = **87.7**

### Final Exam Grade Required
```
Final Grade Needed = (Target Grade - Current Grade Ã— Current Weight%) / Final Exam Weight%
```

**Example:**
- Current Grade: 82%
- Current Weight: 80%
- Target Grade: 90%
- Final Exam Weight: 20%
- **Required**: (90 - 82 Ã— 0.8) / 0.2 = (90 - 65.6) / 0.2 = **122%** (impossible)

## ðŸŽ¯ Design Details

### Components

**Buttons**
- Rounded pills with moss green primary and terracotta secondary colors
- Hover effect: 105% scale with deepened shadow
- Active effect: 95% scale for tactile feedback
- Smooth transitions at 300ms

**Input Fields**
- Pill-shaped (50px border-radius)
- Translucent white background revealing texture beneath
- Soft moss-tinted focus ring with 3px offset
- Smooth transition on focus

**Cards & Containers**
- Rounded 24-32px corners
- Soft timber borders at 50% opacity
- Moss-tinted shadows for depth
- Subtle grain texture overlay

**Tables**
- Gradient header with moss to terracotta
- Hover state fills with subtle moss tint
- Organic card-like container with rounded corners
- Responsive input sizing

**Modals**
- Glassmorphism with backdrop blur
- Organic 32px border-radius
- Dark semi-transparent background
- Smooth fade-in animation

### Responsive Breakpoints
- **Desktop (>768px)**: Full layout with side-by-side grids
- **Tablet (â‰¤768px)**: Single column layout, full-width buttons
- **Mobile (â‰¤480px)**: Compact spacing, optimized touch targets

## ðŸ”§ Customization

### Changing Colors
Edit the CSS variables in the `<style>` section:
```css
:root {
    --primary: #5D7052;      /* Moss green */
    --secondary: #C18C5D;    /* Terracotta */
    --background: #FDFCF8;   /* Off-white */
    /* ... other colors ... */
}
```

### Adjusting Typography
Modify font declarations:
```css
--font-serif: 'Fraunces', serif;  /* Headers */
--font-sans: 'Nunito', sans-serif; /* Body */
```

### Modifying Shadow Depth
Adjust shadow variables:
```css
--shadow-soft: 0 4px 20px -2px rgba(93, 112, 82, 0.15);
--shadow-float: 0 10px 40px -10px rgba(193, 140, 93, 0.2);
```

## ðŸ’¾ Data Storage

All calculations are saved to **browser local storage** (`localStorage`):
- Saved under key: `gradeCalculatorSaves`
- Data format: JSON object with calculation data
- Persists between browser sessions
- Cleared when browser cache is cleared

### Data Structure
```json
{
  "Fall 2024": {
    "tab": "grade-calc",
    "timestamp": "1/8/2026, 2:30:45 PM",
    "grades": [
      { "name": "Assignment", "grade": "100", "weight": "10" },
      // ...
    ],
    "targetAverage": "80",
    "decimalPlaces": "2"
  }
}
```

## ðŸŒ Browser Support
- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge
- Any modern browser with ES6+ JavaScript support

## â™¿ Accessibility

- **Contrast Ratios**: WCAG AA/AAA compliant
  - Primary text on background: 14.5:1 (AAA)
  - Moss on background: 6.2:1 (AA)
- **Focus States**: Clear 2px ring with offset for keyboard navigation
- **Touch Targets**: All interactive elements â‰¥48px height
- **Semantic HTML**: Proper heading hierarchy, form labels, alt text
- **Keyboard Navigation**: Fully keyboard accessible, all features usable without mouse

## ðŸ“ Tips & Tricks

### Maximize Accuracy
- Use consistent decimal places across all inputs
- Double-check weight percentages total to 100% for final grade calculator
- Save calculations before major changes to compare results

### Compare Scenarios
- Use "Open New Tab" feature to run side-by-side comparisons
- Save multiple "what-if" scenarios with descriptive names
- Test different study targets to understand effort needed

### Grade Improvement Planning
- Work backwards from target grade using Final Grade Calculator
- Identify which assignments have highest weight
- Focus study time on weighted high-value assessments

## ðŸ› Troubleshooting

**Calculations showing 0?**
- Ensure you've entered both grade and weight values
- Check that at least one row has valid data

**Weights don't add to 100%?**
- The calculator will show a warning in Final Grade Calculator
- Adjust individual weights or remove unnecessary rows

**Saved calculations disappeared?**
- Check if browser cache/storage was cleared
- Use "Manage Saves" to verify saved items exist
- Consider exporting important calculations

**Mobile layout issues?**
- Zoom out slightly if text appears cut off
- Rotate device to landscape for better table view
- Try different browser if issues persist

## ðŸ“„ License

Free to use, modify, and distribute. Built with â¤ï¸ using the organic design philosophy.

## ðŸŽ“ Educational Use

Perfect for:
- Students tracking semester grades
- Teachers calculating final grades
- Academic advisors planning course loads
- Parents monitoring student progress

## ðŸŒ± Design Philosophy

This calculator embodies the principle that **"there are no straight lines in nature."** Every interaction feels organic, warm, and humanâ€”not cold or mechanical. The soft shadows, rounded shapes, and earth tones create a peaceful, welcoming space for academic planning.

---

**Version**: 1.0  
**Last Updated**: January 8, 2026  
**Created by**: Grade Calculator Team
