## Request Access to Go Green 🌿

Please fill out the [Access Request Form](https://forms.gle/zgNunRYiA1X1zT9N8) to request access to this private project. Once your request is reviewed, I will send you an invitation via GitHub.

# Go Green 🌿

**Go Green** is an eco-friendly e-commerce Flutter app that allows users to browse, purchase, and manage products focused on sustainability, such as plants, seeds, and other agricultural items. This app offers seamless functionality for both admins and regular users, with features for product management, user carts, addresses, and payments. Built using Flutter, this app supports both mobile and web platforms.

## Features ✨

- 🌱 **Admin Panel**: Admins can add, edit, and delete products.
- 🛒 **User Product Browsing**: Users can browse products, add items to their cart, and make purchases.
- 💳 **Razorpay Payment Integration**: Secure online payments using Razorpay.
- 📍 **Google Maps Integration**: Users can add their delivery address using Google Maps for precise location-based services.
- 🔐 **Firebase Authentication**: Secure user authentication using Firebase Auth.
- 🗺 **Geolocation Services**: Users can find and mark their current location or search for specific addresses.
- 📦 **Cart and Orders**: Interactive cart management with real-time updates and multiple stored addresses for easy checkout.
- 📊 **Remote Config**: Use Firebase Remote Config to dynamically change certain app configurations without releasing a new version.
- 📹 **Video Player**: Product videos integrated for a richer product display experience.
- 🔄 **State Management with Riverpod**: Clean, scalable state management using Flutter Riverpod.
- ☁️ **Cloud Firestore & Firebase Storage**: All product data, user data, and media files (images and videos) are stored and managed in Firebase.
- 🧭 **Google Places API**: For autocomplete suggestions when entering delivery addresses.
- 🔒 **Secure Storage**: Store and retrieve essential data using `shared_preferences`.

## Tech Stack 🛠

### Core Dependencies:
- **Flutter**: For building cross-platform mobile and web applications.
- **Google Maps**: For location-based services and delivery addresses.
  - [`google_maps_flutter`](https://pub.dev/packages/google_maps_flutter)
  - [`geolocator`](https://pub.dev/packages/geolocator)
  - [`geocoding`](https://pub.dev/packages/geocoding)
  - [`google_places_flutter`](https://pub.dev/packages/google_places_flutter)
- **Firebase**: For authentication, data storage, media hosting, and real-time updates.
  - [`firebase_core`](https://pub.dev/packages/firebase_core)
  - [`firebase_auth`](https://pub.dev/packages/firebase_auth)
  - [`cloud_firestore`](https://pub.dev/packages/cloud_firestore)
  - [`firebase_storage`](https://pub.dev/packages/firebase_storage)
  - [`firebase_remote_config`](https://pub.dev/packages/firebase_remote_config)
- **State Management**:
  - [`flutter_riverpod`](https://pub.dev/packages/flutter_riverpod)
- **Video Playback**:
  - [`video_player`](https://pub.dev/packages/video_player)
- **Payments**:
  - [`razorpay_flutter`](https://pub.dev/packages/razorpay_flutter)
- **Environment Variables**:
  - [`flutter_dotenv`](https://pub.dev/packages/flutter_dotenv)
- **Local Storage**:
  - [`shared_preferences`](https://pub.dev/packages/shared_preferences)

### Project Structure:

```bash
GoGreen/
├── android/             # Android-specific code
├── ios/                 # iOS-specific code
├── lib/                 # Main source code for the app
│   ├── models/          # Data models (e.g., Product, User, Cart)
│   ├── services/        # Firebase, Geolocation, Razorpay, and other service integrations
│   ├── screens/         # App screens for admin and user (ProductList, Cart, AddProduct, etc.)
│   ├── widgets/         # Reusable UI components
│   ├── providers/       # State management using Riverpod
│   ├── utils/           # Helper functions (e.g., geolocation, product utilities)
│   └── main.dart        # Entry point of the application
├── web/                 # Web-specific code
├── test/                # Unit and widget tests
├── assets/              # Static files such as images
├── pubspec.yaml         # Project dependencies and metadata
└── README.md            # Project description and instructions
