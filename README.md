# Ansible_Project
Ansible automation

## Table of Content
1. Setup 
2. Ansible Playbooks



### 1. Setup

### Setup vm Network

+ Setting up two VMs with MX-Linux in VirtualBox
+ Setting up intern network and NAT for Internet
+ Assigning static ip addresses for the internal network of the two virtual machines


![Alt text](<Screenshot 2023-08-23 221904.png>) &nbsp; &nbsp; &nbsp; &nbsp;![Alt text](<Screenshot 2023-08-23 222247.png>)
<br>
interfaces with example values


+ Add firewall rule for SSH to allow incoming SSH requests from Admin-VM
    + sudo ufw allow from 192.123.1.101 to any port 22

### 2. Ansible Playbooks

### Overview playbook structure

+ Creating an Ansible Playbook Environment with Inventory and Roles in the folder my_test

    + mytestinventory: group_vars and hosts
        + group_vars: Storing vars for different hosts
    + hosts: client, local 
    + roles: Grouping multiple tasks together for different roles
        + role_1
            + create folder
            + create five text files
            + Replace text in line 2 of two text files
            + Run tree command
            + Display tree command output
        + role_2
            + Create a file with text 

    + execute.yml: Declaring where and which role is executed





