# Images Needed for Eruku Project Page

To complete your website, you'll need to download and add the following images from the arXiv paper:

## Required Images

### 1. Teaser Image
- **Filename to save as:** `static/images/eruku_teaser.png`
- **Source:** Figure 1 from the paper (https://arxiv.org/html/2510.23240v1)
- **Description:** The main teaser figure showing Eruku's ability to generate text images with arbitrary length and great text adherence
- **Recommended size:** 1200px width (high resolution for retina displays)

### 2. Architecture Diagram
- **Filename to save as:** `static/images/eruku_architecture.png`
- **Source:** Figure 2 from the paper (https://arxiv.org/html/2510.23240v1)
- **Description:** The training framework diagram showing how Eruku conditions generation on style image, style text, and generation text
- **Recommended size:** 1200px width

### 3. Results/Comparison Image
- **Filename to save as:** `static/images/eruku_results.png`
- **Source:** Qualitative results figures from the paper (Section 5)
- **Description:** Examples of generated text images showing comparisons with other methods and results on various datasets
- **Recommended size:** 1200px width

### 4. Social Preview Image (Optional but Recommended)
- **Filename to save as:** `static/images/social_preview.png`
- **Description:** Create a 1200x630px image for social media previews (Twitter, Facebook, LinkedIn)
- **Recommended content:** Use the teaser image with the paper title overlaid, or create a custom graphic
- **Exact size:** 1200x630px (required for proper social media preview)

### 5. Favicon (Recommended)
- **Filename to replace:** `static/images/favicon.ico`
- **Description:** Replace the default favicon with your own (perhaps a small logo or icon representing the project)
- **Size:** 32x32px or 64x64px .ico file

## How to Download Images from arXiv

1. Visit the paper at: https://arxiv.org/html/2510.23240v1
2. Right-click on each figure and select "Save Image As..."
3. Save them with the filenames listed above in the `static/images/` directory
4. Make sure the images are high resolution (at least 1200px wide for main figures)

## Optional Images

If you want to add more visual content, consider:
- Additional comparison figures from the paper
- Example generations showing different handwriting styles
- Ablation study visualizations
- Results tables (can be saved as images for easy display)

## Notes

- All image paths in `index.html` are already configured to point to these files
- If you can't access certain images, you can remove those sections from the HTML
- For best performance, optimize images using tools like TinyPNG (https://tinypng.com) before uploading
- PNG format is recommended for diagrams and screenshots
- JPG format is acceptable for photographs or renders



