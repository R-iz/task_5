# 🏨 Serenity Haven Hotel - Landing Page

A modern, responsive hotel landing page built with HTML, CSS, and JavaScript. This project showcases a luxury hotel website with elegant design, smooth animations, and interactive booking features.

## ✨ Features

### 🎨 Design & UI
- **Elegant Design** - Luxury hotel aesthetic with warm color palette
- **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **Modern Typography** - Playfair Display for headings, Poppins for body text
- **Smooth Animations** - CSS animations and scroll-triggered effects
- **Interactive Elements** - Hover effects, transitions, and micro-interactions

### 🏨 Hotel-Specific Features
- **Hero Section** - Stunning background with booking call-to-action
- **Room Showcase** - Display of different accommodation types with pricing
- **Amenities Grid** - Visual presentation of hotel facilities
- **Photo Gallery** - Responsive image grid of hotel spaces
- **Guest Testimonials** - Carousel slider with customer reviews
- **Location Information** - Map integration and nearby attractions
- **Booking Forms** - Interactive reservation and contact forms

### 📱 Interactive Components
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Navigation links with smooth scroll behavior
- **Form Validation** - Date validation and input checking
- **Testimonial Slider** - Auto-rotating customer reviews
- **Newsletter Signup** - Email subscription functionality

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and accessibility features
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality and DOM manipulation
- **Google Fonts** - Playfair Display and Poppins typography
- **Responsive Design** - Mobile-first approach

## 📁 Project Structure

```
hotel-landing-page/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── images/             # Image assets (if any)
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/hotel-landing-page.git
   cd hotel-landing-page
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   open index.html
   # or
   double-click index.html
   ```

3. **For development with live server**
   ```bash
   # Using VS Code Live Server extension
   # Right-click on index.html and select "Open with Live Server"
   
   # Or using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx serve .
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Sections

### 1. Navigation Header
- Fixed header with smooth scroll navigation
- Mobile hamburger menu
- Book Now call-to-action button

### 2. Hero Section
- Full-screen background image
- Compelling headline and description
- Primary and secondary action buttons
- Integrated booking form bar

### 3. About Section
- Hotel introduction and story
- Key features with icons
- Professional imagery

### 4. Rooms & Accommodations
- Room cards with images and pricing
- Feature lists for each room type
- Direct booking links

### 5. Amenities
- Grid layout of hotel facilities
- Icon-based presentation
- Hover effects and animations

### 6. Photo Gallery
- Responsive image grid
- Hover effects on images
- View all gallery option

### 7. Guest Testimonials
- Carousel slider with customer reviews
- Star ratings and guest photos
- Auto-rotation functionality

### 8. Location & Contact
- Map integration
- Contact information
- Reservation form with validation

### 9. Footer
- Quick links and hotel information
- Newsletter subscription
- Social media links

## 🔧 Customization

### Colors
Update the CSS custom properties in `:root`:
```css
:root {
    --primary-color: #c8a97e;    /* Gold/Bronze */
    --secondary-color: #1a1a1a;  /* Dark Gray */
    --accent-color: #f8f5f0;     /* Light Cream */
    --text-color: #333333;       /* Dark Text */
    --light-text: #ffffff;       /* White Text */
}
```

### Typography
Change fonts by updating the Google Fonts import and CSS:
```css
@import url('https://fonts.googleapis.com/css2?family=YourFont:wght@300;400;500;600;700&display=swap');

body {
    font-family: 'YourFont', sans-serif;
}
```

### Content
- Update hotel name, description, and contact information in `index.html`
- Replace placeholder images with actual hotel photos
- Modify room types, pricing, and amenities to match your hotel

## 📊 Performance Features

- **Optimized Images** - Responsive images with proper sizing
- **Minimal Dependencies** - Pure HTML, CSS, and JavaScript
- **Fast Loading** - Optimized CSS and JavaScript
- **SEO Friendly** - Semantic HTML structure

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Form Functionality

The contact and booking forms include:
- **Date Validation** - Ensures check-out is after check-in
- **Required Field Validation** - All necessary fields must be completed
- **Email Format Validation** - Proper email format checking
- **Success Messages** - User feedback on form submission

*Note: Forms currently show success messages. For production use, integrate with a backend service or form handler.*


