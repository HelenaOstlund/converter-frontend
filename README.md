## `npm install`
run to install node modules

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Create Admin for Login
Create Admin user in postman using http://localhost:8080/api/v1/auth/register
Username and password are required 

## Insert into database to get the right units for converter:

INSERT INTO units (unit_name, unit_type, conversion_rate) 
VALUES('liter', 'volume', 1), 
('Cup (US)', 'volume', 0.2366), ('Cup (Metric)', 'volume', 0.25),
('Cup (Imperial)', 'volume', 0.2841),
('Deciliter', 'volume', 0.1),
('Fluid Ounces (US)', 'volume', 0.0296),
('Fluid Ounces (UK)' , 'volume', 0.0284),
('gallon (US)', 'volume', 3.78541),
('gallon (UK)', 'volume', 4.55), 
('Pints (UK)', 'volume', 0.5683), 
('Pints (US)', 'volume', 0.4732),
('Quarts (UK)', 'volume', 1.1365),
('Quarts (US)', 'volume', 0.9464),
('Tablespoon (US)', 'volume', 0.0148),
('Tablespoon (Metric)', 'volume', 0.015),
('Tablespoon (Imperial)', 'volume', 0.0178),
('Teaspoon (US)', 'volume', 0.0049),
('Teaspoon (Metric)', 'volume', 0.005),
('Teaspoon (Imperial)', 'volume', 0.0059),
('kg', 'weight', 1), 
('gram', 'weight', 0.001), 
('pound', 'weight', 0.4536), 
('ounce', 'weight', 0.0283);
