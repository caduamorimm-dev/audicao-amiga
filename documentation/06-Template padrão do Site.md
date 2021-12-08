# Template padrão do site e Funcionalidades do Sistema

O template das telas do site criado até o momento contém os seguintes layouts:

- Tela Home-Page (item 6.1)
- Tela de Login (item 6.2)
- Tela de Cadastro (item 6.3)
- Tela Vídeos Traduzidos (item 6.4)
- Tela Sobre o Projeto (item 6.5)
- Tela Conheça os Desenvolvedores (item 6.6)
- Tela Formulário (item 6.7)
- Tela Player dos Vídeos Traduzidos (item 6.8)

Alusivo às funcionalidades do sistema, apresentamos o print das telas desenvolvidas pelo grupo, assim como uma breve descrição, os requisitos atendidos e os artefatos da funcionalidade. A estrutura de dados das telas pode ser encontrada na página do projeto no GitHub, pelo link: https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2021-2-e1-proj-web-t7-ads_2021_02_e1_grupo_05_audicao_amiga.

No tocante às instruções de acesso, os passos são descritos a seguir:
1. Abra o browser e informe o link disponibilizado logo acima.
2. Execute o download do arquivo do projeto ou faça sua clonagem no GitHub.
3. Descompacte o arquivo.
4. Execute a pasta, abrindo-a através do Visual Studio Code (VSC).
5. Conseguirá visualizar a URL através dos arquivos de formato HTML pelo Live Server localizado no próprio VSC.

No que tange à responsividade, optamos por seguir o padrão do Bootstrap e/ou Media Queries. De acordo com Wikipédia (10/2021), “Bootstrap é um framework web com código-fonte aberto para desenvolvimento de componentes de interface e front-end para sites e aplicações web usando HTML, CSS e JavaScript, baseado em modelos de design para a tipografia, melhorando a experiência do usuário em um site amigável e responsivo.” Se referindo ao Media Queries, se trata de um recurso do CSS 3 “que permite a renderização de conteúdo para se adaptar a diferentes condições, como a resolução da tela (por exemplo, tamanho da tela do celular e do desktop). Ele se tornou um padrão recomendado pelo W3C em junho de 2012, e é uma tecnologia fundamental para o design responsivo da Web (RWD).” (WIKIPEDIA, 11/2021)

## Tela Home-Page

Apresenta a tela principal com a logo do sistema, um botão de redirecionamento e uma frase de efeito visando trazer conforto ao usuário.

