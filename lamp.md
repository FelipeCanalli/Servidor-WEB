## Projeto - Servidor WEB LAMP

#

Faça você também passo a passo [Curso Linux WEB Server Level 1](https://www.youtube.com/watch?v=fqR5SymRgLQ&list=PLbEOwbQR9lqySZ9RXfF5cFSyfA-r3n30q)

Esse projeto simula um ambiente real de hospedagem

![Cenario](/img/LAMP-cenario.jpg)

#

### No meu cenário local temos os seguintes endereços utilizados

| Endereço IP  | Descrição                                                            |
| ------------ | -------------------------------------------------------------------- |
| 192.168.0.23 | Endereço da minha máquina real                                       |
| 192.168.0.2  | Endereço do Web server ( CentOS ) virtualizado em modo bridged       |
| 192.168.0.3  | Endereço do ns1 Servidor DNS ( CentOS ) virtualizado em modo bridged |

#

|  ![Teste de conectividade](/img/LAMP-ping-maquina-real.jpg)   |
| :-----------------------------------------------------------: |
| _ping vindo dos servidores até a máquina real (192.168.0.23)_ |

| ![Teste de conectividade 2](/img/LAMP-ping-site-externo.jpg) |
| :----------------------------------------------------------: |
|       _ping vindo dos servidores até um site externo_        |

| ![Teste de conectividade 3](/img/LAMP-ping-servidores.jpg) |
| :--------------------------------------------------------: |
|       _ping vindo da máquina real até os servidores_       |

|              ![Acesso remoto SSH](/img/LAMP-acesso-ssh.jpg)              |
| :----------------------------------------------------------------------: |
| _acesso remoto via SSH ( root está bloqueado para esse tipo de acesso )_ |

| ![Conexão FTP](/img/LAMP-conexao-ftp.jpg) |
| :---------------------------------------: |
|               _conexão FTP_               |

| ![Primeiro site](/img/LAMP-primeiro-site.jpg) |
| :-------------------------------------------: |
| _Primeiro site hospedado em meu servidor web_ |

| ![Segundo site](/img/LAMP-segundo-site.jpg)  |
| :------------------------------------------: |
| _Segundo site hospedado em meu servidor web_ |

| ![Segundo site](/img/LAMP-segundo-site-wordpress.jpg)  |
| :----------------------------------------------------: |
| _Segundo site hospedado em meu servidor web WordPress_ |

| ![Segundo site](/img/LAMP-segundo-site-phpmyadmin.jpg)  |
| :-----------------------------------------------------: |
| _Segundo site hospedado em meu servidor web PhpMyAdmin_ |
