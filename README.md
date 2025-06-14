INDEX.HTML 

🔹 head Section

Purpose: Contains metadata and links to stylesheets and scripts.

Includes:

Character set declaration (UTF-8)

Page title and favicon

Google Fonts for styling

AOS (Animate On Scroll) CSS

Font Awesome for icons

External CSS (style.css) and JS (working.js)

🔹 Navigation Bar (<nav>)
Purpose: Provides site-wide navigation.

Components:

LNCT and NBA logos

Navigation links (Home, About, Contact, Alumni Cell, Placements, etc.)

Dark/light mode toggle button with icons

🔹 Hero Section (<section class="hero">)
Purpose: Welcoming section at the top with main heading and subheading.

Features:

Text: "Welcome to LNCT Group of Colleges"

Subtitle: "Empowering Future Leaders Through Education"

AOS animation applied on scroll

🔹 Introductory Text and Image
Purpose: Highlights LNCT's legacy and reputation.

Features:

Title: “Best Educational Group in Central India”

Description of LNCT’s origin, facilities, and achievements

A clickable image linking to LNCT’s 360° virtual campus tour

🔹 Branches/Institutes Section
Purpose: Showcases different LNCT branches.

Structure:

Horizontally scrollable slider with image cards

Each card links to the respective institute’s website

Arrow icons to indicate interaction

🔹 About Section
Purpose: Concise introduction to LNCT

Layout: Image on one side, description on the other

Animation: Scroll-based animations (AOS)

🔹 Counter Section
Purpose: Displays animated statistics about LNCT

Examples:

NIRF Rank

Number of offers

Top recruiters

Patents published

🔹 "Why LNCT" Section
Purpose: Lists key advantages of studying at LNCT

Layout: Title, brief intro, and multiple highlighted points (like infrastructure, sports, research, etc.)

🔹 Placements Section
Purpose: Visual showcase of recent placements

Content: Multiple images showing students with offer letters and placement drives

🔹 Gallery Section
Purpose: Visual representation of LNCT events and campus life

Content: Image grid from various events, Garba, cultural days, etc.

🔹 International Conference Section
Purpose: Highlights IEEE Conference (ICoEIT)

Features:

Info text

Button linking to the official conference website

🔹 Contact Section
Purpose: Allows visitors to get in touch

Elements:

Name, email, and message fields

Submit button (currently not wired to backend)

🔹 Quick Contact Button
Purpose: Floating button that reveals quick call or email options

Interactions: Toggles visibility of contact options

🔹 Footer
Purpose: Final contact details and branding

Content:

LNCT logo

Phone numbers for reception and admission

Icons for clarity


EVENTS.HTML

🔹 1. <!DOCTYPE html> + <html> tag
Declares the document as HTML5 and sets the page's language to English.

🔹 2. <head> Section
Contains metadata and styling resources:

Meta tags: Define character set and viewport for responsive design.

Title: Page title shown in browser tab.

Internal CSS: All the styles used in your webpage are embedded here using <style>.

🔹 3. <style> Section (within <head>)
This section styles your entire page:

Variables: Declares CSS variables for colors and theme.

body background: Applies a LNCT background image with a translucent white overlay.

Navigation bar: Sticky navbar with logos and menu buttons.

Sliders: Two horizontally scrolling image sliders for events.

Buttons and Cards: Styling for contact and quick contact buttons.

Footer: Fully styled contact details and social media icons.

Animation (@keyframes scroll): Enables continuous scrolling for image sliders.

🔹 4. <body> Starts
🔸 Navigation Bar (<nav>)
Sticky top bar with the LNCT logo, NBA logo, and menu buttons linking to different sections/pages.

🔸 Section Title: LNCT Events
Big heading centered with decorative dashes.

Introduces the events section of the page.

🔸 Image Sliders (.slider-container1 and .slider-container2)
Two auto-scrolling image carousels that show LNCT event photos.

slider-track1 scrolls left to right, slider-track2 scrolls in reverse.

Each image links to https://lnct.ac.in/recent-events.

🔸 Separator
A black line used to visually divide sections of the page.

🔸 Quick Contact Button
Fixed-position button at the bottom-right.

Clicking it reveals quick links to call or email LNCT.

Includes JavaScript logic to toggle the contact options and auto-close when clicking outside.

🔸 Footer (<footer>)
Contains:

LNCT logo

Contact Information: Reception, Admission Cell, T&P Cell, Email, Address

Social Media Icons: Instagram, YouTube, Facebook

Credits: Lists contributors (Team GUI)

Copyright

🔸 Floating Admission Bar
Vertical bar on the right with the text "Admission Open"

Clicking it redirects to LNCT's admissions portal.

🔸 JavaScript
Adds interactivity for the quick contact toggle:

contactToggle: Button to open/close contact options.

Automatically closes if the user clicks outside the quick-contact box.

✅ Summary of Functionality:
Feature	Description
Navigation Bar	Navigation to key LNCT sections
Image Sliders	Visual showcase of recent events
Quick Contact	Floating button for fast communication
Footer	Contact details + social media links
Admission Bar	Prominent link to the admission portal
JavaScript	Enables contact toggle interaction


