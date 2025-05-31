# 👨‍🍳 ChefGem – AI Cooking Assistant App

Welcome to **ChefGem**, an AI-powered cooking assistant app built with **Flutter** and integrated with **Google Gemini**. ChefGem revolutionizes how users interact with recipes by offering intelligent, personalized cooking support.

Whether you're learning how to cook or how to integrate AI into apps, this project is a hands-on and fun way to explore **Flutter development**, **Gemini AI**, and essential mobile app concepts like splash screens, permission handling, and asset management.

---

## 📋 Table of Contents

- [🚀 Overview](#-overview)
- [🧠 Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [📦 Getting Started](#-getting-started)
  - [🔧 Prerequisites](#-prerequisites)
  - [⚙️ Installation](#️-installation)
- [▶️ Usage](#️-usage)
- [🗂️ Project Structure](#️-project-structure)
- [📈 Future Improvements](#-future-improvements)
- [🤝 Contributing](#-contributing)
- [🪪 License](#-license)
- [📬 Contact](#-contact)

---

## 🚀 Overview

ChefGem helps users:
- Explore AI-generated recipe ideas.
- Receive intelligent ingredient suggestions based on what they have.
- Interact with a virtual assistant for real-time cooking help.

This app demonstrates how to build a modern, AI-enhanced Flutter application that is user-friendly, scalable, and production-ready. It’s a perfect starting point for developers aiming to integrate AI in real-world mobile applications.

---

## 🧠 Features

- 🤖 **AI-Powered Recipe Suggestions** – Get tailored meal ideas from the Gemini API.
- 🧾 **Smart Ingredient Recommendations** – Just list what’s in your fridge!
- 🧑‍🍳 **Step-by-Step Cooking Assistance** – AI guides you through recipes.
- 🥦 **Dietary & Allergen Filters** – Stay healthy and safe with filtered results.
- 🛒 **Shopping List Generator** – Build your list from selected recipes.
- 📸 **(Planned) Ingredient Recognition via Camera**
- 🎨 **Clean, Responsive UI** – Built with Material Design principles.
- 🧰 **Splash Screen** – Custom animated introduction on app startup.
- 🔐 **Robust Permission Handling** – Internet, camera, and storage permissions managed securely.
- 📂 **Asset Management** – Fonts, images, icons, and branding handled efficiently.

---

## 🛠️ Technologies Used

| Technology       | Purpose                                          |
|------------------|--------------------------------------------------|
| **Flutter**      | Cross-platform mobile app development            |
| **Dart**         | Programming language used by Flutter             |
| **Gemini API**   | AI model for recipe suggestions & conversation   |
| **Material Design** | Modern and accessible UI/UX design             |
| **Firebase** *(Optional)* | Future integration for storage & auth     |

---

## 📦 Getting Started

### 🔧 Prerequisites

Before you begin, ensure you have:

- ✅ [Flutter SDK](https://flutter.dev/docs/get-started/install)
- ✅ Dart SDK *(bundled with Flutter)*
- ✅ IDE like **VS Code** or **Android Studio**
- ✅ A **Google Cloud project** with Gemini API enabled  
  [Set up Gemini API](https://ai.google.dev/docs/gemini_api_overview)

---

### ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/derksKCodes/chefgem-ai-cooking-assistant.git
   cd chefgem-ai-cooking-assistant

2.  **Install Dependencies**
    ```bash
    flutter pub get
    ```

3.  **Configure Environment Variables**
    Create a `.env` file in the root of your project:
    ```env
    GEMINI_API_KEY=your_gemini_api_key_here
    ```
    (Use `flutter_dotenv` or similar to load it in your app)

4.  **Run the App**
    ```bash
    flutter run
    ```

---

## ▶️ Usage
* Launch the app and enjoy the animated splash screen.
* Enter ingredients or select dietary preferences.
* Chat with the AI assistant for recipes and cooking tips.
* Use advanced features like filtering and shopping list generation.

---

## 🗂️ Project Structure
```bash
chefgem-ai-cooking-assistant/
├── lib/
│   ├── api/             # Gemini API calls
│   ├── assets/          # Fonts, logos, images
│   ├── components/      # Reusable widgets
│   ├── models/          # Data models
│   ├── screens/         # UI screens
│   ├── services/        # Business logic & utilities
│   ├── utils/           # Helper functions
│   └── main.dart        # App entry point
├── assets/              # Root-level media
├── .env                 # API keys and secrets
├── pubspec.yaml         # Dependencies and metadata
├── README.md            # You are here
└── ...

## 📈 Future Improvements
* 🗣️ **Voice-based interaction**
* 📷 **Camera-based ingredient detection**
* 📝 **Save & edit favorite recipes**
* 🌐 **Language translation support**
* ☁️ **Firebase integration** for auth & storage

---

## 🤝 Contributing
We welcome contributions! To get started:

1.  Fork the repository
2.  Create your branch (`git checkout -b feature/my-feature`)
3.  Commit your changes (`git commit -m 'Add feature'`)
4.  Push to the branch (`git push origin feature/my-feature`)
5.  Open a Pull Request

---

## 🪪 License
This project is licensed under the MIT License.

---

## 📬 Contact
* **Developer:** [@derksKCodes](https://github.com/derksKCodes)
* **Project Link:** [https://github.com/derksKCodes/chefgem-ai-cooking-assistant.git](https://github.com/derksKCodes/chefgem-ai-cooking-assistant.git)

Made with ❤️ using Flutter & Gemini
