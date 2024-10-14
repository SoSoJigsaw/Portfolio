# Portfólio - Felipe Sobral

<details>
<summary>Introdução</summary>
<br>

![Profile](https://github.com/SoSoJigsaw/Portfolio/blob/main/Imagens/profile.jpeg)
  
Sou estudante do 6º semestre de Tecnologia em Banco de Dados na FATEC São José dos Campos, onde tive a oportunidade de aplicar conhecimentos acadêmicos em projetos práticos voltados ao mercado. Através da metodologia de Aprendizado por Projetos Integradores (API), desenvolvi soluções reais para empresas parceiras, aprimorando minhas habilidades técnicas em Python, Java, JavaScript/TypeScript e SQL (Oracle, SQL Server e PostgreSQL), além de fortalecer minha experiência em metodologias ágeis, como SCRUM.

Essas experiências me prepararam para enfrentar desafios do mercado de tecnologia, onde a capacidade de solucionar problemas e a colaboração em equipe são tão valorizadas quanto o domínio técnico.

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/SoSoJigsaw) 
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sosojigsaw/)
</details>


<details>  
  <summary>Meus Principais Conhecimentos</summary>
  <br>
  <details>
  <summary>Python</summary>
    <br>
  Desenvolvo em Python desde 2021. Já utilizei a linguagem nos paradigmas procedural e orientado ao objeto. Utilizei o Python tanto para desenvolvimento web, utilizando para isso o microserviço Flask, quanto para análise e tratamento de dados, utilizando o Pandas e Numpy. Em alguns momentos, utilizei o Python também para automatizar processos, como alimentar o banco de dados com uma rotina usando SQLAlchemy para a conexão, e automatizar o processo de baixar uma base de dados disponibilizado em um site através de um script que usa Selenium para simular as ações em um navegador.

Logo, pode-se dizer que em Python eu tenho domínio na criação de scripts para automação de tarefas, análise de dados e desenvolvimento web:
- **Flask** : Experiência na construção de APIs RESTful e aplicações web escaláveis.
- **Pandas** : Habilidade em manipulação, análise e visualização de grandes volumes de dados.
- **NumPy** : Capacidade de realizar operações matemáticas complexas e manipulação de arrays.
- **Data Cleaning** : Competência na limpeza e transformação de dados para garantir análises precisas.
- **Automação** : Proficiência em automatizar processos de coleta e processamento de dados.
- **Visualização de Dados** : Criação de dashboards interativos para facilitar a interpretação de dados. Criação de visualizações gráficas e não-gráficas desses dados.
</details>


  <details>
  <summary>Java</summary>
<br>
Desenvolvo em Java desde 2022. Utilizei a linguagem principalmente para desenvolver o back-end de aplicações web, utilizando para isso o framework Spring Boot com o auxílio do Hibernate, e aplicações desktop, utilizando para isso o JavaFX.
</details>


<details>
<summary>PL/SQL</summary>
<br>
Utilizo o PL/SQL desde 2022, já tendo contato com comandos DDL, DCL e DML da linguagem. Relacionado a isso, eu já arquitetei a modelagem do banco de dados nos modelos Conceitual, Lógico e Físico. Em se tratando de SGBDs, tive experiência com os bancos Oracle, SQL Server e PostgreSQL, criando tabelas, fazendo o insert de novos dados, criando constraints e regras gerais do banco, e administrando o banco de uma forma geral.
</details>


<details>
<summary>SCRUM</summary>
<br>
Tenho contato com o SCRUM desde o primeiro semestre da faculdade, em 2021, sendo que desde então todos os projetos acadêmicos em que participei utilizaram essa metodologia ágil para o gerenciamento da equipe como requisito. Tive experiência como Scrum Master da equipe, onde assumi o posto de líder responsável por organizar a equipe e buscar soluções para as dificuldades apresentadas. Fui também Product Owner (PO) em duas oportunidades, sendo responsável pelo desenvolvimento do produto ao criar o backlog, e pelo diálogo com o cliente em busca de atender as suas necessidades.
</details>

<details>
<summary>JavaScript e TypeScript</summary>
<br>
Desenvolvo com javascript desde 2022, tendo pleno conhecimento tanto dos frameworks de backend quantos os de frontend.
Compreendo perfeitamente todos os conceitos web como o DOM, e conceitos específicos dos frameworks mais utilizados pelo 
mercado ultimamente, como a modularização, presente por exemplo no vue.js e react.
</details>
</details>

