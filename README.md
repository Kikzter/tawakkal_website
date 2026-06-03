# Tawakkal Website

A premium, responsive website for Tawakkal - a food brand offering authentic quality products with traditional recipes.

## Features

- ✨ Modern, responsive design
- 🍽️ Product showcase with detailed descriptions
- 📱 Mobile-optimized
- 💼 Professional About Us section
- 📧 Contact form
- 🎨 Brand-consistent color scheme
- ⚡ Fast loading with minimal dependencies

## Project Structure

```
tawakkal_website/
├── index.html           # Home page
├── products.html        # Products catalog
├── about.html          # About Us page
├── assets/
│   ├── styles.css      # Main stylesheet
│   ├── script.js       # JavaScript functionality
│   ├── logo.png        # Brand logo
│   ├── beef-cutlet.png
│   ├── chicken-cutlet.png
│   ├── mutton-cutlet.png
│   ├── rose-milk.png
│   ├── badam-milk.png
│   ├── nannari-syrup.png
│   └── egg-sweet.png
├── _config.yml         # GitHub Pages config
├── .gitignore         # Git ignore file
└── README.md          # This file

```

## Setup Instructions

### Step 1: Copy Images to Assets Folder

1. Navigate to `c:\Users\mdnay\Documents\tawakkal_website\tawakkal\`
2. Copy the image files and rename them as follows:
   - `tawakkal.png` → Copy to `assets/logo.png`
   - `beef cutlet.png` → Copy to `assets/beef-cutlet.png`
   - `chicken cutlet.png` → Copy to `assets/chicken-cutlet.png`
   - `mutton cutlet.png` → Copy to `assets/mutton-cutlet.png`
   - `rose milk.png` → Copy to `assets/rose-milk.png`
   - `badam milk.png` → Copy to `assets/badam-milk.png`
   - `nanari syrup.png` → Copy to `assets/nannari-syrup.png`
   - `egg sweet post.png` → Copy to `assets/egg-sweet.png`

### Step 2: Test Locally

Open `index.html` in your web browser to test the website locally.

### Step 3: Deploy to GitHub Pages

#### Option A: Using GitHub Desktop or Command Line

1. **Initialize a Git repository:**
   ```bash
   cd c:\Users\mdnay\Documents\tawakkal_website
   git init
   ```

2. **Create a GitHub repository:**
   - Go to [GitHub.com](https://github.com)
   - Click "New repository"
   - Name it `tawakkal-website` or `<your-username>.github.io`
   - Don't initialize with README (you already have one)
   - Click "Create repository"

3. **Push your code:**
   ```bash
   git add .
   git commit -m "Initial commit: Add Tawakkal website"
   git remote add origin https://github.com/YOUR-USERNAME/tawakkal-website.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click Settings
   - Scroll to "GitHub Pages"
   - Under "Source", select "main" branch and "/" (root) folder
   - Click Save
   - Your site will be available at: `https://YOUR-USERNAME.github.io/tawakkal-website`

#### Option B: Using Netlify (Alternative - Even Simpler)

1. Go to [Netlify.com](https://netlify.com)
2. Click "Connect a new site" → "Deploy manually"
3. Drag and drop your `tawakkal_website` folder
4. Netlify will deploy it and give you a URL instantly!

## Customization

### Updating Contact Information

Edit `index.html`, `products.html`, and `about.html`:
- Email: Search for `tawakkal.10565@gmail.com`
- Instagram: Search for `tawakkal_delights`
- Location: Search for `Chennai`

### Changing Colors

Edit `assets/styles.css` - Update these CSS variables at the top:

```css
:root {
    --primary-color: #1e3a5f;      /* Dark Blue */
    --secondary-color: #c41e3a;    /* Red */
    --accent-color: #d4af37;       /* Gold */
    --light-bg: #f5f1e8;          /* Cream */
}
```

### Adding More Products

In `products.html`, duplicate a product card and update:
- Image path: `assets/your-image.png`
- Product name, description
- Badge type and color

## Responsive Design

The website is optimized for:
- 📱 Mobile phones (320px and up)
- 📱 Tablets (768px and up)
- 🖥️ Desktops (1200px and up)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Minimal CSS and JavaScript
- Optimized images recommended (compress before uploading)
- Fast page load times
- SEO-friendly structure

## Contact & Support

For inquiries about Tawakkal products:
- 📧 Email: tawakkal.10565@gmail.com
- 📱 Instagram: @tawakkal_delights
- 📍 Location: Chennai, India

## License

© 2024 Tawakkal. All rights reserved.

---

**Need Help?**

If you encounter any issues:
1. Make sure all image files are correctly placed in the `assets/` folder
2. Clear your browser cache (Ctrl+Shift+Delete)
3. Check that all HTML files are in the root directory
4. Verify image file names match exactly in the HTML

Happy serving! 🍽️
