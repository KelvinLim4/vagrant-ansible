# WordPress + MySQL Provisioning com Vagrant e Ansible

Este projeto utiliza **Vagrant** e **Ansible** para configurar um ambiente de duas máquinas virtuais:  
- Uma máquina com **WordPress** e **Apache**.  
- Uma máquina com **MySQL**.  

## Pré-requisitos

Certifique-se de ter os seguintes softwares instalados em sua máquina:  
- [Vagrant](https://www.vagrantup.com/)  
- [VirtualBox](https://www.virtualbox.org/)  
- [Ansible](https://www.ansible.com/)  

## Configuração do Ambiente

O arquivo `Vagrantfile` foi configurado para criar e gerenciar duas máquinas virtuais:  

### 1. Máquina `wordpress`
- Sistema operacional: **Ubuntu 22.04**  
- IP: `192.168.56.250`  
- Memória: **1024MB**  
- Configurada para rodar o **WordPress** com **Apache**.

### 2. Máquina `mysql`
- Sistema operacional: **Ubuntu 22.04**  
- IP: `192.168.56.249`  
- Configurada para rodar o **MySQL**.

