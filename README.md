**INDEX.HTML**

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


**EVENTS.HTML**

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

**CONTACT.HTML**

1. Head Section
Sets up the page title, character encoding, and mobile responsiveness.

Includes internal CSS styling that defines the look of the entire page, such as colors, layout, fonts, and responsiveness.

2. Body Background
Displays a full-screen background image of the LNCT campus.

A semi-transparent white overlay is used on top of the background to make text and other elements more readable.

3. Sticky Navigation Bar
Located at the top of the page and stays fixed while scrolling.

Contains two logos (LNCT and NBA).

Includes buttons that link to various site pages like Home, About, Contact, Alumni Cell, Placements, Events, and a virtual 360° tour.

4. Main Page Title
Displays a centered heading that reads “LNCT Group of Colleges - Contact Information” to inform users of the page's purpose.

5. Contact Cards Grid
A responsive grid layout that organizes contact information into individual cards.

Each card provides contact details for a specific LNCT campus or department (e.g., admission, reception, placement, and regional offices).

Includes phone numbers, emails, addresses, and website links.

6. Quick Contact Button
A floating button at the bottom right of the screen that expands when clicked.

Offers two quick-access options: calling a number or sending an email.

Makes it easy for users (especially on mobile) to reach out instantly.

7. Admission Open Side Bar
A vertical red bar fixed to the right edge of the screen.

Links directly to the LNCT admissions portal for easy access to the application process.

Always visible as users scroll the page.

8. Footer Section
Displays contact information again for clarity and accessibility.

Includes icons and labels for reception, admission, placement cell, email, and physical address.

Features social media links (Instagram, YouTube, Facebook) using icons.

Ends with a developer credit section listing the names and contact numbers of the development team (Team GUI).

Shows a copyright notice.

9. JavaScript Functionality
Adds interactivity to the quick contact button.

Allows the contact menu to toggle open and closed.

Automatically hides the menu if the user clicks anywhere outside of it.

**PLACEMENT.HTML**

1. Page Setup (Head)
Sets the document's character encoding and responsive layout for mobile devices.

Applies embedded CSS to style the page, defining variables, fonts, layout behavior, colors, and responsiveness.

2. Page Background and Overlay
Displays a fixed background image of the LNCT campus.

Adds a white semi-transparent overlay over the background to improve readability of text and content.

3. Navigation Bar
A fixed top navigation bar with LNCT and NBA logos.

Contains buttons linking to key site pages like Home, About, Contact, Alumni Cell, Placements, and Events.

Styled with a gradient background and slight blur effect.

4. Main Content Section
Placed Students Gallery:
A heading and a grid of student placement photos, representing successful alumni.

Placement Highlights:
A grid of info cards showing key statistics such as:

Top recruiting companies

Average and highest salary packages

Placement rate percentages

Internship opportunities

5. Admission Bar
A fixed vertical red tab on the right side labeled "Admission Open."

Clicking it links directly to the LNCT admissions portal.

Always visible as users scroll.

6. Quick Contact Button
A floating contact button on the bottom right corner.

When clicked, shows options to call or email.

Useful for quick mobile-friendly interaction.

7. Footer Section
Displays detailed contact information including phone numbers, email addresses, and the LNCT campus location.

Uses icons for phones, email, and address.

Shows social media links (Instagram, YouTube, Facebook) as SVG icons.

Includes a “Made by Team GUI” credit with team member names and phone numbers.

Ends with a copyright.

8. JavaScript Functionality
Enables toggling of the quick contact menu.

Hides the contact menu if the user clicks outside of it, improving user experience.

**WORKING.JS**

It first checks the browser’s local storage to see if dark mode was previously turned on by the user.

It finds the button or element on the page that the user will click to switch between dark mode and normal mode.

There’s a function that turns dark mode on by adding a special style class to the webpage and saving this choice in local storage.

Another function turns dark mode off by removing that style class and updating local storage to show dark mode is no longer active.

When the page loads, it automatically applies dark mode if the user had it enabled before.

Finally, it listens for clicks on the toggle button, and each time it’s clicked, it switches dark mode on or off depending on the current state.
