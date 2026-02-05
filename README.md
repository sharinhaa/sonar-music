SONAR MUSIC 
Este projeto consiste no desenvolvimento do layout de um site de música, criado com a intenção de transmitir modernidade, dinamismo e uma boa vibe ao usuário. A proposta foi construir uma interface visualmente agradável e intuitiva, capaz de proporcionar uma experiência fluida e envolvente durante a navegação, aproximando o usuário da música de forma simples e confortável.
O layout foi inspirado em plataformas de streaming musical amplamente conhecidas, como o Spotify, que serviram como referência principalmente em relação à organização dos elementos, hierarquia visual e estilo moderno. A ideia não foi reproduzir esses aplicativos, mas utilizar seus conceitos de design para criar uma identidade própria, alinhada às tendências atuais do design digital.
As escolhas de cores, tipografia e disposição dos elementos foram pensadas para reforçar a sensação de modernidade e criar um ambiente visual equilibrado, evitando excessos e priorizando a clareza das informações. A navegação foi projetada para ser prática e intuitiva, permitindo que o usuário encontre músicas, playlists e conteúdos de forma rápida e natural.
Dessa forma, o projeto busca oferecer não apenas um layout esteticamente agradável, mas também uma experiência positiva e envolvente, transmitindo uma atmosfera atual e leve, onde o usuário se sinta à vontade para explorar, descobrir e se conectar com a música.

USO DE FLEXBOX
1. Layout principal (sidebar + conteúdo)
A estrutura geral da página utiliza display: flex para posicionar a sidebar ao lado do conteúdo principal, garantindo alinhamento correto e adaptação em diferentes larguras de tela.

2. Menu da sidebar
O menu lateral utiliza Flexbox em coluna (flex-direction: column) para organizar os links de navegação de forma vertical e espaçada.

3. Playlists recomendadas
A seção de playlists recomendadas utiliza Flexbox para alinhar os cards lado a lado, com gap para espaçamento e overflow-x: auto para permitir rolagem horizontal, simulando o comportamento de aplicativos reais de música.

4. Seção de músicas/favoritos
Os cards de músicas e favoritos também usam Flexbox para manter alinhamento horizontal, controle de largura (flex-shrink: 0) e responsividade, garantindo consistência visual.

BREAKPOINTS UTILIZADOS 
Para garantir que o site funcione bem em diferentes dispositivos, foram utilizados breakpoints em CSS:

* Até 900px - Utilizado para telas menores como tablets e celulares:
Sidebar é ocultada para priorizar o conteúdo
Barra de busca se adapta melhor à largura disponível
Layout mantém usabilidade sem poluição visual

Além disso, a responsividade também foi garantida por:
Uso de flex-wrap
Cards com largura fixa e rolagem horizontal
Imagens com object-fit: cover

O projeto aplica conceitos fundamentais de HTML semântico, Flexbox, CSS responsivo e design de interfaces modernas, resultando em um layout funcional, organizado e com aparência de aplicação real de streaming de música.