Figura 14 - Tela Home-Page<br>
![image](https://user-images.githubusercontent.com/89549220/144342087-85246229-2ae8-4504-be6f-eb38a8653934.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- index.html
- login.html
- home.css
- grid.css
- normalize.css
- reset.css
- style.css
- icon.ico
- AA.png

## Tela de Login

Tela de autenticação, responsável pela solicitação de um login e senha para cada usuário. Fazendo com que o controle seja decisivo, não correndo risco de usuários utilizarem as contas um dos outros.

Figura 15 - Tela de Login<br>
![image](https://user-images.githubusercontent.com/89549220/144342390-e2ff3844-a6fa-43cb-87c0-ea7fa161650d.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-10: Deve ser possível ao usuário solicitar a redefinição de sua senha, informando o e-mail cadastrado.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- login.html
- cadastro.html
- videostraduzidos.html
- style.css
- cadastro.css
- icon.ico
- Grupo25.png

## Tela de Cadastro

Essa tela representa o formulário de cadastro para acesso às funcionalidades do site. 

Figura 16 - Tela de Cadastro<br>
![image](https://user-images.githubusercontent.com/89549220/144342605-44858b89-46ae-463b-a540-3781407419c8.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-09: O sistema deve permitir o cadastro de novos usuários (deficiente auditivo, surdo, intérprete voluntário), realizando a validação através de um e-mail de confirmação.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- cadastro.html
- home.html
- login.html
- cadastro.css
- style.css
- cadastro.js
- icon.ico
- Grupo25.png

## Tela Vídeos Traduzidos

Nessa tela é possível o acesso aos vídeos traduzidos e separados por categorias, assim como solicitar tradução (para o deficiente auditivo ou surdo) e atender solicitação (para o voluntário intérprete). É possível também pesquisar um vídeo de interesse e/ou acessar as páginas de sobre o projeto e de suporte.

Figura 17 - Tela Vídeos Traduzidos<br>
![image](https://user-images.githubusercontent.com/89549220/144342776-7e9f66b5-838d-4fb8-a145-7e29ca5efbb8.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-01: Permitir que o usuário tenha acesso aos vídeos anteriormente traduzidos por um voluntário, através da plataforma.
- RF-02: Oferecer a possibilidade do usuário deficiente auditivo ou surdo de solicitar a tradução de um vídeo, encaminhando o link do mesmo através de um formulário.
- RF-03: Disponibilizar os vídeos traduzidos separados por categorias personalizadas, para uma melhor interação do usuário.
- RF-06: O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um vídeo específico e fácil acesso aos vídeos já viabilizados na plataforma.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- videostraduzidos.html
- formulario.html
- sobre.html
- conhecadesenvolvedores.html
- playervideostraduzidos.html
- videostraduzidos.css
- normalize.css
- reset.css
- icon.ico
- LogoProjetoFINAL-200.png
- video.png
- LogoProjetoFINAL-200.png

## Tela Sobre o Projeto

Tela que projeta uma breve explicação do projeto Audição Amiga, bem como os valores considerados pelo grupo para montar o projeto. É apresentável também um botão para voltar aos vídeos traduzidos e um botão para acesso à tela de conheça os desenvolvedores.

Figura 18 - Tela Sobre o Projeto<br>
![image](https://user-images.githubusercontent.com/89549220/144342972-7894aa84-529c-4911-b67d-4605ae319c0c.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-08: O site deve permitir visualizar as informações sobre a origem do projeto e dos desenvolvedores do site.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- sobre.html
- videostraduzidos.html
- sobre.css
- icon.ico
- projeto1.png
- projeto2.png
- LogoProjetoFINAL-100.png

## Tela Conheça os Desenvolvedores

Tela que projeta uma breve descrição dos desenvolvedores do projeto, sendo também apresentado um botão para voltar aos vídeos traduzidos e voltar à tela sobre o projeto.

Figura 19 - Tela Conheça os Desenvolvedores<br>
![image](https://user-images.githubusercontent.com/89549220/144343090-41fce564-7f3d-4e15-84b2-fcb813265186.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-07: O site deve permitir visualizar as informações para contato e dúvidas, dos desenvolvedores do site.
- RF-08: O site deve permitir visualizar as informações sobre a origem do projeto e dos desenvolvedores do site.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- conhecadesenvolvedores.html
- videostraduzidos.html
- conhecadesenvolvedores.css
- icon.ico
- Screenshot_1.png
- favicon-32x32.png
- 174857.png
- instagram.png
- AirBrush_20210915213104.png
- 16296438282142.png
- Screenshot_3.png
- IMG-20210910-WA00542.png
- LogoProjetoFINAL-100.png

## Tela Formulário

Nessa tela está disponível o formulário onde o usuário irá especificar nome, e-mail e um campo de mensagem para enviar o link do vídeo desejado para a tradução. Conta-se também com um botão para retornar aos vídeos traduzidos. 

Figura 20 - Tela Formulário<br>
![image](https://user-images.githubusercontent.com/89549220/144343230-44ece933-44cd-4c02-90ba-73e3df6246d2.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-02: Oferecer a possibilidade do usuário deficiente auditivo ou surdo de solicitar a tradução de um vídeo, encaminhando o link do mesmo através de um formulário.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- formulario.html
- videostraduzidos.html
- formulario.css
- style.css
- icon.ico
- LogoProjetoFINAL-100.png

## Tela Player dos Vídeos Traduzidos

Tela que projeta o vídeo escolhido pelo usuário com sua respectiva tradução, e o botão de voltar à tela principal com todos os vídeos disponibilizados.

Figura 21 - Tela Player Vídeos Traduzidos<br>
![image](https://user-images.githubusercontent.com/89549220/144343351-f7a89337-9254-4f20-9807-c65e9397b24f.png)<br>
Fonte: Elaborado pelos autores

### Requisitos Atendidos

- RF-06: O site deve oferecer uma funcionalidade de filtro/pesquisa para permitir ao usuário localizar um vídeo específico e fácil acesso aos vídeos já viabilizados na plataforma.
- RNF-01: O sistema deve ser multiplataforma, possibilitando seu uso em dispositivos com Windows, Linux e macOS.
- RNF-02: O site deve ter bom nível de contraste entre os elementos da tela em conformidade.
- RNF-03: Site compatível com os principais navegadores do mercado (Google Chrome, Mozilla Firefox, Microsoft Edge).
- RNF-08: O desenvolvimento deve ser utilizando nas linguagens de Front-End (HTML, CSS e JavaScript).

### Artefatos da Funcionalidade

- playervideostraduzidos.html
- videostraduzidos.html
- playervideostraduzidos.css
- icon.ico
- ofc.jpeg
