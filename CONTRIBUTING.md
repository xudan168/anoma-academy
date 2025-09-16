# Contributing to Anoma Academy

Thank you for your interest in contributing to Anoma Academy! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Reporting Bugs
- Use the GitHub issue tracker
- Provide detailed steps to reproduce the bug
- Include browser and device information
- Add screenshots if applicable

### Suggesting Features
- Check existing issues first
- Provide clear description of the feature
- Explain the use case and benefits
- Consider implementation complexity

### Code Contributions
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly
5. Commit with clear messages
6. Push to your fork
7. Create a Pull Request

## 📋 Development Guidelines

### Code Style
- Use consistent indentation (2 spaces)
- Follow JavaScript ES6+ standards
- Use meaningful variable and function names
- Add comments for complex logic

### Testing
- Test on multiple browsers
- Verify mobile responsiveness
- Check language switching functionality
- Test user data persistence

### Documentation
- Update README.md for new features
- Add inline comments for complex code
- Update translation files for new text

## 🎮 Adding New Games

1. Create game function following naming convention: `play[GameName]Game()`
2. Add game card to appropriate category in HTML
3. Add translations for game name and description
4. Implement point system integration
5. Test game functionality

## 🌐 Adding Translations

1. Add new translation keys to `translations` object
2. Provide both English and Chinese translations
3. Test language switching functionality
4. Update any hardcoded text

## 🐛 Bug Fixes

1. Identify the root cause
2. Create minimal fix
3. Test the fix thoroughly
4. Update documentation if needed
5. Submit pull request with clear description

## 📝 Pull Request Guidelines

### Before Submitting
- [ ] Code follows project style guidelines
- [ ] All tests pass
- [ ] Documentation updated
- [ ] No console errors
- [ ] Mobile responsive
- [ ] Language switching works

### PR Description
- Clear title describing the change
- Detailed description of what was changed
- Screenshots for UI changes
- Reference related issues

## 🎯 Areas for Contribution

### High Priority
- New educational games
- Additional language support
- Mobile app development
- Performance optimizations

### Medium Priority
- Advanced intent strategies
- Social features
- Analytics dashboard
- Accessibility improvements

### Low Priority
- Code refactoring
- Documentation improvements
- UI/UX enhancements
- Testing coverage

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/anoma-academy.git
   cd anoma-academy
   ```

2. **Open in browser**
   ```bash
   # Use any local server
   python -m http.server 8000
   # or
   npx serve .
   ```

3. **Make changes**
   - Edit `index.html` for main functionality
   - Test changes in browser
   - Ensure all features work

## 📞 Getting Help

- **GitHub Issues**: For bug reports and feature requests
- **Discussions**: For questions and general discussion
- **Email**: [your-email@example.com]

## 🏆 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

## 📄 License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to Anoma Academy! 🎓
