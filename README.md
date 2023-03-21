### Projeto interdiciplinar
##### Socieloo
Integrantes do grupo Grupo  

- <a href = "https://github.com/ademiralves"> Ademir Alves </a>
- <a href = "https://github.com/Aryel15"> Aryel Anne </a>
- <a href = "https://github.com/BiaJL"> Bianca Jesus </a>
- <a href = "https://github.com/DiogoLCarvalho"> Diogo Carvalho </a>
- <a href = "https://github.com/FernandaSena07"> Fernanda Sena </a>
- <a href = "https://github.com/leocaje"> Leonardo Cajé</a>

### Fatec ZL - Centro Paula Souza 
### # Disciplina - Programação Web III 
Grupo X 
- Joaquim da Silva Xavier 
- Jose Bonifacio 
- Isabel Cristina Leopoldina 
##### Processo de Desenvolvimento de Software - PDS
> O PDS segue uma abordagem interativa incremental adaptada do Scrum. Cada interação tem uma definição de pronto estabelecida com objetivo de controlar a qualidade. 
##### Estudo de Caso – SOCIELOO
> No contexto do projeto interdisciplinar o estudo de caso tem como objetivo desenvolver e implantar um site centralizador de ONGs, instituições e projetos sociais da cidade de São Paulo, com o propósito de divulgá-las a possíveis doadores e voluntários e criar, assim, um ELO entre ONGs e a sociedade. O diferencial do site é a maior flexibilidade do usuário para a escolha de Projetos sociais com a localização e segmento de sua preferência, podendo favoritar, analisar e avaliar cada projeto.
##### Product Backlog 
- RU01 - Compras - Registra e acompanha os processos de compras na organização, prevê a entrega programada de pedidos de compra 
- RU02 - Recebimento - Registra, controla e informa sobre a entrada de mercadorias e integra as informações dos dados da nota fiscal de entrada com o estoque 
- RU03 - Vendas – Registra e acompanha as vendas mantendo as informações integradas com o controle de estoque. 
##### Sprint Backlog 
> Cada requisito tem um identificador único de maneira que seja possível rastrear a necessidade do cliente com a implementação do software. 
> 
| Identificador | Descrição | Prioridade | 
| ------------ | ------------------------------------------------------------------------ | ------| 
| REQ01 – Cadastrar ONGs/Instituições/Projetos Sociais | Como – ONG/Instituição/Projeto Social, Eu quero – Cadastrar no site a ação social no site, De maneira que – Seja possível criar um perfil próprio para o projeto (Página de ONG)| Alta |
| REQ02 – Consultar ONGs/Instituições/Projetos Sociais | Como – Usuário, Eu quero – Consultar uma ONG´s/Instituições/Projetos Sociais, De maneira que – Seja possível obter informações sobre a ONG´s/Instituições/Projetos Sociais como descrição textual, sua história, imagens, informações de contato e de doação e mapa de localização. | Alta |
| REQ03 – Atualizar ONGs/Instituições/Projetos Sociais | Como – ONG´s/Instituições/Projetos Sociais, Eu quero – Alterar os dados da ONG/Instituição/Projeto Social, De maneira que – Seja possível atualizar informações de ONG/Instituição/Projeto Social, nos casos de mudanças de endereço, informações de contato, imagens e localização. | Média |
| REQ04 – Excluir ONGs/Instituições/Projetos Sociais | Como – ONG/Instituição/Projeto Social OU Moderador/Administrador, Eu quero (se ONG/Instituição/Projeto Social) – Excluir meu cadastro e minha Página de ONG do site, De maneira que – Meus dados não sejam mais divulgados pelo site. Eu quero (se Moderador/Administrador) – Excluir o cadastro de uma ONG e sua Página de ONG do site, De maneira que – As informações publicadas por aquele projeto não estivessem mais disponíveis no site | Média |
| REQ05 – Cadastrar Usuário | Como – Usuário, Eu quero – Fazer um cadastro de usuário no site, De maneira que – Seja possível criar um perfil próprio para favoritar ONG’s por segmento e região, avaliar ONG’s e preencher formulários de ONG’s | Alta |
| REQ06 – Consultar Usuário | Como – ONG/Instituição/Projeto Social OU Moderador/Administrador, Eu quero – Consultar o perfil de um usuário, De maneira que – Seja possível obter informações sobre o usuário e bloquear ou excluir o seu perfil, se necessário | Baixa |
| REQ07 – Atualizar Usuário | Como – Usuário, Eu quero – Alterar seus dados de Usuário, De maneira que – Seja possível atualizar informações de usuário | Média |
| REQ08 – Excluir Usuário | Como – Usuário OU Moderador/Administrador, Eu quero (se Usuário) – Excluir meu cadastro e meu perfil de usuário, De maneira que – Meus dados não sejam mais divulgados pelo site. Eu quero (se Moderador/Administrador) – Excluir o cadastro de um usuário do site, De maneira que – As informações daquele usuário não estiverem mais disponíveis no site | Média |
| REQ09 – Login de ONGs e usuários | Como – Usuário, Eu quero – Fazer doações, pesquisar ações sociais, avaliar e comentar, De maneira que – Possa consultar e atualizar o perfil de usuário | Alta |
| REQ10 – Fazer Avalições | Como - Usuário, Eu quero – Escrever comentários, De maneira que – Seja possível criar comentários em perfis de ONGs | Média |
| REQ11 – Excluir Avaliações | Como – Moderador, Eu quero – Excluir comentários, De maneira que – Possa retirar comentários ofensivos e ou de conteúdo impróprio  | Média |

