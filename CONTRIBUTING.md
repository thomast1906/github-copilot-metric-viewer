# Contributing to GitHub Copilot Metrics Viewer

🎉 **Thank you for your interest in contributing to the GitHub Copilot Metrics Viewer!**

We welcome contributions of all kinds: bug reports, feature requests, documentation improvements, and code contributions.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Submitting Changes](#submitting-changes)
- [Review Process](#review-process)
- [Community Guidelines](#community-guidelines)

## 🤝 Code of Conduct

### Our Pledge

We pledge to make participation in our project a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

**Examples of behavior that contributes to a positive environment:**
- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

**Examples of unacceptable behavior:**
- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others' private information without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

### Enforcement

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Report any behavior that violates our Code of Conduct by opening an issue or contacting the project maintainers directly.

## 🚀 Getting Started

### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript
- A modern web browser for testing
- Git for version control
- A text editor or IDE

### Development Environment

This project is designed to be simple and requires no build tools or complex setup:

1. **Fork and clone the repository**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/github-copilot-metric-viewer.git
   cd github-copilot-metric-viewer
   ```

2. **Open the project**:
   ```bash
   # Serve locally (recommended)
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   
   # Or open directly in browser
   open index.html
   ```

## 💡 How to Contribute

### 🐛 Reporting Bugs

**Before submitting a bug report:**
- Check existing issues to avoid duplicates
- Test with the latest version
- Gather relevant information (browser, OS, steps to reproduce)

**When submitting a bug report, include:**
- A clear, descriptive title
- Steps to reproduce the issue
- Expected vs actual behavior
- Screenshots or recordings if applicable
- Browser and OS information
- Sample data that causes the issue (if relevant)

### 🚀 Suggesting Features

**Before suggesting a feature:**
- Check if it's already been requested
- Consider if it fits the project's scope and goals
- Think about how it would benefit other users

**When suggesting a feature, include:**
- A clear, descriptive title
- Detailed description of the proposed feature
- Use cases and benefits
- Possible implementation approach
- Mockups or examples if applicable

### 📚 Documentation Improvements

We welcome improvements to:
- README.md clarity and completeness
- Code comments and inline documentation
- Usage examples and tutorials
- API documentation
- Contributing guidelines

## 🛠️ Development Setup

### Code Style

**HTML:**
- Use semantic HTML5 elements
- Maintain consistent indentation (4 spaces)
- Include appropriate alt text for images
- Use meaningful class and ID names

**CSS:**
- Follow BEM methodology where applicable
- Use consistent naming conventions
- Group related styles together
- Include vendor prefixes for compatibility

**JavaScript:**
- Use modern ES6+ features appropriately
- Write self-documenting code with clear variable names
- Include JSDoc comments for functions
- Handle errors gracefully
- Follow consistent formatting

**General:**
- Keep the single-file architecture
- Avoid external dependencies when possible
- Ensure cross-browser compatibility
- Test thoroughly before submitting

### Testing Guidelines

**Manual Testing Checklist:**
- [ ] Test in multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test responsive design on different screen sizes
- [ ] Verify all interactive elements work
- [ ] Test with various data formats and sizes
- [ ] Check for console errors
- [ ] Validate accessibility features

**Data Testing:**
- [ ] Test with empty datasets
- [ ] Test with large datasets
- [ ] Test with malformed data
- [ ] Test edge cases (zero values, missing fields)

## 📤 Submitting Changes

### Pull Request Process

1. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**:
   - Keep commits atomic and focused
   - Write clear commit messages
   - Test thoroughly

3. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Add feature: brief description"
   ```

4. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a Pull Request**:
   - Use a clear, descriptive title
   - Reference any related issues
   - Include a detailed description of changes
   - Add screenshots for UI changes

### Pull Request Guidelines

**PR Title Format:**
- `Add: [brief description]` for new features
- `Fix: [brief description]` for bug fixes
- `Update: [brief description]` for improvements
- `Docs: [brief description]` for documentation

**PR Description Should Include:**
- What changes were made and why
- How to test the changes
- Any breaking changes
- Screenshots for visual changes
- References to related issues

### Commit Message Guidelines

```
Type: Brief description (50 chars or less)

Longer explanation if necessary, wrapped at 72 characters.
Include the motivation for the change and how it differs
from the previous behavior.

- Use bullet points for multiple changes
- Reference issues and pull requests

Closes #123
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation
- `style`: Formatting, missing semicolons, etc.
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

## 🔍 Review Process

### What We Look For

**Code Quality:**
- Clear, readable code
- Appropriate comments
- Consistent style
- No console errors

**Functionality:**
- Features work as intended
- Edge cases are handled
- No breaking changes (unless intentional)
- Cross-browser compatibility

**Documentation:**
- Clear explanation of changes
- Updated documentation if needed
- Proper commit messages

### Review Timeline

- **Initial Response**: Within 2-3 business days
- **Full Review**: Within 1 week for most PRs
- **Complex Changes**: May take longer, we'll communicate expectations

### Addressing Feedback

- Respond to all feedback, even if just to acknowledge
- Make requested changes in new commits (don't force-push)
- Mark conversations as resolved when addressed
- Ask for clarification if feedback is unclear

## 🌟 Community Guidelines

### Types of Contributions

**🔰 Good First Issues:**
- Documentation improvements
- UI/UX enhancements
- Bug fixes with clear reproduction steps
- Adding chart customization options

**🚀 Advanced Contributions:**
- Performance optimizations
- New chart types or analytics
- Accessibility improvements
- Browser compatibility fixes

### Recognition

Contributors will be:
- Listed in the README acknowledgments
- Credited in release notes
- Given appropriate GitHub repository permissions for regular contributors

### Getting Help

**Need Help Getting Started?**
- Check existing issues labeled `good first issue`
- Read through the codebase to understand the structure
- Ask questions in issue comments or discussions

**Stuck on Something?**
- Comment on the relevant issue
- Open a discussion for broader questions
- Reach out to maintainers directly if needed

## 📄 License and Contributions

By contributing to this project, you agree that your contributions will be licensed under the same MIT License that covers the project. This ensures that all contributions remain open and accessible to the community while maintaining license consistency.

For more information about our licensing choices, see [LICENSE_ANALYSIS.md](LICENSE_ANALYSIS.md).

## 🙏 Thank You

Your contributions make this project better for everyone. Whether you're fixing a typo, adding a feature, or helping other users, every contribution is valuable and appreciated.

**Happy Contributing! 🎉**