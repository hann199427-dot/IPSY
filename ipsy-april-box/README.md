# Ipsy Email Template

A beautiful, responsive email template for Ipsy beauty products with clean design and zero border-radius styling.

## 📁 Files Included

- `ipsy-email.html` - Main email template
- `ipsy-email.css` - Stylesheet (border-radius: 0)
- `README.md` - This file

## 🚀 Quick Start

### View Locally

1. Download both `ipsy-email.html` and `ipsy-email.css`
2. Keep them in the same folder
3. Open `ipsy-email.html` in your web browser

### Deploy to GitHub Pages

1. **Create a new repository on GitHub**
   ```bash
   # Create a new repo called "ipsy-email-template"
   ```

2. **Upload files**
   - Click "Add file" → "Upload files"
   - Drag and drop `ipsy-email.html` and `ipsy-email.css`
   - Commit changes

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Select "main" branch
   - Click Save

4. **Access your live email**
   - URL: `https://[your-username].github.io/ipsy-email-template/ipsy-email.html`

## 🎨 Customization

### Update Images

Replace the image URLs in `ipsy-email.html`:

```html
<!-- Featured image (line ~40) -->
<img src="YOUR_IMAGE_URL_HERE" alt="Beauty products collection" />

<!-- Product images (lines ~60-80) -->
<img src="YOUR_IMAGE_URL_HERE" alt="Product name" />
```

### Change Colors

Edit `ipsy-email.css`:

```css
/* Primary pink gradient */
background: linear-gradient(to right, #ff3366, #ff4d6d);

/* Header gradient */
background: linear-gradient(to bottom right, #ff6b8a, #ff4d6d, #ff3366);

/* Dark button */
background: #2a2a2a;
```

### Update Text

All text content is in `ipsy-email.html`. Simply find and replace:
- Brand name: "ipsy"
- Product names
- Descriptions
- CTA button text

## 📧 Email Client Compatibility

For actual email campaigns, you'll need to **inline the CSS**:

### Tools for Inlining CSS:
- [Mailchimp CSS Inliner](https://templates.mailchimp.com/resources/inline-css/)
- [Juice](https://www.npmjs.com/package/juice) (Node.js)
- [Premailer](https://premailer.dialect.ca/) (Online tool)

### Why inline CSS?
Many email clients (Gmail, Outlook) don't support external stylesheets or `<style>` tags. Inlining CSS ensures your email looks great everywhere.

## 🎯 Features

✅ **Zero border-radius** - Clean, sharp edges  
✅ **Fully responsive** - Works on mobile and desktop  
✅ **Beautiful gradients** - Modern pink/white color scheme  
✅ **Product showcase** - Grid layout for multiple products  
✅ **Social links** - Footer with social media links  
✅ **Hover effects** - Interactive elements  

## 📱 Mobile Responsive

The template automatically adjusts for mobile devices:
- Single column on small screens
- Touch-friendly buttons
- Optimized text sizes

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Email Testing Checklist

Before sending your email campaign:

- [ ] Test in Gmail (web and app)
- [ ] Test in Outlook (desktop and web)
- [ ] Test in Apple Mail
- [ ] Test on iPhone/iPad
- [ ] Test on Android devices
- [ ] Check all links work
- [ ] Verify images load
- [ ] Test CTA buttons
- [ ] Check spelling and grammar

## 🎓 Tips for Email Marketing

1. **Subject Lines**: Keep under 50 characters
2. **Preview Text**: Customize the first line of your email
3. **Images**: Use alt text for accessibility
4. **CTAs**: Make buttons large and obvious
5. **Testing**: Always send test emails before launching
6. **Mobile First**: 60%+ of emails are opened on mobile

## 📄 License

Free to use and modify for personal and commercial projects.

## 🤝 Support

For questions or issues:
- Create an issue in this repository
- Check the [GitHub Pages documentation](https://docs.github.com/en/pages)

---

**Made with ❤️ for Ipsy**
