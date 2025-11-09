# Product Website

This is a ready-to-upload static website (single-file index.html + images) generated from your product PDF.
It includes:
- Responsive product grid with placeholder images (SVG)
- Search, sort, min/max price filter
- Product details modal
- CSV export of the product list

## How to publish on GitHub Pages

1. Create a new GitHub repository (public).
2. Upload all files from this ZIP into the repository root (index.html, images/).
3. In the repository Settings → Pages, set:
   - Source: Deploy from a branch
   - Branch: main (root)
4. Save. Your site will be available at:
   https://yourusername.github.io/<repo-name>/index.html

## Notes
- The site uses placeholder SVG images stored in the `images/` folder.
- If you want real product photos, upload them into `images/` and name them `product-1.<ext>`, etc.
