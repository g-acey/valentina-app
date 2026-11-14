# Valentina

**Valentina** is an e-commerce Android application that explores a more interactive online shopping experience through virtual clothing try-on technology. It allows users to browse clothing items and visualize how different outfits might look on them before making a purchase.

The project combines a traditional e-commerce experience with an AI-powered virtual try-on feature, aiming to make online clothing shopping more engaging and help users make more informed purchasing decisions.

## Features

- **Product Browsing** – Explore and browse available clothing items.
- **Product Details** – View information about individual clothing products.
- **Virtual Clothing Try-On** – Visualize how selected clothing items look on the user through a virtual try-on model.
- **E-commerce Experience** – A shopping-oriented interface designed to bring the browsing and virtual try-on experience together.

## Tech Stack

### Android Development
- **Kotlin** – Primary programming language.
- **Jetpack Compose** – Declarative UI toolkit.
- **Material 3** – UI components and design system.
- **Navigation Compose / Navigation 3** – Application navigation.

### Architecture & Dependency Management
- **Dagger Hilt** – Dependency injection.
- **Kotlinx Serialization** – JSON serialization and deserialization.

### Networking & Data
- **Retrofit** – HTTP API communication.
- **OkHttp** – HTTP client and network logging.
- **Gson** – JSON conversion.
- **Room** – Local database.
- **DataStore** – Local preference storage.
- **Coil** – Asynchronous image loading.

### Build & Testing
- **Gradle (Kotlin DSL)** – Build configuration.
- **KSP** – Kotlin Symbol Processing.
- **JUnit** – Unit testing.
- **Espresso** – Android UI testing.

## Screenshots

<img width="411" height="731" alt="Sign up" src="https://github.com/user-attachments/assets/bbfb9aad-ece8-4238-a3e0-b3ede5403527" />
<img width="411" height="731" alt="Home" src="https://github.com/user-attachments/assets/be56345f-e468-451a-a353-8bf884016d2f" />
<img width="411" height="731" alt="Product details" src="https://github.com/user-attachments/assets/a009edfa-eb0c-4ca0-88f8-c27c2fd7f149" />
<img width="411" height="731" alt="Product details bottom sheet" src="https://github.com/user-attachments/assets/dc83e861-21bb-49c6-85a1-5bf97ab2df44" />
<img width="411" height="731" alt="VTO" src="https://github.com/user-attachments/assets/6e5a3ff2-c7ff-4d1e-8c64-c1023c1deddb" />
<img width="411" height="731" alt="Payment" src="https://github.com/user-attachments/assets/45c3dfed-1fd1-4ff2-92f4-a836de92c1d6" />
<img width="411" height="731" alt="Orders" src="https://github.com/user-attachments/assets/8c9013b9-05e4-4353-a901-f963b762868a" />
<img width="411" height="731" alt="Profile" src="https://github.com/user-attachments/assets/01369b57-43d8-4ddd-94b8-2c89c1122f85" />

## Getting Started

### Prerequisites

- Android Studio
- Android SDK
- JDK compatible with the project's Gradle configuration

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/g-acey/valentina-app.git
   ```

2. Open the project in Android Studio.

3. Allow Gradle to sync and download the required dependencies.

4. Run the application using an Android emulator or a connected Android device.

## Notes

This repository focuses on the Android client application. The backend and virtual try-on model were developed and maintained separately as part of the project and are therefore not publicly available here.
