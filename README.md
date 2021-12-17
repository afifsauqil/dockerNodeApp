# dockerNodeJSApp
docker simple build image using node js with CI/CD

pre-requisite (must be installed npm before using this app) :

```
sudo apt install npm
```
```
npm install nodemon
```
```
npm install --save-dev mocha
```

run image using docker-compose :
```
docker-compose -f docker-compose.dev.yml up --build -d
```

test web app :
```
curl http://localhost:8000
```
