# Linux-Commands

Linux Commands reference: E os mistérios do prompt piscante!

Dicas para os alunos de Ciências dos Dados, Ciências da Computação e Engenharias

<img src="https://linuxcommand.org/images/Screenshot-Terminal.png" width="600px">

<img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1649005052591/YY2aPz_V7.png" width="600px">

Porque aprender Linux? 🐧️
- Para aprender sobre como o computador funciona
- Para ter acesso a todo o potencial de um computador
- Para ser capáz de utilizar qualquer computador, de supercomputador até um device de IoT
- Para ser competitivo em oportunidades de trabalho ou projetos
- Para fazer parte de uma comunidade colaborativa, inovadora e conhecer hackers, engenheiros, developers, cientistas, entusiastas, geeks etc...
- Para conquistar a mulher amada e encontrar o amor verdadeiro!!

<img src="https://pbs.twimg.com/media/DQB029JVwAALyEu?format=jpg" width="600px">

O RaspberryPi roda Linux, é um computador menor que um cartão de crédito que custa apenas US$ 15.00

<img src="https://images.prismic.io/rpf-products/9371b539-77d4-47f1-b89b-aa65b23c9833_RPI%20ZERO%20W%20ANGLE%202%20REFRESH_.jpg" width="600px">

O Linux também roda em supercomputadores, e também a computação em nuvem roda sobre o Linux:

<img src="https://www.omgubuntu.co.uk/wp-content/uploads/2018/06/summit-supercomputer-red-hat-linux.jpg" width="600px">

Em meados dos anos 2000, trabalhei com UNIX Solares da Sun Microsystems, rodando aplicações corporativas em Java e Oracle, em servidores E1000 (E10K) entre outros equipamentos. TUDO que aprendi com sistemas UNIX e rede continuam válido no Linux de hoje. É curioso como conhecimento de TI não é tão volátil quanto parece. Os fundamentos de computação são valiosos e de "longa duração".

<img src="https://www.computermuseum.org.uk/pictures/sun_e10000.gif" width="600px">

Sistemas sofisticados mais atuais como da Oracle (que comprou a Sun Microsystem) também usam Linux:

<img src="https://www.bsi.uk.com/media/catalog/product/cache/1/image/1280x960/040ec09b1e35df139433887a97daa66f/o/r/oracle_oda_x7.jpg" width="600px">

O Linux foi "inspirado" em sistemas UNIX, e dominou o mercado de servidores e supercomputadores:

<div style="background-color: white;">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Operating_systems_used_on_top_500_supercomputers.svg" width="600px">
</div>

