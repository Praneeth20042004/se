Inside command Prompt commands
sudo apt update
sudo apt install docker.io
sudo apt install git
Sudo apt install nano
Git Commands
git init
git add .
Git commit –m “first commit”
git branch –M main
git remote add origin <https url>
git push –u origin main
clone the pushed file into aws using repo link inside commnad prmpt
now create docker file using nano Dockerfile inside command prompt
contents of dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
sudo docker build –t mywebapp .
sudo docker run –d –p 80:80 mywebapp
