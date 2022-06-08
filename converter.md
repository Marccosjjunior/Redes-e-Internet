#**Introdução a Redes e Internet**

**Redes**

Backbone: Espinha Dorsal, estruturas que gerenciam o tráfego na internet.

Provedor: Empresas telefônicas contratam o sinal do Backbone e repassam ao usuário final via Banda larga, Fibra ótica, satélite, etc…

www: é um endereço para humanos.

DNS: é responsável por transformar esse endereço humano em um número IP.

127.0.0.1 Local Host

TCP/IP: Protocolo de comunicação entre computadores em rede.

Uma comunicação entre dispositivos é feita  um processo de 4 camadas:

1. - Física: Placa de rede
1. - Rede: IP
1. - Transporte:UDP - rápido mas não confiável, sem confirmação de recebimento, ideal para Livestream / TCP - tem foco na conexão, ou seja, antes de estabelecer a conexão ele pede a confirmação de recebimento, é mais confiável, segue ordem dos dados.

**Portas**

20:FTP

22: SSH

25: SMTP

53: DNS

80: HTTP

443: HTTPS

Modem: Hardware que converte dados em um formato que possa ser transmitido de um computador para outro e lido por outro.

Roteador: Distribui internet para um ou mais dispositivos na rede, pode ser burro, pois manda para todos

Switch: Também distribui a internet, porém de forma mais inteligente..



**Dados Móveis**

SMS: Mensagem de texto

MMS: Multimídia - Áudio e vídeo - conexão de dados primitiva

Velocidade de Conexões Móveis

1G : analógico 10kbps

2G : digital 97 kbps

GPRS : dados + voz 32-80 kbps

3G : 7 Mbps

4G : 22 Mbps

5G : 10 Gbps



**WI-FI**

IEEE - Define os padrões para Wi - fi

IEEE 802,11: 2,4 GHz, 2Mbps

||          a:  5  GHz, 54Mbps

||          b:  2,4  GHz, 11Mbps menos interferência

||          g:  2,4  GHz, 54 Mbps

||          b:  2,4/5  GHz, 150, 600 Mbps

Chaves de Segurança - Senha na Rede

WEP: chaves de 64 e de 128 bits

WPA: chaves trocadas periodicamente

WPA2 (AES) (801.11i) + segurança e + processamento



**Bluetooth**

O bluetooth não necessita da internet para funcionar, ele faz uma conexão ponto a ponto.

Classe       Potência        Alcance  .

1. 100 mW          100m
1. 2,5 mW          10m
1. 1 mW             1m

Versão               Taxa de Transmissão

1.2                      1 Mbps

2.0 + EDR          3 Mbps

3.0                      24 Mbps

4.0                      25 Mbps

5.0                      50 Mbps



**Browser ou Navegador**

É um programa que interpreta  LP e as transforma em algo compreensível para humanos.

Identifica várias LP, de marcação e multimídia. Além disso, existem plug-ins, ou add-ons, que ajudam a navegação.

Cache: São cópias cópias locais de partes importantes dos sites visitados que ficam armazenadas para que nos próximos acessos esses sites carreguem de forma mais rápida.

Cookies: São pedaços de código que dão a um site uma espécie de memória de curto prazo, como suas informações de login e preferências de navegação, para oferecer a você uma experiência mais personalizada.

Página estática: Uma página sem interação, com algumas imagens.

Página dinâmica: Uma página com interação com o usuário, barras de rolagem, partes independentes, logins, compartilhamento, downloads, uploads.

Site

Página da internet com diversos propósitos e podem ser feitas em diversas LP - O HTML está caindo em desuso devido ao dinamismo das páginas.

Aplicativo APP

É um software que é executado no navegador, uma espécie de navegador.

Atualmente, já quase não existe diferença entre site e aplicativo, e o primeiro está em declínio.

E - commerce - Comércio Eletrônico

Site de compra e venda e pagamento, sistema de pagamento pode ser exterior ao site, PICPAY, BOLETOS, PAGSEGURO, PAYPAL, MERCADO PAGO.



**Web - server - Servidor**

Não é possível ter um site, app, e-commerce sem um servidor.

Existem 2 tipos:

Estáticos : Físico - Arquivos , softwares e ou banco de dados - Grandes empresas mantêm servidores com redundância em caso de emergência o acesso aos dados não é perdido.

Dinâmico: Se refere aos softwares que estão presentes no servidor físico. Arquivos, aplicações, banco de dados e o mais comum são todos juntos.

Um site, app, dados de um site, banco de dados de um site ou app precisam estar em um servidor.

Web-service

Interface disponível para fazer requisições e consultas em banco de dados inacessíveis de forma segura (correios e governo).



**Stacks**

É um ambiente de ferramentas da empresa que possibilita a implementação do trabalho, um conjunto de banco de dados, LP, tecnologias e softwares, necessários e suficientes para executar um app/sw.

Quando chegamos a uma empresa temos que conhecer sua Stack, ou seja, seus pontos fortes e fracos, capacidades e limitações. Qual tipo de programação usada, estrutura e velocidade de rede, banco de dados, ambiente de desenvolvimento, tipo de segurança digital… Esses pontos que definem os pontos fortes e fracos de nosso app/sw e são importantes para os líderes e desenvolvedores.

Além disso: Estratégia de negócios (quem são nossos concorrentes), maturidade da empresa e programadores, contratações, planos de riscos, aumento da capacidade ( quais os limites da empresa) e uso de dados.

Front-end

Parte da frente, pessoal que faz a interface do App/ sw. Parte visual de site, sw, app, UI, UX, HTML, CSS, jQuery, JS, AJAX, PHP, Bootstrap.

Back-end

Parte de trás, pessoal que pode até fazer um meio de campo entre interface e banco de dados, trabalha com regras de negócios, validações. MySQL, Oracle, Protocolos de comunicação, PHP, Java, node.js.

Full stack

Profissional que sabe trabalhar em todas as camadas das tecnologias de desenvolvimentos front e back.
