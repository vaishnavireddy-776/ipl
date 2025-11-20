# ipl
#NGROK
ngrok auth token-35hXRX6B9UdSjIR3qNofjKvy0Sd_2draunJLFEDSBG1LHer5J
ngrok config add-authtoken <your_token>
ngrok http 8080
for forwarding add /github-webhook/
git add .
git commit -m "commit"
git push -u origin main

#NAGIOS
1.Pull the nagios docker image
docker pull jasonrivers/nagios:latest
2.run nagios
docker run --name nagiosdemo -p 8888:80 jasonrivers/nagios:latest
3.open localhost:8888
Username: nagiosadmin
Password: nagios
4.Stop the container
docker stop nagiosdemo
5.Delete the container
docker rm nagiosdemo
6.Remove the image
docker rmijasonrivers/nagios:latest

