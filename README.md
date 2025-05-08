# E-Commerce App UI Template for Flutter

<p align="center">
  <img src='https://res.cloudinary.com/dqwntkvge/image/upload/v1673736382/ss_ecommerce_flutter.png'/>
</p>

## Overview

This is a comprehensive E-commerce UI template built with Flutter, featuring a modern and responsive design. The template includes a complete set of screens and components commonly found in e-commerce applications, making it an ideal starting point for building your own e-commerce app.

## Features

- **Product Management**
  - Product listing with categories
  - Detailed product views
  - Product variants support
  - Rating and review system

- **Shopping Experience**
  - Shopping cart functionality
  - Favorites/Wishlist
  - Order status tracking
  - Multiple address support

- **User Interface**
  - Modern and clean design
  - Responsive layouts
  - Animated components
  - Custom widgets and components
  - Star rating system

- **State Management**
  - Implemented using Flutter Bloc
  - Organized cubit structure
  - Efficient state handling

- **Mock Data Integration**
  - Built-in mock data stores
  - Ready-to-use sample products
  - Test data for immediate testing

## Project Structure

```
lib/
├── cubit/          # State management
├── datastore/      # Data handling and mock data
├── localization/   # Multi-language support
├── model/          # Data models
├── navigation/     # Route management
├── page/           # Main app screens
├── service/        # Business logic services
└── widget/         # Reusable UI components
```

## Getting Started

### Prerequisites

- Flutter SDK (latest version)
- Dart SDK (latest version)
- Android Studio/VS Code with Flutter plugins

### Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Navigate to the project directory:
   ```bash
   cd Ecommerce-UI-Template-Flutter
   ```

3. Install dependencies:
   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## Usage

The template comes with mock data implementation, allowing you to run and test the application immediately without any additional setup. The mock data includes:

- Sample products with variants
- Categories
- User profiles
- Shopping cart items
- Favorite items
- Addresses
- Ratings and reviews

## Customization

You can customize the template by:

1. Modifying the `app_theme.dart` file for styling
2. Updating mock data in the `datastore/mock/` directory
3. Adding new features by extending the existing cubits
4. Creating new widgets in the `widget/` directory

## License

This project is available for use under the terms specified in the project license.

## Commercial Version

There is an Envato item that uses this design. For the full-featured commercial version, visit:
[E-commerce App UI Template on CodeCanyon](https://codecanyon.net/item/ecommerce-app-ui-template-for-flutter/43009810)
