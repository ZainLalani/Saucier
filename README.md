# Saucier

## Structure
This app is structured as an api in the `api/` folder which contains the api and python stuff and app which stores the react front end stuff.

### Commands
`npm run start`: Will run both the Demo app and start a package watcher for the API  
`npm run start:app`: Will only run the demo app and listen for react changes, will fully work once we have changes to fast api on a dev server (perminate endpoints)  
`npm run start:api`: Listens to dev api stuff

`uvicorn main:app --reload`: Start Fast api  
`npm i`: Will install dependencies  


### TODO
1. I think prep time and cook time are just ints when parsed, and should be dealt with better