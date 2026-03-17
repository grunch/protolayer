# ProtoLayer - Landing Page

Official website for ProtoLayer, a technology company focused on open-source software and digital infrastructure.

## Tech Stack

- **Framework:** Astro 5
- **Styling:** Custom CSS with design tokens
- **Fonts:** 
  - Sora (Display)
  - Plus Jakarta Sans (Body)
  - JetBrains Mono (Code)

## Design System

### Colors
- **Accent/Brand:** `hsl(160, 84%, 39%)` (emerald green)
- **Light/Dark mode:** Automatic via `prefers-color-scheme`

### Typography
- Display headings: Sora
- Body text: Plus Jakarta Sans
- Code/Terminal: JetBrains Mono

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

This site is deployed via GitHub Pages.

Push to `main` branch to trigger automatic deployment.

## Structure

```
/
├── public/           # Static assets
├── src/
│   └── pages/
│       └── index.astro   # Main landing page
├── astro.config.mjs  # Astro configuration
└── package.json
```

## Content Sections

1. **Hero** - Company introduction with terminal
2. **About** - Company details and founder info
3. **Projects** - Supported open-source projects (Mostro, etc.)
4. **Legal** - Registration and legal information
5. **Contact** - Email for inquiries

## License

MIT
