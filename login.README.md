LOGIN

To update

    # apt update 
    
This service is written in Go language ,so we need to install goloang.

    #apt install golang -y
    
 Getting Started with Go.
 
     #  git clone https://github.com/zelar-soft-todoapp/login.git
     #  cd login 
     #  export GOPATH=/go
     #  go get
     #  go build
     #  ./login
     
   Move the service file and start the service .
   
    # mv systemd.service  /etc/systemd/system/login.service
    # systemctl daemon-reload
    # systemctl start login
    # systemctl enable login
