# Arquitetura da Solução

Apresentamos os detalhes técnicos da arquitetura da solução criada pelo grupo, portando-se dos componentes e do ambiente de hospedagem que fazem parte da solução.

## Diagrama de Componentes

Compreendemos nessa seção os componentes que fazem parte da arquitetura da solução, consoante figura adiante.

Figura 13 - Arquitetura da Solução<br>
![image](https://user-images.githubusercontent.com/91231500/144343764-ad1764fb-985e-406c-a77d-b08ac62bf651.png)<br>
Fonte: Elaborado pelos autores

A arquitetura da solução concretizada conta com os seguintes módulos:

●	Navegador - Interface básica do sistema

   ●	Páginas Web - Conjunto de arquivos HTML5, CSS3, JavaScript, Bootstrap e imagens que efetivam as funcionalidades do sistema.

   ● Local Storage - armazenamento mantido no Navegador, onde são empreendidos bancos de dados baseados em JSON (JavaScript Object Notation).

      * Login - seção de acesso à conta do usuário;

      * Formulários - registro de informações dos usuários, especialmente no que tange aos dados pessoais;

      * Vídeos - lista de vídeos disponibilizados para tradução e de vídeos cedidos para acesso do deficiente
 
●	Hospedagem - local na Internet onde as páginas serão mantidas e conectadas pelo navegador.

●	API (Interface de Programação de Aplicação) - plataformas que permitem o acesso aos vídeos exibidos no site.

## Hospedagem

Utilizaremos a plataforma do GitHub Pages como ambiente de hospedagem do site do projeto, e o mesmo será mantido no ambiente da URL https://caduamorim.github.io/audicaoamiga/

A publicação do site no GitHub Pages será realizada através da submissão do projeto (push) via Git para o repositório remoto que estará disponível no endereço https://caduamorim.github.io/audicaoamiga/
