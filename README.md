# What is it?
This COVID-19 Tracking App is a React application which models and graphs the spread of COVID-19 through multiple visualization tools. Users can specify toggle between all the countries in the world and access live COVID-19 data representation on a table, on a line graph, and through a map.

# Why is it relevant?
This COVID-19 Tracking App allows users to better understand the spread of COVID-19 around the world by providing accurate and up-to-date COVID-19 data. Through different visual representations, users can become more informed of the trends of COVID-19 in different countries around the world.

# How does it work?
This React Application requests and draws data from both the Worldometer and John Hopkins University through a third-party API called disease.sh. Our modelling approached is executed through the use of React Leaflet and Charts.js, which produces a graphically and map-based representation of relevant COVID data such as the the number of new cases, recoveries and deaths. Materials UI components such as "Card" are also brought in as a complimentary data visualization tool through data boxes and tables. Users can interact with the table and find each countries's respective COVID-19 data. Users can also click on the pins on the map to view an interative text, which displays both historical and current COVID-19 information.

# Visual Screenshots of the Project Running
![Alt text](rogerz74/COVID-19-Case-Tracker/COVID_APP_SS1.png?raw=true "Demo 1")
![Alt text](rogerz74/COVID-19-Case-Tracker/COVID_APP_SS2.png?raw=true "Demo 2")

# How to Run this Project

All the files must be downloaded initially. Then in the project directory, you can run:

### `npm start`

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes. You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode. See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance.
The build is minified and the filenames include the hashes. Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
