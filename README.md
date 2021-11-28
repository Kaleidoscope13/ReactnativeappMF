# Udacity React native Mobile-flashcards project
React native project udacity
The React native app is the project required for the React native Udacity React Nanodegree program. 
This application uses the same codebase to create cross platform packages for both Androids and iOS. 

The application allows users to create their own decks. A set of cards containing a question and an answer is included in each deck.
The user can begin a quiz for a certain deck and score their own performance as a result of wrong and right answers.
After finishing a quiz session, users are awarded a score.

The app uses the following packages:

### Core:
- react
- react-native

### Navigation:
- react-navigation

### State Management:
- context api
### Styling:
- stylesheet[React native]
## Installation
Clone the repository, change directories, and use npm or yarn to install the dependencies.
Follow these steps;
1. You need to have Node.js, npm installed
2. Proceed by cloning or downloading the project as a zip
3. Extract and change directory to the project folder
4. Open your Terminal or Command prompt and type ```npm install```
5. Then type ```npm start```
```bash
$ git clone https://github.com/james-priest/mobile-flashcards.git
$ cd Udacity mobile-flashcards
$ npm
```
## Prerequisite
- react native version>0.57

## How to Run the App
The app has been tested on both Android and iOS physical devices 

To run the app on Android, a debug-apk in react native file will be generated. 
A debug .apk file will be useful for initial distribution and testing.
The folllowing steps are used to generate a debug-apk file:

Step 1. Go to the root of the project in the terminal and run the below command:
```react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res```

Step 2. Go to android directory: ``` cd android```

Step 3: Now in this ```android``` folder, run this command:
```./gradlew assembleDebug```

There! you'll find the apk file in the following path:
```yourProject/android/app/build/outputs/apk/debug/app-debug.apk```

Now you have your .apk file generated, and can go ahead to install it on your android phone.


