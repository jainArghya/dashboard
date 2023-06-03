# Backend API
cd to dashboard-backend and write command "node index.js" or if you have nodemon "nodemon-index.js".  

# Frontend React Server
At the end, there is a default readme provided by react which can be used to start the app. "npm start" will be used to start the server.    
Please see the screenshots folder.

# What this project does?
This project is basically a web dashboard in MERN to communicate between two users: Manufacturer and Transporter. Both will have different input forms for entering data.
As first step, manufacturer sends an order request to a transporter selected by the manufacturer. This order request is shown on transporter's landing page who can see the details of the order request and sends a price value for this order. Manufacturer receives the transporter's response along with the order he sent.  

This project uses MongoDB for database, nodejs & expressjs in backend and Reactjs and it's ContextAPI in frontend.  
Some important libraries used are jwt, crypto-js & material-ui.  

# More Details
Registration Form:  
    &emsp;1.Name: Input text box.  
    &emsp;2.Email: Input text box.  
    &emsp;3.Password: Input text box.  
    &emsp;4.Confirm Password: Input text box.  
    &emsp;5.Address: Input text box.  
    &emsp;6.Role: A radio-button.  
      
Login Form:  
    &emsp;1.Email: Input text box.  
    &emsp;2.Password: Input text box.  

Order Request Form for manufacture:  
    &emsp;1. Order ID: an Alphanumeric code (for ex: XB120) is auto-populated.  
    &emsp;2. To:  
    &emsp;3. From:  
    &emsp;4. Quantity: Drop down menu where he can choose 1,2,3 ton.  
    &emsp;5. Address: Address is automatically populated from the user details that the manufacturer has submitted during the registration.  
    &emsp;6. Transporter: Drop down menu to select transporter.  
    &emsp;7. A send button.  
      
Order Response form for transporter:  
    &emsp;1.Order ID: List box to select the order id received from the Manufacturer.  
    &emsp;2.Price(in Rs.): input form, float value.  
    &emsp;3. A reply button.  
      
Search query in message-box(for both manufacture and transporter): It can take values like OrderId, to, from values.  
  
*********** default React Server ReadMe file below. ************  

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
