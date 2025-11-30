# 👕 Wordrobe — Android Fashion App

**Wordrobe** is a native Android application developed in Java using Android Studio. It bridges the gap between style and technology, allowing users to discover clothing items, curate a list of favorites, and create personalized outfits through a seamless and intuitive user experience.

This project was developed as a group assignment for a university course, designed to simulate the full lifecycle of professional mobile app development—from architectural design to final implementation.

---

## 🚀 Key Features

- **Product Discovery:** Browse clothing items categorized by:
  - **T-shirts**
  - **Jeans**
  - **Sneakers**
- **Wishlist Management:**
  - Save products to **Favorites**
  - Manage saved items directly in the **Account** section
- **Outfit Creation:** Build custom outfits manually or utilize the app’s auto-generation feature for instant style suggestions
- **Authentication:** Secure **Login and Registration** via Email or Google Sign-In
- **UI Flexibility:** Full support for both **Light Mode** and **Dark Mode**

---

## 🧠 Tech Stack & Tools

- **Core:** Android Studio (Java)
- **Backend:** **Firebase** (User Authentication & Data Management)
- **Data:**
  - **RapidAPI** for fetching external product data
  - **Room Database** for local caching and offline persistence
- **Collaboration:** **GitHub** for version control and team workflow management
- **Design:** **Figma** for UI/UX prototyping

> **Optimization Note:** To streamline development and preserve API quota limits, we implemented a custom `debug_mode`. This allows the app to load data from local JSON files instead of making live API requests during testing phases.

---

## 🏗️ Architecture

The application is built upon the **MVVM (Model-View-ViewModel)** architecture, utilizing a **Single Activity - Multiple Fragments** approach. This ensures code modularity, scalability, and easier maintenance.

- **ViewModel:** Manages UI-related data state and survives configuration changes
- **Repository:** Acts as a single source of truth, mediating between the local Room database and external APIs
- **UI (Fragments):** Observes data changes via **LiveData** for reactive, real-time interface updates

---

## 📱 Screen Structure

- **Login / Sign Up:** Entry point with Google integration
- **Home:** Main dashboard for catalog exploration
- **New:** Hub for generating and creating new outfits
- **Account:** User profile management and Favorites gallery

*Screenshots demonstrating both Light and Dark modes can be found in the `/screenshots` directory.*

---

## 🔮 Roadmap & Future Enhancements

Potential features planned for future releases:

- **Virtual Wardrobe:** Allow users to upload photos of their own clothes
- **Smart Styling:** AI-driven outfit generation based on color theory and style matching
- **Catalog Expansion:** Integration of a wider range of products and categories
- **UX Improvements:** "Double-tap to like" gestures and password reset functionality

---

## 📌 Conclusion

Wordrobe was a pivotal project that provided hands-on experience in:
- Native Android Development
- Implementing clean Architectural Patterns (MVVM)
- Collaborative coding workflows using Git/GitHub
- Integrating third-party services and APIs

It serves as a solid foundation for further mobile development and future scalability.
