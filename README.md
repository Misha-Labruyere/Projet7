# Creation of a corporate social network

### Frontend :

```
cd frontend
npm install 
npm run serve
```

### Backend :

```
cd backend
npm install
npm start
```

### Database :

Make sure you have `MySQL` installed globally

```
cd backend
```

You'll need to verify that the username and password in the config database.json file, match your local MySQL credentials.

```
npx sequelize-cli db:create
npx sequelize-cli db:migrate
```

Then open on any web browser : http://localhost:8080/

### To run the project with ADMIN :

Create a new user in the application with the following informations :
```
Prénom : Admin
Nom : Admin
Email : admin@admin.com
Mot de passe : Admin23!
```
Then connect to mysql in your terminal with your username and password and copy the following instructions
```
use groupomania_development;
UPDATE Users SET admin = '1' WHERE email = 'admin@admin.com';
```
You're ready to moderate !

## What is this project ?

I have created a corporate social network, for a fictive company.
For this project, I used below techs :
- For the server : Node.js and Express framework
- For the database : MySQL language and Sequelize ORM
- For the frontend : Vue.js (Vue Router, Vuex), Sass, Bootsrap and BootsrapVue

## What did I learn ?

This project allowed me to apply all my backend and frontend knowledge to the development of an entire application from scratch. 
