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
 

### Screenshots :

<p align="center">
  <img src="https://github.com/user-attachments/assets/5932f2e0-15df-4fad-8a40-b6b1d743a9fc" width="300" />
  <img src="https://github.com/user-attachments/assets/810b9aba-e39a-4b1e-9090-59712a6fb786" width="300" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/3bae668e-8953-4659-b2ce-dce4ceee31b3" width="300" />
  <img src="https://github.com/user-attachments/assets/b95acbd0-e4f9-40a9-a294-63cdd1dc9e79" width="300" />
  <img src="https://github.com/user-attachments/assets/0a1cc6e3-b10e-4c45-89a0-17dd2025b834" width="300" />
  <img src="https://github.com/user-attachments/assets/199479e3-4b13-408f-b0ce-4e75cea01881" width="300" />
  <img src="https://github.com/user-attachments/assets/878db298-02d8-49e2-8fa2-25c5f113bf89" width="300" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/5b6c8302-88ba-4cea-8674-b4dbd0e8593f" width="300" />
  <img src="https://github.com/user-attachments/assets/c7c5ddf4-ee2a-41e2-8a4b-33b53dfacb0f" width="300" />
  <img src="https://github.com/user-attachments/assets/f0458dda-6c3e-4653-9bee-39bc327422be" width="300" />
</p>
<p align="center">
   <img src="https://github.com/user-attachments/assets/c8e177b1-45a4-4370-b594-5dd5d1963202" width="300" />
  <img src="https://github.com/user-attachments/assets/6707d50c-3612-497a-bae3-c125e14a807d" width="300" />
</p>



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
