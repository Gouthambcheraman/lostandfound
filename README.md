# 🎯 Lost & Found System

[![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?logo=flutter)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)](https://github.com/Gouthambcheraman/lostandfound)

A modern, user-friendly Flutter application that helps students and faculty efficiently report, track, and recover lost and found items across different departments.

## ✨ Features

### 📍 Department Navigation
Switch seamlessly between departments (Civil, Computer Science, Electrical, Electronics, and Mechanical) using intuitive pill-shaped buttons with active underlines.

### 📱 Lost Item Display
Browse lost items with detailed information including:
- High-quality item images
- Comprehensive descriptions
- Location details
- Time and date found

### 🎨 Enhanced User Experience
- Smooth hover animations on item cards
- Responsive design for web and mobile platforms
- Intuitive navigation and clean UI

### 📝 Report Lost/Found Items
Easily report items with:
- Item images
- Detailed descriptions
- Location information
- Timestamp tracking

## 📁 Project Structure

```
lib/
├── main.dart                    # Application entry point
├── screens/
│   ├── home.dart              # Home page with navigation
│   ├── lostlocate.dart        # Lost items display and filtering
│   └── report.dart            # Report new lost/found items
└── widgets/
    └── item_card.dart         # Reusable item card widget
```

## 🚀 Getting Started

### Prerequisites
- Flutter SDK 3.0 or higher
- Dart 2.18 or higher

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Gouthambcheraman/lostandfound.git
   cd lostandfound
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the application:**
   ```bash
   flutter run
   ```

## ⚙️ Customization

### Add New Departments
Update the `departments` list in `lostlocate.dart`:
```dart
final List<Map<String, dynamic>> departments = [
  {'name': 'Your Department', 'icon': Icons.school},
  // Add more departments here
];
```

### Add New Items
Modify the `items` list in `lostlocate.dart`:
```dart
{
  'name': 'Item Name',
  'image': 'https://example.com/image.jpg',
  'description': 'Item description',
  'location': 'Location details',
  'department': 'Department name',
  'timeFound': 'Time/Date found',
}
```

## 🔧 Troubleshooting

**Flutter not recognized?**
```bash
flutter doctor
```

**App not running?**
Clean and rebuild:
```bash
flutter clean
flutter pub get
flutter run
```

**Build issues?**
- Ensure Flutter is up to date: `flutter upgrade`
- Clear pub cache: `flutter pub cache clean`
- Delete build folder: `rm -rf build/`

## 🤝 Contributing

We welcome contributions! Here's how to help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Goutham Baskaran
- Contributors welcome!

## 📧 Support

For issues, questions, or suggestions, please [open an issue](https://github.com/Gouthambcheraman/lostandfound/issues) on GitHub.

---

**Made with ❤️ for the campus community**