# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados
Neste pequeno texto falaremos sobre os bancos de dados, seus tipos e variações. Mas afinal, o que é um Banco de Dados? E qual seu papel no contexto de análise e apuração de dados?

A <b>Engenharia de Dados</b> é a área de estudo responsável por processar e transformar os dados brutos de uma empresa, e a partir daí, disponibilizá-los, garantindo que outros profissionais possam utilizá-los para diferentes finalidades.

A necessidade por esse tipo de processo surge graças à forma como os dados vêm sendo gerados atualmente — em altos volumes, grande velocidade e trás uma variedade de tamanhos, fontes e tipos. Por conta dessa desuniformidade, fica difícil extrair informações ou identificar determinados padrões.

É por meio da Engenharia que será possível processar os dados para manter a consistência e torná-los seguros, úteis e devidamente estruturados. Isso significa que toda a estratégia nesse sentido, incluindo o trabalho de Cientistas e Analistas de Dados vai depender desse fator.

## O que faz um Engenheiro de Dados?
O Engenheiro de Dados tem a função de gerenciar dados, armazená-los de forma correta e disponibilizar para o restante da equipe de forma lógica e compreensível.

Para isso, ele deve dominar conceitos de Big Data e computação em nuvem, e saber como usar linguagens de programação como Java, Python e Scala para o estudo e análise de dados.

Uma das grandes responsabilidades de um Engenheiro de Dados é a criação de Data Pipelines, um conjunto de etapas para realizar o tratamento dessas informações e transformá-las em formatos utilizáveis. Pensando nisso, ele precisa criar ferramentas personalizadas de acordo com os requisitos do negócio e dos demais membros do time de dados. 



## Vamos para o incício de tudo... o que é um Banco de Dados? 

Um banco de dados é uma coleção organizada de informações - ou dados - estruturadas, normalmente armazenadas eletronicamente em um sistema de computador. 
Um banco de dados é geralmente controlado por um sistema de gerenciamento de banco de dados (DBMS). Juntos, os dados e o DBMS, juntamente com os aplicativos associados a eles, são chamados de sistema de banco de dados, geralmente abreviados para apenas banco de dados.

Os dados nos tipos mais comuns de bancos de dados em operação atualmente são modelados em linhas e colunas em uma série de tabelas para tornar o processamento e a consulta de dados eficientes. Os dados podem ser facilmente acessados, gerenciados, modificados, atualizados, controlados e organizados. A maioria dos bancos de dados usa a linguagem de consulta estruturada (SQL) para escrever e consultar dados.

## O que é SQL?
SQL é uma linguagem padrão para trabalhar com bancos de dados relacionais. Ela é uma linguagem declarativa e que não necessita de profundos conhecimentos de programação para que alguém possa começar a escrever queries, as consultas e pedidps, que trazem resultados de acordo com o que você está buscando. SQL significa Standard Query Language, literalmente a linguagem padrão para realizar queries.

A linguagem SQL é utilizada de maneira relativamente parecida entre os principais bancos de dados relacionais do mercado: Oracle, MySQL, MariaDB, PostgreSQL, Microsoft SQL Server, entre muitos outros. Cada um tem suas características, sendo o MySQL e o PostgreSQL extremamente populares por possuírem versões gratuitas e de código aberto.

É também uma linguagem que muitos profissionais acabam precisando aprender: seja quem usa Excel de forma pesada e acaba migrando as informações para um banco de dados, seja um cientista de dados que usa Python para agregar os dados das diferentes fontes de informações.

## Quais são os principais comandos SQL?

<ul>
<li><b>SELECT</b>: busca linhas em tabelas de acordo com um critério definido dentro da chamada cláusula de WHERE.</li>
<li><b>INSERT</b>: insere novas linhas na tabela. no nosso caso, colocaria novas notas fiscais dado os argumentos que são passados para o INSERT. Por exemplo, no nosso caso: INSERT INTO nf (título, pagamento, valor) VALUES 'canetas', '2019-07-15', 150.</li>
<li><b>UPDATE</b>: atualiza linhas do banco de dados de acordo com um critério de WHERE, como mudar o CPF.</li>
<li><b>DELETE</b>: remove linhas da tabela de acordo com um critério.</li>
</ul>
Há ainda uma infinidade de sub-comandos para fazer buscas melhores e mais elaboradas, como JOIN, LIKE, HAVING e GROUP BY. O trabalho básico com tabelas, linhas, colunas, relacionamentos e chaves não demanda um conhecimento extenso de SQL. Ele vai se fazer necessário para otimizar consultas e tomar decisões de como modelar esses dados.

