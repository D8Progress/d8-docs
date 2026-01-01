# D8 Progress Documentation

User guide and documentation for **D8 Progress** - gamified goal tracking designed specifically for neurodivergent brains.

🌐 **Live Documentation**: https://d8progress.github.io/d8-docs/

## About This Repository

This repository contains the user-facing documentation for D8 Progress, built with [Hugo](https://gohugo.io/) and the [Docsy](https://www.docsy.dev/) theme.

## 🚀 Quick Start

### Prerequisites

1. **Hugo Extended** (v0.110.0+): https://gohugo.io/installation/
2. **Go** (v1.19+): https://golang.org/dl/
3. **Node.js** (for Docsy dependencies)

### Local Development

```bash
# Clone the repository
git clone https://github.com/D8Progress/d8-docs.git
cd d8-docs

# Initialize Hugo modules (downloads Docsy theme)
hugo mod init github.com/D8Progress/d8-docs
hugo mod get -u

# Install dependencies
npm install

# Start local server with live reload
hugo server

# View at http://localhost:1313/d8-docs/
```

## 📝 Contributing to Documentation

We welcome contributions to improve our documentation!

### Content Structure

```
content/
├── _index.md           # Homepage
├── docs/               # Main documentation
│   ├── getting-started/
│   ├── features/
│   ├── gamification/
│   └── accessibility/
└── community/          # Community pages
```

### Making Changes

1. **Fork this repository**
2. **Create a branch**: `git checkout -b improve-docs`
3. **Make your changes** to files in `content/`
4. **Test locally**: `hugo server`
5. **Submit a pull request**

### Writing Style Guidelines

- **Neurodivergent-friendly**: Use clear, direct language
- **Inclusive**: Consider ADHD, autism, and other neurodivergent experiences
- **Practical**: Include specific examples and screenshots
- **Accessible**: Use proper headings, alt text, and clear structure

## 🔧 GitHub Pages Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions when changes are pushed to the `main` branch.

### Custom Domain Setup

To use `docs.d8progress.com`:

1. Add `CNAME` file with domain name
2. Configure DNS to point to GitHub Pages
3. Enable HTTPS in repository settings

## 🛠️ Technical Details

### Hugo Modules

This site uses Hugo Modules instead of git submodules for theme management:

```bash
# Update Docsy theme
hugo mod get -u github.com/google/docsy

# Clean module cache if needed
hugo mod clean
```

### Docsy Theme Configuration

Key customizations:

- **Colors**: Matches D8 Progress branding
- **Navigation**: Links to community and main app
- **Feedback**: Directs users to GitHub issues/discussions
- **Search**: Enabled for better content discovery

## 📞 Support

- **Documentation Issues**: [Open an issue](https://github.com/D8Progress/d8-docs/issues)
- **General Questions**: [Community Discussions](https://github.com/D8Progress/d8-community/discussions)
- **App Support**: [Report in Community](https://github.com/D8Progress/d8-community/issues)

## 📄 License

This documentation is licensed under [Creative Commons Attribution 4.0 International](LICENSE).

D8 Progress application is proprietary software. See the main application for licensing terms.
