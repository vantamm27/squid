# squid

#install 
sudo apt update
sudo apt install -y squid

# create user
## create new user 
htpasswd -c users_passwd <user>
## add new user 
htpasswd users_passwd <user>




