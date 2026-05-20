# The Brotherhood Blueprint - Quick Start Guide

## 🚀 Get Your Site Live in 5 Steps

### Step 1: Update Your Hosts (5 mins)
**File**: `index.html` and `hosts.html`

Find these sections and replace:
```html
<div class="host-name">Host Name</div>
<div class="host-title">Leadership & Vision</div>
<p class="host-bio">Bio text here...</p>
```

**Your host names**: Walter, RaShaun, Derrick  
**Their roles**: Leadership & Vision | Faith & Family | Growth & Accountability

---

### Step 2: Add Your Photos (10 mins)
**Replace these images:**

1. **Hero Group Photo** (index.html, line ~58)
   ```html
   src="https://images.unsplash.com/photo-1552664730-d307ca884978?w=1200&h=600&fit=crop"
   ```
   → Replace with your group photo (1200x600px)

2. **Host Headshots** (3 total, ~400x350px each)
   - index.html: lines ~135, ~155, ~175
   - hosts.html: lines ~53, ~73, ~93

3. **Cinematic Moments** (2 total, 1200x400px each)
   - index.html: lines ~191, ~229
   - about.html: line ~53
   - hosts.html: line ~131

---

### Step 3: Link Your Podcasts (5 mins)
**Spotify & Apple Podcasts links:**

`index.html` line ~50 and `platforms.html` lines ~28-30:
```html
<!-- Replace these URLs with your actual podcast links -->
href="https://open.spotify.com/show/YOUR_SHOW_ID"
href="https://podcasts.apple.com/us/podcast/YOUR_NAME/id123456789"
```

Find your links:
- **Spotify**: Go to your show, click share, copy link
- **Apple Podcasts**: Search your podcast, click "Open in Apple Podcasts", share link

---

### Step 4: Update Social Media (5 mins)
**Your four platforms:**

`index.html` lines ~239-244 and `platforms.html` lines ~94-99:
```html
<a class="social-link" href="https://www.youtube.com/YOUR_CHANNEL">YouTube</a>
<a class="social-link" href="https://www.tiktok.com/@YOUR_HANDLE">TikTok</a>
<a class="social-link" href="https://www.facebook.com/YOUR_PAGE">Facebook</a>
<a class="social-link" href="https://www.instagram.com/YOUR_HANDLE">Instagram</a>
```

---

### Step 5: Set Up Contact Form (5 mins)
**Three easy options:**

**Option A: Simple Email (Easiest)**
Find contact form in `index.html` line ~254:
```html
<form class="contact-form" action="mailto:your-email@example.com" method="POST">
```

**Option B: Formspree (Recommended)**
1. Go to https://formspree.io
2. Sign up free
3. Create new form
4. Replace action with your Formspree endpoint

**Option C: Your Server**
Work with your hosting provider for form processing

---

## 📸 Image Quick Reference

| Location | Size | Purpose |
|----------|------|---------|
| Hero Group Photo | 1200x600 | Brotherhood connection |
| Host Headshots (3) | 400x350 | Individual portraits |
| Featured Episode | 500x500 | Episode cover art |
| Cinematic Moment 1 | 1200x400 | Recording session |
| Cinematic Moment 2 | 1200x400 | Authentic moment |
| Cinematic Moment 3 | 1200x400 | Lifestyle/action |

**Pro Tip**: Use compressed JPEG (~150KB each) for fast loading

---

## 🔗 All Links to Update

### Social Media (index.html, platforms.html)
- [ ] YouTube channel URL
- [ ] TikTok profile URL
- [ ] Facebook page URL
- [ ] Instagram profile URL

### Podcasts (index.html, platforms.html)
- [ ] Spotify show link
- [ ] Apple Podcasts link

### Contact (index.html)
- [ ] Contact form action (email or service)

---

## 🎨 Optional Customizations

### Add Your Logo
Replace emoji in all pages:
```html
<a class="logo" href="index.html">🏛️ The Brotherhood Blueprint</a>
```

