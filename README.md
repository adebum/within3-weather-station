# within3-weather-station
Connect VS Code to git hub and Heroku
$ Heroku login
$ git clone https://github.com/heroku/within3-weather-station
==> create Docker file, as well as package-lock.js generated from package.json
$npm install --start express
==> Also a Procfile should be created with this command in the file
$web: npm start
$ heroku create
$ git push heroku master
===> to run app locally
$npm run start
Local Test : http://localhost:8080
Test: http://172.19.160.1:8000


Create docker file on github
==> In Visual Studio Code, use this command
$ docker login 
$ docker build -t adebum/within3-weather-station .  ==> to run docker image
$ docker push docker push sadebum1/w3weatherstation-repo
$ docker pull sadebum1/w3weatherstation-repo
$ docker run -p 8000:8080 -d sadebum1/w3weatherstation-repo

$ docker ps -a ====> to show lists of docker images and containers running

To confirm attached IP address, use this command
$ ipconfig

Test: http://192.168.1.86:8000/

