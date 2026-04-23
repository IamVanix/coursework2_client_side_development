Spice Haven - Premium Dining Web Experience
Spice Haven is a modern, responsive multi-page website for a premium restaurant. The project focuses on client-side development, featuring dynamic menu filtering, interactive UI elements, and a clean, "glassmorphic" design.

FEATURES
Responsive Multi-Page Design: Fully functional Home, Menu, About, and Contact pages built with HTML5 and Bootstrap 5.
Dynamic Menu Filtering: A categorized menu that allows users to filter between "Veg" and "Non-Veg" options without reloading the page.
Interactive UI:
AOS (Animate On Scroll): Smooth entrance animations for sections and menu cards.
Glassmorphism: Elegant, semi-transparent UI containers for a modern aesthetic.
"Today's Special" Callouts: Dynamic content triggered by user interaction on the landing page.
Booking System: A functional contact form designed for table reservations with client-side validation logic.
Favorites Feature: Users can interact with menu items by toggling a "Favorite" status (heart icons).

TECH STACK
Frontend: HTML5, CSS3
Framework: Bootstrap 5 (Layout and Components)
Interactivity: JavaScript (ES6+)
Animations: AOS Library (Animate on Scroll)
Icons/Fonts: External CDN support for specialized styling.

📁 Project Structure
Plaintext
├── css/
│   └── style.css       # Custom styles including glassmorphism and hero sections
├── js/
│   └── script.js      # Core logic for menu filtering, specials, and form handling
├── images/            # Optimized restaurant and menu item assets
├── index.html         # Landing page with hero section
├── menu.html          # Interactive menu with filter buttons
├── about.html         # Brand story with interactive elements
├── contact.html       # Booking/Contact form
└── README.md          # Project documentation
💻 Installation & Usage
Clone the repository:

BASH
git clone https://github.com/[your-username]/coursework2_client_side_development.git
Open the project:
Navigate to the project folder and open index.html in any modern web browser.

KEY FUNCTIONALITIES
Menu Filtering
The filterMenu() function in script.js manages the visibility of menu items. It targets classes like .veg and .nonveg to provide an instant, seamless user experience.

Form Handling
The booking form uses saveBooking() to process user inputs (Name, Email, Number of People) and provides feedback messages directly on the contact.html page.

Academic Context
This project was developed as part of Coursework 2: Client-Side Development (COM109). It demonstrates proficiency in structuring semantic HTML, implementing responsive CSS, and writing custom JavaScript to enhance the user experience.

Developed by samod and adnan
