
<br>

# URL Shortener
URL shortening service

## Tech Stack
* [Node](https://github.com/nodejs/node)
* [Express](https://github.com/expressjs/express)
* [MongoDB](https://github.com/mongodb/mongo)
* [React](https://github.com/facebook/react)
* [TypeScript](https://github.com/microsoft/TypeScript)
* [Docker](https://github.com/docker)

<br>

## Docker Setup [EASY]
```bash
$ docker-compose build && docker-compose up
```


# [OR]

## Local Setup ( Development  / Local MongoDB Required )
#### Server:
```bash
$ cd server && yarn
```
```bash
$ yarn build:watch
```
```bash
$ yarn dev
```
#### Client:
```bash
$ cd client && yarn
```
```bash
$ yarn start
```

<br>

#### Client:

Create Mongo DB with name of **url-shortener**
<br>
Edit   ```.env``` file and change MONGODB_URL to
```
MONGODB_URL=mongodb://localhost:27017/url-shortener
```
if running on docker MONGODB_URL need to be changed as follows

```
MONGODB_URL=mongodb://database:27017/url-shortener
```


## App URLs
#### Client:
```
http://localhost:3000
```
#### Server:
```
http://localhost:8000
```

<br>
