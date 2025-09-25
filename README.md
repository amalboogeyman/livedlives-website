# Lived Lives Website

A self-contained website for Lived Lives, providing authentic peer support for AYA cancer survivors through conversational AI.

## 📁 Project Structure

```
LivedLives/
├── index.html                       # Main landing page (standard web server file)
├── mission.html                     # Our mission page
├── how_it_works.html                # How it works page
├── contact_us.html                  # Contact us page
├── css/                             # CSS folder (ready for future styling)
│   └── style.css                   # (empty - ready for custom CSS)
├── images/                          # All local images and assets
│   ├── hero.jpg                    # Landing page hero background
│   ├── logo.png                    # Site logo
│   ├── mission-hero.jpg            # Mission page hero image
│   ├── how-it-works-1.jpg          # How it works section 1 image
│   ├── how-it-works-2.jpg          # How it works section 2 image
│   └── how-it-works-3.jpg          # How it works section 3 image
└── README.md                        # This file
```

## 🚀 Deployment Instructions

### For Static Hosting (GitHub Pages, Netlify, Vercel, etc.)

1. **Upload all files** to your hosting provider:
   - All HTML files in the root directory
   - The `images/` folder with all images


2. **File structure on server should be:**
   ```
   /
   ├── index.html                    # Main landing page
   ├── mission.html                  # Our mission page
   ├── how_it_works.html             # How it works page
   ├── contact_us.html               # Contact us page
   ├── css/                          # CSS folder
   │   └── style.css                # (optional custom CSS)
   ├── images/                       # All images
   │   ├── hero.jpg                 # Landing page hero
   │   ├── logo.png                 # Site logo
   │   ├── mission-hero.jpg         # Mission page image
   │   ├── how-it-works-1.jpg       # How it works image 1
   │   ├── how-it-works-2.jpg       # How it works image 2
   │   └── how-it-works-3.jpg       # How it works image 3
   └── README.md                     # This file
   ```

### For Traditional Web Hosting (cPanel, FTP, etc.)

1. **Upload via FTP/cPanel File Manager:**
   - Upload all HTML files to `public_html/` or `www/`
   - Upload the `images/` folder to the same directory
   - Upload your `logo.png` to the root directory

2. **Index page:**
   - `index.html` is already the standard filename
   - Web servers automatically serve this as the default page

## 📋 Required Files Checklist

### ✅ Already Included:
- [x] `index.html` - Main landing page (standard web server file)
- [x] `mission.html` - Our mission page  
- [x] `how_it_works.html` - How it works page
- [x] `contact_us.html` - Contact us page
- [x] `css/` - CSS folder (ready for custom styling)
- [x] `images/hero.jpg` - Landing page background
- [x] `images/logo.png` - Site logo
- [x] `images/mission-hero.jpg` - Mission page image
- [x] `images/how-it-works-1.jpg` - How it works image 1
- [x] `images/how-it-works-2.jpg` - How it works image 2
- [x] `images/how-it-works-3.jpg` - How it works image 3

### ✅ Complete Package:
All files are included and organized according to web standards!

## 🎨 Customization

### Logo Already Included
- The logo (`images/logo.png`) is already included and properly referenced
- It appears in the top-left corner of all pages
- The logo is automatically resized to fit the header design

### Updating Contact Information
- Edit `contactus.html` to change the email address from `info@livedlives.org`
- The email link will automatically open the user's default email client

### Color Scheme
The site uses a consistent color palette:
- **Primary Teal**: `#13ecda`
- **Dark Text**: `#0d1b1a`
- **Light Background**: `#f8fcfb`
- **Border Color**: `#e7f3f2`
- **Link Hover**: `#4c9a93`

## 🔧 Technical Details

### Dependencies
- **Tailwind CSS**: Loaded from CDN (no local files needed)
- **Google Fonts**: Inter font family (loaded from CDN)
- **No JavaScript frameworks**: Pure HTML/CSS

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Works without JavaScript

### Performance
- All images optimized for web
- Total image size: ~1.4MB
- Fast loading with local assets

## 📞 Contact Information

**Email**: info@livedlives.org

## 📄 License

© 2025 Lived Lives. All rights reserved.

---

**Note**: This website is completely self-contained and ready for deployment to any static hosting provider. All external dependencies are loaded from CDNs and will work offline once deployed.
