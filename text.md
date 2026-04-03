## Design Choices

Aesthetic direction — Refined Editorial
Rather than a generic e-commerce template, VAULT leans into a luxury-editorial feel inspired by stores like Aesop and Hay. The palette is warm ivory (#f8f5f0), near-black charcoal (#1c1a17), and a brass gold accent (#b08d57) — earthy, timeless, and far from the overused purple-gradient look.

## Typography

Playfair Display (serif, Google Fonts) — for headings and the logo. Its italics add elegance to callouts like "those who notice"
DM Sans (geometric sans) — for body text and UI labels. Pairs cleanly with Playfair without competing

## Layout & Spacing

Hero uses a 50/50 grid with the image on the right — gives breathing room without feeling empty
Products use a 4-column grid (→ 2-col on tablet → 1-col on mobile)
Generous vertical padding (--space-2xl) creates the airy, premium feel

## Details worth noticing

Animated spinning accent ring on the hero image
Wishlist heart fades in on card hover
Marquee strip communicates perks without cluttering the layout
Badge tags (Bestseller / New / –20%) use distinct color coding
The About section uses a dark panel with a full-bleed photo — a strong visual contrast moment

## Responsiveness

All breakpoints are handled via CSS media queries (no framework dependency):
BreakpointWhat changes≤ 1024px (tablet)Products → 2 columns; About section stacks vertically; Footer stacks≤ 768px (mobile)Hamburger menu appears; Hero → single column; Products → 1 column; Newsletter → stacked≤ 480px (small mobile)Footer nav collapses to 1 column; buttons go full-width
The hamburger menu is pure JS — no library needed. It uses max-height animation for a smooth slide-down effect.

\*\*\* This description was written in French and then translated into English by ChatGPT. \*\*\*
