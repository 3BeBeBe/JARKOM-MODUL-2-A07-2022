# JARKOM-MODUL-2-A07-2022


##No.1
Membangun koneksi ke internet dengan 
```
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.172.0.0/16
```

Melakukan update dengan
```
apt-get update
```


##No.2
Mengarahkan WISE nameserver ke Ostania
```
echo nameserver 192.168.122.1 > /etc/resolv.conf
```

Melakukan update dan install dengan
```
apt-get update
apt-get install bind9 -y
```
Setelah itu melakukan konfigurasi pada file `/etc/bind/named.conf.local`


##No.3

##No.4

##No.5

##No.6

##No.7

