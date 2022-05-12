# Primeiros Passos para Desenvolvimento Web

### Aula 1  - O que é internet

- Primeiro domínio criado segundo a canaltech foi o Symbolics.com;
- primeiro blog pelo Rockcontent foi o open Diary, escrito por um brasileiro que estava estudando no MIT;
- Termos-chave:
  - Download/upload - internet está acima e o computador tá acima;
  - navegador/browser - por onde navegas pelos sites;
  - Banda larga é um tipo de conexão com a internet
  - cache -algumas coisas que ficam salvas de um site no PC para carregar mais rápido na próxima vez que entrar no site
  - crack - forma de piratear um software
  - email - eletronic mails
  - gif/jpg/png - formatos de foto comuns na internet, jpg perde dados e qualidade da imagem
  - host -é um servidor
  - HTML - linguagem de MARCAÇÃO - não é 
  - HTTP - protocolo
  - Link/URL - Link é uma ligação - URL é um endereço - de uma URL pode ser criado um link que vai 
  - mp3 formato de música - pequeno, boa fidelidade de audio
  - multimídia - permite que sejam executados vários tipos de mídias - escrita, audio, video
  - pixel - junção de de picture + element 
  - vírus - software malicioso com fim de causar 
  - keylogger - um tipo de vírus que pega tudo que é digitado
  - phishing - intenção é roubar dados através de contatos com o usuário, tipo de golpe;
  - backup - cópia de segurança dos dados;
  - blog - começou como diário online, hoje é um tipo de site
  - vlog - diário por meio de videos
  - 3g/4g/5g - velocidade das internets moveis
  - cookies - registros de nossas atividades em sites que são utilizados por outros sites 
  - firewall - impede acesso indevido 
  - hacker - nem sempre são maliciosos, mas é comum
  - IP - numero que tudo que está conectado a rede tem, forma de identificar 
  - click bait - notícias, links, que o objetivo é só que seja clicado. Pode gerar lucro no click, roubar dados,  virus;
  - pop-up - caixinhas que aparecem nos sites; 

- Latência - tempo que um dado leva para sair de um local e chegar a outro;

### Aula 2 - Como funciona a internet

- Redes:
  - Backbone - uma estrutura que gerencia as conexões, interliga com outras redes e backbones;
    - geralmente são empresas telefônicas que compram
    - Dial-up
    - ADSL (Banda larga)
    - Fibra ótica - 
    - Rádio - bastante instável
    - Satélite
    - Móvel - torres próprias
    - P2P - Peer to peer
- Caminho inverso: - Internet - PC
  - www (computadores não entendem)
  - Servidor DNS - Domain Name Service - transforma  em número - IP
  - IP
  - Classes de redes (A, B, C, D, E)
  - 127.0.0.1 (IP) - Local host;

### Aula 3 - TCP/IP, Portas, Roteadores, Switches e modems

- **TCP/IP** - TRANSMISSION CONTROL PROTOCOL - PROTOCOLO DE CONTROLE DE TRANSMISSÃO
  - Cabeçalho e outros padrões que precisão ser seguidos para enviar os dados
  - modelo de camadas(4) - TCP
    - Camada física - placa de rede, por onde chega a conexão
    - Rede configurada
    - Forma de transporte definida (TCP ou UDP)
    - Aplicação - FTP - envio de arquivos, SMTP - email, HTTP - requisição de internet
  - UDP x TCP - Duas formas de conexão dos dispositivos e a internet, já está previamente confirgurado,
    - UDP
      - rápida
      - não confiável - coisas se perdem - não tem confirmação de envio e recebimento
      - carro do ovo - tá enviando a mensagem, mas não sabe se todos estão recebendo muito menos quem está recebendo; nem sempre é alguém que tem interesse; 
      - Tem sido usado para livestream
    - TCP 
      - Focado na conexão
      - handshake - primeiro avisa que vai enviar, avisa que recebeu, avisa que soube que recebeu
      - integridade dos dados, tem que seguir uma ordem dos dados enviado
      - Aplicativos de mensagem - não dá pra receber hoje uma mensagem que mandou ontem na hora do almoço, ou manda 10 mensagens e elas chegam fora de ordem e sem constexto.
- IP - Internet Protocol