## O que é NoSQL?
O termo 'NoSQL' se refere a tipos não relacionais de bancos de dados, e esses bancos de dados armazenam dados em um formato diferente das tabelas relacionais. No entanto, os bancos de dados NoSQL podem ser consultados usando APIs de linguagem idiomática, linguagens de consulta estruturadas declarativas e linguagens de consulta por exemplo, razão pela qual também são chamados de bancos de dados "não apenas SQL".

## Para que é usado um banco de dados NoSQL?
Os bancos de dados NoSQL são amplamente usados em aplicativos da web em tempo real e big data, porque suas principais vantagens são alta escalabilidade e alta disponibilidade.
Os bancos de dados NoSQL também são a escolha preferida dos desenvolvedores, pois eles naturalmente aceitam um paradigma de desenvolvimento ágil, adaptando-se rapidamente aos requisitos em constante mudança. Os bancos de dados NoSQL permitem que os dados sejam armazenados de maneiras mais intuitivas e fáceis de entender, ou mais próximas da maneira como os dados são usados pelos aplicativos - com menos transformações necessárias ao armazenar ou recuperar usando APIs no estilo NoSQL. Além disso, os bancos de dados NoSQL podem aproveitar ao máximo a nuvem para oferecer tempo de inatividade zero.

## SQL versus NoSQL
Os bancos de dados SQL são relacionais, enquanto os bancos de dados NoSQL são não relacionais. O sistema de gerenciamento de banco de dados relacional (RDBMS) é a base para a linguagem de consulta estruturada (SQL), que permite aos usuários acessar e manipular dados em tabelas altamente estruturadas. Este é o modelo básico para sistemas de banco de dados como MS SQL Server, IBM DB2, Oracle e MySQL. Mas com bancos de dados NoSQL, a sintaxe de acesso a dados pode ser diferente de banco de dados para banco de dados.

## Banco de dados relacional versus banco de dados NoSQL
Para entender os bancos de dados NoSQL, é importante saber qual é a diferença entre RDBMS e tipos não relacionais de bancos de dados.

Os dados em um RDBMS são armazenados em objetos de banco de dados que são chamados de tabelas. Uma tabela é uma coleção de entradas de dados relacionadas e consiste em colunas e linhas. Esses bancos de dados requerem a definição do esquema com antecedência, ou seja, todas as colunas e seus tipos de dados associados devem ser conhecidos de antemão para que os aplicativos possam gravar dados no banco de dados. Eles também armazenam informações vinculando várias tabelas por meio do uso de chaves, criando assim um relacionamento entre várias tabelas. No caso mais simples, uma chave é usada para recuperar uma linha específica para que ela possa ser examinada ou modificada.

Por outro lado, em bancos de dados NoSQL, os dados podem ser armazenados sem definir o esquema com antecedência—o que significa que você tem a capacidade de se mover e iterar rapidamente, definindo o modelo de dados à medida que avança. Isso pode ser adequado para requisitos específicos de negócios, seja baseado em gráficos, orientado a colunas, orientado a documentos ou como um armazenamento de valor-chave.

Até muito recentemente, os bancos de dados relacionais eram os modelos mais usados. Eles ainda são extremamente onipresentes em muitas empresas; no entanto, a variedade, velocidade e volume de dados que estão sendo acessados hoje às vezes requerem um banco de dados muito diferente para complementar o banco de dados relacional. Isso desencadeou a adoção em algumas áreas dos bancos de dados NoSQL - também chamados de "bancos de dados não relacionais". Devido à sua capacidade de escalar horizontalmente e rapidamente, os bancos de dados não relacionais podem lidar com alto tráfego, o que também os torna altamente adaptáveis.