Developers vem [adotando](https://www.google.com/search?q=developers+adopting+linux&oq=developers+adopting+linux) cada vez mais o Linux, [Dell](https://www.dell.com/pt-br/search/notebook%20gamer?r=37832&p=1&ac=facetselect&t=Product&c=laptops&f=true&gacd=9657105-15013-5761040-275878141-0&dgc=ST&cid=71700000100458207&gclid=Cj0KCQjw7uSkBhDGARIsAMCZNJtw7XWh1XwoGF2iSEZaz6N4HKiWiiNRHPatE1IXYXF6ZOnTKOA5uVYaAnMgEALw_wcB&gclsrc=aw.ds) e [Lonovo](https://www.lenovo.com/br/pt/d/promocoes?cid=br%3Asem%7Cse%7Cgoogle%7Cj-b2c-brand_trafego-awrs-google-search-net%7C%7Clenovo%7C%7C18076414538%7C145816546288%7Ckwd-845751236%7C%7C%7C&gclid=Cj0KCQjw7uSkBhDGARIsAMCZNJtddi2x5egk6ZttfsKE3oojnHlqO_tVKH0VJc1Y_77cR1Zjfdf21RoaAmChEALw_wcB&sort=sortBy&resultsLayoutType=grid&visibleDatas=facet_OperatingSystem%3ALinux) já vendem equipamentos com Linux de fábrica. E a Microsoft implementou o WSL2 para manter os developers, e agora tem sua própria distribuição: [Azure Linux](https://azure.microsoft.com/pt-br/solutions/linux-on-azure/?gclid=Cj0KCQjw7uSkBhDGARIsAMCZNJtP-01d7pUCWBJd50XYKSMDuvx8e8RBTRbnRWRFJd1DixfpvKb1q50aAkQrEALw_wcB#overview/?ef_id=_k_Cj0KCQjw7uSkBhDGARIsAMCZNJtP-01d7pUCWBJd50XYKSMDuvx8e8RBTRbnRWRFJd1DixfpvKb1q50aAkQrEALw_wcB_k_&OCID=AIDcmmzmnb0182_SEM__k_Cj0KCQjw7uSkBhDGARIsAMCZNJtP-01d7pUCWBJd50XYKSMDuvx8e8RBTRbnRWRFJd1DixfpvKb1q50aAkQrEALw_wcB_k_). E mais em: https://www.zdnet.com/article/best-linux-laptop/<br>
Há também fabricantes de computadores e notebooks especializados em Linux como: https://www.pine64.org ou https://system76.com/.

<!--
![image](https://github.com/danielscarvalho/Linux-Commands/assets/916663/45fde545-69e8-4c7e-9af0-73c447e4c20a)
-->

<img src="https://github.com/danielscarvalho/Linux-Commands/assets/916663/45fde545-69e8-4c7e-9af0-73c447e4c20a" width="600px">

O sistema [Android](https://canaltech.com.br/android/android-e-linux-entenda-essa-questao-de-uma-vez-por-todas-230227/) também usa o kernel do Linux, ou seja, há bilhões de usuários do Linux que usam o smartphone do Google:

<img src="https://www.bankmycell.com/blog/wp-content/uploads/2023/02/S21-2-Android-vs-iOS-Market-Share.png" width="600px">

> Outro detalhe importante. Os usuário não instalam e configuram o sistema operacional. Ele já vem instalado de fábrica ou pela empresa, faculdade que fornece o equipamento.

Podemos rodar o Linux no PC com Windows:
- Usando o Oracle Virtual Box: https://www.virtualbox.org/ (VM - Virtual Machine)
- Usando o WSL2 (Windows Subsystem for Linux): https://learn.microsoft.com/pt-br/windows/wsl/install
- Usando um servidor Linux em nuvem (gratuito ou baixo custo) configurando uma VSP - Virtual Private Server
  - Azure: https://azure.microsoft.com/en-us/free/students/
  - Oracle: https://www.oracle.com/br/cloud/free/
  - Google: https://cloud.google.com/free?hl=pt-br 

> O SO (Sistema Operacional) da Apple ([MacOS](https://www.apple.com/br/macos/ventura/)) é uma derivação do UNIX Free BSD, ou seja, já tem CLI Bash (Terminal) e a estrutura muito parecida com a do Linux, os developers e cientistas de dados usam o Mac aos montes!!

Há diversas distribuições Linux para propósitos distintos, podemos utilizar e experimenta-las, recomendo duas distribuições para iniciantes:
  - Ubuntu: https://ubuntu.com
  - Debian: https://www.debian.org

Some discussion:
- [Debian vs Ubuntu: A Detailed Comparison](https://linuxstans.com/debian-vs-ubuntu/)
- [Linux vs. Windows: A Casual, Realistic Perspective](https://linuxstans.com/linux-vs-windows/)
  

[Marketshare](https://w3techs.com/technologies/details/os-linux) das distribuições Linux:<br>
![image](https://github.com/danielscarvalho/Linux-Commands/assets/916663/adc83e20-99ee-4858-88b1-4144480a2fc5)

### A Internet é feita de Linux

A maioria dos sites na Internet, sistemas de e-commerce e CMS (Content Management Sistems) como o WP (WordPress) por exemplos, são feitos com o [LAMP](https://pt.wikipedia.org/wiki/LAMP) stack, que consiste em um ambiente **Linux**, com WEB server **Apache**, banco de dados relacional **MySQL** e a linguagem de progamação **PHP**, **Python** ou **Perl**. Tecnologias abertas e livres. +70% dos sites na Internet usam estas tecnologias: https://w3techs.com/technologies/overview/content_management

## Papéis do Linux

A natureza do Linux/UNIX é flexibilidade, pois o SO pode ser configurado e compilado para atender a diversas aplicações:

- Desktop de usuário final
    - Doméstico
    - Gamer
    - Educação
    - Negócios
    - Developer
    - Ciêntista de Dados
    - IA & Machine Learning - Deep Learning (NVIDIA CUDA)
    - Engenharia e Arquitetura (CAD, CAM)
    - Modelagem 3D
- Router [RouterOS](https://mikrotik.com/software) -  routing, firewall, bandwidth management, wireless access point, backhaul link, hotspot gateway, VPN server, etc
- Robôs [ROS](https://www.ros.org/)
- Kiosk
- ATM (bank machine)
- IoT (Edge Computing)
- Serviços de TI
    - Servidor de arquivos (O drive F: da rede...)
    - Servidor de mídia
    - Servidor de banco de dados
    - Servidor WEB
    - Servidor de aplicação
    - Servidor de Wiki (Colaboração, Knoledge Base)
    - Servidor de E-Commerce
    - Servidor de E-Mail
    - Servidor de impressão
    - Servidor de backup
    - (S)FTP (Arquivos)
    - Firewall e Antivírus (Segurança)
    - Proxy
    - DNS, DHCP, IDS, VPN, LDAP, NTP e diversos serviços de rede
    - Render Server (Computação Gráfica, vídeos 3D)
    - Cluster (Server Farm)
    - PABX, VoIP
    - Docker

> Linux pode ser instalado em computadores antigos, e também em computadores que não suportam Windows 10 ou Windows 11.<br>
> Extende-se a vida útil do computador, e pode ser dado também um destino específico como citado anteriormente...
    
Entre outros...

<img src="https://www.zenarmor.com/docs/assets/images/types-of-servers-507a1970e9401e3fc59727d0fd7dde95.png" width="600px"><br>
https://www.zenarmor.com/docs/network-basics/types-of-servers

<img src="https://pbs.twimg.com/media/F0M-ZcJWcAEZDQn?format=jpg" width="600px">

## Tópicos: Comandos do Linux

### Arquitetura

<img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1680630826055/e1dcd139-949b-445b-8044-20cc6208e164.png" width="600px">

### CLI (Command Line Interface) 

<img src="https://pbs.twimg.com/media/Fz3eQUwXoAALzYH?format=jpg" width="600px">

### Arquivos e Pastas (Diretórios)

<img src="https://github.com/danielscarvalho/Linux-Commands/assets/916663/cdbd3d6b-9cb4-47c7-a5d7-009397b2bb0c" width="600px">

### Navegação


### Organização (diretórios)

<img src="https://miro.medium.com/v2/resize:fit:4800/0*bFnHaO8eYpW3dSuz" width="600px">

### Linux Commands

Lista para iniciantes, feito com a IA LLM do X Grok 3 (beta):

| Comando       | Breve Descrição                              | Exemplo                                      | Categoria                |
|---------------|----------------------------------------------|----------------------------------------------|--------------------------|
| `ls`          | Lista arquivos e diretórios (equivalente ao `dir`) | `ls -l`<br>`ls -a`                         | Navegação nos Diretórios |
| `cd`          | Muda o diretório atual                      | `cd /home/user`<br>`cd ..`                   | Navegação nos Diretórios |
| `pwd`         | Mostra o caminho do diretório atual         | `/home/user`<br>`/etc`                       | Navegação nos Diretórios |
| `mkdir`       | Cria um novo diretório                      | `mkdir novo_dir`<br>`mkdir -p /tmp/teste`    | Manipulação de Arquivos  |
| `rm`          | Remove arquivos ou diretórios               | `rm arquivo.txt`<br>`rm -r dir`              | Manipulação de Arquivos  |
| `cp`          | Copia arquivos ou diretórios                | `cp arquivo.txt copia.txt`<br>`cp -r dir1 dir2` | Manipulação de Arquivos  |
| `mv`          | Move ou renomeia arquivos/diretórios        | `mv arquivo.txt novo.txt`<br>`mv dir1 /tmp`  | Manipulação de Arquivos  |
| `touch`       | Cria um arquivo vazio ou atualiza timestamp | `touch arquivo.txt`<br>`touch -t 202301011200 arquivo.txt` | Manipulação de Arquivos  |
| `cat`         | Exibe o conteúdo de um arquivo              | `cat arquivo.txt`<br>`cat file1.txt file2.txt` | Manipulação de Arquivos  |
| `less`        | Visualiza arquivos página por página        | `less arquivo.txt`<br>`less +G arquivo.txt`  | Manipulação de Arquivos  |
| `grep`        | Busca texto em arquivos                     | `grep "texto" arquivo.txt`<br>`grep -r "palavra" dir` | Manipulação de Arquivos  |
| `find`        | Busca arquivos/diretórios no sistema        | `find / -name arquivo.txt`<br>`find . -type d` | Manipulação de Arquivos  |
| `locate`      | Busca arquivos rapidamente usando um banco de dados | `locate arquivo.txt`<br>`locate -i ARQUIVO` | Manipulação de Arquivos  |
| `wc`          | Conta linhas, palavras e caracteres em arquivos | `wc -l arquivo.txt`<br>`wc -w arquivo.txt` | Manipulação de Arquivos  |
| `head`        | Exibe as primeiras linhas de um arquivo     | `head -n 10 arquivo.txt`<br>`head -n 5 log.txt` | Manipulação de Arquivos  |
| `tail`        | Exibe as últimas linhas de um arquivo       | `tail -n 10 arquivo.txt`<br>`tail -f log.txt` | Manipulação de Arquivos  |
| `more`        | Visualiza arquivos página por página (simples) | `more arquivo.txt`<br>`more +50 arquivo.txt` | Manipulação de Arquivos  |
| `vi`          | Editor de texto em modo terminal            | `vi arquivo.txt`<br>`vi +10 arquivo.txt`     | Manipulação de Arquivos  |
| `nano`        | Editor de texto simples em terminal         | `nano arquivo.txt`<br>`nano -w arquivo.txt`  | Manipulação de Arquivos  |
| `chmod`       | Altera permissões de arquivos/diretórios    | `chmod 755 script.sh`<br>`chmod u+x arquivo` | Gerenciamento de Sistema |
| `chown`       | Altera o proprietário de arquivos/diretórios| `chown user arquivo.txt`<br>`chown user:group dir` | Gerenciamento de Sistema |
| `chgrp`       | Altera o grupo de arquivos/diretórios       | `chgrp grupo arquivo.txt`<br>`chgrp -R grupo dir` | Gerenciamento de Sistema |
| `ps`          | Lista processos em execução                 | `ps aux`<br>`ps -ef`                         | Gerenciamento de Sistema |
| `kill`        | Encerra um processo por ID                  | `kill 1234`<br>`kill -9 5678`                | Gerenciamento de Sistema |
| `top`         | Monitora processos em tempo real            | `top`<br>`top -u user`                       | Gerenciamento de Sistema |
| `htop`        | Monitora processos com interface melhorada  | `htop`<br>`htop -u user`                     | Gerenciamento de Sistema |
| `btop`        | Monitora processos com interface moderna    | `btop`<br>`btop --utf-force`                 | Gerenciamento de Sistema |
| `free`        | Mostra o uso de memória RAM e swap          | `free -h`<br>`free -m`                       | Gerenciamento de Sistema |
| `df`          | Mostra o uso do espaço em disco             | `df -h`<br>`df -T`                           | Gerenciamento de Sistema |
| `du`          | Calcula o tamanho de arquivos/diretórios    | `du -sh /home`<br>`du -h --max-depth=1 dir`  | Gerenciamento de Sistema |
| `whoami`      | Mostra o usuário atual                      | `whoami`<br>`/usr/bin/whoami`                | Gerenciamento de Sistema |
| `who`         | Mostra usuários logados no sistema          | `who`<br>`who -u`                            | Gerenciamento de Sistema |
| `passwd`      | Altera a senha do usuário                   | `passwd`<br>`passwd user`                    | Gerenciamento de Sistema |
| `apt`         | Gerencia pacotes em sistemas baseados em Debian | `apt install pacote`<br>`apt update`       | Gerenciamento de Sistema |
| `jobs`        | Lista processos em segundo plano no shell   | `jobs`<br>`jobs -l`                          | Gerenciamento de Sistema |
| `nohup`       | Executa um comando imune a desconexões      | `nohup script.sh &`<br>`nohup sleep 100 &`   | Gerenciamento de Sistema |
| `uname`       | Exibe informações sobre o sistema operacional | `uname -a`<br>`uname -r`                   | Gerenciamento de Sistema |
| `hostname`    | Exibe ou define o nome do host do sistema   | `hostname`<br>`hostname -I`                  | Gerenciamento de Sistema |
| `sudo`        | Executa comandos com privilégios de administrador | `sudo apt update`<br>`sudo -u user cmd`    | Gerenciamento de Sistema |
| `ping`        | Testa conectividade com outro host          | `ping google.com`<br>`ping -c 4 8.8.8.8`     | Redes                    |
| `curl`        | Faz requisições HTTP/HTTPS                  | `curl http://example.com`<br>`curl -O http://file.com/file.txt` | Redes                    |
| `wget`        | Baixa arquivos da web                       | `wget http://example.com/file`<br>`wget -r http://site.com` | Redes              |
| `ifconfig`    | Exibe configurações de rede (obsoleto em alguns sistemas) | `ifconfig`<br>`ifconfig eth0`          | Redes                    |
| `ip`          | Gerencia configurações de rede              | `ip addr`<br>`ip route`                      | Redes                    |
| `netstat`     | Mostra estatísticas de rede                 | `netstat -tuln`<br>`netstat -i`              | Redes                    |
| `ssh`         | Conecta a um servidor remoto                | `ssh user@host`<br>`ssh -p 2222 user@host`   | Redes                    |
| `whois`       | Consulta informações de domínios            | `whois google.com`<br>`whois 8.8.8.8`        | Redes                    |
| `nslookup`    | Consulta informações de DNS                 | `nslookup google.com`<br>`nslookup 8.8.8.8`  | Redes                    |
| `history`     | Mostra o histórico de comandos              | `history`<br>`history 10`                    | Utilitários              |
| `man`         | Exibe o manual de um comando                | `man ls`<br>`man 5 passwd`                   | Utilitários              |
| `echo`        | Exibe texto ou variáveis                    | `echo $PATH`<br>`echo "Hello World"`         | Utilitários              |
| `clear`       | Limpa a tela do terminal                    | `clear`<br>`/usr/bin/clear`                  | Utilitários              |
| `alias`       | Cria atalhos para comandos                  | `alias ll='ls -l'`<br>`alias cls='clear'`    | Utilitários              |

## Referências:

- The Linux Command Line by William Shotts: https://linuxcommand.org/tlcl.php
- Shell Script Profissional by Aurelio Marinho Jargas: https://www.shellscript.com.br/
- Linux commands Notes for Professionals book: https://books.goalkicker.com/LinuxBook/
- Linux Pocket Guide: Essential Commands, O’Reilly, Daniel J. Barrett: https://a.co/d/cwqTaz8
- Bash Notes for Professionals book: https://books.goalkicker.com/BashBook/
- Vi/Vim cheat sheet: https://i.imgur.com/YLInLlY.png
- OMG Ubuntu: https://www.omgubuntu.co.uk/
- Bash Commands Cheat Sheet (RedHat): https://developers.redhat.com/cheat-sheets/bash-shell-cheat-sheet
- Linux Commands Cheat Sheet (RedHat): https://developers.redhat.com/cheat-sheets/linux-commands-cheat-sheet-old

## Inspiração:

- Linux Complete, by Loren E. Redding: https://a.co/d/39FU3KX
- https://amigoscode.com/p/linux
- https://www.youtube.com/watch?v=ZtqBQ68cfJc
- https://www.shortform.com/best-books/genre/best-unix-books-of-all-time

## Meme:

<img src="https://cdn.thenewstack.io/media/2022/08/0ae25624-exit-vim-the-arrival-way-6n632sipjag61-1024x692.jpg" width="600px"><br>
<img src="https://media.makeameme.org/created/no-existe-nuvem.jpg" width="600px"><br>
<img src="https://gerarmemes.s3.us-east-2.amazonaws.com/memes/f8df6395.webp" width="600px"><br>

