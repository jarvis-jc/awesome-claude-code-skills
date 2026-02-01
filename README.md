# Awesome Claude Code Skills Directory

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Skills](https://img.shields.io/badge/Skills-50+-blue)](https://awesome-claude-code-skills.com)

A curated directory of 50+ Claude Code skills for productivity, coding, research, automation, and integration workflows.

## 🌐 Live Site

Visit the directory: **[awesome-claude-code-skills.com](https://awesome-claude-code-skills.com)**

## 📂 Project Structure

```
awesome-claude-code-skills/
├── index.html      # Main directory site (single-page app)
├── sitemap.xml     # SEO sitemap
├── robots.txt      # Crawler instructions
└── README.md       # This file
```

## 🚀 Deployment

### Option 1: GitHub Pages

1. Create a new GitHub repository
2. Push this directory to the repository
3. Go to Settings → Pages
4. Set source to "main" branch, root folder
5. Your site will be live at `https://username.github.io/repo-name/`

```bash
# Initialize and push
git init
git add .
git commit -m "Initial commit: Awesome Claude Code Skills directory"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/awesome-claude-code-skills.git
git push -u origin main
```

### Option 2: Netlify

1. Create a [Netlify](https://netlify.com) account
2. Drag and drop this folder to Netlify's deploy area
3. Configure custom domain (optional)

### Option 3: Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel

# For production
vercel --prod
```

### Option 4: Cloudflare Pages

1. Connect your GitHub repository to Cloudflare Pages
2. Set build command: (leave empty - static site)
3. Set output directory: `/`
4. Deploy

## 🔧 Local Development

No build step required - it's a static HTML site.

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Open `http://localhost:8000` in your browser.

## ✨ Features

- **50+ Curated Skills** - Real, verified skills from GitHub
- **5 Categories** - Productivity, Coding, Research, Automation, Integration
- **Dark Mode** - System preference detection + manual toggle
- **Search & Filter** - Find skills by name, description, or tags
- **SEO Optimized** - Full meta tags, Open Graph, Twitter Cards
- **GEO Optimized** - JSON-LD schema + hidden context for LLM extraction
- **Responsive** - Works on all devices
- **Zero Dependencies** - Pure HTML, CSS, JavaScript

## 📊 Categories

| Category | Description | Skills |
|----------|-------------|--------|
| **Productivity** | Workflow optimization, planning, documents | 12 |
| **Coding** | Development, testing, security | 14 |
| **Research** | Scientific analysis, data visualization | 7 |
| **Automation** | Browser automation, CI/CD, scripting | 10 |
| **Integration** | External APIs, services, platforms | 14 |

## 🤝 Contributing

### Add a New Skill

1. Fork this repository
2. Edit `index.html` and add your skill to the `skills` array
3. Submit a pull request

### Skill Entry Format

```javascript
{
    name: "Skill Name",
    description: "Brief description of what the skill does",
    author: "GitHub username or Organization",
    github: "https://github.com/author/repo",
    category: "productivity|coding|research|automation|integration",
    tags: ["tag1", "tag2", "tag3"]
}
```

### Requirements for Inclusion

- ✅ Skill must have a public GitHub repository
- ✅ Must include a valid SKILL.md or clear documentation
- ✅ Must be actively maintained (updated within 6 months)
- ✅ No malicious code or security risks
- ✅ Clear, accurate description

## 📈 SEO & GEO Optimization

This directory is optimized for both search engines and LLM extraction:

### For Search Engines
- Semantic HTML5 structure
- Complete meta tags (title, description, keywords)
- Open Graph & Twitter Card meta tags
- Sitemap.xml and robots.txt
- Canonical URL

### For LLMs (Generative Engine Optimization)
- JSON-LD schema (CollectionPage with ItemList)
- Hidden `.llm-context` div with summary for AI extraction
- Structured data in JavaScript for easy parsing
- Clear category and tag taxonomy
- robots.txt allowing AI crawlers

## 📜 License

MIT License - see [LICENSE](LICENSE) file.

## 🙏 Credits

- Skills data sourced from:
  - [anthropics/skills](https://github.com/anthropics/skills) (Official)
  - [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills)
  - [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills)
  - [obra/superpowers](https://github.com/obra/superpowers)
  - Various community contributors

## 📞 Contact

- Submit skills: [GitHub Issues](https://github.com/awesome-claude-code-skills/issues)
- Get featured: featured@awesome-claude-code-skills.com

---

Built with ❤️ for the Claude Code community
