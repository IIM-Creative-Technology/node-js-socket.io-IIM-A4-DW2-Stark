# Node-JS-Socket-A4-E6

## Liens

- Prod :  
  https://node-js-iim-a4-dw2-stark.herokuapp.com


- Pré prod :  
  https://node-js-iim-a4-dw2-stark-dev.herokuapp.com

## Prérequis

```node 18.0```  
```npm ^8.5.0```

## Démarrer le projet

A mettre à la racine du projet :

```npm i```  
```npm start```

***DISCLAIMER : npm start doesn't work on windows we are exploring a fix to solve this before we swap our project. You need to create a new script in package.json like startwindows. Then inside you need to try to use ```set DATABASE_URL=.... && nodemon ./app/app.js```***

## Test

A mettre à la racine du projet :

```npm test```

## DB

We use a postgreSQL database by heroku service.

We use an ORM to interact with our DB : Prisma. If we need to do some changes in our DB, migrations, updates, new
tables, etc.. We need to use this command:

```npm migrate```



