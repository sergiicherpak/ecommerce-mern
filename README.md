# e-commerce
e-commerce site run by MERN stack

### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = your JWT secret
MAILGUN_KEY = your mailgun key
MAILGUN_DOMAIN = your mailgun domain
MAILGUN_EMAIL_SENDER = sergiicherpak1@gmail.com(your mailgun sender)
GOOGLE_CLIENT_ID=your google client id
GOOGLE_CLIENT_SECRET=your google client secret
GOOGLE_CALLBACK_URL=your google callback url
BASE_SERVER_URL=your base server url
```
### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server

# Run frontend only
npm run client
```

### Seed Database
```
You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy