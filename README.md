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

<img width="300" alt="Screenshot 2024-09-16 at 12 47 57 PM" src="https://github.com/user-attachments/assets/2de12f8a-f476-43b6-b8de-9f434ebef507">
<img width="299" alt="Screenshot 2024-09-16 at 12 48 20 PM" src="https://github.com/user-attachments/assets/6ea05afc-db61-4494-ae44-93c48f009559">
![Screenshot_1726471109](https://github.com/user-attachments/assets/6618eb74-8424-4476-87c3-ceaaf5976516)
![Screenshot_1726471120](https://github.com/user-attachments/assets/cd04fd94-9089-42c2-bbd2-16c0b17b500b)
![Screenshot_1726471126](https://github.com/user-attachments/assets/b3af715b-5b4e-4200-9b38-ea8c5ec2a714)
![Screenshot_1726471135](https://github.com/user-attachments/assets/5a3a170d-7ff5-40f1-9076-d42520435df4)
![Screenshot_1726471154](https://github.com/user-attachments/assets/a97510e8-de88-4364-987c-eb1cc5b5ff31)
![Screenshot_1726471157](https://github.com/user-attachments/assets/271e69ba-9aec-45f6-80ba-14f779568c60)
![Screenshot_1726471161](https://github.com/user-attachments/assets/34b72225-9ca1-4f54-bea3-4894e388d0ff)
![Screenshot_1726471193](https://github.com/user-attachments/assets/077bcce0-5382-4b6b-9079-129003c12f61)
![Screenshot_1726471208](https://github.com/user-attachments/assets/bd54c92d-3798-49f5-ab1d-9d917416530e)
![Screenshot_1726471260](https://github.com/user-attachments/assets/75b94ba1-c61f-4dcc-95f4-b720e433282a)
<img width="298" alt="Screenshot 2024-09-16 at 12 48 08 PM" src="https://github.com/user-attachments/assets/987679ed-5185-43c6-807e-fc2412761d64">








<img width="298" alt="Screenshot 2024-09-16 at 12 48 08 PM" src="https://github.com/user-attachments/assets/e5eddfd1-06cc-43c3-bf64-39751d56bfab">
<img width="300" alt="Screenshot 2024-09-16 at 12 47 57 PM" src="https://github.com/user-attachments/assets/2add51bd-0d65-4ec1-9807-a5a716df68a5">



