# Contribution Guidelines

Welcome to the contribution guidelines! We greatly appreciate your interest in contributing to this project. This document explains how you can contribute effectively.

## Getting Started

### Prerequisites
- GitHub account
- Git installed on your local machine
- Node.js v16+ (for local development)
- Basic knowledge of Markdown

### Getting Started
1. **Fork** this repository
2. **Clone** your fork to your local machine:
```bash
git clone https://github.com/nzingxv2/changelo.git
```
3. **Setup** your development environment:
```bash
cd changelo
npm install
npm run dev
```

## Finding Workable Issues

- Check out [Good First Issues](https://github.com/nzingxv2/changelo/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) for beginner-friendly issues
- See [Help Wanted](https://github.com/nzingxv2/changelo/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) for issues that need help
- Check the [Project Roadmap](https://github.com/nzingxv2/changelo/projects/1) for planned features

If you find a bug or have a new feature idea, please [create a new issue](https://github.com/nzingxv2/changelo/issues/new/choose).

## Git Workflow

1. **Create a new branch**:
```bash
git checkout -b type/branch-name
```
Branch types:
- `feat/`: For new features
- `fix/`: For bug fixes
- `docs/`: For documentation changes
- `chore/`: For maintenance tasks

Example: `feat/add-search-functionality`

2. **Make your changes** and commit them:
```bash
git add .
git commit -m "Clear and concise description of the changes"
```

3. **Push your branch**:
```bash
git push origin branch-name
```

4. **Create a Pull Request (PR)** from your branch to the main repository's `main` branch.

## Writing Standards

### Documentation
- Use good and correct Indonesian
- Maintain a consistent writing style
- Use hierarchical headings (H2, H3, etc.)
- For code, use code blocks with language markers:


```javascript
function helloWorld() {
console.log("Hello world!");
}
```

### Commit Message
Follow the format of [Conventional Commits](https://www.conventionalcommits.org/):
```
<type>[scope options]: <description>

[Optional body]

[Optional footnotes]
```

Example:
```
feat(docs): add Windows installation guide

Adds a complete installation guide for Windows users including troubleshooting common issues.

Closes #123
```

Commit types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Formatting changes (spaces, commas, etc.)
- `refactor`: Code changes that are not features or bug fixes
- `test`: Adding or fixing tests
- `chore`: Maintenance task changes

## Testing

### Documentation
1. Make sure all links work:
```bash
npm run check-links
```
2. Verify structure:
```bash
npm run lint-docs
```

### Code (if any)
Run all tests:
```bash
npm test
```

## Contribution Tips
- Discuss big changes through issues before implementing
- Break big PRs into smaller ones
- Update related documentation when changing behavior
- Add screenshots for UI changes

## Recognition
Contributors will be recognized in:
- [Contributors Page](https://github.com/nzingxv2/changelo/graphs/contributors)
- Release notes
- Project README.md

## Questions?
If you have any questions:
- Discuss in [Discussions](https://github.com/nzingxv2/changelo/discussions)