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

## 🛠️Tech Stack
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat) ![SCSS](https://img.shields.io/badge/-SCSS-CD6799?logo=sass&logoColor=white&style=flat) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat) ![Parcel](https://img.shields.io/badge/-Parcel-333?logo=parcel&logoColor=yellow&style=flat) ![JSON](https://img.shields.io/badge/-JSON-000000?logo=json&logoColor=white&style=flat) ![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?logo=bootstrap&logoColor=white&style=flat)

 ## 🧱Structure
- ***Antet Hero*** **(*Hero header)***
- ***Products***
- ***About***
- ***Advantages***
- ***Gallery***
- ***Customer Reviews***
- ***Contacts***
- ***Subsol (Footer)***

🟣 Hero Header <br/>
Includes logo, nav menu (with anchor links), and a “Buy now” button. <br/>
Mobile/tablet: fixed sliding sidebar menu (full viewport height).<br/>
Title: “Ice cream made with passion”.<br/>
Anchor buttons “Products” & “How it’s made?” scroll to respective sections.<br/>
Hero images: absolutely positioned, animated on load.<br/>
“Buy now” opens a custom modal order form.<br/>

🍦 Products Section <br/>
Label: “100% natural” (non-heading tag).<br/>
Title: “Products”.<br/>
Display product cards in a grid.<br/>
Images are decorative → use pseudo-elements.<br/>
Product names are headings.<br/>
Decorative ellipsis via pseudo-elements.<br/>
Arrow button opens detailed product modal (custom implementation).<br/>

🧪 About / How It’s Made <br/>
Label: “Tradition and love”.<br/>
Title: “How it’s made?”.<br/>
Includes paragraph block + “Read more” button (opens custom modal).<br/>
Cow image as PNG (preserve transparency).<br/>
Milk background full width on desktop, container width on mobile.<br/>

✅ Advantages <br/>
Hidden heading for SEO.<br/>
Benefits listed in a grid.<br/>
Use pseudo-elements for icons (originals are PNGs).<br/>

🖼️ Gallery <br/>
Background: two-color gradient.<br/>
Optional: implement Masonry Layout.<br/>

💬 Customer Reviews <br/>
Slider with pagination (house icon + dots).<br/>
Use a slider library and style pagination only.<br/>
Quotation mark = pseudo-element.<br/>
Ellipsis via pseudo-elements.<br/>
Underline with repeating-linear-gradient().<br/>

📍 Contacts <br/>
Hidden heading for SEO.<br/>
Locations listed as a grid.<br/>
“Cafe” & “Food Truck” are categories.<br/>
Phone & email use tel: and mailto:.<br/>
“Our Locations” & “Franchise” open a custom modal with map.(optional)<br/>

🔻 Footer <br/>
Social links via SVG sprite.<br/>
Links open in new tab.<br/>
Phone uses clickable protocol.<br/>

🚨 Notes <br/>
Use valid HTML5 structure.<br/>
Responsive from 320px up.<br/>
Modals, slider, and animations are optional.<br/>

## 🔛Link live
![GitPages] - https://isabelamihai.github.io/icecream-project/
