# 🍕 Black Goose Bistro - Custom Pizza Ordering System

A beautiful, web application for ordering custom pizzas with an intuitive user interface and smooth user experience. Created as part of an assignment from the **Information Technology Institute (ITI)**. 

## 🌟 Features

### 🎨 **Interactive Pizza Customization**
- **4 Crust Options**: Classic White, Multigrain, Stuffed Crust, and Gluten-Free
- **8 Premium Toppings**: Pepperoni, Mushrooms, Red Sauce, Mozzarella, Onions, Peppers, Anchovy, and Bacon
- **Visual Selection**: Click-to-select interface with visual feedback
- **Multiple Toppings**: Choose as many toppings as you want

### 🚀 **User Experience**
- **Smooth Navigation**: Fixed navbar with scroll-to-section functionality
- **Active State Indicators**: Visual feedback for selected items
- **Accessibility Features**: Proper ARIA labels and semantic HTML
- **Form Validation**: Required fields for customer information

### 🎯 **Customer Information System**
- Contact details collection (Name, Email, Phone)
- Delivery address input
- Special delivery instructions textarea
- Order confirmation workflow

## 🛠️ Tech Stack

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with Flexbox , animation
- **Font Awesome**: Icon library for navigation and UI elements
- **Google Fonts**: Custom typography (Gloock, Nothing You Could Do)

## 📁 Project Structure

```
Task 4/
│
├── index.html                 # Main HTML file
├── webfonts                   
├── CSS/
│   ├── style.css             # Main stylesheet
│   └── all.min.css           # Font Awesome icons
├── imgs/                     # Image assets
│   ├── pizza-icon.png        # Favicon
│   ├── pizza1.png            # Classic White pizza
│   ├── pizza2.png            # Multigrain pizza
│   ├── pizza3.png            # Stuffed Crust pizza
│   ├── h4-pizza-3.png        # Gluten-Free pizza
│   ├── pepperoni.png         # Topping icons
│   ├── mushrooms.png
│   ├── tomato-sauce.png
│   ├── cheese.png
│   ├── onions.png
│   ├── peppers.png
│   ├── anchovy.png
│   ├── bacon-strips.png
│   ├── h4-start-piz.png      # Header background
│   └── h4-pizza-3.png        # Header foreground
└── README.md                 # This file
```

## 🚀 Getting Started

### Installation

1. **Clone or Download** the project files
2. **Ensure all assets are in place**:
   - Images in the `/imgs/` folder
   - CSS files in the `/CSS/` folder
   - Font Awesome CSS file (`all.min.css`)

## 🎯 Usage Guide

### For Customers:
1. **Browse Pizza Options**: Scroll through the four crust varieties
2. **Select Your Base**: Click "Choose" on your preferred crust
3. **Add Toppings**: Click on topping icons to select/deselect
4. **Add to Cart**: Click "Add to Cart" when satisfied with selection
5. **Enter Details**: Fill in contact and delivery information
6. **Place Order**: Click "Confirm Order" to submit

## 🎨 Design Features

### Color Palette
- **Primary**: `#e74c3c` (Red)
- **Secondary**: `#d09f45` (Gold)
- **Background**: `#f9edde` (Cream)
- **Content**: `#fff7ed` (Light Cream)
- **Text**: `#2c2c2c` (Dark Gray)

### Typography
- **Headers**: Gloock (Google Fonts)
- **Accent**: Nothing You Could Do (Google Fonts)
- **Body**: System fonts for readability

### Animations
- Smooth hover transitions
- Active state indicators
- Scroll-triggered navigation highlights
- Form focus states

## 🔧 Customization Options

### Adding New Pizza Options
```html
<div class="card">
  <div class="card-img">
    <picture><img src="./imgs/new-pizza.png" alt="New Pizza"/></picture>
  </div>
  <div class="card-txt">
    <h3>New Pizza Name</h3>
    <p>Description of the new pizza...</p>
    <input type="radio" name="pizza" id="pizza5" hidden aria-label="New Pizza"/>
    <label for="pizza5" class="choose-btn">Choose</label>
  </div>
</div>
```

### Adding New Toppings
```html
<input type="checkbox" id="topping9" hidden aria-label="New Topping"/>
<label for="topping9" class="topping-card">
  <div class="topping-icon">
    <img src="./imgs/new-topping.png" alt="New Topping"/>
  </div>
  <div class="topping-name">
    <span>New Topping</span>
  </div>
</label>
```

## 🎭 Accessibility Features

- **Semantic HTML**: Proper heading hierarchy and form structure
- **ARIA Labels**: Screen reader support for interactive elements
- **Keyboard Navigation**: Tab-accessible form controls
- **Color Contrast**: WCAG compliant color combinations
- **Focus Indicators**: Visible focus states for all interactive elements

## 🚧 Future Enhancements

- [ ] **Backend Integration**: Order processing and database storage
- [ ] **Payment Gateway**: Stripe/PayPal integration
- [ ] **Real-time Updates**: Order status tracking
- [ ] **User Accounts**: Login/registration system
- [ ] **Order History**: Previous order tracking
- [ ] **Add to Cart**: Add customized pizza to cart

## 👤 Author

**Mariam Kilany**

---

**🍕 Ready to serve delicious custom pizzas with style!**