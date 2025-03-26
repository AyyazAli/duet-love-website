# Duet Love - App Support Website

This repository contains the support website for the Duet Love mobile application. The website is hosted using GitHub Pages.

## Website Structure

- `index.html` - Main landing page
- `privacy.html` - Privacy Policy
- `support.html` - Support page with FAQs and contact form
- `terms.html` - Terms of Service
- `css/styles.css` - Stylesheet for the website
- `images/` - Directory containing images used on the website

## Setting Up GitHub Pages

Follow these steps to set up GitHub Pages for this repository:

1. Go to your GitHub repository settings
2. Scroll down to the "GitHub Pages" section
3. Under "Source", select the branch you want to use (usually `main`)
4. Select the root folder (`/`) as the source directory
5. Click Save
6. Your site will be published at `https://[your-username].github.io/duet-love-website/`

## Custom Domain (Optional)

To use a custom domain:

1. Purchase a domain from a domain registrar
2. In your GitHub repository settings, under the "GitHub Pages" section, enter your custom domain
3. Configure your domain registrar's DNS settings:
   - For an apex domain (example.com), add an A record pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - For a subdomain (www.example.com), add a CNAME record pointing to `[your-username].github.io`
4. Wait for DNS changes to propagate (can take up to 24 hours)

## Local Development

To work on this website locally:

1. Clone the repository
2. Open the files in your favorite code editor
3. Preview the site using a local server (e.g., `python -m http.server` or using a VS Code extension like Live Server)

## Form Handling

The contact form on the support page uses [Formspree](https://formspree.io/) for handling form submissions. To set it up:

1. Create an account on Formspree
2. Create a new form and get your form endpoint
3. Replace `https://formspree.io/f/your-formspree-endpoint` in `support.html` with your actual endpoint

## App Store Badges

Before publishing, replace the placeholder app store badge images with the official badges from:

- [Apple App Store Marketing Guidelines](https://developer.apple.com/app-store/marketing/guidelines/)
- [Google Play Brand Guidelines](https://developer.android.com/distribute/marketing-tools/brand-guidelines)

## Customization

- Update the logo in the `images` folder
- Add real app screenshots
- Modify contact information and legal details as needed

## License

This website template is available under the MIT license. See the LICENSE file for more info. 