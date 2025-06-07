# The Epoch Tour - EL EL EM

*Teaching the world to speak LLM*

## About

The Epoch Tour by EL EL EM brings world-class Large Language Model education to global innovation hubs. Our intensive workshops transform professionals into AI leaders through hands-on learning with real APIs and production systems.

## Features

- **Global Workshops**: LLM education across major tech hubs worldwide
- **Expert Faculty**: Harvard researchers and industry veterans
- **Hands-On Learning**: Real API integration and production systems
- **Professional Network**: Connect with AI practitioners globally
- **Brand Colors**: #809AFF and Black for consistent branding

## Structure

```
worldtour/
├── _config.yml          # Jekyll configuration
├── index.md             # Homepage
├── _data/
│   └── navigation.yml   # Site navigation structure
├── _pages/
│   ├── workshops.md     # Workshops overview page
│   └── about.md         # About us page
├── _workshops/          # Individual workshop pages
│   └── saopaulo.md      # São Paulo LLM Workshop
├── _includes/
│   └── masthead.html    # Custom header with brand colors
└── assets/
    └── images/          # Images organized by category
        └── header/      # Header images
```

## Getting Started

### Local Development

1. **Install dependencies**:
   ```bash
   bundle install
   ```

2. **Run the development server**:
   ```bash
   bundle exec jekyll serve
   ```

3. **Visit**: http://localhost:4000

### GitHub Pages Deployment

This site is configured for GitHub Pages deployment using the minimal-mistakes theme.

1. Fork or clone this repository
2. Update `_config.yml` with your GitHub username in the `url` field
3. Push to your GitHub repository
4. Enable GitHub Pages in repository settings
5. Your site will be available at `https://your-username.github.io/repository-name`

## Customization

### Adding New Workshops

1. Create a new file in `_workshops/` directory
2. Follow the existing workshop page format (see `saopaulo.md`)
3. Add navigation entry in `_data/navigation.yml`
4. Use brand colors (#809AFF and Black) for consistency

### Modifying Design

- Global styles: Edit `_config.yml` for theme settings
- Custom header: Edit `_includes/masthead.html`
- Workshop pages: Add `<style>` blocks to individual pages
- Brand colors: Use #809AFF (primary) and Black (secondary)

### Content Updates

- Homepage: Edit `index.md`
- About page: Edit `_pages/about.md`
- Workshops: Edit `_pages/workshops.md`
- Navigation: Edit `_data/navigation.yml`

## Key Features

### Workshop Pages
Each workshop includes:
- Professional hero section with brand colors
- Comprehensive schedule and curriculum
- Faculty information
- Prerequisites and learning outcomes
- Venue details and pricing
- Registration call-to-action

### Responsive Design
- Mobile-first approach
- Wide layout for better content display
- Professional color scheme
- Modern CSS with hover effects

## Configuration

Key configuration files:
- `_config.yml` - Main site configuration with remote theme
- `_data/navigation.yml` - Site navigation
- `_workshops/` - Workshop content
- `_includes/masthead.html` - Custom header with brand colors

## Dependencies

- Jekyll (via github-pages gem)
- Minimal Mistakes remote theme
- GitHub Pages compatible plugins

## Brand Colors

- Primary: #809AFF
- Secondary: Black (#000000)

## Contact

For workshop inquiries: workshops@epochtour.com

---

*Teaching the world to speak LLM - The Epoch Tour by EL EL EM*