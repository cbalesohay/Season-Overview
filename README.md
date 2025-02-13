## Precision Agriculture Project

# Goal: Develop a full stack mobile application to integrate wirelessly sensed data into site specific degree day models.

- Researched agriculture extension degree day model.
- Developing front-end and back-end React Native mobile application.
- Developing React Native / MongoDB integration for data flow.


## Current UI of App

<img src="https://github.com/user-attachments/assets/1bf5e667-a0bc-41bf-a0fe-c05483be906e" width="250" height="550" title="iPhone 16 Pro Screenshot" alt="iPhone 16 Pro Screenshot"/>

<img src="https://github.com/user-attachments/assets/bc30c1c9-5710-4a2a-a3c3-0e32a3436abf" width="250" height="550" title="Android Screenshot" alt="Android Screenshot"/>

## Front-End

The front end of this project is a React Native application written using TypeScript. The tought behind making the switch from JavaScript to TypeScript was to type check the information. 

# Front-End tech used

- React Native
- TypeScript
- Zustand


## Back-End

The back end of this project is written using Typescript. The tought behind making the switch from JavaScript to TypeScript was to type check the information that is getting parsed and sent to the front end. It connects to mongoDB through mongoose and Express.js, as well as accepting a post request to handle the async data pull and a /get to check health status of the server. 

# Functions

- Fetching functions pull data from the mongoDB database and store them in variables
- Sorting function to sort the data and store them in variables. It can calculate the day high, low, current, and average for Temperature and Humidity.
- Store data functions, vary from sorting metrics and then storing them to coversions for tempature and rainfall

# Back-End tech used

- TypeScript
- Node.js
- Express.js
- Mongoose
