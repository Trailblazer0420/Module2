# Module2
CSS Grid Dashboard Layout

A simple responsive dashboard layout built with pure HTML and CSS Grid — no frameworks, no JavaScript.

Files
index.html — page markup (semantic tags: header, aside, main, section, footer)
index.css — grid layout, colors, typography, and hover effects
Layout

The page uses named CSS Grid areas to arrange six sections:

header  header   header
sidebar content1 content2
sidebar content3 content3
footer  footer   footer
Header — full-width top bar
Sidebar — spans the two middle rows on the left
Content1 / Content2 — side-by-side panels
Content3 — spans both columns beneath Content1/Content2
Footer — full-width bottom bar
Styling
Font: Poppins (Google Fonts)
Palette: charcoal (
#2f3e46), sage green (
#52796f, 
#84a98c), soft sand background (
#f4f1ea)
Each box has rounded corners, a soft drop shadow, and lifts slightly on hover
Running it

No build step required — just open index.html in a browser. Make sure index.css is in the same folder.

Customizing
Adjust column widths: edit grid-template-columns in .container
Adjust row heights: edit grid-template-rows in .container
Rearrange sections: change the grid-template-areas string and the matching grid-area on each #ID
Swap colors: update the background/color values under each #ID selector
