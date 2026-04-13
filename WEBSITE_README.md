# Amalia Francalangia - Professional Website

A modern, sleek, and professional website for soprano Amalia Francalangia.

## Features

- **Modern Design**: Clean, professional layout with elegant typography
- **Responsive**: Fully mobile-friendly and adapts to all screen sizes
- **Fast Loading**: Lightweight HTML, CSS, and vanilla JavaScript
- **Easy to Customize**: Well-organized code with clear instructions
- **Free Hosting**: Ready for GitHub Pages (free hosting!)

## Website Pages

1. **Home** (`index.html`) - Biography and introduction
2. **Resume** (`resume.html`) - Complete performance history and credentials
3. **Photos** (`photos.html`) - Photo gallery
4. **Listen** (`listen.html`) - Audio recordings
5. **Watch** (`watch.html`) - Video performances
6. **Connect** (`connect.html`) - Contact information

## Customization Guide

### 1. Update Contact Email

In `connect.html`, replace the placeholder email:
```html
<a href="mailto:your.email@example.com" class="email-button">Email Me</a>
```
Change `your.email@example.com` to your actual email address.

### 2. Add Photos

Create a folder named `photos` in the root directory and add your images. Then in `photos.html`, replace the placeholders:

```html
<!-- Replace this: -->
<div class="photo-placeholder">
    <p>Photo 1<br>Add your photos here</p>
</div>

<!-- With this: -->
<img src="photos/your-photo.jpg" alt="Description of photo" style="width: 100%; border-radius: 8px;">
```

### 3. Add Audio Files

1. Create a folder named `audio` in the root directory
2. Add your MP3 files with these names (or update the HTML to match your filenames):
   - `csardas.mp3`
   - `chio-mi-scordi.mp3`
   - `ne-poi-krasavitsa.mp3`
   - `de-que-me-sirve.mp3`
   - `och-jaky-zal.mp3`
   - `biblical-songs-1.mp3`, `biblical-songs-2.mp3`, etc.
   - `korngold-1.mp3`, `korngold-3.mp3`, etc.

### 4. Add YouTube Videos

In `watch.html`, replace each `YOUR_VIDEO_ID` with your actual YouTube video ID:

```html
<!-- Find the video ID in your YouTube URL -->
<!-- Example: https://www.youtube.com/watch?v=dQw4w9WgXcQ -->
<!-- The ID is: dQw4w9WgXcQ -->

<!-- Replace in the iframe: -->
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" ...></iframe>
```

### 5. Customize Colors

In `styles.css`, update the color variables at the top:

```css
:root {
    --primary-color: #8B2635;      /* Main burgundy color */
    --primary-dark: #6B1828;       /* Darker burgundy */
    --accent-gold: #D4AF37;        /* Gold accent */
    /* Change these hex values to your preferred colors */
}
```

## Hosting on GitHub Pages

### Option 1: Quick Setup

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section
4. Under "Source", select the branch `claude/redesign-website-Sqahl`
5. Click **Save**
6. Your site will be live at: `https://afrancal13.github.io/probable-fiesta/`

### Option 2: Custom Domain

If you want to use `amaliafrancalangia.com`:

1. Follow Option 1 first
2. In GitHub Pages settings, add your custom domain: `amaliafrancalangia.com`
3. In your domain registrar (where you bought the domain):
   - Add a CNAME record pointing to `afrancal13.github.io`
   - Or add A records pointing to GitHub's IP addresses (see [GitHub's guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site))

### Option 3: Merge to Main Branch

For cleaner URLs, merge the changes to your `main` branch:

1. Create a pull request from `claude/redesign-website-Sqahl` to `main`
2. Merge the pull request
3. In GitHub Pages settings, select `main` as the source branch
4. Your site will be at: `https://afrancal13.github.io/probable-fiesta/`

## Alternative Free Hosting Options

### Netlify
1. Sign up at [netlify.com](https://netlify.com)
2. Connect your GitHub repository
3. Deploy automatically
4. Free custom domain support

### Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click
4. Free SSL and custom domains

### Cloudflare Pages
1. Sign up at [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect repository
3. Deploy instantly
4. Free with great performance

## File Structure

```
probable-fiesta/
├── index.html          # Home page
├── resume.html         # Resume page
├── photos.html         # Photos gallery
├── listen.html         # Audio recordings
├── watch.html          # Video performances
├── connect.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript for interactions
├── README.md           # Repository readme
└── WEBSITE_README.md   # This file (website documentation)
```

After adding media:
```
probable-fiesta/
├── ... (files above)
├── photos/             # Your photo files
│   ├── photo1.jpg
│   ├── photo2.jpg
│   └── ...
└── audio/              # Your audio files
    ├── csardas.mp3
    ├── biblical-songs-1.mp3
    └── ...
```

## Browser Compatibility

The website works on:
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Support

If you need help:
1. Check the customization guide above
2. Review the HTML comments in each file
3. The CSS is well-organized and commented

## License

© 2026 Amalia Francalangia. All rights reserved.

---

**Need to update content?** Just edit the HTML files - they're written in plain, easy-to-read HTML!
