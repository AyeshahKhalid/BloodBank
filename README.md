# BloodBank

A blood donor management app with react native and firebase.


# Features
Search donors with name or address
Filter with blood group and availability according to last donation date
Users can sign in with Facebook to enlist their blood group and contact pieces of information
Users can choose to share their contact information only with the admin, in that case, the admin contact is shown in their profile info screen
Admin can manually add donors or update last donation information
Admin or user can update their last donation information

# Key technologies/packages used
React Native
React Native Firebase
React Native Elements
React Navigation
Redux

# Steps to clone this project
First of all, you will need to install and configure Android SDK. Follow the Building Projects with Native Code section in this official guide.

Then clone and rename this project. Renaming can be tricky. Try using this package.

Create a Firebase project here.

A google-services.json file contains all of the information required by the Firebase Android SDK to connect to your Firebase project. To automatically generate the JSON file, follow this guide. Once downloaded, place this file in the root of the project at android/app/google-services.json. Replace the existing file.

Create a real-time database from the firebase console with the following security rules.


Follow the Getting Started Guide for Facebook Android SDK to set up a Facebook app. You don't need to follow the whole guide, just create a new facebook app, update the strings.xml and add the Key Hash

Install the dependencies with yarn install.

Now you should be able to run the project with react-native run-android
