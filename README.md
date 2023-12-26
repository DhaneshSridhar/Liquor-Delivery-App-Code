# Install Expo CLI globally
npm install -g expo-cli

# Create a new Expo project
expo init LiquorDeliveryApp
cd LiquorDeliveryApp

# Install required dependencies
npm install react-navigation react-navigation-stack react-native-gesture-handler react-native-reanimated

# Create navigation structure
mkdir navigation
touch navigation/AppNavigator.js

# Create screens
mkdir screens
touch screens/HomeScreen.js
touch screens/OrderScreen.js
touch screens/ProfileScreen.js

# Create components
mkdir components
touch components/ProductCard.js

# App entry point
touch App.js
