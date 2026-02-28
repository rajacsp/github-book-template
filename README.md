# GitHub Book Template

This is the GitHub Book Template - a modern, professional documentation template for creating and publishing books, guides, and technical documentation using Sphinx and GitHub Pages.

## Overview

The GitHub Book Template provides a complete setup for building beautiful, searchable documentation websites. It combines the power of Sphinx documentation generator with GitHub Pages hosting, making it easy to create and maintain professional documentation.

## Features

- **Sphinx-based Documentation**: Built on Sphinx, the industry-standard documentation generator
- **GitHub Pages Integration**: Automatically publish your documentation to GitHub Pages
- **Responsive Design**: Read the Docs theme for beautiful, mobile-friendly documentation
- **Search Functionality**: Full-text search across all documentation pages
- **Version Control**: Keep your documentation in sync with your code
- **Easy Editing**: Edit on GitHub links for community contributions
- **LaTeX Support**: Mathematical equations and complex formatting support
- **Multiple Output Formats**: Generate HTML, PDF, and other formats

## Quick Start

1. **Clone the Repository**
   ```bash
   git clone https://github.com/rajacsp/github-book-template.git
   cd github-book-template
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Build Documentation**
   ```bash
   cd doc
   make html
   ```

4. **View Documentation**
   Open `docs/index.html` in your browser

## Project Structure

```
.
├── doc/                    # Source documentation files
│   ├── conf.py            # Sphinx configuration
│   ├── index.rst          # Documentation home page
│   ├── preface.rst        # Preface/introduction
│   ├── ch02_*.rst         # Chapter files
│   ├── ch03_*.rst         # Chapter files
│   ├── images/            # Images and assets
│   └── scripts/           # Build scripts
├── docs/                  # Generated HTML documentation
├── README.md              # This file
└── requirements.txt       # Python dependencies
```

## Configuration

Edit `doc/conf.py` to customize:
- Project name and copyright
- GitHub repository information
- Theme settings
- Extensions and plugins

## Building Documentation

### HTML Output
```bash
cd doc
make html
```

### PDF Output
```bash
cd doc
make latexpdf
```

### Clean Build
```bash
cd doc
make clean
```

## Publishing to GitHub Pages

1. Push your changes to the `main` branch
2. The generated `docs/` folder is automatically served as your GitHub Pages site
3. Access your documentation at: `https://rajacsp.github.io/github-book-template/`

## Contributing

To contribute to this template:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Documentation Structure

- **Preface**: Introduction and overview
- **Chapters**: Organized content sections with examples and explanations
- **Images**: Visual assets and diagrams
- **Code Examples**: Embedded code samples and demonstrations

## Requirements

- Python 3.6+
- Sphinx 2.0+
- sphinx-rtd-theme
- Other dependencies listed in `requirements.txt`

## License

See LICENSE file for details.

## Support

For issues, questions, or suggestions, please open an issue on GitHub.

---

**Happy documenting!** 📚
