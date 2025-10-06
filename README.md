Christoffel’s Menu Management App

Module: MAST5112 – Portfolio of Evidence (Part 2)
Student: Tsheamo Malape
Student Number: ST10480436
Year: 2025


📘 Project Overview

This project is a cross-platform mobile application developed using React Native (Expo) for Christoffel, a private chef who requires a simple and flexible system to manage and update his daily menus for clients.

The app enables the chef to add, view, and manage menu items dynamically without hardcoding data or saving it permanently.


🎯 Features Implemented

✅ Chef can add new menu items dynamically
✅ Each menu item includes:

Dish Name
Description
Price
Course (Starter, Main, Dessert)

✅ Predefined list of course options
✅ Menu list automatically displays added items
✅ Displays the total number of menu items on the home screen
✅ Data resets when the app reloads (not stored permanently)


🛠 Technologies Used

React Native
Expo CLI
JavaScript (ES6+)
React Hooks (useState)
@react-native-picker/picker


⚙ Installation and Setup Guide

1️⃣ Prerequisites

Ensure you have installed:
Node.js → https://nodejs.org
VS Code → https://code.visualstudio.com
Expo Go App (on your mobile device)


2️⃣ Project Setup

Open VS Code terminal and run:
# Install Expo CLI
npm install -g expo-cli

# Create new project
npx create-expo-app chef-menu-app

# Move into project folder
cd chef-menu-app

# Install Picker library
npm install @react-native-picker/picker


3️⃣ Running the App

Replace the contents of App.js with the provided project code.
Then run:
npx expo start

This will:
Launch the Expo development server.
Display a QR code in the terminal or browser.
Scan the code using the Expo Go app to view the app live on your phone.


🎥 Demonstration

A screen recording was created to demonstrate all app features, including:

Adding menu items
Selecting courses
Viewing the list and total count

