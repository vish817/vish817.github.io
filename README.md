# Toolify — GitHub Pages build

## Deploy from a phone (GitHub website)
1. Open your Toolify GitHub repository.
2. Upload the files from this ZIP to the repository's top/root folder. The root must contain `index.html` and the `public` folder.
3. In repository Settings → Pages, select **Deploy from a branch**, choose your main branch and **/(root)**, then Save.
4. Wait for the Pages deployment to finish and refresh your published URL.

## What's included
- Responsive, light professional homepage with five categories and 50 listed tools.
- Browser-side image tools, PDF merge/split/page removal/rotation, image-to-PDF, first-page PDF-to-JPG, ZIP tools, text tools, QR generation, password generation and daily utilities.
- Uses CDN libraries for QR, PDF and ZIP features; those features need an internet connection.

## Important honest limitations
- Background removal requires a secure server and a paid/valid external API key. It is deliberately not enabled on GitHub Pages.
- PDF password lock/unlock and DOCX-to-PDF require server-side tools and are deliberately not enabled.
- PDF text extraction outputs TXT, not a formatted DOCX.
- PDF re-saving does not guarantee a smaller file.
- Image crop uses pixel coordinates entered by the user; dimensions must be within the original image.
- Some browser APIs and downloads behave differently on older phones. Test with small files first.

This is a static GitHub Pages deployment. Do not upload API keys to GitHub or put secrets in JavaScript.
