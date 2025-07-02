link:http://127.0.0.1:5500/index.html

Documendation :
📝 Project Documentation: Real Estate Property Listing UI
📁 Files Structure
bash
Copy
Edit
/project-root
│
├── index.html          # Main HTML file containing the structure
├── style.css           # Main styling for the layout and components
├── media.css           # Responsive design styles using media queries
├── /images             # Folder containing property, icons, and profile images
├── /css                # Folder where style.css and media.css would typically be placed
└── /Font               # Font files (referenced but not included)
📄 1. index.html – Structure & Content
This file defines a section of a real estate website called "Our Properties".

🔍 Key Components:
Section Title:

Our Properties

Featured Properties

Property Cards (4 total):
Each card includes:

Background image of the property

Price (including original & discounted if applicable)

Agent information (image + name + posted time)

Property title

Location

Sale tag

Icons: bed, bath, size (with values)

✅ Technologies Used:
HTML5

Font Awesome (for icons)

WebP/JPG images

External CSS for styling

🎨 2. style.css – Styling & Design
This file styles the layout using:

Custom CSS Variables (like --theme-text-green)

Utility Classes (e.g., .d-flex, .align-items-center)

Card Design:

Box shadow

Hover effect: background image overlay disappears on hover

Property Card Elements:

.price, .price-1, .price-2 – Different styles for pricing

.profile-img – Circular agent image

.icons – Bed, bath, and area icons

✨ Highlights:
Clean, modular design

Soft color palette with shadows

Minimalistic font (Nunito Sans)

📱 3. media.css – Responsive Design
This file ensures the layout adapts across screen sizes using CSS Media Queries.

📐 Breakpoints Used:
576px (sm): 2 columns

786px (md): 2 columns

992px (lg): 3 columns

1200px (xl): 4 columns

1400px (xxl): 4 columns (with extra width)

🧩 Responsive Classes:
.container-sm, .container-md, ..., .container-xxl – Control overall layout width

.col-sm-6, .col-lg-4, .col-xl-3 – Control column width per device
