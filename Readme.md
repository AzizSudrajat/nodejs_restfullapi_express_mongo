# NodeJS - API - API RESTfull
RESTfull API build on :
- NodeJS Language
- Express Framwork
- MVC Pattern
- Depedencies : [body-parser](github.com/expressjs/body-parser), [express](github.com/expressjs/express), [mongoose](github.com/Automattic/mongoose)
- Mongo DB Community
## Installation
NodeJS required [Link](https://nodejs.org/en/download/) v15.* to run
NPM required [Link](https://nodejs.org/en/download/) v7.* to run
Mongo DB Community required [Link](https://www.mongodb.com/try/download/community)
```sh
- Download or Clone from Github -
cd nodejs_restfullapi_express_mongo
touch .env
echo "PORT=:8000" >> .env
echo "MONGODB=mongodb://{yourhost}/{yourcollection}" >> .env
```
Running Code
```sh
npm install
npm start
```
## API Endpoint
| METHOD | ENDPOINT | Description |
| ------ | ------ | ------ |
| GET | http://{yourhost}:8000/api/contacts | GET ALL Contacts |
| GET | http://{yourhost}:8000/api/contact/{id} | GET ONE Contact  |
| POST | http://{yourhost}:8000/api/contact | CREATE Contact |
| PUT | http://{yourhost}:8000/api/contact/{id} | UPDATE Contact |
| DELETE | http://{yourhost}:8000/api/contact/{id} | DELETE Contact |

## Postman Collection
File on Directory demo/postman

## License
MIT
