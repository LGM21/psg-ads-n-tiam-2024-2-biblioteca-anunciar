# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

![Arquitetura da Solução](img/02-mob-arch.png)

## Diagrama de Classes

O diagrama de classes ilustra graficamente como será a estrutura do software, e como cada uma das classes da sua estrutura estarão interligadas. Essas classes servem de modelo para materializar os objetos que executarão na memória.

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Classes”.

> - [Diagramas de Classes - Documentação da IBM](https://www.ibm.com/docs/pt-br/rational-soft-arch/9.6.1?topic=diagrams-class)
> - [O que é um diagrama de classe UML? | Lucidchart](https://www.lucidchart.com/pages/pt/o-que-e-diagrama-de-classe-uml)

## Modelo ER

O Modelo ER representa através de um diagrama como as entidades (coisas, objetos) se relacionam entre si na aplicação interativa.]

As referências abaixo irão auxiliá-lo na geração do artefato “Modelo ER”.

> - [Como fazer um diagrama entidade relacionamento | Lucidchart](https://www.lucidchart.com/pages/pt/como-fazer-um-diagrama-entidade-relacionamento)

## Esquema Relacional

O Esquema Relacional corresponde à representação dos dados em tabelas juntamente com as restrições de integridade e chave primária.
 
As referências abaixo irão auxiliá-lo na geração do artefato “Esquema Relacional”.

> - [Criando um modelo relacional - Documentação da IBM](https://www.ibm.com/docs/pt-br/cognos-analytics/10.2.2?topic=designer-creating-relational-model)

## Modelo Físico

Entregar um arquivo banco.sql contendo os scripts de criação das tabelas do banco de dados. Este arquivo deverá ser incluído dentro da pasta src\bd.

## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)

## Qualidade de Software

1.	Funcionalidade
	•	Completude Funcional: O aplicativo deve incluir todas as funcionalidades necessárias para catalogação, busca e gerenciamento de empréstimos e devoluções de livros.
	•	Correção Funcional: As funcionalidades implementadas devem operar corretamente, sem falhas, garantindo que os usuários possam realizar suas operações sem erros.           
2.	Usabilidade
	•	Operacionalidade: O aplicativo deve ser intuitivo, permitindo que os usuários realizem operações sem dificuldades, facilitando a experiência de uso, especialmente para aqueles com menos familiaridade com tecnologia.
	•	Acessibilidade: O design do aplicativo deve considerar as necessidades de todos os usuários, incluindo aqueles com deficiências, garantindo que todos possam acessar e utilizar o sistema adequadamente.
3.	Confiabilidade
	•	Disponibilidade: O sistema deve estar disponível para uso sempre que necessário, minimizando o tempo de inatividade e garantindo que os usuários possam acessar as funcionalidades do aplicativo sempre que precisarem.
	•	Recuperabilidade: O aplicativo deve ter mecanismos de recuperação de dados em caso de falhas, assegurando que as informações não sejam perdidas.
4.	Eficiência
	•	Tempo de Resposta: O aplicativo deve ser responsivo, com tempos de resposta rápidos para as operações realizadas pelos usuários, como buscas e registros de empréstimos.
	•	Utilização de Recursos: O sistema deve ser desenvolvido de forma a otimizar o uso de recursos do dispositivo em que está sendo executado, garantindo um desempenho adequado mesmo em máquinas com especificações mais modestas.

Justificativa das Subcaracterísticas Escolhidas

As subcaracterísticas escolhidas são fundamentais para garantir que o aplicativo atenda efetivamente às necessidades da comunidade da Igreja Batista Anunciar. A funcionalidade é crucial para que os usuários consigam realizar as operações de catalogação e gerenciamento sem frustrações. A usabilidade garante que o sistema seja acessível e fácil de usar, promovendo uma melhor experiência para todos os membros da igreja, independentemente de sua habilidade tecnológica. A confiabilidade assegura que o sistema seja um recurso confiável, onde os usuários podem depender de sua operação sem medo de perder informações. Por fim, a eficiência é essencial para que o aplicativo funcione de maneira fluida, proporcionando uma interação rápida e agradável para os usuários.

Métricas de Avaliação

Para garantir que as subcaracterísticas de qualidade estão sendo atendidas, as seguintes métricas serão utilizadas:

	•	Funcionalidade:
	•	Percentual de funcionalidades implementadas conforme as especificações.
	•	Taxa de erro em funcionalidades após testes.
	•	Usabilidade:
	•	Tempo médio que um usuário leva para realizar operações específicas (como buscar um livro ou registrar um empréstimo).
	•	Resultados de questionários de satisfação do usuário sobre a interface e facilidade de uso.
	•	Confiabilidade:
	•	Tempo médio entre falhas (MTBF) durante testes de uso.
	•	Tempo médio para recuperação de falhas (MTTR).
	•	Eficiência:
	•	Tempo médio de resposta para operações críticas, como busca de livros.
	•	Consumo de recursos (CPU e memória) durante operações do aplicativo.

Com essa estrutura, você pode abordar a qualidade de software de forma clara e objetiva, alinhando as necessidades do seu projeto com as características e métricas adequadas. Se precisar de mais ajustes ou detalhes, estou à disposição
> **Links Úteis**:
>
> - [ISO/IEC 25010:2011 - Systems and software engineering — Systems and software Quality Requirements and Evaluation (SQuaRE) — System and software quality models](https://www.iso.org/standard/35733.html/)
> - [Análise sobre a ISO 9126 – NBR 13596](https://www.tiespecialistas.com.br/analise-sobre-iso-9126-nbr-13596/)
> - [Qualidade de Software - Engenharia de Software 29](https://www.devmedia.com.br/qualidade-de-software-engenharia-de-software-29/18209/)
