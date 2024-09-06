# React Native Tailwind Starter

🚀 A **React Native** project starter using **Tailwind CSS** for fast and responsive UI development.

This template allows you to quickly build React Native apps with the power of **Tailwind CSS** by integrating `tailwind-rn`, making your development process more productive and efficient.

## Features

- 💨 **Tailwind CSS** support using `tailwind-rn`
- 🔄 **Fast styling** with utility-first classes
- 🎨 **Customizable** Tailwind configuration for easy theming
- 🏗️ **Responsive layouts** out of the box
- 📱 **Cross-platform** support (iOS & Android)

## Installation

Follow these steps to set up the project and integrate Tailwind CSS into your React Native application.

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/react-native-tailwind.git
cd react-native-tailwind
```

### 2. Install Dependencies

Run the following command to install all the required dependencies:

```bash
npm install
# or
yarn install
```

### 3. Install and Configure Tailwind for React Native

You will need to install `tailwind-rn` to integrate Tailwind CSS:

```bash
npm install tailwind-rn
# or
yarn add tailwind-rn
```

After installing, initialize the `tailwind.config.js` file to customize your Tailwind CSS configuration:

```bash
npx tailwind-rn init
```

### 4. Linking Assets (For React Native)

If you're using any native modules or fonts, make sure to run:

```bash
npx react-native link
```

### 5. Start the Development Server

Run the following commands to start the development server for React Native:

```bash
npm run android
# or
npm run ios
```

## Usage

You can start using **Tailwind CSS** in your React Native components as follows:

### Example

```tsx
import React from 'react';
import { View, Text } from 'react-native';
import tailwind from 'tailwind-rn';

export default function App() {
  return (
    <View style={tailwind('flex-1 justify-center items-center bg-gray-100')}>
      <Text style={tailwind('text-xl font-bold text-blue-500')}>
        Welcome to React Native with Tailwind CSS!
      </Text>
    </View>
  );
}
```

### Customizing Tailwind Configuration

You can modify the `tailwind.config.js` file to add custom colors, fonts, and other utility classes:

```js
module.exports = {
  theme: {
    extend: {
      colors: {
        customBlue: '#1E40AF',
      },
    },
  },
  variants: {},
  plugins: [],
};
```

### Screenshots

| ![LoginPage](https://github.com/user-attachments/assets/b87d9ac1-0218-4eb2-bcfe-2238da57ada2) | ![Screenshot_1725634531](https://github.com/user-attachments/assets/629469f5-d72e-49a9-85da-be0a31def0bc) |
|:------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------:|
| ![Screenshot_1725633857](https://github.com/user-attachments/assets/9ac435bc-d747-432a-8af8-e6f4f14bd945) | ![Screenshot_1725633850](https://github.com/user-attachments/assets/ed8fda91-0d2b-46b0-a33c-7b8da9181859) |





## Available Scripts

- `npm run android` – Runs the app on Android emulator.
- `npm run ios` – Runs the app on iOS simulator.
- `npm run start` – Starts the development server.
- `npm run build` – Builds the app for production.

## Project Structure

```
📂 react-native-tailwind
├── 📂 assets        # Static assets like images, fonts
├── 📂 src           # Source code (components, screens)
├── 📄 App.tsx       # Main app entry point
├── 📄 tailwind.config.js  # Tailwind CSS configuration
└── 📄 README.md     # This file
```

## Contributing

We welcome contributions! If you have any suggestions or improvements, feel free to open a pull request or create an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Built with ❤️ by [alizee].
```

### Key Additions:
1. **Screenshot Section**: 
   - Added placeholders for the screenshots, where you can insert images showcasing the key screens of your app.
   - Make sure to replace `link-to-home-screenshot` and other placeholders with the actual image URLs.

This setup helps visually communicate the features and look of the app!
