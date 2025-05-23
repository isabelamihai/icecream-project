*Parcel Template*

# 🌐Icecream Team Project via Parcel
Developed a functional website for a fictive company called "Ice Cream" following the given instructions and Figma design. <br/>
Figma design: https://www.figma.com/design/Ltoc0qV4LrKSoYiNFRbqVl/ICE-CREAM-PROJECT-TEAM-3?node-id=0-1&p=f&t=kZIHzfRMTg7qsTlO-0 

## 📋Tehnical task specifications:
- Responsive Design with breakpoints at 480px, 768px, and 1280px. The mobile version of the site must be fully responsive. The website should display correctly on all screen sizes and device orientations, starting from 320px width, both in portrait and landscape mode.

- Valid Markup
The layout must pass validation checks using tools such as:
https://validator.w3.org/
https://validator.w3.org/unicorn/

- HTML5 Semantics
Use semantic HTML5 tags according to modern web standards.

- Graphic Optimization
Optimize the size of both vector (SVG) and bitmap images (e.g., PNG, JPG).

- Retina Display Support
Provide high-resolution image support for Retina and high-DPI displays.

- Image Loading Optimization
Apply appropriate techniques (e.g., modern formats, lazy loading) to reduce image load time.

- Favicon Integration
Add a favicon to the page for browser tab display.

 ## 🧱Structure
- ***Antet Hero*** **(*Hero header)***
- ***Products***
- ***About***
- ***Advantages***
- ***Gallery***
- ***Customer Reviews***
- ***Contacts***
- ***Subsol (Footer)***

🟣 Hero Header
Includes logo, nav menu (with anchor links), and a “Buy now” button.
Mobile/tablet: fixed sliding sidebar menu (full viewport height).
Title: “Ice cream made with passion”.
Anchor buttons “Products” & “How it’s made?” scroll to respective sections.
Hero images: absolutely positioned, animated on load.
“Buy now” opens a custom modal order form.

🍦 Products Section
Label: “100% natural” (non-heading tag).
Title: “Products”.
Display product cards in a grid.
Images are decorative → use pseudo-elements.
Product names are headings.
Decorative ellipsis via pseudo-elements.
Arrow button opens detailed product modal (custom implementation).

🧪 About / How It’s Made
Label: “Tradition and love”.
Title: “How it’s made?”.
Includes paragraph block + “Read more” button (opens custom modal).
Cow image as PNG (preserve transparency).
Milk background full width on desktop, container width on mobile.

✅ Advantages
Hidden heading for SEO.
Benefits listed in a grid.
Use pseudo-elements for icons (originals are PNGs).

🖼️ Gallery
Background: two-color gradient.
Optional: implement Masonry Layout.

💬 Customer Reviews
Slider with pagination (house icon + dots).
Use a slider library and style pagination only.
Quotation mark = pseudo-element.
Ellipsis via pseudo-elements.
Underline with repeating-linear-gradient().

📍 Contacts
Hidden heading for SEO.
Locations listed as a grid.
“Cafe” & “Food Truck” are categories.
Phone & email use tel: and mailto:.
“Our Locations” & “Franchise” open a custom modal with map.

🔻 Footer
Social links via SVG sprite.
Links open in new tab.
Phone uses clickable protocol.

🚨 Notes
Use valid HTML5 structure.
Responsive from 320px up.
Modals, slider, and animations are optional.

## 🛠️Tech Stack
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat) ![Parcel](https://img.shields.io/badge/-Parcel-333?logo=parcel&logoColor=yellow&style=flat) ![JSON](https://img.shields.io/badge/-JSON-000000?logo=json&logoColor=white&style=flat) ![SASS](https://img.shields.io/badge/-SASS-CC6699?logo=sass&logoColor=white&style=flat) ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white&style=flat)

