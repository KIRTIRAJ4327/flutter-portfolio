# Flutter Portfolio Website

A sleek, modern, and responsive portfolio website built with Flutter for web. This project serves as a comprehensive digital portfolio to showcase your skills, experience, and achievements to potential employers.

## Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop views
- **Dark/Light Mode**: Toggle between dark and light themes
- **Smooth Animations**: Micro-interactions and scroll animations for enhanced user experience
- **SEO Friendly**: Properly structured HTML elements for better search engine visibility
- **Fast Loading**: Optimized assets and lazy loading for quick performance
- **Interactive UI Elements**: Hover effects, parallax scrolling, and more
- **Contact Form**: Integrated contact form with validation
- **Resume Download**: Easy access to your CV/resume

## Sections

1. **Home**: Striking introduction with animated text and call-to-action buttons
2. **About**: Personal information, bio, and professional values
3. **Experience**: Interactive timeline of work history and internships
4. **Projects**: Showcase of recent projects with filtering capabilities
5. **Skills**: Visual representation of technical and soft skills
6. **Education**: Academic background and certifications
7. **Contact**: Contact information and form for direct communication

## Technology Stack

- **Flutter**: Cross-platform UI toolkit for building natively compiled applications
- **Dart**: Programming language optimized for building user interfaces
- **Provider**: State management solution for managing app state
- **Google Fonts**: Library of free fonts optimized for the web
- **Font Awesome Icons**: Vector icons and social logos
- **Animations**: Custom animations using Flutter's animation controller
- **Responsive Design**: Custom breakpoints for different device sizes

## Getting Started

### Prerequisites

- Flutter SDK (latest version)
- Dart SDK (latest version)
- A code editor (VS Code, Android Studio, etc.)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/flutter-portfolio.git
   ```

2. Navigate to the project directory:
   ```
   cd flutter-portfolio
   ```

3. Install dependencies:
   ```
   flutter pub get
   ```

4. Run the app in development mode:
   ```
   flutter run -d chrome
   ```

### Customization

1. **Personal Details**: Update the personal information in each section file located in the `sections` folder
2. **Theme Colors**: Modify the colors in the `theme_provider.dart` file
3. **Profile Picture**: Replace the placeholder images with your own photos
4. **Projects**: Add your projects in the `_getProjectsData()` method in the `projects_section.dart` file
5. **Experience**: Update your work history in the `_getExperienceData()` method in the `experience_section.dart` file
6. **Skills**: Customize your skills in the various methods in the `skills_section.dart` file
7. **Resume**: Replace the placeholder URL with your actual resume PDF link

## Deployment

### Build for Web

1. Build the web version:
   ```
   flutter build web --release
   ```

2. The output will be in the `build/web` directory, which can be deployed to any web hosting platform.

### Hosting Options

- **Firebase Hosting**: Great for Flutter projects with easy deployment
- **GitHub Pages**: Free hosting for static websites
- **Netlify**: Continuous deployment with Git integration
- **Vercel**: Optimized for frontend projects with automatic deployments

## Performance Optimization

- Images are compressed and optimized for web
- Lazy loading is implemented for content below the fold
- Minimal use of heavy dependencies
- Code splitting for better loading performance

## Browser Compatibility

Tested and working on:
- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge
- Opera
- Mobile browsers (iOS Safari, Android Chrome)

## Accessibility

- Semantic HTML structure
- Keyboard navigation support
- ARIA attributes for screen readers
- High contrast ratios for text elements
- Alt text for images

## Project Structure

```
lib/
  ├── main.dart               # Main application entry point
  ├── theme_provider.dart     # Theme management
  ├── scroll_provider.dart    # Scroll state management
  ├── sections/
  │   ├── home_section.dart      # Home hero section
  │   ├── about_section.dart     # About me section
  │   ├── experience_section.dart # Work experience section
  │   ├── projects_section.dart  # Projects portfolio section
  │   ├── skills_section.dart    # Skills and expertise section
  │   ├── education_section.dart # Education and certifications section
  │   └── contact_section.dart   # Contact form and info section
  └── widgets/
      ├── animated_text.dart     # Custom animated text components
      ├── responsive_wrapper.dart # Responsive layout utilities
      └── custom_buttons.dart    # Reusable button components
```

## Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
  google_fonts: ^6.1.0
  provider: ^6.1.1
  font_awesome_flutter: ^10.6.0
  url_launcher: ^6.2.1
  animated_text_kit: ^4.2.2
  visibility_detector: ^0.4.0+2
```

## Future Improvements

- Add blog section with articles
- Implement i18n for multiple languages
- Add more interactive project demos
- Integrate analytics for visitor tracking
- Create admin panel for easier content updates
- Progressive Web App (PWA) functionality for offline access

## Contribution

Contributions are welcome! If you'd like to improve this portfolio template:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

- [Flutter](https://flutter.dev/)
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Unsplash](https://unsplash.com/) for placeholder images

## Contact

For any questions or feedback, feel free to reach out:

- Email: your.email@example.com
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourusername)
- GitHub: [Your GitHub](https://github.com/yourusername)

---

Made with ❤️ and Flutter
