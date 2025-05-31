# ChefGem AI Cooking Assistant

An AI-powered cooking assistant app built with Flutter and integrated with Google Gemini. This project aims to demonstrate the integration of advanced AI capabilities into a mobile application, while also covering fundamental mobile development concepts such as permission handling, asset management, and splash screen implementation.

## Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project

ChefGem is designed to revolutionize the cooking experience by providing intelligent assistance to users. From suggesting recipes based on available ingredients to offering real-time cooking tips and dietary advice, this app leverages the power of AI to make cooking more accessible, enjoyable, and efficient. This project serves as a learning ground for integrating AI models (specifically Google Gemini) into a Flutter application, emphasizing best practices in mobile development.

## Features

- **AI-Powered Recipe Suggestions:** Get personalized recipe recommendations based on ingredients you have, dietary preferences, and meal types.
- **Real-time Cooking Assistance:** Receive step-by-step guidance and tips during the cooking process.
- **Ingredient Recognition (Future):** Potentially recognize ingredients using device camera.
- **Dietary and Allergen Filtering:** Filter recipes based on dietary restrictions and allergies.
- **Shopping List Generator:** Automatically create shopping lists from selected recipes.
- **User-friendly Interface:** A clean and intuitive design for a seamless cooking experience.
- **Robust Permission Handling:** Securely manage necessary device permissions (e.g., camera, storage).
- **Custom Splash Screen:** A branded introductory screen for the app.
- **Efficient Asset Management:** Proper handling of images, fonts, and other app assets.

## Technologies Used

* **Flutter:** The UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase.
* **Google Gemini API:** The powerful AI model for generating text, understanding natural language, and providing intelligent responses.
* **Dart:** The programming language used by Flutter.
* **Firebase (Optional, for future features like authentication or database):** A platform for building mobile and web applications (e.g., for storing user preferences or saved recipes).

## Getting Started

Follow these steps to set up the project on your local machine.

### Prerequisites

Before you begin, ensure you have the following installed:

* **Flutter SDK:** [Install Flutter](https://flutter.dev/docs/get-started/install)
* **Dart SDK:** (Comes with Flutter)
* **VS Code** or **Android Studio:** Recommended IDEs for Flutter development.
* **Google Cloud Project with Gemini API enabled:** You will need to create a Google Cloud project and enable the Gemini API. Obtain an API key for authentication. Refer to the [Gemini API documentation](https://ai.google.dev/docs/gemini_api_overview) for detailed instructions.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/chefgem-ai-cooking-assistant.git](https://github.com/yourusername/chefgem-ai-cooking-assistant.git)
    cd chefgem-ai-cooking-assistant
    ```

2.  **Install Flutter dependencies:**
    ```bash
    flutter pub get
    ```

3.  **Configure Gemini API Key:**
    * Create a file named `.env` in the root of your project.
    * Add your Gemini API key to this file:
        ```
        GEMINI_API_KEY=YOUR_API_KEY_HERE
        ```
    * **Note:** For production, it's recommended to use more secure methods for handling API keys, such as environment variables during build time or a secure backend.

4.  **Run the application:**
    ```bash
    flutter run
    ```
    This command will launch the app on your connected device or emulator.

## Usage

* Upon launching the app, you will be greeted by a splash screen.
* The main screen will allow you to input ingredients or select dietary preferences.
* Interact with the AI assistant to get recipe suggestions and cooking guidance.
* Explore different features as they become available.

## Project Structure