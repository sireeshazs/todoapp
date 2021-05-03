User Service

Update all packages and install Java and Maven

    # apt update
    # apt install maven 
    # apt-get install openjdk-8-jdk
    
Get the code from git

    # git clone https://github.com/zelar-soft-todoapp/users.git
    # cd users
    
 Move systemd file
 
    # mv systemd.service /etc/systemd/system/users.service
    
 Build the code
 
    # mvn clean package
    
 Copy the service file and Start the services 
 
    # mv systemd.service /etc/systemd/system/users.service
    # systemctl daemon-reload
    # systemctl start users
    # systemctl enable users 
    # systemctl status users
    
