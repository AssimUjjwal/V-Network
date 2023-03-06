
# V-NETWORK | Social Media Web App

**_✨ A MERN Stack Clone of the social networking giant - Instagram_**


![MERN](https://img.shields.io/badge/MERN-Stack-teal)
![MongoDB](https://img.shields.io/badge/MongoDB-database-green)
![Express](https://img.shields.io/badge/Express-server-orange)
![React](https://img.shields.io/badge/React-front--end-blue)
![Node.js](https://img.shields.io/badge/Node.js-back--end-yellow)
![Redux](https://img.shields.io/badge/Redux-state--management-red)
![Cloudinary](https://img.shields.io/badge/Cloudinary-image--video--service-blue)


# 1. Key features

- ***User registration and authentication:*** Users are able to sign up and log in securely to the app - **JWT authentication**.

- ***User profiles:*** Each user have a profile page that displays their information and activity on the app.

- ***Messaging:*** Users are able to send private messages to each other. This feature requires implementing a real-time messaging system using Node.js and Socket.io.

- ***Search functionality:*** Users are able to search for other users and content on the app.

- ***Notifications:*** Users receive notifications when they receive a new message, a comment, or other relevant activity on the app. This feature requires implementing a real-time notification system using Node.js and Socket.io.

- ***Commenting and liking:*** Users are able to comment on and like posts and other content on the app.

- ***Discover:*** The app have a discover section that suggests new content and new registered users to the user.

- ***Followers and followings:*** Users are able to follow other users and see the users they are following on their profile page. Users are also be able to see their followers and receive notifications when someone new follows them. 
# 2. Demo


![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(41).png)  |  ![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(42).png)
:-------------------------:|:-------------------------:
![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(48).png)  |  ![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(46).png)
![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(49).png)  |  ![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(52).png)
![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(50).png)  |  ![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(54).png)
![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(56).png)  |  ![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(58).png)
![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(61).png)  |  ![image](https://raw.githubusercontent.com/AssimUjjwal/V-Network/main/assets/Screenshot%20(64).png)


# 3. Deployment

### A. Clone and install packages

1. Fork this project from the top right of the screen to create a copy of the code.
2. Download your fork of the project locally on your machine or clone it using

   ```bash
    git clone git@github.com:AssimUjjwal/V-Network.git
   ```

3. Navigate to the folder and run `npm install` for installing all packages & dependencies for the server/backend via npm.
4. Navigate to the `client` and run `npm install` to install all dependencies & packages required for the frontend via yarn.

   ```bash
    npm install
    cd ./client/
    npm install
   ```

### B. Create API secrets for external services

1. This project uses external services and APIs which require a secret/API pass-key for operations. Please ensure you obtain a pass-key from all these sources before running the project locally.

   - [Cloudinary](https://cloudinary.com/users/register/free) : For storing & fetching images.
   - [MongoDB](https://www.mongodb.com/cloud/atlas) : Either a cloud hosted cluster on Mongo Atlas or your local mongo URL.

### C. Environment Variables

1. Add .env file to parent repository as well as client.
2. Now add the following environment variables to your .env file of parent directory.

- `MONGODB_URL`
- `ACCESS_TOKEN_SECRET`
- `REFRESH_TOKEN_SECRET`

3.Then add below environment variables to your .env file of client directory. (These are from cloudinary media hosting)

- `REACT_APP_UPLOAD_PRESET`
- `REACT_APP_CLOUD_NAME`
- `REACT_APP_CLOUDINARY_URL`


### D. Run the project locally

1. Start the express server (via nodemon) for the backend. By default, it starts on port: `5000`
   ```bash
   npm run server
   ```
2. Navigate to the client to start the frontend server. By default, it starts on port: `3000`.

   ```bash
   cd ./client/
   npm start
   ```


## License

[MIT](https://choosealicense.com/licenses/mit/)

