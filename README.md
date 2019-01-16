Project: Mobile FlashCard
This project is a questionary game in order to help user to aquire new knowledge on different subjects. User can create deck (subject) and add cards (questions) in the deck. Each card has a question and a link to see the answer. The user can then click on correct or incorrect button from his guess. At the end of deck (quiz) user can see his score, star again or go back to deck option. User can also delete a specific deck. The user also get a daily notification at specific time if he didnt complete one Quiz.


This project use react-native react/redux library, for convenient purpose 
AsyncStorage and API is use for storing/fetching data.

#Actions & Reducers
- index.js (reducer)

# Components
- App.js
- AddDeck.js
- AddQuestion.js
- DeckItem.js
- DeckList.js
- DeckView.js
- QuizView.js
- StandardBtn.js
- TextButton.js

# Middleware
- index.js
- logger.js

# Utils
- _data.js
- api.js
- helpers.js
- colors.js

This project was bootstrapped with [Create React Native App](https://github.com/react-community/create-react-native-app).

## Available Scripts

In the project directory, you can run:
App.js

### Tested on
Emulator iphone XR 12.1 with Expo Xcode
Emulator Android SDK built for x86 Expo Snack

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:19002](http://localhost:19002) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


## Learn More

You can learn more in the [Create React Native App documentation](https://docs.expo.io/versions/latest/introduction/installation).

To learn React, check out the [React documentation](https://reactjs.org/).
