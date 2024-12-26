# omnicognitia-doctrina-es

Spanish Learning App with React UI in Android with Ionic/Capacitor

## To Run
### Install Ionic CLI

npm install -g @ionic/cli

Create a New Ionic Project with React

ionic start appNameHere blank --type=react

### Install Capacitor

ionic integrations enable capacitor

ionic capacitor add android

### Install Dependencies and Run the App

yarn install

Browser run locally: 

ionic serve

### Build and Deploy to Native Devices

Android:

ionic build
ionic capacitor copy android
ionic capacitor open android

### If there are issues

Re-sync Capacitor

npx cap sync

npx cap open android