##### Definição de pronto 
> O sprint será considerado concluido quando: 
> 1) Os casos de teste de aceitação forem executados e obtiverem 100% de satisfatorios. Os casos de teste (CT) são rastreáveis para os requisiitos (REQ). O elo de rastreabilidade 
é estabelecido pelo identificador do caso de teste.
> 2) Depois de executado os casos de teste com 100% de satisfatorios o código deve ser armazenado no github (commit). 
##### Casos de teste 
| Identificador | Cenário de uso | 
| ------------ | ------------------------------------------------------------------------ | 
| REQ01CT01 | Dado (setup) que o CPF do cliente não está cadastrado; Quando (ação) o usuário confirma o cadastro; Então (resultado esperado) o sistema envia uma mensagem de cadastro realizado com sucesso | 
| REQ01CT02 | Dado (setup) que o CPF do cliente está cadastrado; Quando (ação) o usuário confirma o cadastro; Então (resultado esperado) o sistema rejeita e envia uma mensagem de dados inválidos | 
> 
O modelo de dominio (Larman, 2006 - classes conceituais ou classes de negócio) foi definido considerando as seguintes classes: 

![Diagrama de classes - socieloo ENG - Diagrama de classe](https://user-images.githubusercontent.com/99555037/226616730-d7baffe5-9504-4466-956c-0b75252f9d3d.jpeg)

A arquitetura segue uma abordagem orientada a serviços. Os serviços foram classificados em três tipos (ERL, 2007): 
- **1. Serviços utilitários**. Implementam funcionalidades comuns a vários tipos de aplicações, como, por exemplo: log, notificação, transformação de informações. Um exemplo de serviço utilitário é um serviço de conversão de moeda que 
poderá ser acessado para calcular a conversão de uma moeda (por exemplo, dólares) para outra (por exemplo, euros). 
- **2. Serviços de entidade (serviços de negócios)**. Derivado de uma ou mais entidades de negócio (domínio), possuindo um alto grau de reutilização. Geralmente são serviços que fazem operações CRUD (Create, Read, Update e Delete). 
- **3. Serviços de tarefa (coordenação de processos-workflow)**. Tipo de serviço mais específico que possui baixo grau de reuso. Consome outros serviços para atender seus consumidores. São serviços que suportam um processo de negócios 
amplo que geralmente envolve atividades e atores diferentes. Um exemplo de serviço de coordenação em uma empresa é um serviço de pedidos em que os pedidos são feitos, os produtos são aceitos e os pagamentos são efetuados. 
A visão lógica da arquitetura para API de Cliente é apresentada na figura abaixo. A visã lógica descreve como o código está organizado, as classes os pacotes e os relacionamentos entre eles. 
![f3_visao_logica](https://user-images.githubusercontent.com/68782201/162488505-5ec27561-eb83-42dc-a05f-27760e5bb7f3.jpg) 
>A entidade Cliente foi identificada como um serviço (ERL, 2007 - serviço do tipo entidade) o contrado das operações de sistema (LARMAN, 2006, pag.140) foram definidas no diagrama abaixo. 
```mermaid 
classDiagram 
 class ClienteServicoI 
 <<interface>> ClienteServicoI 
 
 ClienteServicoI : +List<Cliente> consultaTodos() 
 ClienteServicoI : +Optional<<Cliente>> consultaPorCpf(String cpf) 
 ClienteServicoI : +Optional<<Cliente>> consultaPorId(Long id) 
 ClienteServicoI : +Optional<<Cliente>> save(Cliente c) 
 ClienteServicoI : +void delete (Long id) 
 ClienteServicoI : +Optional<<Cliente>> altera (Cliente c) 
``` 
>O diagrama de sequência descreve como os varios componentes arquiteturais colaboram para manipular uma operação de sistema (exemplo para operação consultaTodos()) 
```mermaid 
sequenceDiagram 
Usuario ->> APIClienteController: GET /api/v1/clientes 
APIClienteController ->> ClienteServiceI: consultaTodos ( ) 
ClienteServiceI ->> ClienteRepository: findAll ( ) 
ClienteRepository -->> ClienteServiceI: List[] 
ClienteServiceI-->> APIClienteController: List[] 
APIClienteController -->> Usuario: JSon[] 
``` 


```mermaid
sequenceDiagram 
BEATRIZ ->> APIClienteController: GET /api/v1/clientes 
APIClienteController ->> ClienteServiceI: consultaTodos ( ) 
ClienteServiceI ->> ClienteRepository: findAll ( ) 
ClienteRepository -->> ClienteServiceI: List[] 
ClienteServiceI-->> APIClienteController: List[] 
APIClienteController -->> Usuario: JSon[] 
```


>Referencias 
- [1] KRUCHTEN, Philippe. Reference: Title: Architectural blueprints—the “4+ 1” view model of software architecture. IEEE software, v. 12, n. 6, 1995. 
- [2] RICHARDSON, Chris. Microservices patterns: with examples in Java. Simon and Schuster, 2018. 
- [3] ERL, Thomas. SOA principles of service design (the Prentice Hall service-oriented computing series from Thomas Erl). Prentice Hall PTR, 2007. 
- [4] LARMAN, Craig. Utilizando UML e padrões. 2aed., Porto Alegre: Bookman Editora, 2006 (pag. 147)
