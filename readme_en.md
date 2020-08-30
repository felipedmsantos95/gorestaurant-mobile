# GoRestaurant Web

<p align="center">
    <a href="readme_en.md">English</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="readme.md">Português</a>&nbsp;&nbsp;&nbsp;
</p>

<!-- ## Application Preview

<p align="center">
  <img src="https://github.com/felipedmsantos95/gorestaurant-mobile/blob/master/img/gorestaurant-mobile.gif"/>
</p> -->

## About

Mobile version of the [GoRestaurant](https://github.com/felipedmsantos95/gorestaurant-web) where is possible do filters and orders at the restaurant.


## Technologies used

- React.js

## Requirements

To execute the project it is necessary to have the following requirements installed in the system:

- Node 12.x or later
- Yarn 1.21 or later

## Running the project

### Cloning the project

```bash
$ git clone https://github.com/felipedmsantos95/gorestaurant-mobile
$ cd gorestaurant-mobile
```

### Scripts for project execution

Inside the project directory for the first time, you must run the `yarn` command to install the dependencies, so it will be possible to run the following scripts:

#### Running Fake API

```bash
$  yarn json-server server.json -p 3333
```

To display data on screen, there is a file to be used as a kind of fake API to provide this data. For that, there is a dependency in package.json called json-server, and a file called server.json that contains the data for the following routes:

**`/foods`**: Returns all foods registered in the API

**`/foods/:id`**: Returns a plate of food registered in API by `id`

**`/categories`**: Returns all categories registered in API

**`/orders`**: Returns all orders registered in API

**`/favorites`**: Returns all favorite foods registered in API


#### Run the app in the development mode

```bash
$ yarn start
```
Abra [http://localhost:3000](http://localhost:3000) para ver em um navegador web.

The page will reload if you make edits.
You will also see any lint errors in the console.


#### Run tests script

```bash
$ yarn test
```
