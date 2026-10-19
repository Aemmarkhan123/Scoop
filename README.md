# Scoop — Premium Handcrafted Ice Cream

A responsive, visually rich landing page for **Scoop**, a fictional premium ice cream brand. Built with semantic HTML and custom CSS, the site showcases signature flavors, brand storytelling, customer testimonials, a photo gallery, and a promotional signup section.

## Features

- **Hero section** with call-to-action links and social-proof styling
- **Signature flavors** cards with descriptions, prices, and badges for featured and seasonal flavors
- **Brand story** section with an overlapping image layout
- **Why choose Scoop?** feature cards highlighting ingredients and small-batch preparation
- **Photo gallery** with hover overlays
- **Customer testimonials** with profile images and star ratings
- **Promotional signup form** offering a first-order discount
- **Responsive navigation** with a CSS-only mobile menu
- **Responsive layouts** for desktop, tablet, and mobile
- **Accessible details** including image alt text, form labels, and visible keyboard focus styles
- **Reduced-motion support** for visitors who prefer less animation

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, custom properties, media queries)
- Google Fonts: Fraunces and Outfit
- Unsplash-hosted images

No JavaScript framework, build tool, or package installation is required.

## Project Structure

```text
.
├── index.html
├── style.css
└── README.md
```

> Keep `index.html` and `style.css` in the same directory. The HTML file links to the stylesheet using `style.css`.

## Getting Started

### Run locally

1. Download or clone the project.
2. Make sure the HTML and CSS files are in the same folder.
3. Rename the uploaded files to the expected names if necessary:
   - `index(20261019-082351).html` → `index.html`
   - `style(20261019-082351).css` → `style.css`
4. Open `index.html` in your browser.

Alternatively, use VS Code with the **Live Server** extension and choose **Open with Live Server**.

## Sections

| Section | Description |
| --- | --- |
| Home | Brand introduction and primary calls to action |
| Flavors | Six featured ice cream flavors with prices |
| Our Story | Brand values and handcrafted preparation |
| Features | Ingredient quality, small batches, and flavor variety |
| Gallery | Six-image gallery with hover overlays |
| Testimonials | Three sample customer reviews |
| Promotion | Email field for a first-order discount offer |
| Contact | Contact details, quick links, and social links |

## Customization

- **Brand colors:** Edit the CSS variables in `:root` at the top of `style.css`.
- **Typography:** Update the Google Fonts import in `index.html` and the font variables in `style.css`.
- **Flavor cards:** Change the flavor names, descriptions, prices, badges, and image URLs in `index.html`.
- **Images:** Replace Unsplash image URLs with your own optimized images.
- **Contact details:** Update the sample email address, phone number, and social links in the footer.
- **Promotion:** Customize the discount text and signup form to match your offer.

## Important Notes

- The email signup form is currently **front-end only**. It prevents the default form submission but does not save email addresses or send discounts. Connect it to a backend or email marketing service to make it functional.
- The flavor “+” buttons are visual UI elements only; no cart or checkout functionality is implemented.
- The “Order Now” links point to `#order`, but the provided page does not define an order section. Connect these links to a real ordering flow or add an order section before publishing.
- Some navigation links, such as `#about`, do not currently match a section ID in the page. Update the target or add the corresponding section.
- Images and Google Fonts load from external services, so an internet connection is needed for those assets to appear as intended.
- Brand claims, customer reviews, contact information, and prices are sample content. Replace them with verified details before using the site commercially.

## Accessibility

The page includes descriptive image alt text, a label for the email input, semantic sectioning elements, and keyboard-visible focus styles. Before production, test contrast, keyboard navigation, mobile menu behavior, and form feedback with real users.

## License

No license is specified. Add a license file if you intend to distribute or reuse this project publicly.
