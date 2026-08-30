# Priprava virtualnega okolja

## Kaj sem naredil

Prenesil [VirtualBox](https://www.virtualbox.org/wiki/Downloads) in [Windows Server 2025](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2025) evaluation ISO.

Naredil novo VM v VirtualBox Manager (New): 8GB RAM, 4 CPU jedra, 60GB virtualni disk (.vdi format), priklopu Windows Server ISO.

Preveril da je Network nastavljen na NAT(Network Address Translation).

<details>
<summary>📸 Screenshoti</summary>

![Nastavitve nove VM](../images/new1.png)
![NAT nastavitev](../images/nat1.png)

</details>

## Naučeno
- Namestitev VirtualBoxa je bla preprosta, brez težav
- NAT je kot recepcija - moj VM ima notranji naslov, NAT pa poskrbi da lahko pošlje pakete ven na internet in da odgovori pridejo nazaj k pravemu naslovu (VM-ju)