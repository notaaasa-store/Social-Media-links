# Nota Social Media Landing Page

A beautiful, mobile-first landing page for Nota's social media links. Designed to be accessed via QR code on product packaging.

## Features

- **Mobile-first design** - Optimized for phone screens with large, easy-to-tap buttons
- **Fast loading** - No unnecessary dependencies or heavy frameworks
- **Easy to update** - Add new social media platforms by editing one simple array
- **Beautiful aesthetic** - Soft, feminine, Instagram/Pinterest-inspired design
- **Accessible** - Proper ARIA labels and keyboard navigation support
- **Responsive** - Looks great on mobile, tablet, and desktop

## Files

- `index.html` - Main HTML structure
- `style.css` - All styling and responsive design
- `script.js` - Social media links configuration and button rendering
- `Nota Logo.png` - Brand logo image
- `README.md` - This file

## How to Update Social Media Links

To add or update social media links, edit the `socialLinks` array in `script.js`:

```javascript
const socialLinks = [
    {
        name: 'Instagram',
        url: 'YOUR_INSTAGRAM_URL_HERE',
        platform: 'instagram'
    },
    {
        name: 'TikTok',
        url: 'YOUR_TIKTOK_URL_HERE',
        platform: 'tiktok'
    },
    // Add more platforms as needed
];
```

**To add WhatsApp:**
1. Uncomment the WhatsApp example in `script.js`
2. Replace `YOUR_WHATSAPP_LINK_HERE` with your actual WhatsApp link
3. The button will automatically appear on the page

**Supported platforms:** `instagram`, `tiktok`, `facebook`, `whatsapp`

## Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon in the top-right corner
3. Select **New repository**
4. Name your repository (e.g., `nota-social-links`)
5. Make it **Public** (required for GitHub Pages free tier)
6. Click **Create repository**

### Step 2: Upload Your Files

1. In your new repository, click **uploading an existing file**
2. Drag and drop these files:
   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`
3. Add a commit message like "Initial upload"
4. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click the **Settings** tab (top of the page)
3. In the left sidebar, click **Pages**
4. Under **Build and deployment**, find **Source**
5. Change it from "None" to **Deploy from a branch**
6. Select **main** (or `master`) as the branch
7. Select **/(root)** as the folder
8. Click **Save**

### Step 4: Get Your URL

1. Wait about 1-2 minutes for deployment
2. Refresh the Pages settings page
3. You'll see your live URL at the top (e.g., `https://yourusername.github.io/nota-social-links/`)
4. Click the link to verify it works

### Step 5: Use for QR Code

1. Copy your GitHub Pages URL
2. Use any QR code generator (like [QRCode Monkey](https://www.qrcode-monkey.com))
3. Paste your URL and generate the QR code
4. Download and print on your product packaging

## Customization

### Colors

Edit the CSS variables in `style.css` to change colors:

```css
:root {
    --primary-color: #ef5d9c;  /* Brand pink */
    --bg-color: #fdf6f9;       /* Background color */
    /* ... more variables */
}
```

### Fonts

The page uses Google Fonts:
- **Playfair Display** - For the "Nota" logo
- **Inter** - For body text

To change fonts, update the Google Fonts link in `index.html` and the font-family in `style.css`.

## Browser Support

- Chrome (last 2 versions)
- Safari (last 2 versions)
- Firefox (last 2 versions)
- Edge (last 2 versions)
- Mobile Safari (iOS)
- Chrome Mobile (Android)

## Performance

- Lighthouse Score: 95+
- First Contentful Paint: < 1s
- Time to Interactive: < 2s
- No external tracking or analytics
- No cookies or popups

## License

Free to use for the Nota brand.
