# dotnetcorewebapi
Web API project in .NET core

Step-1 : Clone the respository
git clone https://github.com/pango89/dotnetcorewebapi.git

Step-2 : Go to the dotnetcorewebapi folder
cd dotnetcorewebapi

Step-3 : Build a docker image
docker build -t mywebapiimage .

Step-4 : Run the docker container using docker image
docker run -d -p 8080:80 mywebapiimage

Step-5 : Check in a browser or Postman tool
http://localhost:8080/api/values