With your logo or custom text:
```html
<a class="logo" href="index.html">
  <img src="assets/logo.png" alt="Logo" style="height: 40px;">
</a>
```

### Change Colors
Edit `assets/css/styles.css` lines 3-11:
```css
--bg-primary: #0f172a;        /* Dark background */
--accent-blue: #2f5d95;       /* Bright accent */
--text-primary: #f1f5f9;      /* Text color */
--text-secondary: #94a3b8;    /* Secondary text */
```

### Update Site Title
All 4 HTML files:
```html
<title>The Brotherhood Blueprint - Build Men. Build Legacy.</title>
<meta name="description" content="Your description here...">
```

---

## 🧪 Testing Checklist

Before going live:

- [ ] All host names and bios filled in
- [ ] All photos uploaded (6 total)
- [ ] Social media links work
- [ ] Podcast links work
- [ ] Contact form sends
- [ ] Site looks good on phone
- [ ] All buttons work
- [ ] No broken links

**Test on phone**: Open `index.html` in mobile browser, scroll through pages

---

## 🚀 Deploy to Web

### Option 1: GitHub Pages (Free)
1. Create GitHub account
2. Upload files to new repository
3. Settings → Pages → enable
4. Site live at `username.github.io`

### Option 2: Netlify (Free & Easy)
1. Go to netlify.com
2. Drag & drop your folder
3. Site live in seconds
4. Custom domain available

### Option 3: Your Own Server
Upload files via FTP or hosting control panel

---

## 📱 Mobile Testing

After uploading, test on real devices:

1. **Phone**: Check all text reads well, images load
2. **Tablet**: Verify layout looks balanced
3. **Desktop**: Ensure wide spacing feels premium

Use browser dev tools (F12 → responsive mode) to test all sizes

---

## 🎯 Launch Day Checklist

1. ✅ All content updated
2. ✅ All images uploaded (and optimized)
3. ✅ All links work (social, podcast, contact)
4. ✅ Site tested on mobile
5. ✅ Domain name set (if custom)
6. ✅ Analytics set up (if desired)
7. ✅ Deployed to hosting
8. ✅ Share on social media
9. ✅ Promote to email list
10. ✅ Submit to podcast directories

---

## 📚 Full Documentation

For more details, see:
- **CUSTOMIZATION_GUIDE.md** - Detailed customization
- **DESIGN_REFERENCE.md** - Design system reference
- **IMPLEMENTATION_SUMMARY.md** - What was built

---

## ⏱️ Time Estimate

| Task | Time |
|------|------|
| Update host info | 5 min |
| Upload photos | 10 min |
| Add podcast links | 5 min |
| Update socials | 5 min |
| Set up contact form | 5 min |
| Test on mobile | 10 min |
| Deploy | 5 min |
| **Total** | **45 min** |

---

## 💡 Pro Tips

1. **Use Unsplash** (https://unsplash.com) for placeholder images while you gather real photos
2. **Optimize images** before uploading to keep site fast
3. **Test everything** on real phone before sharing
4. **Update content regularly** to keep site fresh
5. **Monitor contact form** to respond quickly to inquiries
6. **Share updates** on social media regularly

---

## 🆘 Troubleshooting

**Images not showing?**
- Check file path is correct
- Use full URLs for images from other sites

**Links not working?**
- Make sure URLs are complete (https://...)
- Test in different browser

**Form not sending?**
- Set up email service (Formspree)
- Or use form plugin for your host

**Site looks wrong on mobile?**
- Clear browser cache (Ctrl+Shift+Delete)
- Test in different mobile browser

---

## 🎊 You're Done!

Your premium podcast website is ready to inspire, connect, and build community.

**"Build Men. Build Legacy."**

---

**Questions?** See CUSTOMIZATION_GUIDE.md for detailed instructions.  
**Need design help?** Check DESIGN_REFERENCE.md for all colors and spacing.
