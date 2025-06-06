# GitHub Copilot Metrics Viewer

🤖 **Interactive dashboard for visualizing GitHub Copilot usage metrics and analytics**

A web-based dashboard that provides insights into GitHub Copilot usage patterns, acceptance rates, editor distribution, and user engagement trends. Built as a single-page application with no external dependencies.

> 🚀 **Ready to use in seconds!** Just open in your browser - no installation, no setup, no server required. All data processing happens locally for complete privacy.

![GitHub Copilot Dashboard](https://img.shields.io/badge/GitHub-Copilot-blue?style=for-the-badge&logo=github)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-F5788D?style=for-the-badge&logo=chart.js&logoColor=white)

## ✨ Features

- **🔒 Privacy-First**: All data processing happens locally in your browser - no external transmission
- **⚡ Zero Setup**: Just open in any modern browser - no installation or configuration required
- **📊 Overview Analytics**: Daily active users, chat usage by editor, code completions by language
- **🔍 Advanced Analytics**: Suggestions vs acceptances, acceptance rates, usage patterns by day type
- **💡 Insights Dashboard**: Usage heatmap, interactive filtering, detailed statistics tables

## 🚀 Getting Started

### Option 1: GitHub Pages (Recommended)
✨ **Instant access**: Visit the live dashboard at: https://thomast1906.github.io/github-copilot-metric-viewer-test/

### Option 2: Local Usage
📁 **Download and go**: Clone the repository and open `index.html` in your browser  
📊 **Load your data**: Click "📁 Load Data" and upload your GitHub Copilot metrics JSON file  
🎮 **Try the demo**: Use the included `sample.json` file to explore features  
💡 **No server required**: The dashboard works directly from your file system - just double-click and open!

### Option 3: Clone/Fork and Deploy
Clone or fork the repository and run it with your own GitHub Actions to deploy to your own GitHub Pages or other hosting platforms. The included GitHub Actions workflow in `.github/workflows/deploy.yml` automatically deploys to GitHub Pages on push to the main branch.

## 🧪 Sample Data

A sample dataset (`sample.json`) is included in the repository to help you:
- Explore the dashboard features without your own data
- Understand the expected data format
- Test new features during development

The sample data includes:
- 27 days of metrics spanning various dates in 2024-2025
- Multiple editors (VS Code, JetBrains)
- Various programming languages (JavaScript, Python, TypeScript, Java, Kotlin, React)
- Both code completion and chat usage data
- Realistic usage patterns and acceptance rates

## 📋 Getting Your Data

**Ready to see your own Copilot insights?** Here's how to get your data in 3 simple steps:

> 💡 **New to the dashboard?** Try the [live demo](https://thomast1906.github.io/github-copilot-metric-viewer-test/) with sample data first by clicking "📝 Load Sample Data"

### 🚀 Quick Start (Most Common)

1. **Get your data** via GitHub's Copilot metrics API:
   ```bash
   curl -L \
     -H "Accept: application/vnd.github+json" \
     -H "Authorization: Bearer <YOUR-TOKEN>" \
     -H "X-GitHub-Api-Version: 2022-11-28" \
     https://api.github.com/orgs/YOUR-ORG/copilot/metrics
   ```

2. **Save the response** to a `.json` file (e.g., `copilot-metrics.json`)

3. **Load it in the dashboard** - visit the [live dashboard](https://thomast1906.github.io/github-copilot-metric-viewer-test/), click "📊 Load GitHub Copilot Data", and paste your JSON data

### 📍 Where to Get Your Token
For detailed information about authentication and token setup, see the [GitHub Copilot Metrics API documentation](https://docs.github.com/en/rest/copilot/copilot-metrics?apiVersion=2022-11-28).

### 📋 Expected Data Format

Your JSON data should be an array of daily metrics records. Here's what the structure looks like:
```json
[
  {
    "date": "2024-01-01",
    "total_active_users": 150,
    "total_engaged_users": 140,
    "copilot_ide_code_completions": {
      "total_engaged_users": 120,
      "editors": [
        {
          "name": "vscode",
          "total_engaged_users": 100,
          "models": [
            {
              "name": "default",
              "languages": [
                {
                  "name": "javascript",
                  "total_engaged_users": 50,
                  "total_code_suggestions": 1000,
                  "total_code_acceptances": 750,
                  "total_code_lines_suggested": 5000,
                  "total_code_lines_accepted": 3750
                }
              ]
            }
          ]
        }
      ]
    },
    "copilot_ide_chat": {
      "total_engaged_users": 80,
      "editors": [
        {
          "name": "vscode",
          "total_engaged_users": 70,
          "models": [
            {
              "name": "gpt-4",
              "total_chats": 200
            }
          ]
        }
      ]
    }
  }
]
```

## 🛠️ Technical Details

Built with HTML5, CSS3, vanilla JavaScript, and Chart.js. Works in all modern browsers with no build process required. All data processing happens client-side for maximum privacy and security.

## 📖 Usage Examples

**Enterprise Teams**: Monitor Copilot adoption, track acceptance rates, analyze usage patterns, optimize licensing costs

**Individual Developers**: Personal productivity tracking, language-specific insights, editor preference analysis

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

1. Fork the repository → 2. Create a feature branch → 3. Make changes → 4. Test → 5. Submit PR

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

For a detailed analysis of why MIT License was chosen for this project, see [LICENSE_ANALYSIS.md](LICENSE_ANALYSIS.md).

## 🆘 Support

- **Issues**: [GitHub Issues](https://github.com/thomast1906/github-copilot-metric-viewer-test/issues)
- **Discussions**: [GitHub Discussions](https://github.com/thomast1906/github-copilot-metric-viewer-test/discussions)

## 🏗️ Roadmap

- (Coming Soon)

---

**Made with ❤️ for the GitHub Copilot community**