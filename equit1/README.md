# Equit - Empowering Through Knowledge

Equit is a Flutter application designed to empower citizens through easy access to legal information and real-time social awareness. Our app integrates News APIs to provide up-to-date information about social issues, legal developments, and constitutional rights.

## Key Features

### Real-Time News Integration
- Live news feed using News API
- Curated content focused on legal and social issues
- Easy-to-understand summaries of complex legal news
- Customizable news categories and filters

### Legal Information Access
- Simplified constitutional rights explanations
- Important law updates and interpretations
- User-friendly legal resource directory
- Educational content about citizen rights

### Technical Features
- News API integration for real-time updates
- Gemini integration for intelligent content processing
- WebView integration for external resources
- URL launcher for additional information

## Prerequisites

Before you begin, ensure you have the following installed:
- Flutter SDK (>=3.2.5)
- Dart SDK
- Android Studio or VS Code with Flutter plugin
- Git
- News API key (Register at newsapi.org)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/GDSC_Soln_chlg.git
cd GDSC_Soln_chlg/equit1
```

2. Configure API Keys:
Create a `config.dart` file in the `lib` directory:
```dart
const String NEWS_API_KEY = 'your_api_key_here';
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## Dependencies

The app uses the following main dependencies:
- `http`: For News API integration
- `webview_flutter`: For rendering web content
- `url_launcher`: For launching external URLs
- `cupertino_icons`: For iOS style icons

Add them to your project by running:
```bash
flutter pub add http webview_flutter url_launcher
```

## Project Structure

```
equit1/
├── lib/
│   ├── controller/     # Business logic
│   ├── model/         # Data models
│   ├── screen/        # UI screens
│   ├── view/          # View components
│   ├── FetchNews.dart # News API integration
│   ├── newsArt.dart   # News article model
│   ├── screen.dart    # Screen management
│   └── main.dart      # App entry point
├── assets/           # Static assets
└── pubspec.yaml     # Project configuration
```

## News API Integration

The app uses the News API to fetch the latest news about:
- Legal developments
- Constitutional updates
- Social justice issues
- Civil rights movements
- Educational reforms

## Contributing

We welcome contributions, especially in:
- Improving news filtering algorithms
- Adding new news sources
- Enhancing content summaries
- UI/UX improvements
- Documentation

## Support

For support:
- Email: equitysquad004@gmail.com
- Join our community channels
- Follow us on social media

## License

This project is licensed under the MIT License - see the LICENSE file for details.
