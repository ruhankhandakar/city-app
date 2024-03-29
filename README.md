# City-App

NodeJS and ExpressJS App for attainu hiring challenge

---

How to Run this project in Local Environment

> 1. Download or clone this repo
> 2. Create `.env` file in root folder. After that use below lines

        NODE_ENV=development
        PORT=5000
        # Set your database/API connection information here
        MONGO_URL=.... (your mongo URL)

> 3. Now run this command --> `node seeder.js -i` , this will take all data from json file and will store all data into your database. (`node seeder.js -d` this will remove everything from your database.)
> 4. Go to this folder and run `npm i` or `yarn install` to `install` all of dependencies
> 5. To start server run this command `yarn run dev` or `npm run dev`. this will start your server from your given port number.

---

Live Demo Link -->
[city-app](https://attainu-city-app.herokuapp.com/)

---

# City-App

NodeJS and ExpressJS App for attainu hiring challenge
Live link https://attainu-city-app.herokuapp.com/

## Indices

- [Default](#default)

  - [Delete city from given state](#1-delete-city-from-given-state)
  - [Add city into a state](#2-add-city-into-a-state)
  - [Return all city name which is match with the given alphabet](#3-return-all-city-name-which-is-match-with-the-given-alphabet)
  - [Get state name from city name](#4-get-state-name-from-city-name)
  - [Get Frequent State from 5 given cites name](#5-get-frequent-state-from-5-given-cites-name)

---

## Default

### 1. Delete city from given state

Delete a city from the given state, if both are find in our database

**_Endpoint:_**

```bash
Method: DELETE
Type:
URL: https://attainu-city-app.herokuapp.com/state/delhi/remove/new delhi
```

### 2. Add city into a state

This route will store new city into given state.

**_Endpoint:_**

```bash
Method: POST
Type:
URL: https://attainu-city-app.herokuapp.com/state/delhi/add/new delhi
```

### 3. Return all city name which is match with the given alphabet

This end point will return all matched City name with alphabetical order

**_Endpoint:_**

```bash
Method: GET
Type:
URL: https://attainu-city-app.herokuapp.com/show-all-cities/z
```

### 4. Get state name from city name

This routes is for getting state name by city name

**_Endpoint:_**

```bash
Method: GET
Type:
URL: https://attainu-city-app.herokuapp.com/state/malda
```

### 5. Get Frequent State from 5 given cites name

This route has 5 input fields with one submit button. after the submission the frequent state name will be render below the form.

Link Link: https://attainu-city-app.herokuapp.com/findFrequentState/

**_Endpoint:_**

```bash
Method: GET
Type:
URL: https://attainu-city-app.herokuapp.com/findFrequentState/
```

---

[Back to top](#city-app)

> Made with &#9829; by [thedevsaddam](https://github.com/thedevsaddam) | Generated at: 2019-12-15 22:11:23 by [docgen](https://github.com/thedevsaddam/docgen)
