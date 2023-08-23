# Ansible_Project
Ansible automation

## Table of Content
1. Environment / Setup 
2. Ansible Playbooks


### 1. Environment


Setup vm Network

+ Setting up two VMs with MX-Linux in VirtualBox
+ Setting up intern network and NAT for Internet

+ Assigning static ip addresses for the internal network of the two virtual machines

![image](https://github.com/Felix541/Ansible_Project/assets/136257812/cb0a8d77-a82a-4d45-90eb-f9176150ab4a)




% dann die Datei interfaces auswählen mit nano interfaces und dann Screenshot machen )
% Beschreibung unter Bild "Statische Zuweisung der IP-Adressen"

+ Erstellen von SSH private und publik key
+ Hinzufügen Firewallregel: sudo ufw allow from 192.179.1.101 to any port 22

### 2. Ansible Playbooks

+ Erstellen einer Ansible Playbook Umgebung mit Inventory und Rollen
+ Ausführen von unterschiedlichen Aufgaben auf dem Zielhost, bzw. auf dem localhost

% Screenshot wenn
ansible-playbook -i mytestinventory -e '@extra_vars.json' execute.yml 
% ausgeführt wurde

% Screenshot von den geänderten Verzeichnissen auf Zielhost und Local





