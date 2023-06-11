# Ansible_Project
Ansible automation

## Table of Content
1. Environment / Setup (% sowas in die Richtung, sowas wie Überblick)
2. Ansible Playbooks


### 1. Environment

% Zeichnung VM Netzwerk

+ Setting up two VMs with MX-Linux in VirtualBox
+ Setting up internes Netzwerk and NAT for Internet

% Screenshot von allen beiden VM machen (%Weg zu Screenshot cd /etc/network
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





