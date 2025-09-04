# mcserver
cd forge
sh run.sh
sudo tailscaled --tun=userspace-networking --socks5-server=localhost:1055 &
