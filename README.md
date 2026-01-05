# Nandini Gantayat — Portfolio

Static portfolio website for Quantum Machine Learning research.

## Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (npx)
npx serve
```

## Deploy to Vercel

### Option 1: Vercel CLI

```bash
npm i -g vercel
vercel
```

### Option 2: GitHub Integration

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Import the repository
4. Deploy (no configuration needed)

### Option 3: Drag & Drop

1. Go to [vercel.com/new](https://vercel.com/new)
2. Drag the entire folder to the upload area

## Structure

```
├── index.html      # Home page
├── research.html   # Research Spine
├── journey.html    # Career timeline
├── beyond.html     # Interests & contact
├── styles.css      # All styling
├── vercel.json     # Vercel config (clean URLs)
└── README.md
```

## Customization

- **Colors**: Edit CSS variables in `:root` block in `styles.css`
- **Fonts**: Change Google Fonts import at top of `styles.css`
- **Content**: Edit HTML files directly
