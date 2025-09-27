# FitCore Studio - Gym Website

This build produces a complete, production-ready 3-page gym website using a modern, Tailwind CSS-based design system.

What’s included
- index.html: Home page with hero, services, testimonials, and footer
- about.html: About page with mission and team
- contact.html: Contact form and location details
- Responsive, accessible, and keyboard-friendly navigation
- Font pairing: Oswald (headings) and Roboto (body) per Gym category
- Background image placeholders for hero sections using the provided image tokens
- Phase 2 deliverable compatible with the specified JSON-based pipeline

How to customize
- Replace background image placeholders in the style attributes of the hero sections:
  style='background-image: url("{{image:...}}");'
- Update text content to match your branding
- Change the internal links if you add more pages later

Notes
- All pages use Tailwind CSS via CDN and semantic HTML5 elements
- Font imports are included to ensure category-appropriate typography
- The content is designed to be easily adaptable for additional services or pages