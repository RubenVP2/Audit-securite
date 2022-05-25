# Audit-securite
Prise de note du cours audit securité.

# Scan du reseau 
Get l'adresse  
`ip ad`  
Utiliser netdiscover pour analyser le réseau  
`sudo netdiscover -i eth0 `  
Scanner le réseau.  
`sudo nmap -sS <ip>`  
Scanner le réseau avec précision des ports.  
`sudo nmap -sS -p 80,22,6665 --reason 192.168.56.10`  
MDP Disque vm apache : 
`IPIEH`
MDP Kali : 
`kali
