# Assignment 2 - Internship Application Form

## Project: Student Internship Application Form

A complete HTML form demonstrating various input types and form elements.

---

## 📁 Files:
- `from.html` - Main form page (HTML)
- `from.css` - Basic styling for the form

---

## 📋 Form Fields Included:

### Basic Information:
- ✅ Full Name (text input, required)
- ✅ Email (email input with validation, required)
- ✅ Password (password input, required)
- ✅ Phone Number (tel input, required)
- ✅ Portfolio URL (url input, optional)
- ✅ Age (number input with min validation, required)

### Personal Details:
- ✅ Gender (radio buttons - Male/Female/Other)

### Education Section:
- ✅ Course (dropdown/select menu)
  - B.Tech Computer Science & Engineering
  - B.Tech Electrical Engineering
  - B.Tech Mechanical Engineering
  - Other

### Preferences:
- ✅ Preferred City (dropdown)
  - Bareilly, Delhi, Mumbai, Bangalore, Other

### Skills:
- ✅ Skills Selection (checkboxes)
  - HTML
  - CSS
  - JavaScript

### Upload & Extras:
- ✅ Available From (date picker)
- ✅ Interview Time (time picker)
- ✅ Resume Upload (file input - accepts .pdf, .doc, .docx)
- ✅ Expected Stipend (range slider with live value display)
- ✅ Favourite Colour (color picker)
- ✅ Reason for Application (textarea with min/max length)

### Form Controls:
- ✅ Submit button
- ✅ Reset button

---

## 🎯 HTML Input Types Demonstrated:

1. `type="text"` - Text input
2. `type="email"` - Email validation
3. `type="password"` - Password field
4. `type="tel"` - Phone number
5. `type="url"` - URL input
6. `type="number"` - Numeric input with min/max
7. `type="radio"` - Radio buttons
8. `type="checkbox"` - Checkboxes
9. `type="date"` - Date picker
10. `type="time"` - Time picker
11. `type="file"` - File upload
12. `type="range"` - Range slider
13. `type="color"` - Color picker
14. `<select>` - Dropdown menu
15. `<textarea>` - Multi-line text input

---

## 🎨 Styling:

- Background: Light green gradient
- Form elements: Green color scheme
- Legend: Dark green background with white text
- Input styling: Simple with placeholders
- Fieldset for organization

---

## ✨ Special Features:

1. **Live Stipend Display:**
   - Range slider shows selected value in real-time
   - Updates as you move the slider
   - Displays in Indian Rupees format

2. **Form Validation:**
   - Required fields marked with asterisk (*)
   - Email validation
   - Phone number format
   - Minimum age requirement
   - Textarea character limits (50-500 chars)

3. **File Upload:**
   - Accepts specific formats (.pdf, .doc, .docx)
   - Required field for resume submission

---

## 🚀 How to View:

```powershell
Start-Process "from.html"
```

---

## 📝 Form Structure:

```
Internship Application Form
├── Basic Info (Name, Email, Password, Phone, Portfolio, Age)
├── Gender Selection (Radio Buttons)
└── Education Fieldset
    ├── Course (Dropdown)
    ├── Preferred City (Dropdown)
    ├── Skills (Checkboxes)
    └── Uploads & Extras
        ├── Available Date
        ├── Interview Time
        ├── Resume Upload
        ├── Expected Stipend (Slider)
        ├── Favourite Color
        └── Reason (Textarea)
```

---

## 🎓 Learning Objectives:

- Understanding different HTML input types
- Form validation attributes (required, min, max, minlength, maxlength)
- Organizing forms with fieldset and legend
- File upload handling
- Interactive elements (range slider with JavaScript)
- Proper form structure and accessibility

---

**Created by:** Ichhit Agarwal  
**Assignment:** 2 - HTML Forms Practice  
**Date:** November 2026
