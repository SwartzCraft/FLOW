# FLOW

A static promotional website for showcasing handcrafted products, creative services, and completed work.

> **Project Status:** Active Development  
> **Hosting:** GitHub Pages  
> **Business Name:** Subject to Change

## Live Website

The current development version is available through GitHub Pages:

https://swartzcraft.github.io/Stitch-and-Crafts-by-Wolves/

## About the Project

FLOW is a lightweight static website designed to provide a central advertising and portfolio hub for a small craft business.

The website is intended to:

- Present available services
- Showcase completed projects through an image gallery
- Introduce the business and its team
- Provide business contact information
- Allow prospective customers to initiate contact through email or telephone
- Maintain a responsive design for desktop and mobile devices

The site is intentionally designed without a server-side application or database. GitHub Pages provides static hosting, allowing the website to remain free to host and maintain.

The visual design currently uses a pastel color palette requested by project stakeholders.

## Current Features

- Home page with service overview
- Responsive layout under development
- About section
- Team profile structure
- Filterable project gallery
- Contact section
- Email and telephone link support
- Mobile navigation
- GitHub Pages deployment

Some content remains populated with development placeholders while business information and production assets are finalized.

## Built With

- **HTML5** — semantic structure and website content
- **CSS3** — visual design, layout, and responsive behavior
- **JavaScript** — navigation, gallery filtering, and interactive behavior
- **GitHub Pages** — static website hosting
- **Git/GitHub** — version control and repository management

No front-end framework or server-side application is currently required.

## Project Structure

Planned repository organization:

```text
Stitch-and-Crafts-by-Wolves/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
│   ├── gallery/
│   ├── team/
│   └── branding/
├── documents/
└── README.md
```

The structure may change as development continues.

## Development Priorities

- [ ] Finalize business contact information
- [ ] Add team member names, roles, and biographies
- [ ] Replace placeholder team photographs
- [ ] Replace gallery placeholders with production images
- [ ] Finalize gallery project descriptions
- [ ] Complete the business story
- [ ] Determine whether a downloadable order form is required
- [ ] Refine desktop navigation
- [ ] Refine mobile navigation
- [ ] Improve accessibility and keyboard navigation
- [ ] Optimize images and page performance
- [ ] Separate production CSS and JavaScript from `index.html`
- [ ] Complete responsive-design testing
- [ ] Review security configuration
- [ ] Consider optional dark-mode support
- [ ] Finalize business/site branding
- [ ] Update repository name and URL after branding is finalized

## Security

FLOW is designed as a static informational website and does not currently require:

- User accounts or authentication
- A customer database
- Payment processing
- Server-side form processing
- Storage of customer information

Development should preserve this limited attack surface whenever practical.

### Security Practices

When modifying the website:

- Never commit passwords, API keys, tokens, credentials, or other secrets.
- Never publish private customer information.
- Do not publish personal residential addresses.
- Use dedicated business contact information rather than personal contact information.
- Use HTTPS resources.
- Minimize third-party scripts and dependencies.
- Validate external links before deployment.
- Avoid inserting untrusted content into the DOM as HTML.
- Keep dependencies to a minimum.
- Review external resources before adding them to the website.

Sensitive transactions, authentication, payment information, and private customer information should not be handled directly by this static website.

## Accessibility

Development should work toward accessible interaction and content, including:

- Semantic HTML elements
- Descriptive alternative text for meaningful images
- Keyboard-accessible navigation
- Visible keyboard focus indicators
- Sufficient text/background contrast
- Appropriate heading hierarchy
- Accessible mobile navigation
- Reduced reliance on hover-only interactions

Accessibility should be reviewed as production content replaces development placeholders.

## Code Documentation

Source code should contain comments where they clarify architecture, behavior, configuration, or non-obvious implementation decisions.

Comments should explain **why** code behaves a particular way when that reasoning is not apparent from the code itself. Routine HTML and CSS should remain readable without requiring line-by-line comments.

## Updating the Website

Content updates generally require:

1. Modify the appropriate HTML, CSS, JavaScript, or asset files.
2. Test the changes locally.
3. Verify desktop and mobile behavior.
4. Commit the changes to Git.
5. Push the commit to GitHub.
6. Allow GitHub Pages to deploy the updated site.
7. Verify the production deployment.

## Troubleshooting

### Website Not Updating

- Confirm that the changes were committed and pushed successfully.
- Check the repository's GitHub Pages deployment status.
- Allow time for the deployment to complete.
- Refresh the page after deployment.
- If necessary, perform a hard refresh to eliminate locally cached resources.

### Images Not Showing

- Verify that the image exists in the repository.
- Verify the image path in the HTML or CSS.
- Confirm that the filename and capitalization match exactly.
- Confirm that the file extension is correct.
- Check the browser developer console for failed resource requests.

### Navigation Not Working

- Verify that the JavaScript file is loading successfully.
- Check the browser developer console for JavaScript errors.
- Verify that HTML IDs, classes, and JavaScript selectors agree.
- Confirm that event listeners are attached to the intended elements.
- Test desktop and mobile navigation independently.

## Resources

- [MDN Web Docs](https://developer.mozilla.org/) — HTML, CSS, JavaScript, accessibility, and web-platform reference
- [GitHub Pages Documentation](https://docs.github.com/en/pages) — deployment and GitHub Pages configuration
- [W3C Web Standards](https://www.w3.org/standards/) — web standards and accessibility resources

## Future Enhancements

Potential future capabilities include:

- Custom domain
- Dark-mode support
- Customer testimonials or reviews
- Social-media links
- Additional gallery functionality
- News or business-update section
- Integration with an external e-commerce platform if required

E-commerce functionality would remain external to the static GitHub Pages architecture unless the project's requirements substantially change.

## Contact

For website maintenance or development questions:

- **Repository Owner:** SwartzCraft
- **Business Owner:** Pending
- **Business Email:** Pending

## License

All rights reserved.

Website content, branding, photographs, artwork, and other business assets may not be reused without permission from their respective owners.

---

**Last Updated:** September 30, 2026

**Development Note:** The business name and branding are subject to change. The website is being developed so that branding can be replaced without requiring a complete redesign.
