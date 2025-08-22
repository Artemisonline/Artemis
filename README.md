
## Setup Instructions

1. **Download the website files**
   - Save the provided HTML code as `index.html`
   - Create folders for images and other assets as needed

2. **Customize content**
   - Replace placeholder text with your actual product information
   - Add your product images to the `products/` folder
   - Update color scheme by modifying CSS variables if desired

3. **Add your products**
   - Edit the product cards in the HTML file
   - Update product names, descriptions, and prices
   - Replace the background-image URLs with your actual product images

4. **Update contact information**
   - Modify footer links and contact details
   - Add your social media profiles

## Deployment Guide

### Free Hosting Options

1. **GitHub Pages** (Recommended)
   - Create a GitHub account at [github.com](https://github.com)
   - Create a new repository named `yourusername.github.io`
   - Upload your website files to this repository
   - Go to Settings → Pages → Select main branch as source
   - Your site will be live at `https://yourusername.github.io`

2. **Netlify**
   - Create an account at [netlify.com](https://netlify.com)
   - Drag and drop your project folder to deploy
   - Or connect your GitHub repository for continuous deployment

3. **Vercel**
   - Create an account at [vercel.com](https://vercel.com)
   - Import your project from GitHub or upload manually

### Custom Domain Setup (Optional)

1. Purchase a domain name from a registrar (Namecheap, GoDaddy, etc.)
2. In your hosting platform's settings, add your custom domain
3. Update DNS records to point to your hosting provider

## Customization

### Changing Colors

The color scheme uses these main values:
- Primary green: `#6a8c7c`
- Dark green: `#4a6b5b`
- Light green: `#5a7c6c`

To change the color scheme, replace these values throughout the CSS.

### Adding New Products

Add new product cards by copying this structure:

```html
<div class="product-card">
    <div class="product-img" style="background-image: url('path-to-image.jpg');"></div>
    <div class="product-info">
        <h3>Product Name</h3>
        <p>Product description</p>
        <div class="price">$0.00</div>
        <a href="#" class="btn">Add to Cart</a>
    </div>
</div>
