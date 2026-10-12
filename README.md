# FashionHub 👗

**FashionHub – Fashion Shopping Android Application**

##  About the Project

FashionHub is a fashion shopping application developed using **Android Studio**. It provides a user-friendly interface for browsing fashion products and interacting with shopping features through a mobile application.

The application is built using Kotlin for Android integration and HTML, CSS, and JavaScript for the user interface. Android WebView loads the shopping interface locally within the Android application.

##  Features

* **Product Browsing:** Explore fashion products through the shopping interface.
* **Search:** Search for products.
* **Category Filtering:** Filter products based on available categories.
* **Shopping Cart:** Add and manage products in the cart.
* **Wishlist:** Save favorite products for later.
* **Local Storage:** Store supported shopping data locally in the browser environment.
* **Mobile-Friendly Interface:** Access the shopping interface through an Android application.

##  Technologies Used

| Technology          | Purpose                             |
| ------------------- | ----------------------------------- |
| Android Studio      | Android app development environment |
| Kotlin              | Android application logic           |
| Android WebView     | Displays the shopping interface     |
| HTML5               | Structure of the interface          |
| CSS3                | Styling and layout                  |
| JavaScript          | Interactive shopping features       |
| Local Storage       | Persists supported data locally     |
| Gradle (Kotlin DSL) | Project build configuration         |

##  Project Structure

```text
FashionHub/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── assets/
│   │       │   └── index.html
│   │       ├── java/
│   │       │   └── com/example/fashionhub/
│   │       │       └── MainActivity.kt
│   │       ├── res/
│   │       │   ├── layout/
│   │       │   │   └── activity_main.xml
│   │       │   ├── drawable/
│   │       │   └── values/
│   │       └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## ⚙️ How It Works

1. The application starts through `MainActivity.kt`.
2. The activity initializes an Android WebView.
3. JavaScript and DOM storage are enabled in the WebView.
4. The WebView loads `index.html` from the application's assets folder.
5. The HTML, CSS, and JavaScript provide the shopping interface and interactive features.

## 🚀 Installation and Setup

1. Download or clone the project repository.
2. Extract the project if it is downloaded as a ZIP file.
3. Open Android Studio.
4. Select **Open** and choose the `FashionHub` project folder.
5. Allow Gradle to sync and download the required dependencies.
6. Connect an Android device or start an emulator.
7. Click **Run ▶** to build and launch the application.

### Requirements

* Android Studio
* Android SDK 34
* Minimum Android version: Android 7.0 (API 24)
* Java 17-compatible development environment
* Kotlin and Gradle support

##  Project Objective

The objective of FashionHub is to demonstrate how web technologies can be integrated into an Android application to create an interactive fashion shopping experience. The project combines native Android development with web-based UI development.

##  Future Enhancements

* User registration and authentication
* Backend integration and database support
* Product details and product recommendations
* Secure payment gateway integration
* Order placement and order tracking
* User profile and address management
* Cloud synchronization for cart and wishlist data

##  Development

Developed using Android Studio with Kotlin, HTML, CSS, and JavaScript.

##  License

This project is intended for educational and learning purposes. Add a specific open-source license if you plan to distribute it publicly.