## Quando escolher um banco de dados NoSQL?
Com empresas e organizações precisando inovar rapidamente, ser capaz de se manter ágil e continuar operando em qualquer escala faz parte do jogo. Os bancos de dados NoSQL oferecem esquemas flexíveis e também suportam uma variedade de modelos de dados que são ideais para a construção de aplicativos que requerem grandes volumes de dados e baixa latência ou tempos de resposta—por exemplo, jogos online e aplicativos da web de e-commerce.

## Quando não escolher um banco de dados NoSQL?
Os bancos de dados NoSQL normalmente dependem de dados desnormalizados, suportando os tipos de aplicativos que usam menos tabelas (ou contêineres) e cujos relacionamentos de dados não são modelados usando referências, mas sim como registros (ou documentos) incorporados. Muitos aplicativos de negócios de back-office clássicos em finanças, contabilidade e planejamento de recursos corporativos contam com dados altamente normalizados para evitar anomalias de dados, bem como a duplicação de dados. Esses são os tipos comuns de aplicações que não são adequadas para um Banco de Dados NoSQL.

Outra distinção dos bancos de dados NoSQL é a complexidade da consulta. Os bancos de dados NoSQL funcionam incrivelmente bem com consultas em uma única tabela. No entanto, conforme a complexidade das consultas aumenta, os bancos de dados relacionais são uma escolha melhor. O banco de dados NoSQL normalmente não oferece junções complexas, subconsultas e aninhamento de consultas em uma cláusula WHERE.

Às vezes, porém, não é necessário escolher entre bancos de dados relacionais e não relacionais. Em muitas ocasiões, as empresas optaram por bancos de dados que oferecem um modelo convergente, no qual podem empregar uma combinação de modelos de dados relacionais e não relacionais. Essa abordagem híbrida oferece maior flexibilidade no tratamento de diferentes tipos de dados, ao mesmo tempo que garante a consistência de leitura e gravação sem degradar o desempenho.

## Benefícios de um banco de dados NoSQL
A velocidade e escala sem precedentes da interação digital e do consumo de dados observada nas últimas duas décadas exigiram que as empresas adotassem uma abordagem mais moderna e fluida de como armazenam dados e como os acessam. Com usuários em todo o mundo exigindo um fluxo ininterrupto de conteúdo e funções, não é de se admirar que os bancos de dados tenham que adaptar-se rapidamente. Com isso em mente, aqui estão alguns dos principais motivos pelos quais os desenvolvedores estão escolhendo NoSQL/bancos de dados não relacionais, como Flexibilidade, escalabilidade, alto desempenho, disponibilidade e por ser altamente funcional.


## Tipos de bancos de dados NoSQL
### Existem quatro tipos principais de bancos de dados NoSQL:

<dl>
<dt>Valor principal
<dd>Este é o tipo mais flexível de banco de dados NoSQL porque o aplicativo tem controle total sobre o que é armazenado no campo de valor sem quaisquer restrições.</dd></dt>

<dt>Documento</dt>
<dd>Também conhecidos como armazenamento de documentos ou bancos de dados orientados a documentos, esses bancos de dados são usados para armazenar, recuperar e gerenciar dados semiestruturados. Não há necessidade de especificar quais campos um documento conterá.</dd>

<dt>Gráfico</dt>
<dd>Este banco de dados organiza os dados como nós e relacionamentos, que mostram as conexões entre os nós. Isso oferece suporte a uma representação de dados mais rica e completa. Bancos de dados gráficos são aplicados em redes sociais, sistemas de reserva e detecção de fraudes.</dd>

<dt>Coluna larga</dt>
<dd>Esses bancos de dados armazenam e gerenciam dados na forma de tabelas, linhas e colunas. Eles são amplamente implantados em aplicativos que requerem um formato de coluna para capturar dados sem esquema.</dd>
</dl>

## Referências :globe_with_meridians:
A seguir, as referencias utilizadas para redigir este texto:

https://pt.wikipedia.org/wiki/SQL
https://pt.wikipedia.org/wiki/Banco_de_dados
https://www.alura.com.br/artigos/o-que-e-sql
https://www.oracle.com/br/database/nosql/what-is-nosql/#:~:text=O%20termo%20'NoSQL'%20se%20refere,formato%20diferente%20das%20tabelas%20relacionais.