- **PORTAS** - em inglês é ports (de porto, não porta)
  - portinhas por onde os dados sairão e chegarão
  - 20: FTP - envio de arquivos
  - 22: SSH - conexão segura entre computadores
  - 25: SMTP - emails
  - 53: DNS - 
  - 80: HTTP - requisição simples na internet
  - 443: HTTPS - requisição segura na internet
    _EXERCÍCIO_ Porta utilizada pelo MySQL por padrão é a 3306. APACHE: 443
- **MODEM** - modulator-demodulator
  - modula e demodula sinais;
  - Quando vemos um vídeo as informações contidas nele não são compreendidas pelo computador e nem pela internet que só entendem 0 e 1 - o modem vai modular os dados que enviamos e quando chega no computador que vai receber, demodula para que sua máquina possa apresentar da forma que humanos entendam;
- **ROTEADOR** 
  - distribui internet
  - pode comunicar entre redes
  - o roteador manda o sinal para todos os dispositivos conectados, não só para o computador que solicitou - gera muito tráfego - 
  - Atualmente é mais inteligente
- **SWITCH**
  - resolve o problema da burrice do roteador
  - distribui a internet para os dispositivos

### Aula 4 - Celular, internet e outros dispositivos

- **Dados móveis**
  - No início era o SMS - que não custa nada para as operadoras para ser enviado;
  - MMS - envio de mensagens multimídias
  - 1G -analógico 10kbps - primeira conexão
  - 2G - GSM 97kbps - ou internet, ou ligação
  - GPRS - mais lento que o 2G, mas conseguia ligar e usar a internet
- Wi-fi
  - IEEE - Empresa que define vários padrões de Wi-fi
    - IEE 802.11n: 2,4GHz/5GHz, 150-600Mbps
    - IEE 802.11G: 2,4GHz, 54 Mbps
- Segurança
  - WEP - chaves de 64 bits e de 128 bits
  - WPA - chave trocada periodicamente
  - WPA2 - mais segurança, mais processamento, mais lento - mais seguro;
- Chromecast - projeta a tela através da internet
- **Bluetooth**
  - Conexão ponto a ponto, sem depender de internet
  - 3 classes atualmente
    - 1 - 100m
    - 2 - 10m
    - 3 - 1m

### Aula 5 Browser, sites, aplicativos e webserver

- **Browser**
  - Navegador
  - Facilita a visualização de sites, existem outras formas de acessar a internet, mas os sites precisão de um navegador para traduzir as LP (Linguagem de programação);
  - Identificam diversas LP, linguagens de marcação e conteúdos multimídia
  - plug-ins - peças de lego que ligam outras funcionalidades (add blocker)
  - cache e coockies

- **Página estática x Dinâmica**
- **Site**
  - Página da internet
  - Diversos propósitos - colaborativa, indexador (google)
  - diversas LP
  - HTML- caindo em desuso
  - D/HTML - Dynamic HTML
- **Aplicativo**
  - Software executado no navegador
  - aplicativo é uma espécie de navegador;
  - Cada vez mais não há diferença entre site e aplicativo
- **E-commerce**
  - e - de electronic
  - Site com sistema de pagamento
  - Sistema de pagamento pode ficar fora do site
- **Web-Server** 
  - Estáticos: servidor físico - armazenas arquivos, bancos de dados...
  - dinâmicos: softwares que estão dentro dos servidores físicos;
    - Arquivos (file server)
    - Aplicações (application server)
    - banco de dados (database)
    - tudo junto
    - Dados de um site/app precisa estar em um servidor
  - WEB-SERVER - Interface  disponível para fazer requisições e consultas (CEP)
    - permite que não acesse dados sensíveis do banco de dados , não compromete a segurança;

### Aula 6 - Stacks

- **Stacks** 
  - Pilhas de tecnologia,
  - Conjunto de softwares necessários para executar um app/programa
  - Inclui as linguagens de programação; ambientes de desenvolvimento; ambiente de testes...
  - Todas as ferramentas e tecnologias que fazem parte da empresa; o que está à sua disposição para desenvolvimento do app;
  - Bancos de dados
  - sistemas operacionais
  - tipo de comunicação
  - qual o tipo de segurança
  - rede, infra
  - Capacidade e limitação de performance;
  - Pontos fortes e fracos do sw (software);
  - IDE's;

