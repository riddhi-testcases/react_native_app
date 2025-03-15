# React Native App

A simple React Native application that fetches and displays user data from the *Random Data API*.

## Built With

- React Native
- Redux
- React Navigation
- Axios
- React Native Elements
- React Native Gesture Handler
- React Native Vector Icons
- Redux Actions
- Redux Saga
- Reselect

## Dependencies

json
{
  "axios": "^0.18.0",
  "prop-types": "^15.7.2",
  "react": "16.6.3",
  "react-native": "0.58.5",
  "react-native-elements": "^1.1.0",
  "react-native-gesture-handler": "^1.0.16",
  "react-native-vector-icons": "^6.3.0",
  "react-navigation": "^3.3.2",
  "react-redux": "^6.0.1",
  "redux": "^4.0.1",
  "redux-actions": "^2.6.4",
  "redux-saga": "^1.0.2",
  "reselect": "^4.0.0"
}

## Installation

1. Clone the repository:
   sh
   git clone <repo-url>
   cd react-native-user-data-app

2. Install dependencies:
   sh
   npm install

3. Start the Metro Bundler:
   sh
   npx react-native start

4. Run the app:
   sh
   npx react-native run-android  # For Android
   npx react-native run-ios      # For iOS

## Features

- Fetches user data from *Random Data API*.
- Displays user information including:
  - ID
  - UID
  - Password
  - First Name
  - Last Name
  - Username
  - Email
  - Avatar (user image)
- Supports navigation using *react-navigation*.
- Implements Redux for state management.
- Uses *Redux Saga* for handling side effects.
- Provides a clean and responsive UI with *React Native Elements*.
- Supports gesture-based navigation with *React Native Gesture Handler*.

## License

MIT License.
