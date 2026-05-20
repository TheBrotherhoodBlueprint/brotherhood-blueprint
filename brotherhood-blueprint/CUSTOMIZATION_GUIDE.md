# The Brotherhood Blueprint - Premium Podcast Website
## Customization Guide

---

## 🎨 Design System Overview

Your website now features a premium, cinematic dark-mode aesthetic with blueprint-inspired elements. The design combines modern masculine branding with emotional depth.

### Color Palette
- **Background**: `#0f172a` (Deep Navy)
- **Blueprint Blue Accent**: `#2f5d95` (Premium Accent)
- **Text Primary**: `#f1f5f9` (Soft White)
- **Text Secondary**: `#94a3b8` (Muted Gray)

All colors are defined as CSS custom properties in `assets/css/styles.css` under `:root`

### Typography
- **Font Stack**: System fonts (Segoe UI, Roboto, Helvetica Neue) for modern performance
- **Heading Scale**: From `h1` (3.75rem) down to `h4` (1.25rem)
- **Line Heights**: 1.3 for headings, 1.8 for body text
- **Letter Spacing**: Subtle (-0.5px for headings, 0.3px for body)

---

## 📝 Quick Customization Steps

### 1. Update Host Information
**File**: `index.html` and `hosts.html`

```html
<!-- Replace placeholder names and bios -->
<div class="host-name">Your Host Name</div>
<div class="host-title">Your Title/Role</div>
<p class="host-bio">Your host bio here...</p>
```

Host images are placeholders from Unsplash. Replace URLs with your actual headshots:
```html
<img 
  src="YOUR_IMAGE_URL" 
  alt="Host name" 
  class="host-image"
/>
```

### 2. Add Your Logo
**File**: `index.html`, `about.html`, `hosts.html`, `platforms.html`

Replace the emoji logo `🏛️` with your actual logo:
```html
<a class="logo" href="index.html">YOUR_LOGO The Brotherhood Blueprint</a>
```

Or use an image:
```html
<a class="logo" href="index.html">
  <img src="assets/logo.png" alt="The Brotherhood Blueprint" style="height: 40px;">
</a>
```

### 3. Update Social Media Links
**File**: `index.html`

Replace placeholder links with your actual social profiles:
```html
<a class="social-link" href="https://www.youtube.com/your-channel" target="_blank">YouTube</a>
<a class="social-link" href="https://www.tiktok.com/@yourprofile" target="_blank">TikTok</a>
<a class="social-link" href="https://www.facebook.com/yourpage" target="_blank">Facebook</a>
<a class="social-link" href="https://www.instagram.com/yourprofile" target="_blank">Instagram</a>
```

### 4. Link Spotify & Apple Podcasts
**File**: `index.html` and `platforms.html`

Replace placeholder URLs:
```html
<a class="button button-primary" href="https://open.spotify.com/show/YOUR_SHOW_ID">🎵 Spotify</a>
<a class="button button-primary" href="https://podcasts.apple.com/us/podcast/YOUR_PODCAST_NAME/id123456789">🎙️ Apple Podcasts</a>
```

### 5. Update Featured Episode
**File**: `index.html`

```html
<h3>Latest Episode</h3>
<h2>Your Episode Title</h2>
<p>Your episode description...</p>
```

### 6. Replace Placeholder Images

Three photo sections are ready for your content:

1. **Group Photo** (Hero section) - ~1200x600px
   ```html
   <img src="path/to/group-photo.jpg" alt="The Brotherhood Blueprint hosts together" />
   ```

2. **Featured Moment** (Mid-page) - 1200x400px
   ```html
   <img src="path/to/moment-photo.jpg" alt="Authentic moment from recording" />
   ```

3. **Cinematic Lifestyle** (Near bottom) - 1200x400px
   ```html
   <img src="path/to/lifestyle-photo.jpg" alt="Brotherhood in action" />
   ```

### 7. Enable Contact Form
**File**: `index.html`

The contact form currently submits to `#`. To make it functional:

**Option A: Simple Email Link**
```html
<form action="mailto:your-email@example.com" method="POST" enctype="text/plain">
```

**Option B: Formspree (Free service)**
1. Go to https://formspree.io
2. Create account and form
3. Replace `action="#"` with your Formspree endpoint

**Option C: Server-side processing**
Contact your hosting provider for form processing setup

### 8. Update Site Metadata
**Files**: All `.html` files

Update the `<title>` and `<meta name="description">` tags for better SEO:

```html
<title>The Brotherhood Blueprint - Build Men. Build Legacy.</title>
<meta name="description" content="Your custom description here...">
```

---

## 🎨 Design Customization

### Change Color Scheme
Edit `assets/css/styles.css` root variables:

```css
:root {
  --bg-primary: #0f172a;        /* Main background */
  --accent-blue: #2f5d95;       /* Primary accent */
  --text-primary: #f1f5f9;      /* Main text */
  --text-secondary: #94a3b8;    /* Secondary text */
}
```

### Adjust Spacing
Spacing scale is defined in root:
```css
--spacing-xs: 0.5rem;
--spacing-sm: 1rem;
--spacing-md: 1.5rem;
--spacing-lg: 2rem;
--spacing-xl: 3rem;
--spacing-2xl: 4rem;
--spacing-3xl: 6rem;
```

### Modify Typography Sizes
```css
--text-6xl: 3.75rem;    /* h1 */
--text-5xl: 3rem;       /* h1 secondary */
--text-4xl: 2.25rem;    /* h2 */
--text-2xl: 1.5rem;     /* h3 */
```

### Change Button Styling
Modify `.button`, `.button-primary`, `.button-secondary` classes in CSS.

### Adjust Card Hover Effects
Edit `.card:hover`, `.host-card:hover` in CSS to customize animation and elevation.

---

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- **Desktop**: Default (1200px max-width)
- **Tablet**: `@media (max-width: 768px)`
- **Mobile**: `@media (max-width: 480px)`

All spacing and typography scales down automatically on smaller screens.

---

## 🔧 Advanced Customization

### Add New Sections
Use the existing `.container` and section patterns:

```html
<section class="container">
  <h2>New Section Title</h2>
  <p>Your content...</p>
</section>
```

### Create Custom Cards
Base card styling:
```html
<div class="card">
  <h3>Card Title</h3>
  <p>Card content...</p>
</div>
```

### Add Animations
All transitions use CSS variables:
```css
transition: all var(--transition-base);  /* 250ms ease */
transition: all var(--transition-fast);  /* 150ms ease */
transition: all var(--transition-slow);  /* 350ms ease */
```

### Modify Navigation
Edit `.nav-links` and `.nav-links a` styles in CSS.

---

## 📋 Content Checklist

Before launch, ensure you've updated:

- [ ] Host names and bios (index.html, hosts.html)
- [ ] Host headshot images
- [ ] Group photo (hero section)
- [ ] Cinematic moment photos (2)
- [ ] Featured episode title and description
- [ ] Social media links (YouTube, TikTok, Facebook, Instagram)
- [ ] Spotify and Apple Podcasts links
- [ ] Contact form action
- [ ] Site metadata (title, description)
- [ ] Logo/branding
- [ ] All image alt text (for accessibility)

---

## 🚀 Performance Tips

1. **Optimize Images**: Use compressed JPG/WebP (under 200KB each)
2. **Lazy Load Images**: Add `loading="lazy"` attribute to images
3. **Cache Busting**: Append version to CSS: `styles.css?v=1.0`
4. **Minify CSS**: Use CSS minifier for production

---

## 🎯 SEO Best Practices

- Use descriptive titles and meta descriptions
- Include relevant keywords in headings
- Add alt text to all images
- Use semantic HTML (h1-h6 hierarchy)
- Link internally between pages
- Include structured data (Schema.org) for podcast

---

## 🛠️ Troubleshooting

**Images not showing?**
- Check image URLs are correct and accessible
- Ensure correct file paths (relative vs absolute)

**Styles not applying?**
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Verify CSS file path is correct in HTML

**Layout breaking on mobile?**
- Check responsive breakpoints in CSS
- Test with browser dev tools (F12)

**Form not working?**
- Ensure form `action` attribute is set correctly
- Test with a form service like Formspree

---

## 📚 File Structure

```
brotherhood-blueprint/
├── index.html              (Homepage)
├── about.html              (About page)
├── hosts.html              (Hosts page)
├── platforms.html          (Listen page)
├── assets/
│   └── css/
│       └── styles.css      (Main stylesheet)
└── Photos/                 (Your image files)
```

---

## 💡 Design Philosophy

Your site embodies:
- **Premium**: High-end, sophisticated aesthetic
- **Cinematic**: Dark-mode with strategic lighting
- **Masculine**: Bold typography, confident spacing
- **Emotional**: Warm color accents, inviting layout
- **Modern**: Clean lines, smooth animations
- **Accessible**: High contrast, readable fonts

---

## 🔗 Resources

- **Color Reference**: https://www.color-hex.com/
- **Typography**: https://systemfontstack.com/
- **Images**: https://unsplash.com/ (free stock photos)
- **Form Service**: https://formspree.io/
- **Podcast URLs**: Check your podcast provider's share links

---

## 📞 Support

For questions about customization or technical issues, refer to the inline comments in:
- `assets/css/styles.css` - Design tokens and component reference
- Individual `.html` files - Section comments

---

**Last Updated**: May 18, 2026  
**Version**: 1.0
