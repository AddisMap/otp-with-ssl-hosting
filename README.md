# otp-with-ssl-hosting
Docker Hosting Setup for OTP

## HowTo Use

GTFS Data / Configuration is expected in `./data`

    apt install docker.io docker-compose
    sudo systemctl start docker
    sudo systemctl enable docker
    cd /root
    git clone https://github.com/AddisMap/otp-with-ssl-hosting.git
    cd otp-with-ssl-hosting
    echo "HOSTNAME=your hostname" > .env
    docker-compose up -d
