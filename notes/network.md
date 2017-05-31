# Network

* Customize routes passing through VPN
> # redirect all default traffic via the VPN 
> 
> redirect-gateway def1 
>
> # redirect the Intranet network 192.168.1/24 via the VPN 
>
> route 192.168.1.0 255.255.255.0 
>
> # redirect another network to NOT go via the VPN 
>
> route 10.10.0. 0 255.255.255.0 net_gateway 
>
> # redirect a host using a domainname to NOT go via the VPN 
>
> route www.google.ca 255.255.255.255 net_gateway

*source*: https://serverfault.com/a/631048
