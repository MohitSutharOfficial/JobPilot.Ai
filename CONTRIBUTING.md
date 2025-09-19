# Contributing to JobPilot.Ai 🚀

Thank you for your interest in contributing to JobPilot.Ai! We welcome contributions from developers of all skill levels. This guide will help you get started with contributing to our project.

## 📋 Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
3. [How to Contribute](#how-to-contribute)
4. [Development Workflow](#development-workflow)
5. [Coding Standards](#coding-standards)
6. [Submitting Changes](#submitting-changes)
7. [Review Process](#review-process)
8. [Recognition](#recognition)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v16 or higher)
- npm or yarn
- Git
- A code editor (VS Code recommended)

### Setup Development Environment

1. **Fork the Repository**
   ```bash
   # Click the "Fork" button on GitHub
   ```

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/JobPilot.Ai.git
   cd JobPilot.Ai
   ```

3. **Add Upstream Remote**
   ```bash
   git remote add upstream https://github.com/MohitSutharOfficial/JobPilot.Ai.git
   ```

4. **Install Dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

5. **Start Development Server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

## 🤝 How to Contribute

### Types of Contributions

We welcome various types of contributions:

- 🐛 **Bug fixes**
- ✨ **New features**
- 📚 **Documentation improvements**
- 🎨 **UI/UX enhancements**
- 🧪 **Test coverage**
- 🔧 **Performance improvements**
- 🌐 **Accessibility improvements**

### Finding Issues to Work On

1. Check our [Issues](https://github.com/MohitSutharOfficial/JobPilot.Ai/issues) page
2. Look for issues labeled:
   - `good first issue` - Perfect for beginners
   - `help wanted` - Community help needed
   - `enhancement` - New feature requests
   - `bug` - Bug reports

3. **GSSoC Contributors**: Look for issues with appropriate difficulty levels and point values

## 🔄 Development Workflow

### Branch Naming Convention

Use descriptive branch names:
- `feature/feature-name` - For new features
- `fix/bug-description` - For bug fixes
- `docs/update-description` - For documentation
- `refactor/component-name` - For refactoring

### Step-by-Step Workflow

1. **Sync with Upstream**
   ```bash
   git checkout main
   git fetch upstream
   git merge upstream/main
   ```

2. **Create Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**
   - Write clean, readable code
   - Follow our coding standards
   - Add tests for new features
   - Update documentation

4. **Test Your Changes**
   ```bash
   npm test
   npm run build
   ```

5. **Commit Changes**
   ```bash
   git add .
   git commit -m "type: descriptive commit message"
   ```

### Commit Message Format

Follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type: description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Build process or auxiliary tool changes

**Examples:**
```bash
feat: add AI interview scheduler component
fix: resolve authentication token expiration issue
docs: update contributing guidelines
style: format code according to prettier rules
```

## 📏 Coding Standards

### General Guidelines

- Write clean, readable, and maintainable code
- Use meaningful variable and function names
- Comment complex logic
- Follow DRY (Don't Repeat Yourself) principles
- Ensure responsive design for all UI components

### JavaScript/TypeScript

- Use ES6+ features
- Prefer `const` over `let`, avoid `var`
- Use arrow functions for callbacks
- Implement proper error handling
- Use TypeScript for type safety

### React/Next.js

- Use functional components with hooks
- Implement proper component composition
- Use meaningful component and prop names
- Implement proper error boundaries
- Follow React best practices

### CSS/Styling

- Use semantic class names
- Implement mobile-first responsive design
- Follow consistent spacing and typography
- Use CSS modules or styled-components
- Ensure accessibility standards

## 📤 Submitting Changes

### Before Submitting

1. **Test thoroughly**
   - Run all tests: `npm test`
   - Test in different browsers
   - Verify responsive design
   - Check accessibility

2. **Update documentation**
   - Update README if needed
   - Add JSDoc comments
   - Update API documentation

3. **Run linting and formatting**
   ```bash
   npm run lint
   npm run format
   ```

### Creating Pull Request

1. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Create Pull Request**
   - Use our [PR template](.github/PULL_REQUEST_TEMPLATE.md)
   - Link related issues
   - Provide clear description
   - Add screenshots for UI changes

3. **PR Checklist**
   - [ ] Code follows project standards
   - [ ] Tests pass
   - [ ] Documentation updated
   - [ ] No console errors
   - [ ] Responsive design verified
   - [ ] Accessibility checked

## 🔍 Review Process

### What to Expect

1. **Automated Checks**
   - Code linting
   - Test execution
   - Build verification

2. **Code Review**
   - Maintainer review
   - Community feedback
   - Requested changes

3. **Approval and Merge**
   - Final approval
   - Merge to main branch
   - Release planning

### Review Criteria

- Code quality and standards
- Test coverage
- Documentation completeness
- Performance impact
- Security considerations

## 🏆 Recognition

### Contributors

- All contributors are recognized in our README
- Active contributors may be invited as collaborators
- Outstanding contributions get special recognition

### GSSoC Participants

- Points awarded based on contribution complexity
- Regular feedback and mentoring
- Certificate of completion
- Potential internship opportunities

## 📞 Getting Help

### Communication Channels

- **GitHub Issues**: For bugs and feature requests
- **GitHub Discussions**: For questions and community interaction
- **Discord**: [Join our server] (if available)
- **Email**: [Contact maintainers]

### Questions?

Don't hesitate to ask questions! We're here to help:

1. Check existing issues and discussions
2. Create a new issue with the `question` label
3. Join our community discussions

## 🎯 Tips for First-Time Contributors

1. **Start small**: Look for `good first issue` labels
2. **Read the code**: Understand the project structure
3. **Ask questions**: Don't be afraid to ask for help
4. **Be patient**: Code review takes time
5. **Learn and improve**: Each contribution is a learning opportunity

## 📊 Contribution Points (GSSoC)

| Contribution Type | Points |
|-------------------|--------|
| Bug Fix (Easy) | 10 |
| Bug Fix (Medium) | 25 |
| Bug Fix (Hard) | 45 |
| Feature (Easy) | 10 |
| Feature (Medium) | 25 |
| Feature (Hard) | 45 |
| Documentation | 5-10 |
| Testing | 5-15 |

Thank you for contributing to JobPilot.Ai! Together, we're building something amazing! 🚀

---

**Happy Coding!** 💻✨