This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# 📝 Todo App

A sleek, modern task management application built with **React Native**. This app features a minimalist **dark theme** with vibrant orange accents, giving users an intuitive and stylish experience for managing daily tasks.

---

## 🚀 Features

- ✅ Create tasks with title and description
- 🔄 Edit existing tasks
- ✅ Mark tasks as complete/incomplete with visual indicators
- 🗑️ Delete tasks with confirmation
- 📤 Share tasks via native sharing functionality (including WhatsApp, Facebook, etc.)
- 💾 Persistent storage using **AsyncStorage** and **Zustand**
- 🎨 Responsive and intuitive UI with dark theme and orange accents

---

## 📦 Setup Instructions

### 🔧 Prerequisites

- [Node.js](https://nodejs.org/) (v14 or newer)
- npm or Yarn
- React Native CLI
- For iOS:
  - macOS with Xcode installed
- For Android:
  - Android Studio with emulator configured

---

### 📥 Installation

```bash
# Clone the repository
git clone [your-repository-url]
cd todo-app

# Install dependencies
npm install
# or
yarn install
```

### Install iOS dependencies (macOS only):

```bash
# Install CocoaPods (if not installed)
sudo gem install cocoapods

# Install iOS dependencies
npx pod-install
# or
cd ios && pod install && cd ..
```
## 📱 Running the App

### Start Metro Bundler

```bash
# Using npm
npm start
# or
yarn start
```
### Android

```bash
npm run android
# or
yarn android
```
### iOS (macOS only)

```bash
npm run ios
# or
yarn ios
```
## 🧪 Testing on Physical Devices

### Android
1) Enable Developer Options and USB Debugging on your Android device.
2) Connect your device via USB.
3) Run:
```bash
npx react-native run-android
```
### iOS
1) Connect your iPhone to your Mac.
2) Open ios/todo-app.xcworkspace in Xcode.
3) Select your device and click Run.

## 📁 Project Structure
```bash
todo-app/
├── App.js                 # Root component
├── src/
│   ├── components/        # Reusable UI components
│   │   ├── AddTaskInput.js
│   │   ├── CustomModal.js
│   │   ├── TaskItem.js
│   │   └── TaskList.js
│   ├── constants/         # Color and theme definitions
│   │   └── colors.js
│   ├── screens/           # Screen components
│   │   └── HomeScreen.js
│   └── services/          # State and storage management
│       ├── storage.js
│       └── zustandStore.js
└── assets/                # Icons, images, and static files
```

## 🎨 Design

This app was developed based on a Figma design spec: 👉 [(https://www.figma.com/design/3DtluHGmPEdVU4OLq8A1Ns/Untitled?node-id=0-1&t=iLalOP6GmXsDDA7V-1)]

All design elements strictly follow the spacing, typography, and color specifications.

## 🎬 Demo Video

![App Demo](./media/screen-20250424-231303.mp4)

## 📸 Screenshot

<img src="./media/Screenshot%202025-04-24%20221059.png" width="200"/>
<img src="./media/Screenshot%202025-04-24%20221339.png" width="200"/>
<img src="./media/Screenshot%202025-04-24%20221354.png" width="200"/>
<img src="./media/Screenshot%202025-04-24%20221419.png" width="200"/>
<img src="./media/Screenshot%202025-04-24%20221438.png" width="200"/>
<img src="./media/Screenshot%202025-04-24%20221458.png" width="200"/>
<img src="./media/Screenshot%202025-04-24%20221515.png" width="200"/>

## 🛠️ Technologies Used

- React Native
- Zustand for state management
- AsyncStorage for local storage
- React Native Share API
