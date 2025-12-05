# Contributing to Dev Resources Library

Thank you for your interest in contributing! This repository thrives on community contributions. Whether you're adding a new library, updating documentation, sharing a template, or fixing a typo, we appreciate your help.

## 📜 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Adding a Library](#adding-a-library)
- [Adding Templates](#adding-templates)
- [Documentation Style Guide](#documentation-style-guide)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Pull Request Process](#pull-request-process)

## 🤝 Code of Conduct

By participating in this project, you agree to:

- Be respectful and inclusive
- Welcome newcomers and help them contribute
- Accept constructive feedback graciously
- Focus on what's best for the community

## 🚀 How to Contribute

### Quick Fixes

For typos or small documentation fixes:

1. Click the edit button (pencil icon) on any file
2. Make your changes
3. Submit a pull request

### Larger Contributions

1. **Fork the repository**
   ```bash
   # Click the Fork button on GitHub
   ```

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/dev-resources-library.git
   cd dev-resources-library
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-addition
   ```

4. **Make your changes**
   - Follow our style guide
   - Test any code examples
   - Update documentation

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add: Brief description of changes"
   ```

6. **Push to your fork**
   ```bash
   git push origin feature/amazing-addition
   ```

7. **Open a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Fill out the PR template

## 📦 Adding a Library

### Evaluation Criteria

Before adding a library, ensure it meets these criteria:

- ✅ Actively maintained (commits within last 6 months)
- ✅ Good documentation
- ✅ Significant community adoption
- ✅ Clear use case or advantage
- ✅ Compatible license (MIT, Apache 2.0, BSD, etc.)

### Library Entry Template

Use this format when adding a library to README.md:

```markdown
| [Library Name](https://library-url.com/) | Brief description | Key features | Best for |
```

### Detailed Library Documentation

For libraries requiring more detail, create a file in `docs/libraries/`:

```markdown
# Library Name

## Overview
Brief description of what the library does.

## Key Features
- Feature 1
- Feature 2
- Feature 3

## Installation
```bash
npm install library-name
```

## Quick Start
```javascript
import { Component } from 'library-name';

// Example usage
```

## Pros & Cons

### Pros
- Advantage 1
- Advantage 2

### Cons
- Limitation 1
- Limitation 2

## Use Cases
- Use case 1
- Use case 2

## Alternatives
- Alternative 1
- Alternative 2

## Resources
- [Official Documentation](url)
- [GitHub Repository](url)
- [Community Discord/Slack](url)
```

## 📋 Adding Templates

### Template Structure

All templates should follow this structure:

```
templates/your-template-name/
├── README.md           # Template documentation
├── package.json        # Dependencies
├── .gitignore
├── src/
│   └── ...            # Source files
└── docs/
    └── SETUP.md       # Setup instructions
```

### Template README Requirements

Each template must include:

```markdown
# Template Name

## Description
What this template provides and what problem it solves.

## Tech Stack
- Framework/Library 1
- Tool 2
- Service 3

## Features
- ✅ Feature 1
- ✅ Feature 2
- ✅ Feature 3

## Prerequisites
- Node.js 18+
- pnpm/npm/yarn

## Quick Start
```bash
# Clone and setup commands
```

## Configuration
How to customize the template.

## Deployment
How to deploy this template.

## Screenshots
![Screenshot](./docs/screenshot.png)

## License
MIT
```

## 📖 Documentation Style Guide

### Markdown Formatting

- Use `#` for H1, `##` for H2, etc.
- Use **bold** for emphasis
- Use `code` for inline code
- Use ```language blocks for code snippets
- Include emojis for visual appeal (but don't overdo it)

### Code Examples

- Always include language identifier in code blocks
- Provide working, tested examples
- Add comments to explain complex code
- Keep examples concise and focused

### Links

- Use descriptive link text (avoid "click here")
- Check all links before submitting
- Use relative links for internal documentation
- Use absolute links for external resources

### Screenshots

- Place screenshots in `/docs/images/`
- Use descriptive filenames: `shadcn-ui-buttons-example.png`
- Optimize images (< 500KB)
- Include alt text for accessibility

## 📝 Commit Message Guidelines

We follow conventional commits for clear history:

### Format

```
Type: Brief description

Detailed explanation (optional)

Footer (optional)
```

### Types

- **Add:** New libraries, templates, or features
- **Update:** Changes to existing content
- **Fix:** Bug fixes or corrections
- **Docs:** Documentation-only changes
- **Style:** Formatting, typos (no code changes)
- **Refactor:** Code restructuring
- **Test:** Adding or updating tests
- **Chore:** Maintenance tasks

### Examples

```bash
# Good
git commit -m "Add: Visx library to data viz section"
git commit -m "Update: Shadcn UI feature list"
git commit -m "Fix: Broken link to Storybook docs"
git commit -m "Docs: Add agentic workflow examples"

# Not ideal
git commit -m "updated stuff"
git commit -m "asdf"
```

## 🔄 Pull Request Process

### Before Submitting

- [ ] Test all code examples
- [ ] Check all links work
- [ ] Update table of contents if needed
- [ ] Follow the style guide
- [ ] Write a clear PR description

### PR Title Format

```
Type: Brief description of changes
```

Examples:
- `Add: Motion Primitives library to UI section`
- `Update: Contributing guidelines with template info`
- `Fix: Typo in QUICKSTART.md`

### PR Description Template

```markdown
## Description
What does this PR do?

## Type of Change
- [ ] New library/tool
- [ ] Template
- [ ] Documentation update
- [ ] Bug fix
- [ ] Other (please specify)

## Checklist
- [ ] I have followed the style guide
- [ ] I have tested all code examples
- [ ] I have checked all links
- [ ] I have updated the table of contents
- [ ] Screenshots are included (if applicable)

## Additional Notes
Any other context or information.
```

### Review Process

1. Maintainer will review within 48 hours
2. Address any feedback
3. Once approved, your PR will be merged
4. You'll be added to contributors list!

## 💬 Questions or Need Help?

Feel free to:

- Open an issue with the question label
- Start a discussion
- Reach out to maintainers

## 👏 Recognition

All contributors will be:

- Listed in README contributors section
- Mentioned in release notes
- Part of an amazing community!

---

Thank you for contributing to Dev Resources Library! 🎉
