# Beim Router
apt install sudo
   10  ip root
   11  ip link set dev ens4 up
   12  ip link set dev ens5 up
   13  ip a
   15  ping 8.8.8.8
   23  ip addr add 192.168.50.1/24 dev ens5
   24  ip addr add 192.168.10.1/24 dev ens4
   28  nft add table ip nat
   29  nft -- add chain ip nat prerouting { type nat hook prerouting priority -100 \; }
   30  nft add table ip nat
   31  nft -- add chain ip nat prerouting { type nat hook prerouting priority -100 \; }
   32  nft add chain ip nat postrouting { type nat hook postrouting priority 100 \; }
   33  sysctl net.ipv4.ip_forward
   34  net.ipv4.ip_forward = 0
   35  sysctl net.ipv4.ip_forward
   36  sysctl -w net.ipv4.ip_forward=1
   37  sudo nano /etc/sysctl.conf
   38  sudo nano /etc/sysctl.conf
   39  sysctl net.ipv4.ip_forward
   40  sysctl -p
   41  systemctl status sysctl
   42  sudo systemctl start sysctl
   43  systemctl status sysctl
   44  sysctl -p
   45  sudo nano /etc/sysctl.conf
   46  rc-service sysctl status
   47  sudo nano /etc/sysctl.conf
   48  y
   49  sysctl -p
   50  sysctl -p
   51  sudo nftables.conf
   52  nano /etc/nftables.conf
   53  nano /etc/nftables.conf
   54  ping 8.8.8.8
   55  ip a
   56  systemctl restart nftables
   57  systemctl restart nftables.service
   58  systemctl status nftables.service
   59  systemctl status nftables
   60  systemctl status nftables
   61  clr
   62  clear
   63  clear
   64  systemctl status nftables
   65  systemctl enable nftables.service
   66  systemctl enable nftables.service
   67  systemctl enable nftables
   68  systemctl restart nftables
   69  sudo nft -f /etc/nftables.conf
   70  nano /etc/nftables.conf
   71  sudo nft -f /etc/nftables.conf
   72  sysctl -p
   73  systemctl restart nftables
   74  ssh user@192.168.50.10
   75  apt install sudo
   76  sudo hostnamectl set-hostname router-firewall
   77  hostnamectl status
   78  vi /etc/hosts
   79  cat /etc/hostname
   80  nano /etc/hosts
   81  nano /etc/hosts
   82  ip a
   83  su -
   84  sudo nano /etc/network/interfaces
   85  sudo nano /etc/network/interfaces
   86  sudo nano /etc/network/interfaces
   87  sudo nano /etc/network/interfaces
   88  sudo nano /etc/network/interfaces
   89  sudo nano /etc/network/iptables
   90  sudo nano /etc/network/nftables
   91  cd
   92  sudo nano /etc/nftables.conf
   93*
   94  ip a
   95  ping 192.168.10.10
   96  ping 192.168.10.1
   97  ping 192.168.10.10
   98  sudo nano /etc/nftables.conf
   99  sudo nano /etc/network/nftables
  100  sudo nano /etc/network/interfaces
  101  ip a
  102  ping 192.168.50.10
  103  sudo nano /etc/nftables.conf
  104  sudo nano /etc/nftables.conf
  105  sudo nano /etc/network/interfaces.d
  106  sudo nano /etc/interfaces.d
  107  sudo nano /etc/interfaces.
  108  sudo nano /etc/interfaces
  109  nano /etc/network/interfaces
  110  nano /proc/sys/net/ipv4/ip_forward
  111  nano /etc/sysctl.conf
  112  nano /etc/network/interfaces
  113  nano /etc/network/interfaces
  114  sudo nano /etc/nftables.conf
  115  ip a
  116  sudo nano /etc/nftables.conf
  117  sudo nano /etc/nftables.conf
  118  sudo nano /etc/nftables.conf
  119  sudo nano /etc/nftables.conf
  120  nano /etc/network/interfaces
  121  nano /etc/sysctl.conf
![[Unbenannt.jpg]]
![[Unbenannt 1.jpg]]
![[Unbenannt-1.jpg]]


# Beim DNS Server 
![[Unbenannt 2.jpg]]
![[Unbenannt-1 1.jpg]]
