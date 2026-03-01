# ZOYORCHID E-Commerce Website

## Project Overview
This is a responsive e-commerce website for ZOYORCHID, a clothing brand. The website features a clean, modern design with product browsing, shopping cart functionality, and multiple pages for different sections.

## Project Structure
```
web/
├── index.html              # Homepage with hero section and featured products
├── shop.html               # Shop page displaying all products
├── productDetails.html     # Individual product details page
├── about.html              # About us page
├── contact.html            # Contact page
├── style.css               # Complete styling for all pages
├── script.js               # JavaScript for mobile navigation menu
├── img/                    # Image assets folder
│   ├── LOGO.png           # Company logo
│   ├── mainScreen.png     # Hero section background
│   ├── banner.png         # Banner for about/contact pages
│   ├── b14.png            # Newsletter section background
│   └── products/          # Product images
└── .vscode/
    └── settings.json      # VS Code workspace settings
```

## Features Implemented

### 1. Navigation System
- **Fixed Navigation Bar**: Sticky header that remains at top when scrolling
- **Responsive Menu**: Mobile-friendly hamburger menu for smaller screens
- **Active Page Indicator**: Visual feedback showing current page
- **Shopping Cart Icon**: Quick access to cart
- **Pages**: Home, Shop, About, Contact

### 2. Homepage (index.html)
- **Hero Section**: Large banner with call-to-action button
  - Background image with product showcase
  - "SHOP NOW" button
  - Tagline: "We'll provide you with our best"
- **Featured Products Section**: 
  - Display of 4 product cards
  - Each product shows: image, brand, name, star rating, price
  - Shopping cart icon for quick add-to-cart
- **Newsletter Signup**: Email subscription form
- **Footer**: Contact info, social media links, account links

### 3. Shop Page (shop.html)
- **Product Grid**: Full product catalog display
- **Clickable Products**: Products link to detail pages
- **Consistent Layout**: Same header and footer as homepage
- **Product Cards**: Multiple products with pricing (Rs.900)
- **Pagination**: Page navigation at bottom

### 4. Product Details Page (productDetails.html)
- **Product Gallery**:
  - Large main product image
  - Small thumbnail images for multiple views
  - Interactive image switching capability
- **Product Information**:
  - Product name and category (Home/Jacket)
  - Price display (Rs.800)
  - Size selector dropdown (XL, XXL, Small, Large)
  - Quantity input field
  - "Add to Cart" button
  - Product details section

### 5. About Page (about.html)
- **Hero Banner**: Large "ABOUT US" heading
- **Newsletter Section**: Email signup
- **Footer**: Contact and social media information

### 6. Contact Page (contact.html)
- **Hero Banner**: "CONTACT US" heading
- **Contact Details Section**: Placeholder for contact information
- **Newsletter Section**: Email subscription
- **Footer**: Complete company information

## Styling (style.css)

### Color Scheme
- **Primary Background**: Burlywood (navigation, accents)
- **Text Colors**: #222 (headings), #464646 (paragraphs)
- **Accent Color**: #088178 (buttons, links)
- **Dark Background**: #041e42 (newsletter section)

### Design Elements
- **Typography**: Spartan font family
- **Responsive Grid**: Flexbox-based product layout
- **Hover Effects**: 
  - Navigation items scale up to 200%
  - Product cards get shadow on hover
  - Buttons change color
- **Border Radius**: Rounded corners on images (20px)
- **Shadows**: Subtle shadows for depth

### Responsive Design
**Desktop (>799px)**:
- Full navigation bar
- 4 products per row (23% width each)
- Full-width sections with 80px padding

**Tablet (478px - 799px)**:
- Hamburger menu appears
- Slide-in mobile navigation from right
- Adjusted background positions
- Cart icon in mobile menu

**Mobile (<477px)**:
- Single column product layout (100% width)
- Reduced padding (20px)
- Stacked newsletter form
- Smaller hero text (80px)
- Single column product details view

## JavaScript Functionality (script.js)

### Mobile Navigation
```javascript
- Hamburger menu toggle (bar icon)
- Close button functionality
- Sidebar navigation slide-in animation
- Active class management
- DOM ready event listener
```

**Features**:
- Opens/closes mobile menu
- Smooth transition (0.3s)
- Menu slides from right (-300px to 0px)
- Background overlay effect
- Responsive to screen size

## Technical Details

### External Dependencies
- **Font Awesome 6.5.2**: Icon library for cart, social media, and UI icons
- **Google Fonts**: Spartan font family

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for mobile devices
- Touch-friendly navigation

### Images Required
- LOGO.png
- mainScreen.png (hero background)
- banner.png (about/contact hero)
- b14.png (newsletter background)
- Product images in products/ folder (jacket.jpg)

## Key CSS Classes & IDs

### Layout
- `.section-p1`: 40px 80px padding
- `.section-m1`: 40px margin
- `#header`: Fixed navigation bar
- `#footer`: Footer layout

### Components
- `#navbar`: Navigation menu
- `#main`: Hero section
- `#products`: Product grid
- `#pro-details`: Product details layout
- `#new-comers`: Newsletter section
- `.pro`: Individual product card
- `.cart`: Shopping cart icon

### Responsive
- `#tab`: Mobile menu toggle
- `#bar`: Hamburger icon
- `#close`: Close button
- `#bag`: Cart icon (hidden on mobile)

## Incomplete/Placeholder Features

### Cart Functionality
- Cart page referenced (cart.html) but not created
- Add to cart buttons not functional
- No cart state management

### Contact Page
- Contact details section is empty
- No contact form implemented

### Product Data
- Products are hardcoded
- All products show same image (jacket.jpg)
- No backend integration
- No database connection

### User Account
- Sign in links present but no authentication
- "My Account" footer links not functional
- No user dashboard

## Future Enhancements Needed
1. Implement cart.html with shopping cart functionality
2. Add JavaScript for add-to-cart functionality
3. Create contact form with validation
4. Connect to backend/database for dynamic product loading
5. Implement user authentication system
6. Add product filtering and search
7. Create checkout process
8. Add payment gateway integration
9. Implement order tracking
10. Add more product variety with real images

## Development Notes
- Built with vanilla HTML, CSS, and JavaScript
- No framework dependencies
- Mobile-first responsive approach
- Clean, semantic HTML structure
- Modular CSS organization
- Ready for backend integration

## How to Run
1. Open `index.html` in a web browser
2. Navigate between pages using the menu
3. View responsive design by resizing browser window
4. Test mobile menu on screens < 799px width

---

**Project Status**: Frontend Complete | Backend/Database Integration Pending
**Last Updated**: February 2026
