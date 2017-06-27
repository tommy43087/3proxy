# 3proxy

Install 3proxy proxy server on Ubuntu 16.04 server.

```
wget https://raw.githubusercontent.com/tommy43087/3proxy/master/install.sh
./install.sh
```

Setting password

```
echo 'username:CL:password' > /etc/3proxy/users
```

Retart 3proxy

```
service 3proxy restart
```
