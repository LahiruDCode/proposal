# 💕 Proposal Web App — by Lahiruuu

## How to Add Your Photos

Place your photos inside the `/photos/` folder in this project.

### Main page photos (top section):
- `photos/photo1.jpg` → first photo (left)
- `photos/photo2.jpg` → second photo (right)

### Celebration popup photos (when she clicks YES):
- `photos/photo1.jpg` → top left
- `photos/photo2.jpg` → top right
- `photos/photo3.jpg` → bottom left
- `photos/photo4.jpg` → bottom right

---

## How to Activate the Photos in the Code

Open `index.html` and find the comment lines like:
```html
<!-- Replace with: <img src="photos/photo1.jpg" alt="Us"> -->
```

Replace the `<div class="photo-placeholder">...</div>` block below each comment with:
```html
<img src="photos/photo1.jpg" alt="Us">
```

Do the same for the celebration section — find the `<!-- <img src="photos/photo1.jpg"> -->` comments and uncomment them (remove the `<!--` and `-->`).

---

## Deploy to Vercel

1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → Import your repo
3. No build settings needed — just deploy!

---

## Project Structure

```
proposal/
├── index.html       ← Main web page
├── photos/          ← Put your photos here
│   ├── photo1.jpg
│   ├── photo2.jpg
│   ├── photo3.jpg
│   └── photo4.jpg
└── README.md
```

---

Made with ♥ by Lahiruuu
