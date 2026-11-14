# Assignment 5 - Travel Agency Landing Page

## Project: WanderLust Travels

A complete business landing page for a travel agency showcasing HTML and CSS fundamentals.

---

## 📁 Files:
- `index.html` - Main landing page
- `style.css` - Complete styling

---

## 🌟 Website Sections:

### 1. **Navigation Bar**
- Logo with emoji
- Menu links (Home, Services, Gallery, Reviews, Contact)
- Clean horizontal layout

### 2. **Hero Section**
- Full-screen background image
- Dark overlay for text contrast
- Large headline and tagline
- Call-to-action button
- Badge showing "500+ Happy Travelers"
- **Position & Z-index** used for layering

### 3. **About Section - 3 Different Card Styles**

**Card 1 - Simple Shadow:**
- White background
- `border-radius: 10px`
- `box-shadow` for depth
- Hover effect with transform

**Card 2 - Colored Border:**
- White background
- `border: 3px solid #ff6b6b`
- `border-radius: 15px`
- Hover changes background color

**Card 3 - Different Radius:**
- White background
- `border-radius: 20px`
- Colored shadow effect
- Hover with transform

### 4. **Services Section - 3 More Card Variants**

**Box 1 - White Card:**
- `border-radius: 12px`
- Clean shadow
- List of features

**Box 2 - Bordered Card:**
- `border: 2px solid #ff6b6b`
- `border-radius: 15px`
- Colored shadow

**Box 3 - Gradient Background:**
- `linear-gradient` background
- `border-radius: 18px`
- White text on colored background

### 5. **Gallery Section**
- 6 beautiful travel photos
- CSS Grid layout (3 columns)
- Hover zoom effect
- Images from Unsplash

### 6. **Testimonials/Reviews**
- 3 customer reviews
- Avatar circles with initials
- Star ratings (text)
- Card layout with shadows

### 7. **Contact Section**
- Contact information (address, phone, email)
- Contact form with:
  - Name input
  - Email input
  - Phone input
  - Destination dropdown
  - Message textarea
  - Submit button

### 8. **Footer**
- 4 columns with information
- Quick links
- Popular destinations
- Follow us links
- Copyright text

---

## 🎨 Design Features:

### Colors:
- Primary: #ff6b6b (coral red)
- Background: #f5f5f5 (light gray)
- Text: #333, #666, #555
- White cards for contrast

### Typography:
- Font: 'Poppins' from Google Fonts
- Headings: Bold and large
- Body: Regular weight, good line-height

### Layout Techniques:
- **Flexbox** for navigation, cards, reviews
- **CSS Grid** for gallery
- **Position absolute** for hero overlay and badge
- **Z-index** for layering elements

### Hover Effects:
- Scale transform on cards
- Color changes
- Background color transitions

---

## 🎯 CSS Concepts Used:

1. **Position & Z-index:**
   - `.overlay` - position: absolute, z-index: 1
   - `.hero-text` - position: relative, z-index: 2
   - `.trip-badge` - position: absolute, z-index: 3

2. **Different Border Radius:**
   - 10px, 15px, 18px, 20px variations

3. **Multiple Shadow Types:**
   - Simple: `0 3px 15px rgba(0,0,0,0.1)`
   - Colored: `0 0 20px rgba(255,107,107,0.3)`

4. **Background Images:**
   - Hero section full background
   - Gallery images as backgrounds
   - `background-size: cover`

5. **Layout:**
   - Flexbox for rows and columns
   - Grid for photo gallery
   - Responsive with basic media query

---

## 📱 Basic Responsive:

One media query at 768px:
- Cards stack vertically
- Gallery becomes single column
- Contact form stacks
- Hero text sizes reduced

---

## 🚀 How to View:

```powershell
Start-Process "index.html"
```

---

## 💼 Business Information:

**Company:** WanderLust Travels  
**Tagline:** "Your dream vacation starts here"  
**Services:**
- Flight Booking
- Hotel Booking
- Tour Packages

**Featured Destinations:**
- Bali, Indonesia
- Paris, France
- Dubai, UAE
- Maldives

---

## 🎓 Learning Objectives:

- Creating a complete business landing page
- Using position and z-index for layering
- Implementing different card styles (3 types)
- Working with background images
- Building functional forms
- Creating navigation and footer
- Basic responsive design
- Professional color schemes
- CSS transitions and transforms

---

## 📝 Notes:

- This is a basic responsive version
- For fully responsive optimized version, see Assignment 8
- Uses only HTML and CSS (no JavaScript)
- Images from Unsplash (free stock photos)

---

**Created by:** Ichhit Agarwal  
**Assignment:** 5 - Business Landing Page  
**Theme:** Travel Agency Website  
**Date:** November 2026
