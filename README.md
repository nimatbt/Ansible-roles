# Ansible Roles

This Ansible roles install the last version of some usefull apps on Ubuntu:
- Wireguard(wg)
- Zsh and oh-my-zsh
- Zabbix agent

 ## What is Ansible?

- Ansible is IaC tool for configuration management. With the aid of Ansible, we can configure a multitude of systems without direct human interactions.
Ansible is responsible for configuring existing systems, usually mutable ones.
Ansible.com for more information.

 ## What is wireGuard?
 
- WireGuard is a communication protocol and free and open-source software that implements encrypted virtual private networks (VPNs), and was designed with the goals of ease of use, high speed performance, and low attack surface.

 ## What is zsh and oh-my-zsh?
  
- ZSH, also called the Z shell, is an extended version of the Bourne Shell (sh), with plenty of new features, and support for plugins and themes. Since it’s based on the same shell as Bash, ZSH has many of the same features, and switching over is a breeze.

- Oh-My-Zsh is the most popular plugin framework for ZSH, and it comes with many built-in plugins and themes as well. 


 ## What is Zabbix?

- Zabbix is defined as an open-source monitoring tool used for monitoring of servers, network, IT components, cloud services and virtual machines. The Zabbix monitoring tool is used to provide the monitoring metrics and monitor the network utilization, consumption of disk space, and CPU load.
  

 ## Get started guide:

Ansible version: 5.2.0

1) Install python3-pip and python3-venv on your system
    ```
    apt install -y python3-pip python3-venv
    ```

2) Clone repository
   ```
   git clone https://github.com/nimatbt/Ansible-roles.git
   ```

3) Create virtual environment(venv)
    ```
    python -m venv venv
    ```


4) Install requirements package from requirements.txt
   ```
   pip install -r requirements.txt
   ```

5) Run this command:
  - For normal installation
    ```
    ansible-playbook -i inventory.ini playbook.yaml
    ```
    
    
- Name: Nima Tabatabaee

Copyright 2022 Nima Tabatabaee <nima.tabatabaee@gmail.com>
