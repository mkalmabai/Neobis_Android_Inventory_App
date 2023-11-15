# Neobis Android Inventory App

## Overview

This project is designed to manage a list of products, providing a user-friendly interface with essential functionalities. The app follows the MVP (Model-View-Presenter) architecture and incorporates various technologies such as Coroutines, Room for database management, gallery interaction, and Navigation Component for seamless navigation.

## Features

### Bottom Navigation

The main activity includes a bottom navigation bar for easy navigation between different fragments, enhancing the overall user experience.

### Product List Screen

The primary screen displays the current list of products. Users can interact with each item, leading to the product editing screen upon selection.

### Product Editing and Creation

The product editing and creation screen enables users to perform the following actions:

- **Create Product**: Users can choose a photo from the gallery, fill in fields such as name, price, manufacturer, and quantity. The corresponding input types are configured accordingly.

- **Edit Product**: Clicking on a product from the list opens the editing screen, allowing users to modify the existing product details.

## Technology Stack

- **MVP Architecture**: The project follows the Model-View-Presenter architecture for clear separation of concerns and maintainability.

- **Coroutines**: Asynchronous programming is handled efficiently using Kotlin Coroutines, ensuring smooth execution of tasks.

- **Room Database**:
  - **DAO (Data Access Object)**: Manages data access and manipulation operations.
  - **Entity (Tables)**: Defines the structure of the database, including primary keys and column information.
  - **Database**: Handles database access, migration, and related functionalities.

- **Navigation Component**: Enables efficient navigation between fragments, enhancing the overall flow of the application.

## Getting Started

To set up the project locally and start working on it, follow these steps:

1. Clone the repository: `git clone https://github.com/mkalmabai/Neobis_Android_Inventory_App.git`
2. Open the project in your preferred IDE (Android Studio, IntelliJ, etc.).
3. Build and run the project on an emulator or physical device.

## Screenshots  
![Screenshot_1700065482](https://github.com/mkalmabai/Neobis_Android_Inventory_App/assets/96809964/cb506dc6-f935-4995-83ca-f488743cf6e8)
![Screenshot_1700065676](https://github.com/mkalmabai/Neobis_Android_Inventory_App/assets/96809964/98f03040-7e3a-4505-808a-ff3bd76f6607)
![Screenshot_1700062791](https://github.com/mkalmabai/Neobis_Android_Inventory_App/assets/96809964/73c0ef3d-5fbe-4f7c-b8d4-4631505fc0a0)
