# OLX Sample Website - Testing Project

## 📋 Project Overview

A sample e-commerce website inspired by OLX (Online Shopping Platform) created for testing and demonstration purposes. This project showcases a multi-category marketplace where users can browse and add items to their cart across different product categories.

## 🎯 Project Details

**Project Type:** Software Testing Lab Project  
**Course:** Diploma in Computer Science  
**Technologies Used:** HTML, JavaScript  
**Testing Type:** Sample Website Testing

## 🛍️ Product Categories

The website features four main categories:

1. **🚗 CARS** - Pre-owned vehicles (Maruti Suzuki, Honda)
2. **🏠 HOUSE** - Properties and apartments for sale/rent
3. **📱 PHONE** - Mobile phones (Nokia, Honor, Apple)
4. **📺 TV** - Televisions (Nokia, Onida, Samsung)

## 📁 Project Structure

```
Software Testing Lab/
├── home.html           # Main landing page with category navigation
├── cars.html           # Cars listing page
├── house.html          # House/Property listing page
├── phone.html          # Mobile phones listing page
├── tv.html             # Television listing page
├── images/
│   ├── OLX_logo.PNG    # OLX logo
│   ├── car images      # Car product images
│   ├── house images    # Property images
│   ├── phone images    # Mobile phone images
│   └── tv images       # TV product images
└── README.md           # Project documentation
```

## 🔧 Features Implemented

### Navigation System
- **Left Sidebar Menu** - Persistent navigation on all pages
- **Category Links** - Quick access to all product categories
- **Home Button** - Return to main page from any category

### Product Listings
- **Product Images** - Visual representation of items
- **Product Details** - Name and price information
- **Add to Cart Button** - Interactive cart functionality

### JavaScript Functionality
```javascript
function sub() {
    alert("your item is added to cart");
}
```
- Cart alert notification when items are added
- Client-side interaction without page reload

### Design Elements
- **Color Scheme:**
  - Home page: Yellow background
  - Category pages: Pink background
  - Black text with Times New Roman font
- **Responsive Tables** - Structured layout for content
- **Centered Content** - Professional product display

## 🚀 How to Run

1. **Download** all project files
2. Ensure all **images** are in the correct directory
3. **Open** `home.html` in any web browser
4. **Navigate** through categories using the left sidebar
5. **Click** "Add to Cart" to test cart functionality

## 📱 Page Structure

### Home Page (home.html)
- OLX logo display
- Category navigation menu
- Yellow background theme

### Category Pages
Each category page includes:
- Persistent navigation sidebar
- Category heading
- Product cards with:
  - Product image (500px × 200px)
  - Product name
  - Price in INR (₹)
  - "Add to Cart" button

## 💻 HTML Elements Used

### Basic Structure
- `<html>`, `<head>`, `<body>`, `<title>`
- `<script>` - JavaScript integration

### Content Elements
- `<h1>` - Headings and titles
- `<p>` - Product descriptions
- `<b>` - Bold text emphasis
- `<a>` - Navigation hyperlinks
- `<img>` - Product images

### Layout Elements
- `<table>` - Page layout structure
- `<tr>`, `<td>` - Table rows and cells
- `<center>` - Content centering

### Interactive Elements
- `<input type="button">` - Add to Cart buttons
- `onclick` event - JavaScript function trigger

## 📊 Product Inventory

### Cars Section
| Product | Price | Image |
|---------|-------|-------|
| Maruti Suzuki | ₹21,000 | ✓ |
| Maruti Suzuki | ₹50,000 | ✓ |
| Honda | ₹5,00,000 | ✓ |

### House Section
| Product | Price | Image |
|---------|-------|-------|
| Philippines Apartment | ₹2,00,000 | ✓ |
| House | ₹5,00,000 | ✓ |
| House | ₹3,00,000 | ✓ |

### Phone Section
| Product | Price | Image |
|---------|-------|-------|
| Nokia | ₹20,000 | ✓ |
| Honor | ₹5,000 | ✓ |
| Apple | ₹30,000 | ✓ |

### TV Section
| Product | Price | Image |
|---------|-------|-------|
| Nokia TV | ₹20,000 | ✓ |
| Onida | ₹50,000 | ✓ |
| Samsung | ₹30,000 | ✓ |

