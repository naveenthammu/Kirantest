# Kirantest

install git 

sudo apt update
sudo yum update -y
sudo apt install git
git --version
git config --global user.name "naveenthammu"
git config --global user.email "naveenn610@gmail.com"

For generating token -
GitHub -> Settings -> Developer Settings -> Personal access tokens (classic). Click on your token and ensure repo (Full control of private repositories) is checked. Save it.

Format: git remote set-url origin https://<TOKEN>@github.com/<USER>/<REPO>.git
git remote set-url origin https://----------@github.com/naveenthammu/Kirantest.git
git remote set-url origin https://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@github.com/naveenthammu/Kirantest.git

to unset the Credential
git config --global --unset credential.helper

Dotnet install 
-------------
sudo apt-get update
sudo apt-get install -y dotnet-sdk-10.0

dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Swashbuckle.AspNetCore
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet list package


Docker install
-------------
sudo apt update
sudo apt install docker.io docker-compose -y
sudo systemctl enable docker
sudo systemctl start docker

Docker ps - check how many continers are used 
docker-compose logs api -  to check api logs
docker logs CONTAINER ID

now enable port 5000 on AWS security groups 

To start backend services 

docker-compose down
docker-compose build --no-cache
docker-compose up


------------------------------------

Frontend fix:

Install NPM
------------
sudo apt update
sudo apt install nodejs npm

cd EmployeeManagementSystem_Full_Project/myapp-frontend
npm install
npm install axios
npm install react-router-dom
npm install @mui/material
npm install @emotion/react
npm install @emotion/styled
npm install concurrently
npm install dotenv
