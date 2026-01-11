## Mobile Development Setup with Expo
* Task 0: Setting Up and Testing Your Mobile Development Environment
- Objective

The goal of this task is to set up a mobile development environment using the Expo Framework for React Native and test it on a physical device using Expo Go.

Tools Used

Node.js LTS

Visual Studio Code

Windows Operating System

Expo Framework

Expo Go (Android – Physical Device)

Expo Go Installation Steps

Visited the Expo Go homepage at https://expo.dev/go

Selected the latest SDK version

Installed Expo Go from the Google Play Store

Opened the Expo Go application

Logged into my Expo account

Challenges Faced

Android emulator was not detected initially

This was resolved by using a physical Android device with Expo Go

Task 1: Create Your First Mobile App
Objective

To scaffold a React Native application using the Expo Router template and understand the project structure.

Steps Followed

Navigated to the project directory:

cd prodev-mobile-setup


Initialized an Expo Router project:

npx create-expo-app@latest .


Modified the home screen:

File: app/(tabs)/index.tsx

Changed the text from Welcome! to First App Created

Started the development server:

npx expo start


Scanned the QR code using the Expo Go app on a physical Android device

Reset Project Observation

Command used:

npm run reset-project


Observation:

Removed default template files

Reset the project to a clean state

Simplified the app structure for fresh development

Task 2: Implementing Mobile Components in React Native
Objective

To understand React Native core components and apply styles using StyleSheet.

Project Directory
prodev-mobile-app-0x01

File Modified
app/index.tsx

Changes Made

Updated the main text to "Entry Screen - Awesome"

Replaced inline styles with styles.container

Added three <Text> components with different font sizes and styles

Defined styles using StyleSheet.create

Task 3: Safe Areas, Images, and Touchable Components
Objective

To implement SafeAreaView, background images, images, and touchable components.

Project Directory
prodev-mobile-app-0x02

Features Implemented

Wrapped application with SafeAreaProvider and SafeAreaView

Added full-screen background image using ImageBackground

Displayed company logo using Image

Added text content and call-to-action buttons using TouchableOpacity

Implemented responsive height using Dimensions

Assets Used
assets/images/Logo.png
assets/images/background-image.png

Task 4: Explore More Core Components
Objective

To build a login screen using core React Native components and reusable styles.

Project Directory
prodev-mobile-app-0x03

Files Created / Modified

styles/index.tsx

app/index.tsx

app/_layout.tsx

Components Used

View

Text

TextInput

Image

TouchableOpacity

SafeAreaView

Icons from @expo/vector-icons

Final Testing

Command used:

npx expo start


Application was tested using Expo Go on a physical Android device

All components rendered correctly
