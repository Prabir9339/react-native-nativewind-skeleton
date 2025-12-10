# React Native Expo Template with NativeWind

A modern React Native skeleton project built with Expo Router and NativeWind (Tailwind CSS for React Native). This template provides a solid foundation for building cross-platform mobile applications with a beautiful, utility-first styling approach.

## ✨ Features

- 🚀 **Expo Router** - File-based routing for React Native
- 🎨 **NativeWind v4** - Tailwind CSS for React Native
- 📱 **Cross-platform** - iOS, Android, and Web support
- 🔷 **TypeScript** - Full TypeScript support
- 🏗️ **New Architecture** - React Native's new architecture enabled
- 📦 **Expo SDK 54** - Latest Expo features and improvements
- ⚡ **React 19** - Latest React version
- 🎯 **React Navigation** - Navigation libraries included
- 🎨 **Modern UI** - Pre-configured with Tailwind CSS utilities

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/) (optional, but recommended)
- [iOS Simulator](https://developer.apple.com/xcode/) (for iOS development on macOS)
- [Android Studio](https://developer.android.com/studio) (for Android development)

## 🚀 Getting Started

### Installation

1. Clone the repository:

```bash
git clone <your-repo-url>
cd react-native-nativewind-skeleton
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

### Running on Different Platforms

- **iOS Simulator**: `npm run ios`
- **Android Emulator**: `npm run android`
- **Web Browser**: `npm run web`

## 📁 Project Structure

```
.
├── app/                    # Expo Router app directory
│   ├── _layout.tsx        # Root layout component
│   └── index.tsx          # Home screen
├── assets/                 # Static assets (images, icons)
│   └── images/            # Image assets
├── src/                    # Source files
│   └── global.css         # Global Tailwind CSS imports
├── app.json               # Expo configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
└── package.json           # Project dependencies
```

## 🛠️ Available Scripts

- `npm start` - Start the Expo development server
- `npm start:clear` - Start Expo with cleared cache
- `npm run ios` - Run on iOS simulator
- `npm run android` - Run on Android emulator
- `npm run web` - Run in web browser
- `npm run lint` - Run ESLint

## 🎨 NativeWind Usage

This project uses NativeWind v4, which allows you to use Tailwind CSS classes directly in your React Native components.

### Example

```tsx
import { View, Text } from "react-native";

export default function MyComponent() {
  return (
    <View className="flex-1 items-center justify-center bg-white">
      <Text className="text-2xl font-bold text-blue-500">
        Hello NativeWind!
      </Text>
    </View>
  );
}
```

### Configuration

Tailwind configuration is located in `tailwind.config.js`. The content paths are configured to scan:

- `./app/**/*.{js,jsx,ts,tsx}`
- `./src/**/*.{js,jsx,ts,tsx}`

Make sure to import the global CSS file in your root layout (already done in `app/_layout.tsx`).

## 🔧 Technologies Used

- **Expo** (~54.0.27) - React Native framework
- **Expo Router** (~6.0.17) - File-based routing
- **NativeWind** (^4.2.1) - Tailwind CSS for React Native
- **React** (19.1.0) - UI library
- **React Native** (0.81.5) - Mobile framework
- **TypeScript** (~5.9.2) - Type safety
- **React Navigation** - Navigation libraries
- **Expo Image** - Optimized image component
- **React Native Reanimated** - Animation library

## 📱 Platform Support

- ✅ iOS
- ✅ Android
- ✅ Web

## 🎯 Key Features

### Expo Router

This project uses Expo Router for file-based routing. Create new screens by adding files to the `app/` directory.

### NativeWind v4

NativeWind v4 provides a seamless Tailwind CSS experience in React Native. Use familiar Tailwind utility classes directly in your components.

### New Architecture

The project is configured with React Native's new architecture enabled, providing better performance and developer experience.

### TypeScript

Full TypeScript support with proper type definitions for Expo and React Native.

## 🚧 Development Tips

1. **Hot Reload**: Changes are automatically reflected in your app
2. **Tailwind Classes**: Use any Tailwind utility classes directly in `className` props
3. **Type Safety**: Leverage TypeScript for better development experience
4. **Routing**: Add new routes by creating files in the `app/` directory

## 📝 License

MIT

## 🤝 Contributing

This is a skeleton/template project. Feel free to customize it for your needs!

---

Built with ❤️ using Expo and NativeWind
