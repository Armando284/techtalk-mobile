# TechTalk Mobile App

This is the mobile application for the TechTalk platform, built using React Native with Expo. The app allows developers to interact with the TechTalk platform on their mobile devices.

## Requirements

- Node.js (v14 or higher)
- npm (v6 or higher) or pnpm/yarn
- Expo CLI

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/techtalk-mobile.git
cd techtalk-mobile
```

### 2. Install dependencies

```bash
npm install
```

Alternatively, you can use `pnpm` or `yarn`:

```bash
pnpm install
# or
yarn install
```

### 3. Create a `.env` file

Create a `.env` file in the root directory with the following contents:

```
API_URL=http://localhost:3000/api
```

Replace `http://localhost:3000/api` with your actual backend API URL.

### 4. Start the Expo development server

```bash
npx expo start
```

This will start the Expo bundler. You can scan the QR code with the Expo Go app on your mobile device to run the app or use an iOS/Android simulator.

### 5. Run the app

After starting Expo, choose one of the following:

- **iOS**: Press `i` in the terminal to run the app on an iOS simulator (Xcode is required).
- **Android**: Press `a` in the terminal to run the app on an Android emulator (Android Studio is required).
- **Mobile Device**: Use the Expo Go app to scan the QR code and run the app directly on your phone.

## TypeScript

This project is configured to use TypeScript. You can start using TypeScript in your components by creating `.tsx` files instead of `.js` files.

### Example

```tsx
import React from 'react';
import { Text, View } from 'react-native';

const App: React.FC = () => {
  return (
    <View>
      <Text>Welcome to TechTalk Mobile!</Text>
    </View>
  );
};

export default App;
```

## Build for production

Expo provides easy ways to build your app for production:

```bash
npx expo build:android
npx expo build:ios
```

Follow the prompts to generate the appropriate binaries for Android or iOS. Expo handles most of the configuration for you.

## Deployment

1. For iOS, you can upload the generated `.ipa` file to the App Store via Xcode or Transporter.
2. For Android, you can upload the generated `.apk` or `.aab` file to the Google Play Console.

Expo also supports over-the-air (OTA) updates, which allow you to push updates without requiring users to download a new version from the app stores.

## Scripts

- `npm start`: Start the Expo development server.
- `npm run build`: Build the app for production (with Expo).
- `npm run lint`: Lint the project files.
- `npm run type-check`: Run TypeScript type checks.

## License

This project is licensed under the MIT License.

---

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
