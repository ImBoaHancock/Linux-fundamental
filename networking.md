Topic: MAC Address Spoofing (Linux / Kali)

Commands:
1. ifconfig eth0 down
   → Disable interface

2. ifconfig eth0 hw ether <new-mac>
   → Change MAC address (spoofing)

3. ifconfig eth0 up
   → Enable interface

Verification:
- ifconfig
- Check "ether" field

Notes:
- Change is temporary (resets after reboot)
- IPv6 address changes automatically (EUI-64)
- Used for privacy, testing, bypassing MAC filters

Modern Alternative:
ip link set eth0 down
ip link set eth0 address <new-mac>
ip link set eth0 up


Malware means - malicious software




-- check exe file for possible virus 
https://www.virustotal.com/gui/home/upload




# DMZ demilitarized zone
