# Proffy

## 🛠️ Technologies
- [Node.js](https://nodejs.org/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/learn)
- [TypeScript](https://www.typescriptlang.org/)

## 📂 Libs/Modules
### 🚪 Server (API Restful)
- [express] - for server creation.
- [cors] - to allow the API to be accessible to the web application.
- [Knex.js] - SQL query builder for Javascript.

### 🌐 Web
- [axios] - make HTTP requests to nodejs API.
- [react-router-dom] - create routes and handle it.

### 📱 Mobile
- [@react-navigation] - create routes and handle it.
- [@react-navigation/stack and @react-navigation/bottom-tabs] - a way for the app to transition between screens.
- [axios] - make HTTP requests to nodejs API.

## 💻 About the application
Proffy is a web and mobile app for online classes. If you can teach someone all you need is to register (for free). If you are looking for a class all you need is to search for a teacher and choose a time to study.

### 🚪 Server
The server is an API Restful; it is the heart of the application.

### 🌐 Web app
The web app is for registering and search for teachers.

#### 🏠 Home Page
Here is the Home Page; click the button to register your waste collection point.

[image]

#### 📋 Registration Page
Here is the Registration Page; fill in the fields to get your waste collection point registered and ready to be found.

  
### 📱 Mobile app
The mobile app is where you can find the waste collection point. You can contact the owner's waste collection point via email and whatsapp for more details.

#### 🏠 Home
Here is the Home Screen; fill in the fields with your state and city to check out the available waste collection point near you.



#### 📭 Points
Here is the Points Screen; select the kind of residue you would like so you can see the available waste collection point near you.



#### 📃 Detail
Here is the Detail Screen; here you can see more about the waste collection point and send a whatsapp message or email it.



## 🚀 Get started
### ⚠️ Requirements
- [Node.js](https://nodejs.org/)
- [Expo](https://expo.io/learn)

### 🧭 Cloning, installing and some configs
1. At first, clone the repo by running `git clone https://github.com/ribeiromatheus/proffy.git` or `hub clone ribeiromatheus/proffy` - if you have hub installed on your machine - on your favorite terminal.
2. After cloning run `yarn` or `npm install` on **server**, **web** and **mobile** folder.
3. After that, go to **server** folder and rename `.env.example` file to `.env`, then enter your own credentials.
4. Still in the **server** folder, run **yarn knex:migrate** or **npm run knex:migrate** to generate the database.
5. Next, go to **mobile/src** folder and create a folder named **credentials**, then create a **json** file named **baseUrl** so you can add your ip address followed by server port or your server url only.

```json
{
    "ip": "http://<ip goes here>:<port goes here>"
}
```

```powershell
🎲 Running the server (API)
# run with yarn
cd ecoplace/server
yarn dev

# run with npm
npm run dev
🎲 Running the Web app
# run with yarn
cd ecoplace/web
yarn start

# run with npm
npm run start
🎲 Running the Mobile app

# run with yarn
cd ecoplace/mobile
yarn start

# run with npm
npm run start
```

## 📝 License
This project is under the MIT license. See the [LICENSE](https://github.com/ribeiromatheus/proffy/blob/master/LICENSE) file for more details.