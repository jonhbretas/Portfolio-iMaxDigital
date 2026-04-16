# iMaxDigital.com — Portfolio Website

## Project Structure

```
imaxdigital/
├── index.html          ← Main page
├── projects.json       ← All projects data (edit this to add/remove)
├── images/             ← Screenshot thumbnails for each project
│   ├── dental-clinic.jpg
│   ├── fashion-store.jpg
│   └── ...
├── assets/
│   └── favicon.svg     ← Site favicon
└── README.md           ← You are here
```

## How to Add / Edit Projects

1. Open `projects.json`
2. Add a new entry following this format:

```json
{
  "title": "Project Name",
  "tag": "business",
  "link": "https://your-live-site-or-drive-link.com",
  "thumb": "images/project-name.jpg",
  "desc": "Short description"
}
```

3. Drop the screenshot image into the `images/` folder
4. Push to GitHub → Vercel auto-deploys

### Available tags (categories):
- `landing-page`
- `business`
- `e-commerce`
- `portfolio`
- `blog`

You can add new categories by editing the filter buttons in `index.html`.

### Recommended image size:
- **1280 x 800px** (16:10 ratio)
- Format: `.jpg` or `.webp` for best performance
- Keep file size under 200KB (use TinyPNG to compress)
