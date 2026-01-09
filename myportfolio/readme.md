Project screenshot placeholders

This portfolio includes SVG placeholder screenshots for the three live projects in the `img/` folder.

How to replace with real screenshots:
1. Open the live project in your browser, e.g. https://smartinterviewpeparationchatbot.netlify.app
2. Resize the browser to the desired width (1200px works well) and take a screenshot (browser dev tools -> Responsive -> Capture screenshot or use OS screenshot tool).
3. Save the screenshot to the `img/` folder and name it to match the current placeholder filename (smart-interview.svg, vs-chatterbox.svg, vs-amazon-clone.svg), or update the `src` attribute for the image in `index.html`.
4. Consider scaling down large PNGs for faster load or converting to SVG/PWA-friendly formats.

Accessibility & SEO tips:
- Keep `alt` attributes descriptive and accurate.
- Add `title` attributes to images if you want hover tooltips.
- For better performance, prefer WebP/optimized PNG if possible.

If you'd like, I can help capture live screenshots and add them directly here — tell me whether you want me to fetch images from the live URLs or to add resized versions locally.

Social icons in hero:
- Update social links in `index.html` inside the hero section where `class="social-links"` is placed. Replace `href="#"` with your actual profile links (LinkedIn/GitHub) and your email address in the `mailto:` link.
 - Update social links in `index.html` inside the hero section where `class="social-links"` is placed. Replace `href="#"` with your actual profile links (LinkedIn/GitHub/Phone) and your email address in the `mailto:` link.
	- Suggested pattern: `https://www.linkedin.com/in/vaishnavi-satwadhar/` or `https://github.com/vaishnavi-satwadhar` and `tel:+91XXXXXXXXXX` for phone.
 - Header LinkedIn icon: I've added an accessible LinkedIn icon in the header that links to `https://www.linkedin.com/in/vaishnavi-satwadhar12`. If you'd like this changed, update the URL in the header `href`.