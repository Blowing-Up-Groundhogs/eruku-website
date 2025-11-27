# Eruku Project Page - Setup Instructions

Your website has been customized for the Eruku project! Here's what's been done and what you need to do next.

## ✅ Completed Customizations

### Meta Tags & SEO
- ✅ Updated all meta tags with Eruku project details
- ✅ Configured Open Graph tags for social media sharing
- ✅ Set up Twitter Card metadata
- ✅ Added structured data (Schema.org) for academic indexing
- ✅ Configured Google Scholar citation meta tags

### Content
- ✅ Updated paper title: "Autoregressive Styled Text Image Generation, but Make it Reliable"
- ✅ Added all 6 authors with correct affiliations (UNIMORE + Google)
- ✅ Set venue to WACV 2026
- ✅ Linked to arXiv paper (2510.23240)
- ✅ Linked to GitHub repository (https://github.com/Blowing-Up-Groundhogs/Eruku)
- ✅ Linked to Hugging Face demo (https://huggingface.co/spaces/carminezacc/eruku)
- ✅ Added complete abstract
- ✅ Created Key Features section highlighting:
  - Optional Style Text
  - Explicit Stopping mechanism
  - CFG-Inspired Strategy
- ✅ Added Results section with qualitative and quantitative comparisons
- ✅ Updated BibTeX citation
- ✅ Added related work (VATr++)

## 🔲 What You Need to Do

### 1. Download Images (CRITICAL)

See the `IMAGES_NEEDED.md` file for detailed instructions. You need to download these images from the arXiv paper:

```
static/images/eruku_teaser.png          (Figure 1 from paper)
static/images/eruku_architecture.png    (Figure 2 from paper)
static/images/eruku_results.png         (Results figures from paper)
static/images/social_preview.png        (Create 1200x630px preview)
static/images/favicon.ico               (Optional: custom favicon)
```

**Quick download:**
1. Visit https://arxiv.org/html/2510.23240v1
2. Right-click and save each figure
3. Rename them as specified above
4. Place in `static/images/` directory

### 2. Update Placeholder URLs

Search for `YOUR_DOMAIN.com` in `index.html` and replace with your actual domain:

```bash
# Example replacements:
YOUR_DOMAIN.com → blowing-up-groundhogs.github.io
# or
YOUR_DOMAIN.com → your-actual-domain.com
```

**Locations to update:**
- Line ~20-30: Open Graph URL
- Line ~37: Twitter image URL
- Line ~164: Schema.org image URL
- Line ~194: Organization logo URL

### 3. Test Locally

Your web server is already running on port 8989. Open your browser and visit:

```
http://localhost:8989
```

Check that:
- All sections display correctly
- Images load properly (after you download them)
- Links work correctly
- Mobile responsive design looks good (test by resizing browser)

### 4. Optional Enhancements

#### Add Author Personal Links
Update line ~248 for Fabio Quattrini's homepage (currently set to `#`):
```html
<a href="https://fabio-quattrini-homepage.com" target="_blank">Fabio Quattrini</a>
```

#### Add Your Personal Homepage URL
The page currently links to your homepage at `https://carzacc.github.io` (line ~246). Update if needed.

#### Create Social Preview Image
The social preview image (1200x630px) will appear when you share the link on Twitter, Facebook, or LinkedIn. Consider:
- Using the teaser image with title overlay
- Creating a custom graphic with key results
- Including author photos or logos

#### Add More Content (Optional)
You might want to add:
- Demo video (if available)
- Interactive visualizations
- Code examples
- Dataset download links
- Model checkpoints download links

## 📋 Final Checklist

Before deploying:

- [ ] Downloaded all required images
- [ ] Replaced `YOUR_DOMAIN.com` placeholders
- [ ] Tested all links (arXiv, GitHub, author pages)
- [ ] Verified images display correctly
- [ ] Checked mobile responsiveness
- [ ] Created social preview image (1200x630px)
- [ ] Replaced favicon.ico
- [ ] Tested BibTeX copy button
- [ ] Proofread all text content
- [ ] Validated HTML (optional: use https://validator.w3.org/)

## 🚀 Deployment Options

### GitHub Pages (Recommended)
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select branch (usually `main`) and root folder
4. Your site will be at: `https://username.github.io/repo-name/`

### Other Options
- Netlify: Drag and drop your folder
- Vercel: Connect your GitHub repo
- Traditional web hosting: Upload via FTP

## 🔧 Customization Tips

### Removing Sections
If you don't need certain sections, you can comment them out or delete them:
- Teaser image section (lines ~305-315)
- Key features section (lines ~357-384)
- Results section (lines ~387-418)
- Related works dropdown (lines ~189-235)

### Adding More Related Works
Edit lines ~225-232 to add more papers from your lab.

### Changing Colors
The main theme color is defined in meta tags (line ~53-54). You can also edit `static/css/index.css` for more customization.

## 📞 Support

- Template documentation: https://github.com/eliahuhorwitz/Academic-project-page-template
- Issues with template: Open issue on original template repo
- Your paper: https://arxiv.org/abs/2510.23240
- Your code: https://github.com/Blowing-Up-Groundhogs/Eruku

## 🎉 You're Almost Done!

The hard work is complete! Just download the images, test locally, and deploy. Your academic project page will look professional and be fully SEO-optimized.

Good luck with your paper! 🚀

