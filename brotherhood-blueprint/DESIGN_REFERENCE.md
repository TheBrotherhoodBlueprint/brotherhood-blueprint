# The Brotherhood Blueprint - Design Quick Reference

## 🎨 Color Palette

```
Primary Background    #0f172a  (Deep Navy - Very Dark Blue)
Secondary Background  #1a2744  (Slightly Lighter Navy)
Tertiary Background   #243656  (Even Lighter Navy)

Primary Accent        #2f5d95  (Blueprint Blue)
Light Accent          #3d7abb  (Lighter Blueprint Blue)

Primary Text          #f1f5f9  (Soft White)
Secondary Text        #94a3b8  (Muted Gray)
Muted Text           #64748b  (Darker Gray)
```

## 📐 Design System

### Spacing Scale
```
xs  = 0.5rem   (8px)
sm  = 1rem     (16px)
md  = 1.5rem   (24px)
lg  = 2rem     (32px)
xl  = 3rem     (48px)
2xl = 4rem     (64px)
3xl = 6rem     (96px)
```

### Typography Scale
```
h1  (text-6xl)  = 3.75rem  (60px)
h2  (text-4xl)  = 2.25rem  (36px)
h3  (text-2xl)  = 1.5rem   (24px)
h4  (text-xl)   = 1.25rem  (20px)
p   (text-base) = 1rem     (16px)
```

### Font Family
```
Primary: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 
         'Helvetica Neue', Arial, sans-serif
```

### Animation Speeds
```
Fast  = 150ms ease
Base  = 250ms ease
Slow  = 350ms ease
```

## 🧩 Component Classes

### Buttons
```html
<a class="button button-primary">Primary Button</a>
<a class="button button-secondary">Secondary Button</a>
```

### Cards
```html
<div class="card">Card Content</div>
```

### Host Cards
```html
<div class="host-card">
  <img class="host-image" src="..."/>
  <div class="host-content">
    <div class="host-name">Name</div>
    <div class="host-title">Title</div>
    <p class="host-bio">Bio</p>
  </div>
</div>
```

### Grids
```html
<div class="hosts-grid">...</div>    <!-- 3 columns responsive -->
<div class="images-grid">...</div>   <!-- 3 columns responsive -->
<div class="social-grid">...</div>   <!-- 4 columns responsive -->
<div class="preview">...</div>       <!-- 3 columns responsive -->
```

## 📄 Page Sections

### Homepage (index.html)
1. ✅ Navigation Header with Logo
2. ✅ Hero Section (Tagline, CTA)
3. ✅ Group Photo (Photo #1)
4. ✅ Mission Statement
5. ✅ 3 Host Profile Cards
6. ✅ Cinematic Moment (Photo #2)
7. ✅ Featured Episode
8. ✅ What We Discuss (3 topics)
9. ✅ Cinematic Moment (Photo #3)
10. ✅ Listen Now (Spotify + Apple)
11. ✅ Social Media Links
12. ✅ Contact Form
13. ✅ Footer

### About Page (about.html)
1. ✅ Section Intro
2. ✅ Vision Statement
3. ✅ Core Values (6 cards)
4. ✅ Cinematic Moment
5. ✅ Topics Covered (3 cards)
6. ✅ Why It Matters
7. ✅ CTA Buttons

### Hosts Page (hosts.html)
1. ✅ Section Intro
2. ✅ Detailed Host Cards (3)
3. ✅ Cinematic Moment
4. ✅ Why These Three
5. ✅ What to Expect (3 cards)
6. ✅ CTA Button

### Listen Page (platforms.html)
1. ✅ Section Intro
2. ✅ Featured Platforms (2 buttons)
3. ✅ All Platforms Grid (6 cards)
4. ✅ Cinematic Moment
5. ✅ Subscribe Section
6. ✅ Social Media Section
7. ✅ FAQ Section
8. ✅ Contact CTA

## 🔗 Social Media & Platforms

Replace these placeholder URLs with your actual links:

### Social Media
```
YouTube:   https://www.youtube.com/
TikTok:    https://www.tiktok.com/
Facebook:  https://www.facebook.com/
Instagram: https://www.instagram.com/
```

### Podcast Platforms
```
Spotify:         https://open.spotify.com/show/YOUR_ID
Apple Podcasts:  https://podcasts.apple.com/us/podcast/
Google Podcasts: https://www.google.com/podcasts/
Amazon Music:    https://music.amazon.com/
Stitcher:        https://www.stitcher.com/
Podbean:         https://www.podbean.com/
iHeartRadio:     https://www.iheartradio.com/
Deezer:          https://www.deezer.com/
```

## 🖼️ Image Specifications

### Group Photo (Hero)
- Size: 1200x600px (or 16:9 aspect ratio)
- Location: index.html, group-photo-section
- Purpose: Establishes brotherhood & cohesion

### Featured Episode Image
- Size: 500x500px (square)
- Location: index.html, featured-episode-image
- Purpose: Episode cover art

### Cinematic Moments (2 locations)
- Size: 1200x400px (3:1 aspect ratio)
- Locations: index.html (2x), about.html (1x), hosts.html (1x)
- Purpose: Atmospheric, authentic moments

### Host Headshots (3)
- Size: 400x350px (4:3.5 aspect ratio)
- Location: index.html, hosts.html
- Purpose: Individual portraits

## ✨ Key Design Features

- **Sticky Navigation**: Header stays visible while scrolling
- **Hover Effects**: Cards lift on hover with shadow and color change
- **Smooth Transitions**: All interactive elements use CSS transitions
- **Responsive Images**: Images scale with viewport
- **Blueprint Accents**: Subtle gradient overlays and border colors
- **Dark-Mode Premium**: Deep navy base with bright accent colors
- **Cinematic Feel**: Large images, generous spacing, dramatic overlays
- **Accessibility**: High contrast ratios, semantic HTML, proper alt text

## 🚀 Deployment Ready

- ✅ No dependencies required
- ✅ No build process needed
- ✅ Works with any hosting (static files)
- ✅ Mobile responsive (320px+)
- ✅ Fast loading (optimized CSS)
- ✅ SEO friendly (semantic HTML)

## 📱 Breakpoints

```
Desktop:  Default (1200px max-width)
Tablet:   @media (max-width: 768px)
Mobile:   @media (max-width: 480px)
```

Layouts automatically adjust for smaller screens with responsive grid columns and scaled typography.

---

**Design System Version**: 1.0  
**Last Updated**: May 18, 2026  
**Tagline**: "Build Men. Build Legacy."
