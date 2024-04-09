## Teste Conceitual: Solução de Problema

### Problema a Resolver:

Suponha que a plataforma SpiritShop está enfrentando um problema: apesar do site
ser responsivo, muitos usuários têm relatado que a experiência de uso no mobile é
inferior, principalmente devido a tempos de carregamento lentos e dificuldades na
interação com elementos da UI em telas menores.

### Questões:

1. Como você diagnosticaria e identificaria as causas específicas desses
   problemas de performance e usabilidade no mobile?

2. Que estratégias e ferramentas você utilizaria para otimizar a performance do
   site no mobile?

3. Como você melhoraria a usabilidade da interface para usuários de
   dispositivos móveis, garantindo que a experiência seja tão boa quanto no
   desktop?

### Respostas:

1 - Para realizar o diagnóstico das causas específicas para os problemas de performance e usabilidade, eu seguiria três passos:
1 - Coleta e análise de feedback de usuários. Com a análise dessas informações, poderiamos definir quais problemas são prioridade para serem solucionadas. Assim, agiriamos onde há maior desconforto na usabilidade das aplicações.
2 - Avaliaria performance através de softwares especializados para isso. Assim, as informações geradas por essas ferramentas podem nos guiar para soluções mais específicas. Um exemplo de ferramenta a ser usada é o Google Analytics.
3 - Testaria a usabilidade, focando nos pontos levantados através de feedbacks de usuários em vários dispositivos, para levantar pontos de convergência e divergência nos problemas.

2 - Uma das coisas que mais influencia em perda de eficiência são imagens muito pesadas, por isso, adaptaria as imagens para um formato mais "web Friendly" como .webp. Revisaria e refatoraria os códigos, focando em minimizar arquivos JS e CSS e Revisaria todas as requisições realizadas para o backend, com foco de reutilizar dados e diminuir a quantidade de requisições realizadas do Frontend para o Backend.

3 - Realizar adaptações de layout para telas menores, utilizando algum padrão de código focado para dispositivos móveis, como o Mobile Firts, onde você desenvolve, primeiro, para telas móveis e depois para telas maiores. Analisaria as interações do usuários com a disposição dos elementos nas páginas, por exemplo, analisaria o gesto físico que o usuário realiza para acionar um botão, ou realizar o scroll nas páginas e assim por diante. Usando essas abordagens, sempre focando na acessibilidade, através de cores com contraste e fontes com tamanhos adequados.

### Teste Aberto:

### Respostas

1 - Para garantir a acessibilidade web, é imprecindível a implementação de tecnoligas assistivas, como leitores de tela e softwares de receonhecimento de voz. Devemos adicionar textos alternativos nas imagens, títulos e descrições que remetam de forma real o conteúdo presente nesses elementos. Adotar um estrutura clara e organizada, através de marcações semânticas, nagevação simples e consistente. Adotar fontes e cores com contrastes e tamanhos que facilitam a visualização do conteúdo e Garantir uma usabilidade simples, através de focos e acionamento do teclados nos elementos corretos, na ordem correta.

2 - Para melhorar a performace no Frontend, devemos modificar o frontend e o backend. No frontend, podemos minimizar e compactar arquivos JS e CSS. Otimizar imagens, adotar estratégias de memória cache no navegador, para garantir a resposta de dados mais rápida para o usuários, adotar o lazy-loading para carregar imagens e vídeos. Diminuir o número de requisições HTTP e se possível, implementar técnicas de SSR, ou Server-Side Rendering. No Backend, devemos otimizar as consultas no banco de dados, de modo a diminuir o tempo das respostas, adotar estratégias de cache no servidor, adotando camadas de respostas mais rápidas através de ferramentas como Redis. Distribuir conteudo estáticos para servidores mais próximos do usuário e adotar estratégias de load balancing e scale de infra.

3 - Para garantir uma ótima experiência em dispositivos diferentes, podemos adotar estratégias de desenvolvimento como Mobile First, focando em layout flexível, imagens responsivas, tipografias com tamanhos e contéudo simples e práticos.

4 - Para garantir a segurança no frontend, é necessário validar as entradas de dados, codificar a saída de dados, para evitar o XSS, implementar requisições HTTPS e implementar Tokens CSRF para evitar falsificação de requisições.

5 - Estratégias de SEO são as principais ferramentas para melhorar a usabilidade e facilitar o acesso às nossas aplicações. Adotar palavras chaves relevantes para o conteúdo da pagina, usar HTML Semantico, para uma estrutura mais clara e simples das páginas, otimizar formato de imagens para carregamento mais rápido, garantir acessibilidade, através de textos alternativos e ferramentar de acessibilidade e outros.

6 - Existem vantagens e desvantagens para todas abordagens de códigos.

#### As SPAs e frameworks de desenvolvimento tem seus prós e contras:

#### Prós:

- Desenvolvimento mais veloz e eficiente
- Código mais organizado e modular
- Ampla comunidade de desenvolvedores e recursos

#### Contras:

- Curva de aprendizado maior
- Aumento de tamanho nos códigos
- possibilidade de problemas de dependencias e compatibilidade entre ferramentas externas

#### Vanilla JS

#### Prós:

- Código mais leve e performático
- Maior controle sobre o código
- Menor dependencia de ferramentas externas

#### Contras:

- Desenvolvimento mais lento, tabalhoso e verboso
- Maior dificuldade de organizar e modularizar o código

A escolha ideal, deve levar em consideração o escopo do projeto e o conforto ddos desenvolvedores.

7 - O gerenciamento de estado global nas SPAs são cruciais para manter o controle das informações e garantir melhor usabilidade dos usuários. Para isso, podemos usar algumas ferramentas, como Context API do react, Redux, VueX, MobS, Saga entre outras. A ferramenta ideal depende do escopo do projeto e do conforto dos desenvolvedores.

8 - O processo de desenvolvimento e deploy de uma aplicação web deve seguir alguns passos, como:
1 - Planejamento, onde há a definição de requisitos, objetivos e funcionalidade da aplicação
2 - Desenvolvimento que inclui a criação de prototipos das interfaces de usuários e definicação de regras de negócios.
3 - Teste, criação de testes para garantir uma escalabilidade segura dos códigos desenvolvidos
4 - deploy
5 - Manutenção

9 - A alteração de requisitos nunca é algo bom, pois geralmente, vem cercado de retrabalho. Mas isso é impossível de prever e evitar, portanto, busco entender o que motivou a necessidade das mudanças, para melhorar o planejamento dos próximos projetos e buscar a melhor maneira de realizar as mudanças necessárias de forma eficas e ágil.
