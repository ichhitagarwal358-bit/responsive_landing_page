# Assignment 3 - HTML Table with CSS

## Project: College Class Timetable

A comprehensive timetable demonstrating advanced HTML table features and CSS styling.

---

## 📁 Files:
- `table.html` - College timetable page
- `table.css` - Complete styling with CSS variables

---

## 📊 Table Features:

### Table Structure:
- ✅ **20+ Rows** - Including thead, 20 tbody rows, and tfoot
- ✅ **10 Columns** - Time, Mon-Sat, Room, Faculty, Credits
- ✅ **`<caption>`** - Weekly Class Schedule - Section A
- ✅ **`<thead>`** - Table header with column titles
- ✅ **`<tbody>`** - Main content rows
- ✅ **`<tfoot>`** - Summary/total row
- ✅ **`<th>` with scope** - Both scope="row" and scope="col"

### Advanced Table Features:

**Colspan Usage (2 instances):**
1. Tea Break row - spans all 10 columns
2. Lunch Break row - spans all 10 columns

**Rowspan Usage (2 instances):**
1. Lab - Web Dev - spans 2 time slots
2. Lab - DBMS - spans 2 time slots

---

## 🎨 CSS Features:

### CSS Variables in `:root`:
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    --bg-color: #ecf0f1;
    --border-color: #bdc3c7;
    --hover-color: #f39c12;
    --break-color: #ffe5b4;
    --lunch-color: #ffcccc;
    
    --table-padding: 12px;
    --border-radius: 8px;
    --font-size-base: 14px;
    --font-size-heading: 16px;
    --spacing-small: 10px;
    --spacing-medium: 20px;
    --spacing-large: 40px;
}
```

### Styling Features:
- ✅ **border-collapse: collapse** - Clean table borders
- ✅ **padding** - Proper cell spacing using variables
- ✅ **Striped rows** - `tr:nth-child(even)` for alternate colors
- ✅ **Hover effect** - Interactive row highlighting with transform
- ✅ **Gradient backgrounds** - Header and footer with gradients
- ✅ **Box shadows** - Depth and elevation
- ✅ **Border radius** - Rounded corners

---

## 📚 Content Details:

### Subjects Covered:
- Web Development
- Database Systems
- Operating System
- Computer Networks
- Software Engineering
- Machine Learning
- Artificial Intelligence
- Data Analytics
- Cloud Computing
- Cyber Security
- Research Method
- Technical Writing
- Project Work
- And more...

### Time Slots:
- Morning Classes: 9:00 AM - 1:15 PM
- Tea Break: 11:00 - 11:15 AM
- Lunch Break: 1:15 - 2:00 PM
- Afternoon/Evening: 2:00 PM - 9:00 PM
- Extra Classes for specialized topics

### Additional Info:
- Room numbers (201-408)
- Faculty names
- Credit hours per subject
- Lab sessions (2-hour blocks)
- Tutorial and seminar slots

---

## 🎯 Special Styling:

1. **Header:**
   - Gradient background (primary to secondary color)
   - White text
   - Bold font

2. **Break Rows:**
   - Tea Break: Light orange background
   - Lunch Break: Light pink background
   - Centered text with accent color

3. **Hover Effect:**
   - Background changes to orange
   - Text becomes white
   - Slight scale transform (1.02)
   - Box shadow appears
   - Smooth transitions

4. **Footer:**
   - Dark gradient background
   - Summary statistics
   - Bold white text

---

## 📱 Responsive Design:

**Tablet (max-width: 1200px):**
- Smaller font sizes
- Reduced padding

**Mobile (max-width: 768px):**
- Even smaller fonts
- Compact layout
- Minimal padding

---

## 🎓 Learning Objectives:

- Complex HTML table structure
- Semantic table elements (caption, thead, tbody, tfoot)
- Colspan and rowspan for merged cells
- CSS variables for maintainability
- Border-collapse property
- Pseudo-selectors (nth-child for striped rows)
- Hover effects with transforms
- Responsive table design
- Professional color schemes

---

## 🚀 How to View:

```powershell
Start-Process "table.html"
```

---

## 💡 Design Highlights:

- Clean and professional look
- Easy to read and navigate
- Color-coded special rows (breaks)
- Interactive hover feedback
- Consistent spacing using variables
- Mobile-friendly (scrollable)

---

**Created by:** Ichhit Agarwal  
**Assignment:** 3 - Complex HTML Table with CSS  
**Theme:** Computer Science Department Timetable  
**Date:** November 2026
