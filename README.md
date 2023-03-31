# cisco-desafio-PacketTracer
  ## Algumas Habilidades durante curso Cybersecurity Essentials 

Cenário:

Esta atividade final inclui muitas das habilidades que foram adiquiridas durante o curso. Será configurado
um roteador sem fio, fazer upload e baixar arquivos usando FTP, conectar-se com segurança a um site
remoto usando uma VPN e proteger um roteador Cisco IOS.

![](/imagens/tabela.png)



###  Fazendo o upload do arquivo secure.txt para o servidor FTP/Web usando FTP:
![](/imagens/1-Carregue%20o%20arquivo%20secure.txt%20no%20servidor%20FTPWeb%20usando%20FTP.gif)
- Usuário sally com senha ftpaccess
- Será feito upload do arquivo secure.txt
- Use o endereço IP do servidor FTP/Web localizado na tabela de endereçamento.

***

###  Conectando o computador de Sally ao site Gotham Healthcare Branch via uma VPN cliente-para-site:
![](/imagens/2-Conecte%20o%20computador%20de%20Sally%20ao%20site%20Gotham%20Healthcare%20Branch%20via%20uma%20VPN%20cliente-para-site.gif)
- Use o endereço IP do servidor VPN localizado na tabela de endereçamento e pingue o servidor VPN
- Conecte a VPN cliente-para-site com o usuário sally e a senha vpnsally
- Use o grupo VPNGROUP e a chave 123

***

### Usando a conexão VPN, baixe o arquivo transactions.txt do servidor BackupFiles usando FTP:
![](/imagens/3-Usando%20a%20conexão%20VPN,%20baixe%20o%20arquivo%20transactions.txt%20do%20servidor%20BackupFiles%20usando%20FTP.gif)

- Use o endereço IP do servidor BackupFiles localizado na tabela de endereçamento.
- Usuário sally com senha securesally
- O arquivo a ser baixado é transactions.txt

***

### Configurando o roteador HQ_Sem fio
![](/imagens/4-Configure%20o%20roteador%20HQ_Sem%20fio.gif)
- Use o endereço IP do roteador HQ_Sem fio localizado na tabela de endereçamento.
- Use o navegador da Web para configurar o roteador HQ_Sem fio do notebook de Phil.
- Usuário admin com senha p@ssword
- Altere o SSID de DefaultWIFI para HQwifi
- Defina o SSID para ser visto (em broadcast) para clientes sem fio.
- Configure a segurança sem fio de WPA2 Personal com a senha cisco321.

***

### Protejendo o HQ_Router
![](/imagens/5-Proteja%20o%20HQ_Router.gif)
- Use o endereço IP do roteador HQ_Router localizado na tabela de endereçamento.
- Use o Command prompt (Prompt de comando) para ssh para HQ_Router com o usuário phil e a senha securessh
- Use o comando enable e a senha cisco.
- Ative o recurso de Configuração resiliente do Cisco IOS.
  
  ***

  ### Configurando um banner de mensagem e senha Authorized Access Only
  ![](/imagens/6-Configure%20um%20banner%20de%20mensagem.gif)

  ***

  ### Conectando ao notebook de Gina à rede sem fio
![](/imagens/7-Conecte%20o%20notebook%20de%20Gina%20à%20rede%20sem%20fio.gif)

- Conecte-se ao SSID de HQwifi
- Use a chave pré-compartilhada cisco321
- Verifique se o notebook usa DHCP
