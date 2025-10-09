# Mangilik As - Restaurant Management System

## About the Project

This is my midterm project for the web development course. I built a restaurant website called "Mangilik As" that includes everything a modern restaurant needs - online ordering, table reservations, staff management, and more.

The name "Mangilik As" means "Eternal Food" in Kazakh, which reflects the timeless quality of good cuisine.

## What I Built

The website has 6 main pages:

1. **Home Page** - First thing visitors see. Has a big hero image, some info about the restaurant's history, featured dishes in cards, and customer reviews at the bottom.

2. **Menu Page** - Shows all the food we serve. You can filter by category (appetizers, mains, desserts, drinks) or search for specific dishes. Each item has a photo, description, price, and an "Add to Cart" button. There's also a pricing comparison table at the bottom.

3. **Reservations** - Lets customers book a table. They pick a date, time slot, number of guests, and can even select which table they want from a visual layout. Added some notes about cancellation policies too.

4. **Order Online** - Shopping cart page where people can order food for delivery or pickup. Shows their cart items, lets them change quantities, add special instructions, and checkout. Calculates tax and delivery fees automatically.

5. **Staff Dashboard** - Internal page for restaurant employees. Shows today's stats (orders, revenue, table occupancy), a queue of active orders, table status grid, and the staff schedule. Managers can accept orders, mark them ready, etc.

6. **Contact & About** - Has our story, profiles of the chef team with photos, contact form, location info, customer reviews with ratings, and social media links.

## Technologies Used

- HTML5 (semantic tags like header, nav, section, footer)
- CSS3 (Grid, Flexbox, media queries, animations)
- Bootstrap 5.3 (for grid system and some utilities)
- Vanilla JavaScript (for forms, filters, cart functionality)

## Key Features

- Fully responsive - works on desktop, tablet, and mobile
- Interactive menu filtering and search
- Real-time cart calculations
- Form validation on all forms
- Consistent navigation across all pages
- Accessible color scheme with good contrast
- Smooth hover effects and transitions

## Technical Stuff I Implemented

**HTML:**
- Used proper semantic elements everywhere
- Two data tables (menu pricing and staff schedule)
- Three working forms (reservations, ordering, contact)
- Lists, images, links - all the basics

**CSS:**
- CSS Grid for menu items, stats cards, team profiles, reviews
- Flexbox for navbar, card layouts, form elements
- Media queries at 992px, 768px, and 576px breakpoints
- CSS variables for consistent colors
- Sticky navbar with fixed positioning
- Various hover effects and animations

**Bootstrap:**
- Grid system (container, row, col classes)
- Navbar component
- Utility classes for spacing and alignment
- Made sure everything is mobile-first

## Design Choices

Went with an orange/dark blue color scheme because:
- Orange (#d4611e) = warmth, appetite, energy
- Dark blue (#2c3e50) = trust, professionalism
- Creates good contrast and looks modern

Used photos from Unsplash to keep it looking professional without copyright issues.

## How to Run

Just open `index.html` in any browser. All the CSS is inline so no external files needed. Bootstrap and other resources load from CDN.

## Live Demo
https://restaurantmanagementsystemproject.netlify.app/

## Project Structure
mangilik-as/
├── index.html          (Home page)
├── menu.html           (Interactive menu)
├── reservations.html   (Booking system)
├── order.html          (Online ordering)
├── staff.html          (Staff dashboard)
├── contact.html        (About & contact)
└── README.md          (This file)

## Challenges I Faced

The hardest part was making the staff dashboard look clean while showing so much information. Also spent a lot of time getting the cart calculations right on the order page.

Making everything responsive was tricky too - had to reorganize layouts quite a bit for mobile screens.

## Future Improvements

If I had more time, I'd add:
- Actual backend integration (right now it's all frontend)
- User authentication for the staff page
- Real payment processing
- Database for menu items and orders
- Email notifications for reservations

But for a midterm project focusing on HTML/CSS/Bootstrap, I think it covers everything well.

## Course Requirements Met

✓ 5+ pages (made 6)
✓ Navigation on all pages
✓ Semantic HTML5
✓ Tables (2 tables - pricing and schedule)
✓ Forms (3 forms - all with validation)
✓ CSS with classes/IDs
✓ Flexbox and Grid layouts
✓ Positioning techniques
✓ Media queries for responsiveness
✓ Bootstrap grid system
✓ Bootstrap utilities
✓ Published online
✓ Clean, indented code

Made with ☕ and lots of debugging for Web Technologies Course
https://restaurantmanagementsystemproject.netlify.app/
