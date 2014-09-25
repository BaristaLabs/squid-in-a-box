squid-in-a-box
==============

docker run --net host BaristaLabs/squid-in-a-box
iptables -t nat -A PREROUTING -p tcp --dport 80 -j REDIRECT --to 3129
