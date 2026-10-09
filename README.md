Login Screen – Authentication Platform

This project consists of a modern login interface designed with a focus on clean design, responsiveness, and usability. Its visual and structural conception was inspired by standards used in major digital platforms (such as streaming services like Netflix and academic university portals), where the primary goal is user immersion and the complete absence of external distractions (such as complex navigation bars or traditional footers).

🚀 Project Concept

Unlike institutional pages or content portals that require extensive footers (footer) and navigation menus (nav), high-performance authentication screens prioritize minimalism:

Single Focus: All visual weight of the page is directed toward the main action (filling out access credentials).

Immersive Experience: The use of a full-screen background image with a blur effect (backdrop-filter blur) creates a sophisticated and straight-to-the-point aesthetic environment.

Absence of Superfluous Elements: Removing conventional footers prevents unnecessary scrolling on standard displays and keeps the interface clean.

Note on Background: The background image changes dynamically upon every page refresh because it utilizes a random placeholder URL (picsum.photos), creating a fresh visual experience with each load.

🛠️ Technologies Used

HTML5: Semantic structure focused on accessibility (<main>, <form>, aria-hidden attributes).

CSS3:

Flexbox for element alignment and centering.

Modern visual properties and relative units (min(), calc()).

Advanced visual effects (backdrop-filter for the frosted glass / glassmorphism effect).

Google Fonts: Typography utilizing the Poppins font family.

📱 Responsiveness

The layout has been fully adapted for different screen resolutions using Media Queries:

Desktops and Tablets: Centralized display with controlled fixed width (min(420px, ...)).

Mobile Devices (max-width: 480px): Automatic adjustment of margins, subtle reduction in font sizes, and adaptation of input fields for touch interaction on smaller screens.

📁 File Structure

├── index.html        # Main structure of the login page
├── style.css         # Complete styling and responsiveness rules
└── assets/           # Icons and visual assets used inside the inputs
