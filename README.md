# Baukasten SCSS Framework

A modular SCSS framework with hot reload capabilities for rapid development.

## Features

- 🎨 Modular SCSS architecture
- 🔥 Hot reload development server
- 📱 Responsive grid system
- 🧩 Utility-first approach
- 🎯 Customizable themes
- ✅ Built-in linting and formatting

## Quick Start

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start development server with hot reload:
   ```bash
   npm run dev
   ```

3. Build for production:
   ```bash
   npm run build
   npm run build:compressed
   ```

## Available Scripts

- `npm run build` - Compile SCSS to CSS (expanded)
- `npm run build:compressed` - Compile SCSS to minified CSS
- `npm run watch` - Watch SCSS files for changes
- `npm run dev` - Start development server with hot reload
- `npm run serve` - Start live server
- `npm run lint` - Lint SCSS files
- `npm run format` - Format SCSS files with Prettier

## Project Structure

```
baukasten/
├── src/
│   ├── base/              # Reset, variables, typography
│   ├── layout/            # Grid, flexbox, container
│   ├── components/        # Buttons, cards, forms
│   ├── utilities/         # Spacing, colors, display
│   ├── themes/            # Theme variations
│   └── baukasten.scss     # Main entry point
├── dist/                  # Compiled CSS files
├── demo/                  # Demo HTML files
└── package.json
```

## Customization

### Variables
Customize the framework by modifying CSS custom properties in `src/base/_variables.scss`.

### Themes
Add new themes in the `src/themes/` directory and import them in the main SCSS file.

### Components
Create new components in `src/components/` and import them in `baukasten.scss`.

## Browser Support

- Chrome (latest)
- Firefox (latest) 
- Safari (latest)
- Edge (latest)

## License

MIT