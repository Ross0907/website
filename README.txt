Site README

Add a PDF to the site root named `resume.pdf` to host it directly.
When you share `https://<your-site-domain>/resume.pdf` the browser will open the PDF directly.

Files changed:
- Added a direct link in the navigation and a footer button in `index.html` pointing to `resume.pdf`.

Instructions:
1. Place your PDF file in the project root and name it `resume.pdf`.
2. Commit and deploy the site (for GitHub Pages or your static host). The URL `https://<your-domain>/resume.pdf` will serve the PDF with the correct Content-Type and open directly in browsers.

If you want me to add a small placeholder `resume.pdf` file to the repo, say so and I will create one.

Changes made:
- Renamed `resume.pdf` → `ec_lab_delta_sigma.pdf` and updated links in `index.html`.
- Added three minimal image-only pages that display project images without the site chrome:
	- `image_work_1.html` -> `images/work_1_large.jpg`
	- `image_work_2.html` -> `images/work_2_large.jpg`
	- `image_work_3.html` -> `images/work_3_large.jpg`

Direct links you can share:
- PDF: `https://<your-domain>/ec_lab_delta_sigma.pdf`
- Images: `https://<your-domain>/image_work_1.html`, `https://<your-domain>/image_work_2.html`, `https://<your-domain>/image_work_3.html`

Gallery:
- A simple gallery page was added at `gallery.html` which links to clean image pages suitable for sharing.
- New page: `gallery.html` (thumbnail grid)
- New page: `image_work_4.html` (image-only view for work_4_large.jpg)

Share example URLs once deployed:
- `https://<your-domain>/gallery.html`
- `https://<your-domain>/image_work_4.html`
