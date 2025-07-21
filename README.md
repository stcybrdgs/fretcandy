# Fret Candy

A coding-in-public blog documenting my journey from zero to indie hacker, with a focus on building music apps and tools for string players in the practice room.

> ### _"Music meets code, let's go!"_ 🎸

## About

Welcome to Fret Candy! This blog chronicles my adventure as a musician and developer turned music-app maker. My goal is to share all of my experiments, discoveries, and weird ideas - from initial concepts to (hopefully) successful MVPs.

What You'll Find Here:

- `Coding Journey Posts` - Raw, unfiltered updates on learning new technologies and tackling development challenges
- `Project Deep Dives` - Detailed breakdowns of app ideas, from initial concepts to implementation struggles
- `Music Tech Experiments` - Quick prototypes and weird ideas that may or may not work
- `Indie Hacker Insights` - Lessons learned, failures celebrated, and small wins documented
- `String Player Tools` - Progress updates on apps designed to make practice time more efficient

## Tech Stack

Keeping it simple:

- **Static Site Generator**: [Hugo](https://gohugo.io/)
- **Theme Template**: [Papermod](<[text](https://themes.gohugo.io/themes/hugo-papermod/)>)
- **Frontend**: HTML, CSS, JavaScript with Hugo templating
- **Deployment**: [Netlify](https://www.netlify.com/)
- **Domain**: fretcandy.com(https://fretcandy.com)

## Development

If you like my blog layout, feel free to quick start one of your own by cloning my repo.

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (extended version recommended)
- Git

### Local Development

1. Clone the repository:

   ```bash
   git init
   git clone https://github.com/stcybrdgs/fretcandy.com.git
   cd fretcandy.com
   ```

2. Start the Hugo development server:

   ```bash
   # serve the blog site with published posts
   hugo server

   # serve the blog site with published and draft posts
   hugo server -D
   ```

3. Open your browser to `http://localhost:1313`

### Building for Production

```bash
hugo --minify
```

The site will be built with minified files to the `public/` directory.

## Content Structure

If you clone the repo, you'll find the interesting stuff at these locations in the project structure:

```txt
fretcandy.com
├── content/
│   ├── posts/ # blog posts about the journey
│   └── tags/ # navbar tags page
│       ├── archives # navbar archives page
│       └── search # navbar search page
├── layouts/
│   └── shortcodes # embedded micro apps
└── themes/ # hugo themes
    └── PaperMod/ # fretcandy.com blog theme
```

## Deployment

Because the blog site is setup on Netlify, the site is automatically deployed by Netlify whenever changes are pushed to the main GitHub branch. Netlify handles:

- Automatic builds using Hugo
- Custom domain configuration
- SSL certificates
- Form handling

You can learn more about using Hugo with Netlify at [Hugo on Netlify](<[text](https://docs.netlify.com/frameworks/hugo/)>)

## Following the Journey

- **Blog**: [fretcandy.com](https://fretcandy.com)
- **Twitter/X**: [@stcybrdgs](https://x.com/stcybrdgs)

## Current Projects

### Fret Charts

A web application for string players to create custom:

- Musical staves
- Tablature lines
- Practice charts
- Shareable and downloadable PDFs

_Status: In development - follow along for updates!_

## Contributing

While this is primarily a personal blog documenting my journey, I welcome:

- Bug reports and fixes
- Suggestions for blog topics
- Ideas for music apps that would help string players
- General feedback and encouragement

Feel free to [Contact](https://fretcandy.com/contact) me on the blog!

## License

Content is licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).

Code is licensed under the [MIT License](LICENSE).

---

_"Music meets code, let's go!"_ 🎸
