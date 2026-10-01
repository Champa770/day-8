
day 8
Flexbox
What Flexbox is
Flexbox (Flexible Box Layout) is a CSS layout system for arranging items in a single direction — a row or a column — and distributing space between them. Before Flexbox, centering something vertically was a well-known pain; Flexbox fixes that in one line.
Turning on Flexbox
​
The moment you set display: flex on a parent, all its direct children become "flex items" and start behaving differently — they line up in a row by default.
​
These three divs will now sit side by side automatically, no float or manual positioning needed.
Two axes — this is the core mental model
Main axis — the direction items flow in (default: horizontal/row)
Cross axis — perpendicular to the main axis (default: vertical)
Everything in flexbox is about aligning things along these two axes. Once this clicks, the rest is just property names.
flex-direction — sets the main axis
​
Note: changing to column also flips what "main axis" and "cross axis" mean for the alignment properties below.
justify-content — aligns items along the main axis
​
align-items — aligns items along the cross axis
# day-8
Flexbox