# Projeto Acadêmico 1 (API) – 2º Semestre de 2021

- **Parceiro Aacadêmico:** Própria FATEC

- **Projeto de Monitoramento e Análise de Dados da COVID-19:** Este projeto foi desenvolvido em parceria com os docentes da faculdade ocupando o papel de clientes, com o objetivo de criar uma ferramenta robusta para monitoramento em tempo real dos dados relacionados à pandemia de COVID-19 no estado de São Paulo. A ferramenta abrange a coleta, processamento e visualização de dados, permitindo uma análise detalhada e contínua da evolução da pandemia.
<br>

<details>
<summary>Visão do Projeto</summary>
<br>

![Foto do Projeto](https://raw.githubusercontent.com/SoSoJigsaw/Carcara/main/Sprint%201/picture/2%20new.jpg)
![GIF do Projeto](https://raw.githubusercontent.com/SoSoJigsaw/Carcara/refs/heads/main/Sprint%201/GIFs/PANDEMIA%20ESTRUTURADA%20GIF%203.gif)
![GIF do Projeto 2](https://raw.githubusercontent.com/SoSoJigsaw/Carcara/refs/heads/main/Sprint%201/GIFs/PANDEMIA%20ESTRUTURADA%20GIF%204.gif)
 
- O problema central abordado pelo projeto foi a necessidade de monitoramento contínuo e preciso da pandemia de COVID-19. Com a grande quantidade de dados gerados diariamente, havia uma dificuldade em consolidar essas informações de forma acessível e útil para o cliente, que tinha um interesse por acompanhar o avanço da pandemia em nosso Estado.
- A solução entregue foi uma aplicação web que coleta, processa e visualiza dados da COVID-19 em tempo real. Utilizando tecnologias como Flask, Pandas e diversas bibliotecas Python, a aplicação oferece dashboards interativos que mostram a evolução dos casos, óbitos, vacinação, ocupação de leitos e índices de isolamento social. Além disso, foram implementadas funcionalidades de filtragem de dados por data e município, proporcionando uma análise detalhada e customizada.

[Repositório do Projeto](https://github.com/SoSoJigsaw/Carcara)
</details>

<details>
<summary>Tecnologias adotadas na solução</summary>
<br>
  
- **Python**: Fundamental para o desenvolvimento dos scripts de coleta e processamento de dados. A linguagem foi escolhida por sua simplicidade e poderosas bibliotecas para análise de dados.
- **Selenium**: Utilizado para automações de requests persistentes, onde era necessário fazer o download através de uma requisição web diariamente para atualizar com os dados mais atuais da pandemia. Como o dataset utilizado não dispunha de uma API, havia essa necessidade de reproduzir comandos humanos em um navegador, para assim poder baixar os dados atualizados pela identificação de certos elementos imutáveis na página.
- **Flask**: Utilizado para construir a API e o backend da aplicação web. Flask foi escolhido devido à sua flexibilidade e capacidade de criar aplicações web escaláveis.
- **Pandas**: Essencial para a manipulação e análise dos dados coletados. Pandas permitiu a transformação e limpeza dos dados de forma eficiente.
- **NumPy**: Utilizado para operações matemáticas e manipulação de arrays, complementando as funcionalidades do Pandas.
</details>

<details>
<summary>Contribuições Individuais</summary>
<br>
Minhas principais contribuições para o projeto incluíram:

- **Desenvolvimento de Scripts de Coleta de Dados**:
  Fui responsável por desenvolver scripts automatizados que coletam dados de diversas fontes, como arquivos CSV armazenados localmente e dados disponibilizados online. Utilizando a biblioteca `glob`, automatizei a identificação e leitura dos arquivos mais recentes, garantindo que a aplicação sempre tivesse acesso aos dados mais atualizados.

- **Processamento e Limpeza de Dados**:
  Utilizei `Pandas` para realizar operações de limpeza e transformação dos dados. Isso incluiu a remoção de duplicatas, tratamento de valores ausentes e padronização de formatos de data. A limpeza de dados é crucial para garantir a precisão das análises, e consegui implementar uma pipeline eficiente que trata grandes volumes de dados de forma rápida e precisa.

- **Desenvolvimento da Aplicação Flask**:
  No backend, utilizei o `Flask` para criar uma API RESTful que serve os dados processados para a interface web. Implementei rotas que permitem a consulta de dados filtrados por data e município, e configurei o servidor para suportar múltiplas requisições simultâneas, garantindo a escalabilidade da aplicação.

- **Visualização de Dados**:
  Criei dashboards interativos utilizando bibliotecas como `Matplotlib` e `Plotly`, que permitiram visualizar a evolução dos casos, óbitos, vacinação, ocupação de leitos e índices de isolamento social. As visualizações são atualizadas em tempo real, proporcionando uma ferramenta poderosa para a tomada de decisões informadas.

- **Integração de Múltiplas Fontes de Dados**:
  Combinei dados de diferentes fontes para criar um banco de dados unificado e coerente. Isso envolveu a junção de dataframes, o tratamento de colunas inconsistentes e a agregação de informações complementares. A integração de dados foi fundamental para fornecer uma visão holística da situação da pandemia.
</details>

<details>
<summary>Aprendizados Efetivos</summary>
<br>
  <details>  
  <summary>Hard Skills</summary>
<br>

| Hard Skills           | Descrição                                                                                           |
|-----------------------|-----------------------------------------------------------------------------------------------------|
| **Python**            | Desenvolvimento avançado de scripts e aplicações, especialmente para automação de tarefas e análise de dados. |
| **Pandas**            | Proficiência em operações complexas de limpeza e transformação de dados, manipulação de grandes datasets e geração de análises precisas. |
| **Flask**             | Desenvolvimento de APIs RESTful e backend de aplicações web, incluindo configuração de servidor e gerenciamento de rotas. |
| **NumPy**             | Realização de cálculos matemáticos avançados e manipulação de arrays multidimensionais.               |
| **Data Cleaning**     | Habilidade de identificar e corrigir problemas nos dados, garantindo a integridade e a qualidade das análises. |
| **Visualização de Dados** | Criação de gráficos e dashboards interativos que facilitam a interpretação de grandes volumes de dados. |
  </details>

  <details>
  <summary>Soft Skills</summary>
<br> 
    
| Soft Skills           | Descrição                                                                                           |
|-----------------------|-----------------------------------------------------------------------------------------------------|
| **Comunicação Assertiva**        | Durante o projeto, a comunicação foi essencial para alinhar as expectativas com a equipe. Participei ativamente de reuniões semanais, apresentando o progresso e discutindo desafios técnicos. Minha habilidade de comunicar ideias complexas de maneira clara foi fundamental para o sucesso do projeto. |
| **Gerenciamento de Tempo** | Trabalhei com prazos apertados e múltiplas tarefas simultâneas. Utilizei técnicas de gerenciamento de tempo, como a priorização de tarefas e o uso de listas de verificação, para garantir que todas as entregas fossem concluídas dentro dos prazos estabelecidos. |
| **Pensamento Analítico** | A análise detalhada dos dados foi crucial para identificar padrões e tendências na evolução da pandemia. Utilizei minhas habilidades analíticas para interpretar os dados de forma crítica, proporcionando insights valiosos para a tomada de decisões. |
| **Resiliência**           | Trabalhei com prazos curtos e dados inconsistentes, superando obstáculos para entregar soluções viáveis. |
| **Autonomia**             | Executei grande parte do projeto de forma independente, tomando decisões por conta própria.       |
  </details>
</details>
<br>

# Projeto Acadêmico 2 (API) – 1º Semestre de 2022

- **Parceiro Acadêmico:** Dom Rock

[Logo DomRock]()

Projeto realizado em parceria com a Dom Rock, uma empresa especializada em soluções de Big Data e Inteligência Artificial.
<br>

<details>
<summary>Visão do Projeto</summary>
<br>

![Foto do Projeto](https://github.com/fluffyfatec/Dom_Rock/raw/main/GIT/cabecario2.jpg)
![GIF do Projeto](https://github.com/fluffyfatec/Dom_Rock/raw/main/GIT/prototipo.gif)
  
- O objetivo foi desenvolver uma API robusta e eficiente para a gestão e análise de dados, que fosse capaz de suportar grandes volumes de informações e múltiplos usuários simultaneamente.
- O projeto consistiu na criação de uma API para integração, processamento e gerenciamento de dados provenientes de diversas fontes. A API foi projetada com foco em escalabilidade, segurança e performance, permitindo a geração de relatórios e análises avançadas para suportar a tomada de decisão dos clientes da Dom Rock.

[Repositório do Projeto](https://github.com/fluffyfatec/Dom_Rock)
</details>

<details>
<summary>Tecnologias Utilizadas</summary>
<br>

- **Java:** Escolhida pela sua robustez, portabilidade e vasto ecossistema de bibliotecas e frameworks, facilitando o desenvolvimento de aplicações escaláveis e de alta performance.
- **Spring Boot:** Framework que simplifica o desenvolvimento de aplicações Java, oferecendo configuração automática, suporte a segurança, e fácil gerenciamento de dependências.
- **JavaFX:** Utilizado para a criação de interfaces gráficas, proporcionando uma experiência de usuário rica e interativa.
- **PL/SQL:** Utilizado para a manipulação e gestão dos dados no banco de dados, garantindo eficiência nas operações e integridade dos dados.
- **SCRUM:** Metodologia ágil adotada para gerenciar o projeto de forma iterativa e incremental, promovendo a colaboração e a adaptabilidade da equipe.
</details>

<details>
<summary>Contribuições Pessoais</summary>
<br>

Durante o desenvolvimento deste projeto, minhas contribuições foram diversas e abrangentes, focando em assegurar a entrega de uma solução técnica sólida e funcional.

<details>
<summary>Desenvolvimento do Back-end</summary>
<br>

- **Criação de Serviços RESTful:** Utilizei Java e Spring Boot para desenvolver uma série de serviços RESTful. Esses serviços foram responsáveis por manipular e integrar dados provenientes de diversas fontes, garantindo escalabilidade e alta performance. Implementações específicas incluíram endpoints para criação, leitura, atualização e exclusão de dados (CRUD), bem como serviços para autenticação e autorização de usuários.
- **Implementação de Segurança:** Integrei o Spring Security para implementar medidas robustas de segurança na API. Isso incluiu a configuração de autenticação baseada em tokens JWT (JSON Web Tokens), controle de acesso baseado em roles (papéis) de usuário, e proteção contra ataques comuns como CSRF (Cross- Site Request Forgery).
</details>

<details>
<summary>Integração com Banco de Dados</summary>
<br>
  
- **Modelagem de Dados:** Utilizando PL/SQL, fui responsável por modelar o banco de dados, criando tabelas, views, stored procedures e triggers. A modelagem foi projetada para otimizar o desempenho das consultas e garantir a integridade referencial dos dados.
- **Consultas Eficientes:** Escrevi queries complexas e otimizadas para suportar grandes volumes de dados. Utilizei técnicas como índices, joins eficientes e subconsultas para melhorar a performance das operações de leitura e escrita no banco de dados.
</details>

<details>
<summary>Desenvolvimento de Interfaces Gráficas</summary>
<br>

- **Interfaces com JavaFX:** Desenvolvi interfaces gráficas utilizando JavaFX, permitindo uma interação intuitiva e responsiva com a aplicação. As interfaces incluíam dashboards para visualização de dados, formulários para entrada de informações, e componentes visuais para a navegação na aplicação.
</details>

<details>
<summary>Gestão de Equipe e Metodologias Ágeis</summary>
<br>

- **Product Owner:** Assumi o papel de Product Owner, criando e priorizando o backlog do produto em alinhamento com os requisitos do parceiro acadêmico. Isso envolveu a definição de histórias de usuário, critérios de aceitação e a comunicação constante com os stakeholders para garantir que as entregas atendiam às expectativas.
</details>
</details>

<details>
<summary>Aprendizados Efetivos</summary>
<br>
<details>
<summary>Hard Skills</summary>
<br>
  
| Hard Skills           | Descrição                                                                                           |
|-----------------------|-----------------------------------------------------------------------------------------------------|
| **Java**              | Aprimorei minhas habilidades em Java, focando em práticas avançadas de programação, como a utilização de padrões de design (Design Patterns) para assegurar um código limpo e sustentável. |
| **PL/SQL**            | Aprofundei meus conhecimentos em PL/SQL, escrevendo scripts complexos para manipulação de dados e otimização de consultas. |
| **JavaFX**            | Desenvolvi interfaces gráficas avançadas, utilizando bindings, event handling e customização de componentes visuais para melhorar a experiência do usuário. |
</details>

<details>
<summary>Soft Skills</summary>
<br>

| Soft Skills           | Descrição                                                                                           |
|-----------------------|-----------------------------------------------------------------------------------------------------|
| **Trabalho em Equipe** | Fomentei um ambiente de colaboração, trabalhando efetivamente com colegas de equipe para superar desafios técnicos e cumprir prazos. |
| **Liderança Técnica**             | Coordenei discussões técnicas e orientei a equipe sobre soluções envolvendo integração de sistemas.   |
| **Negociação e Alinhamento**      | Alinhei expectativas e negociei ajustes nos requisitos do projeto, mantendo o progresso sem atritos. |
| **Colaboração**                   | Trabalhei em estreita colaboração com a equipe, contribuindo para revisões de código e conhecimento compartilhado. |
</details>
</details>
<br>

# Projeto Acadêmico 3 (API) – 2º Semestre de 2022

- **Parceiro Acadêmico:** IACIT

[Logo IACIT]()

Projeto feito com a parceria da IACIT, uma empresa de São José dos Campos que presta consultoria meteorológica, sendo que um de seus serviços atuais é fornecer aos clientes relatórios customizados de dados meteorológicos.

<details>
<summary>Visão do projeto</summary>
<br>

![Foto do Projeto](https://github.com/fluffyfatec/Iacit/raw/Sprint-1/GIT/cabecario%20(3).jpg)
![GIF do Projeto](https://github.com/fluffyfatec/Iacit/raw/Sprint-2/GIT/VID-20221009-WA0013%20(2).gif)
  
Como a empresa trabalhava processando muitas informações manualmente, ela acabava por perder tempo, desperdiçando recursos com esse processo. Por isso, a empresa precisava da criação de um sistema que permitisse realizar a importação dos dados meteorológicos, bem como armazená- los em uma base de dados, para posteriormente gerar os relatórios desejados por seus clientes.

Dessa forma, o projeto visava desenvolver uma aplicação web para a empresa que possibilite a automatização desde o download, o processamento dos dados e a persistência dos dados no banco de dados de forma simplificada. Além disso, a aplicação aspirava possibilitar realizar a filtragem desses dados por temperatura, umidade, estações, vento, pressão atmosférica, radiação global e precipitação, além de possibilitar diversas visualizações desses dados. Por fim, a aplicação objetivava a criação de diferentes níveis de usuários juntamente com o painel administrativo, possibilitando a exportação dos relatórios a partir dos dados.

[Repositório do Projeto](https://github.com/fluffyfatec/Iacit)
</details>

<details>
<summary>Tecnologias adotadas na solução</summary>
<br>

- **HTML5 / CSS3 / Javascript (EC6)** : O front- end da aplicação foi desenvolvida em HTML para marcação de hipertexto, CSS3 para estilização da página, e Javascript (EC6) para utilização do AJAX, permitindo assim enviar e receber dados assincronamente do servidor web e evitar o recarregamento da página inteira sem a necessidade de uma nova solicitação, também para criar paginação personalizada, utilizar jsPDF para a geração de PDFs dos gráficos, e enviar variáveis ao servidor por requisições GET através da url da página.
- **Spring Boot** : O back-end da aplicação web foi realizada através do Spring Boot, onde foi definida toda a estrutura do projeto do lado servidor, criando para isso os packages controller, dto, modal, report, repository e service. Os controllers foram criados para gerenciar os endpoints e definir suas lógicas, o dto e o modal foram criados para mapear as entidades do banco de dados na aplicação, o report foi para definir classes que contém a lógica de criação dos PDFs que posteriormente seriam acessados em determinados endpoints dos controllers, o repository foi usado para criar interfaces que estendem o JpaRepository para declarar querys que serão utilizadas na lógica dos controllers, e o service foi usado para conter classes que encapsulam a lógica de negócios da aplicação e para expor serviços que podem ser acessados pelos controllers, como as ações de deletar e atualizar usuário ou a validação do login por um usuário.
- **Python** : O Python foi utilizado para analisar e tratar os dados meteorológicos que seriam utilizados na aplicação, e também para a criação de script de automação do povoamento do banco de dados por esses mesmos dados. Os dados precisaram primeiro serem tratados pelo Pandas para posteriormente serem analisados pela mesma biblioteca, e a criação do script de automação do povoamento foi realizado com o uso da biblioteca SQLAlchemy, que permitiu a utilização de comandos SQL dentro do Python, automatizando o processo de inserts à medida que os dados eram tratados. Foi utilizado o paradigma da orientação ao objeto nesse script, o que reduziu a reutilização de código e permitiu o processamento progressivo de toda a lógica do script ao permitir o acesso de uma classe às demais classes.
- **PostgreSQL** : O PostgreSQL foi o SGBD escolhido para a criação do banco de dados exigido no projeto. Através dele, foi feita toda a modelagem e administração do banco, que foi responsável por armazenar todos os dados meteorológicos que foram utilizados para o dashboard da aplicação e para o CRUD de usuários. Além da criação das tabelas e constraints, e inserts realizados, a aplicação necessitou do uso de views que limitavam o acesso aos dados pelo usuário final, triggers para permitir a criação de uma tabela de auditoria que faz um controle de todas as modificações realizadas por um usuário nas tabelas de interesse, e a criação de índices para as tabelas para melhorar o desempenho de consultas, redução de tempo de resposta, otimização da utilização de memória e, por fim, trazer melhorias em operações de junção, que foram muito utilizadas no projeto.
</details>

<details>
<summary>Contribuições Individuais</summary>
<br>

Em grande parte do projeto eu trabalhei no back-end da aplicação, e em alguns momentos ajudei também no front-end.

<details>
<summary>Script de Automação do povoamento do banco</summary>
<br>

No back-end, fui responsável por:

- criar um script no Python que recebia os dados meteorológicos de uma base de dados disponibilizado em um servidor web através de um request, toda vez que o script era executado ele fazia o request e verificava se havia novos dados para serem baixados. Se houvesse novos dados, ele os baixava para um diretório reservado do projeto.

- O script acessava em loop todos os dados baixados no diretório e fazia o tratamento deles utilizando Pandas, mudando seus tipos e formatação de forma que depois de tratados estivessem em um formato adequado à lógica das tabelas do banco de dados criado.

- Assim que terminava o tratamento desses dados, os dataframes eram enviados à outro método que fazia a rotina de enviar esses dados ao banco de dados, fazendo inserts nas tabelas devidas, usando para isso o SQLAlchemy para criar a conexão com o banco e utilizar comandos de SQL puro dentro do Python. Essa rotina incluía tratamento de erros, evitando a duplicação de dados no banco, redundância, e quebra de constraints de chave primária. O script foi otimizado, permitindo que a tentativa de envio de dados ao banco, ou seja, a execução do comando SQL, só acontecesse caso o dataframe trouxesse novos dados.

[Veja mais detalhes](https://github.com/SoSoJigsaw/Portfolio/blob/main/Detalhes%20das%20Contribui%C3%A7%C3%B5es/ScriptDeAutomacao.md)
</details>

<details>
<summary>Geração de Relatórios</summary>
<br>

[Veja mais detalhes](https://github.com/SoSoJigsaw/Portfolio/blob/main/Detalhes%20das%20Contribui%C3%A7%C3%B5es/RelatoriosPDF.md)
</details>

<details>
<summary>Geração de PDFs dos gráficos</summary>
<br>

No front- end, eu ajudei em partes na estilização das páginas. No entanto, fui responsável por criar o método que gerava o PDF dos gráficos. Para isso:

- eu usei uma biblioteca do JavaScript chamada jsPDF, que estilizou o PDF e incluiu o gráfico nele, gráfico esse que foi convertido de elemento canvas HTML em um arquivo de imagem PNG e possibilitou dentro do mesmo método o download em PDF

[Veja mais detalhes](https://github.com/SoSoJigsaw/Portfolio/blob/main/Detalhes%20das%20Contribui%C3%A7%C3%B5es/PDFsGraficos.md)
</details>
</details>

<details>
<summary>Aprendizados Efetivos</summary>
<br>
<details>
<summary>Hard Skills</summary>
<br>

| Hard Skills                                      | Descrição                                                                                           |
|--------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Interação e persistência de dados com o banco de dados** | Desenvolvi habilidades na escrita de código para interagir com banco de dados, considerando questões de segurança, integridade de dados e boas práticas, como o uso de transações e validação de dados. Utilizei a biblioteca SQLAlchemy no Python para realizar essas operações. |
| **Paradigma da Programação Orientada a Objetos (POO) em Python** | Ganhei autonomia no uso de POO em Python, aplicando conceitos como encapsulamento, herança e polimorfismo. Reduzi redundâncias no código utilizando a reusabilidade de métodos e parâmetros. |
| **Manipulação de arquivos e requisições no Python** | Dominei a manipulação de arquivos e diretórios no Python com os módulos "os", "zipfile", "shutil", e utilizei o "requests" para fazer requisições HTTP. Manipulei dados em formato CSV com o "pandas". |
| **Geração de logs e tratamento de exceções em Python** | Adquiri autonomia para gerar logs e tratar exceções em Python, utilizando `try`, `except` e `raise` para melhorar a depuração e o controle de erros no código. |
| **Aprimoramento no tratamento e análise de dados usando Pandas** | Aperfeiçoei habilidades em manipulação e transformação de dados com Pandas, realizando tarefas como renomeação de colunas, tratamento de valores nulos e conversão de tipos de dados. |
| **Manipulação de PDFs através do Java**          | Desenvolvi habilidades na criação e manipulação de PDFs com Java, utilizando loops e listas de objetos para povoar documentos com dados variáveis. |
| **Utilização da arquitetura MVC no SpringBoot**  | Aprendi a criar métodos de requisição no Controller do Spring, utilizando anotações como `@GetMapping` e `@PathVariable`, e construí respostas HTTP com `ResponseEntity`. |
| **Manipulação de PDFs com JavaScript e HTML canvas** | Criei e manipulei PDFs com JavaScript, convertendo elementos HTML canvas em PNG e inserindo-os nos documentos gerados. |
</details>

<details>
<summary>Soft Skills</summary>
<br>
  
| Soft Skills                        | Descrição                                                                                           |
|------------------------------------|-----------------------------------------------------------------------------------------------------|
| **Organização e Priorização**      | Organizei tarefas críticas para garantir a conclusão do projeto dentro do prazo estipulado.          |
| **Proatividade**                   | Identifiquei melhorias e tomei a iniciativa de implementá-las, otimizando processos e scripts.       |
| **Autogestão**                     | Gerenciei minhas próprias responsabilidades e prazos, entregando soluções sem necessidade de supervisão constante. |
| **Atenção aos Detalhes**           | Garanti a integridade dos dados processados, identificando possíveis inconsistências durante a automação. |
</details>
</details>
<br>

# Projeto Acadêmico 4 (API) – 1º Semestre de 2023

- **Parceiro Acadêmico:** Embraer

[Logo Embraer]()

Projeto realizado em parceria com a Embraer, uma empresa especializada em soluções de aeronáutica, defesa e segurança, proporcionando inovações tecnológicas para o setor aeroespacial.

<details>
<summary>Visão do Projeto</summary>
<br>

![Foto do Projeto](https://github.com/fluffyfatec/Projeto-Integrador-Embraer/blob/main/GIT/head.jpeg)
![Gif do Projeto](https://github.com/fluffyfatec/Projeto-Integrador-Embraer/raw/main/GIT/mockup-web.gif)

- O objetivo foi desenvolver uma aplicação robusta e eficiente para a integração e gerenciamento de dados de aeronaves, contribuindo para a otimização das operações e manutenção.
- O projeto consistiu na criação de uma API para integração, processamento e gerenciamento de dados provenientes de sistemas de monitoramento de aeronaves, manutenção e operações. A API foi projetada com foco em escalabilidade, segurança e performance, permitindo a geração de relatórios detalhados e visualização de dados em tempo real.

[Repositório do Projeto](https://github.com/fluffyfatec/Projeto-Integrador-Embraer)
</details>

<details>
<summary>Tecnologias Utilizadas</summary>
<br>

- **Vue.js:** Escolhido para a construção das interfaces de usuário devido à sua reatividade e facilidade de integração com outras bibliotecas, além de sua simplicidade e eficiência na criação de interfaces reativas e componentes reutilizáveis.
- **TypeScript:** Utilizado para adicionar tipagem estática ao JavaScript, melhorando a qualidade do código e facilitando a manutenção.
- **Pinia:** Gerenciador de estado escolhido por sua simplicidade e integração com Vue.js.
- **Vite:** Ferramenta de build moderna e rápida, utilizada para otimizar o desenvolvimento e a construção do projeto.
- **Axios:** Biblioteca para realizar requisições HTTP, essencial para comunicação entre o frontend e backend.
- **Spring Boot:** Framework utilizado para o desenvolvimento do backend devido à sua robustez e suporte para a criação de APIs RESTful.
- **SCRUM:** Metodologia ágil adotada para gerenciar o projeto de forma iterativa e incremental, promovendo a colaboração e a adaptabilidade da equipe.
</details>

<details>
<summary>Contribuições Pessoais</summary>
<br>

Durante o desenvolvimento deste projeto, minhas contribuições foram diversas e abrangentes, focando em várias áreas críticas do projeto.

<details>
<summary>Desenvolvimento do Back-end</summary>
<br>

- **Criação de Serviços RESTful:** Utilizei Spring Boot para desenvolver uma série de serviços RESTful. Esses serviços foram responsáveis por manipular e integrar dados provenientes de diversas fontes, garantindo escalabilidade e alta performance. Implementações específicas incluíram endpoints para criação, leitura, atualização e exclusão de dados (CRUD), bem como serviços para autenticação e autorização de usuários.
- **Implementação de Segurança:** Integrei o Spring Security para implementar medidas robustas de segurança na API. Isso incluiu a configuração de autenticação baseada em tokens JWT (JSON Web Tokens), controle de acesso baseado em roles (papéis) de usuário, e proteção contra ataques comuns como CSRF (Cross-Site Request Forgery).
- **Spring Boot:** Escolhido por sua capacidade de criar aplicações standalone de produção e seu ecossistema abrangente.
</details>

<details>
<summary>Integração com Banco de Dados</summary>
<br>

- **Mapeamento e manipulação de Dados do banco:** Utilizando JPA, fui responsável pelo mapeamento e manipulação do banco de dados através da API SpringBoot. O uso do JPA foi projetado para otimizar o desempenho das consultas e da persistência dos dados através da API, e também garantir a integridade referencial destes mesmos dados.
- **Hibernate:** Utilizado para facilitar a interação com o banco de dados, reduzindo o código boilerplate e aumentando a produtividade.
</details>

<details>
<summary>Desenvolvimento de Interfaces Gráficas</summary>
<br>

- **Interfaces com Vue.js:** Desenvolvi interfaces gráficas utilizando Vue.js, permitindo uma interação intuitiva e responsiva com a aplicação. As interfaces incluíam dashboards para visualização de dados, formulários para entrada de informações, e componentes visuais para a navegação na aplicação.
</details>

<details>
<summary>Gestão de Equipe e Metodologias Ágeis</summary>
<br>

- **Product Owner:** Assumi o papel de Product Owner, criando e priorizando o backlog do produto, garantindo que a equipe estivesse focada nas tarefas de maior valor para o cliente e alinhada com os objetivos do projeto.
</details>
</details>

<details>
<summary>Aprendizados Efetivos</summary>
<br>
<details>
<summary>Hard Skills</summary>
<br>

| Hard Skills           | Descrição                                                                                           |
|-----------------------|-----------------------------------------------------------------------------------------------------|
| **Vue.js**            | Aprimorei minhas habilidades em Vue.js, focando em práticas avançadas de programação, como a utilização de mixins, directives e componentes dinâmicos. |
| **Spring Boot**       | Dominei o desenvolvimento de APIs RESTful com Spring Boot, incluindo o uso de Spring Security, Spring Data JPA, Hibernate e testes de integração. |
| **TypeScript**        | Aprofundei meus conhecimentos em TypeScript, escrevendo scripts complexos para garantir a robustez e a segurança do código. |
</details>

<details>
<summary>Soft Skills</summary>
<br>
  
| Soft Skills                      | Descrição                                                                                           |
|----------------------------------|-----------------------------------------------------------------------------------------------------|
| **Gerenciamento de Stakeholders** | Mantive comunicação constante com a Embraer, ajustando as entregas de acordo com suas expectativas.  |
| **Adaptação a Padrões Externos**  | Adaptei-me rapidamente aos padrões técnicos e processos exigidos pela Embraer para atender suas normas. |
| **Resolução de Conflitos**        | Mediei conflitos entre requisitos e prazos, garantindo que o projeto permanecesse dentro do cronograma. |
| **Trabalho Sob Pressão**          | Trabalhei sob prazos rigorosos e exigências altas, mantendo a qualidade e entregando dentro do prazo. |
| **Foco em Resultados**            | Concentrei-me na entrega de um sistema que atendesse às expectativas da Embraer e fosse funcional dentro do prazo. |
</details>
</details>