## 🧪 Testing Checklist

### Functional Testing
- [ ] All navigation links work correctly
- [ ] Add to Cart button triggers alert
- [ ] Images load properly on all pages
- [ ] Product information displays correctly
- [ ] Price formatting is consistent

### UI Testing
- [ ] Layout is consistent across pages
- [ ] Colors render correctly (yellow/pink backgrounds)
- [ ] Text is readable (black on yellow/pink)
- [ ] Images are properly sized
- [ ] Buttons are clickable

### Browser Compatibility Testing
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge
- [ ] Mobile browsers

### Usability Testing
- [ ] Navigation is intuitive
- [ ] Category organization makes sense
- [ ] Product information is clear
- [ ] Alert messages are user-friendly

## 📚 Learning Outcomes

This project demonstrates:
- ✅ Multi-page website development
- ✅ HTML table-based layouts
- ✅ JavaScript event handling
- ✅ Alert box implementation
- ✅ Navigation system design
- ✅ Product catalog structure
- ✅ E-commerce website basics
- ✅ Client-side interactivity

## 🔄 Future Enhancements

Potential improvements for the project:

### Frontend
- [ ] Add CSS for modern styling
- [ ] Implement responsive design
- [ ] Create product detail pages
- [ ] Add image zoom functionality
- [ ] Improve cart with item counter

### Functionality
- [ ] Shopping cart page with item list
- [ ] Remove from cart functionality
- [ ] Total price calculation
- [ ] Checkout form
- [ ] Search functionality
- [ ] Filter and sort options

### Backend (Future Scope)
- [ ] Database integration
- [ ] User authentication
- [ ] Payment gateway
- [ ] Order management
- [ ] Admin panel

## 🛠️ Technologies Stack

| Technology | Purpose |
|------------|---------|
| HTML | Structure and content |
| JavaScript | Interactive functionality |
| Images | Product visualization |
| Tables | Layout management |

## 📋 Required Assets

### Images Needed
- `OLX_logo.PNG` - Main logo
- `23-1474603849-olx-pre-owned-vehicles-01.png` - Car image 1
- `23-1474603862-olx-pre-owned-vehicles-03.jpg` - Car image 2
- `car3.jpg` - Car image 3
- `eda8f1fb48d8a44b8a20445a5984b025--philippines-apartments.jpg` - House 1
- `th.jpg` - House 2
- `thghj (1).jpg` - House 3
- `phones(1).jpg` - Phone 1
- `p2.jpg` - Phone 2
- `p3.jpg` - Phone 3
- `tv1.jpg` - TV 1
- `tv2.jpg` - TV 2
- `tv3.jpg` - TV 3

## 🐛 Known Issues

1. Cart functionality is alert-based (no actual cart storage)
2. No backend integration
3. Layout uses deprecated table-based design
4. No form validation
5. Prices are static

## 📖 Code Documentation

### JavaScript Function
```javascript
function sub() {
    alert("your item is added to cart");
}
```
**Purpose:** Display confirmation message when user clicks "Add to Cart"  
**Trigger:** onclick event on Add to Cart buttons  
**Type:** Client-side alert notification

## 💡 Best Practices Implemented

- Consistent navigation across all pages
- Clear product information display
- User feedback via alerts
- Organized file structure
- Descriptive naming conventions

## 🔐 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ⚠️ IE 11 (Limited support)

## 📝 Testing Notes

This is a **sample/test website** created for:
- Learning HTML and JavaScript basics
- Understanding e-commerce website structure
- Testing navigation and interactivity
- Practicing web development fundamentals

**Note:** This is not a production-ready website and is intended for educational and testing purposes only.

## 📄 License

This project is created for educational purposes as part of a diploma software testing lab assignment.

## 🙏 Acknowledgments

- **OLX** - Inspiration for the project design
- **Lab Instructor** - For project guidance and requirements
- **Computer Science Department** - For providing the platform

---

## 📞 Support

For issues or questions about this project, please contact the development team through the institution.

---
## Developed By Tejushree BM

*Developed for Software Testing Lab | Diploma in Computer Science*

**Project Status:** ✅ Completed for Lab Submission
