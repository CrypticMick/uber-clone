# Uber-clone
Uber ride share mobile app clone built with React Native & Expo

## Getting Started

* Go through the [React Native Expo CLI instructions](https://reactnative.dev/docs/environment-setup) for `Expo CLI Quickstart` to install the necessary applications and tools. 
  * `yarn global add expo-cli` *// If Expo is not already installed*
  * To run app on your mobile device, install the [Expo client app](https://docs.expo.dev/get-started/installation/#2-expo-go-app-for-ios-and) on your iOS or Android phone and connect to the same wireless network as your computer.
  * [Expo official docs](https://docs.expo.dev/get-started/installation/#2-expo-go-app-for-ios-and)
* `cd uber-clone`
* Run `yarn`
* Run `yarn start` *// You can also use `expo start`*


## Google Cloud (Google Places API Keys)
* Go to the [Google Cloud](cloud.google.com), login and create a new project
  * *Billing must be enabled on the Google account*
* Select the new project 
* Click Menu and visit **"API & Services"** Dashboard
* Click **“Enable API and Services”** and enable the following:
  * Google Directions API
  * Google Places API
  * Distance Matrix API (How long to get from point A to point B)
* Click Menu and visit **"Credentials"** Dashboard
  * *Create an API Key (This will allow you to access all of the APIs we just enabled)*
  * Click “Create Credentials”
  * Select **API Key**
  * Copy API Key
* Create `.env` file in the `root` folder and add the API key: `GOOGLE_MAPS_APIKEY=Y0UR_API_K3Y`
