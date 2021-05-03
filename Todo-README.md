Todo

Update the Packages

    # apt update
    
 This service is written in NodeJS, Hence need to install NodeJS in the system
 
    # apt install npm -y
    
 Now , fetch the code from git-hub
 
    # git clone https://github.com/zelar-soft-todoapp/todo.git
    # cd todo
    # npm install
    
 Copy the service file and start the service.
 
    # mv systemd.service /etc/systemd/system/todo.service
    # systemctl daemon-reload
    # systemctl start todo
    # systemctl enable todo
    # systemctl status todo
   
