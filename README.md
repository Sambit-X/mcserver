# mcserver

sudo apt-get update
sudo apt install openjdk-17-jdk-headless
curl -fsSL https://tailscale.com/install.sh | sh

cd forge
sh run.sh
sudo tailscaled --tun=userspace-networking --socks5-server=localhost:1055 &
