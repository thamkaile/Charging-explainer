# Mobile Charging Physics Explainer

An interactive React-based physics explainer about mobile charging speeds.

## Deploy to Vercel

### Option 1: Vercel CLI (Recommended)

1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Navigate to this folder and deploy:
   ```bash
   cd C:\Users\user\charging-explainer-app
   vercel deploy
   ```

3. Follow the prompts to link/create a project.

### Option 2: Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Import this folder from your computer or push to GitHub first
4. Vercel will automatically detect it as a static site

### Option 3: Drag & Drop (via Vercel CLI)

```bash
vercel --prod
```

## Project Structure

```
charging-explainer-app/
├── index.html      # Main React app (single file)
├── vercel.json     # Vercel config (static site)
└── README.md       # This file
```

## Features

- 🔌 Interactive charger comparison (5W, 18W, 45W, 120W)
- ⚡ Real-time electron flow animation
- 📊 Power calculator with sliders
- 📚 Physics concepts (Voltage, Current, Power, Energy)
- 🔬 Ohm's Law simulator
- 🎨 Glassmorphism dark theme
- 📱 Fully responsive design
