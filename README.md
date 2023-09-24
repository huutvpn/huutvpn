# 🇮🇩 HUUT 🇮🇩
# STEP INSTALL Vps 
# 1 ]
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y</code></pre>
# 
# 2 ]
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/huutvpn/huutvpn/main/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && screen -S setup ./setup.sh</code></pre>
#
# ![This is an image](https://raw.githubusercontent.com/huutvpn/huutvpn/main/r20w1678676611229.jpg)

![This is an image]

