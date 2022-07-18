# Modulo 1


### Pensamento computacional

Pensamento computacional processo de pensamento envolvido na expressão de solução em passos computacionais ou algoritmos que podem ser implementados no computador. 

- __Sistemático e eficiente__

  -  Formulação e resolução de problemas - o ser humano e o computador são capaz de resolver.
-  __Os 4 pilares__ 

  - __Decomposição__- pega o problema e dividir encontrar problemas menores e resolvíeis
  - __Reconhecimento de padrões__- identificar similaridades e tendência dentro de um contexto ou contexto distinto 
  - __Designer do algoritmo__- _automatizar_- definir passo a passo a solução do problema
- __Abstração__- extrapolar um conceito de algum problema para uma forma generalista- mundo completo e mundo das ideias 

## Introdução a Lógica de Programação

Lógica é a parte da filosofia que trata das formas do pensamento em geral e das operações intelectuais que visam a determinação do que é verdadeiro ou não

### Técnicas da lógica

- Técnica linear: Modelo tradicional, não tem vínculo, estrutura hierárquica, programação de computadores, execução sequencial, recursos limitados e única dimensão.
- Técnica estruturada: A organização disposição é ordem dos elementos essenciais que compõem o corpo.
- Técnica modular: controlado por regras.

Dados de entrada → Processo de transformação → Dados de saída 

## Fundamentos de algoritmo

### __Tipologia e variável __

A função do computador é processar as informações compostas por dados puros e instruções, normativas para executar determinadas ações e por fim esses dados são tratados e processados.

#### **Tipos de dados:**

Numéricos - Inteiros e Reais _(int , float)_

Caracteres - Tudo não representado por número ("") seria _String_

Lógico/booleano - V(1) ou F(0), no português estruturado são acompanhados de um ponto no antes.

#####  Variável

É um tipo de estrutura mutável inconstante que pode assumir qualquer valor de um determinado conjunto de valores.

Nome da variável - atribuição de um ou mais caracteres, sem espaços em branco,vetado a utilização de palavras reservada.

Ou vai ser de ação modificando o estado de algoritmo e controle utilizado para controle de alguma estrutura ou equação.

Constante- tudo que é fixo ou estável.

Objetivo- com os dados tratados e processados as instruções são as operações que processam os dados.

As operações normalmente são cálculos matemáticos com variáveis e constantes e operadores podem ser binário e unário.

### Instruções primitivas

Linguagem de vocabulário de uma determinada programação que tem por finalidade comandar um computador que irá tratar dos dados.

Notação está relacionada aos operadores.

Entrada processamento e saída dos dados- importados de um lugar como diretório, levado ao ambiente computacional para serem processados para serem imprimidos 

### Estrutura condicional

Condição é o estado de uma pessoa os uma coisa

Condicional expressa uma condição ou suposição, ele contem ou implica com uma suposição ou hipótese.

Condicional simples- com apenas uma resolução, exemplo se a resposta da condição for Verdadeira ela vai ser imprimida, se não apenas encerrada

Condicional composta- Resolução da operação e Impressão para o verdadeiro e o falso

Condicional encadeado- Sucessão de condicionais 

#### Operadores lógicos 

Resposta simplificada como V e F

- AND - Se tiver uma condição falso o resultado é falso 
- OR - Se uma condição for verdadeiro o resultado é verdadeiro
- NOT - Inversão do resultado logico é o resultado da operação

## Estrutura de repetição

- Laços, controle de fluxo, malhas de repetição, loop

Condição de parada- numero de repetição pré-fixada ou condição satisfeita

## Vetores e matrizes

Vetor é caracterizado por uma variável dimensionada com tamanho pré-fixado; Matriz é uma tabela organizada por linha e coluna, M x N onde m representa linhas e N colunas

- Numéricos: Inteiros e reais

## Funções 

As funções são blocos de instruções que realizam tarefas especificas, identificados por nomes e parâmetros.

Semelhante ao conceito de funções na matematica onde F = a →b

## Instruções de entrada e Saída 

Entrada - Consiste na inserção e recebimento de dados do mundo real por meio da ação de alguma interface, seja teclado, Mouse, arquivos, entre outros 

Saída - Consiste na impressão dos dados do mundo abstrato digital por meio da ação de alguma interface. Os formatos podem variar desde simples arquivos binários até complexas querys de bancos de dados 

Existem dois tipos de saída-  Saída programada pode ser condicional quando aguarda o dispositivo para executar a saída dos valores e por interrupção definida pelos periféricos através de um erro de execução

## Linguagem de programação

Historia da computação

Programa é um amontado de palavras senão for possível que o computador entenda.

Programa fonte é mandado para o compilador que executa a analise do programa transforma em programa objeto e resulta em linguagem de maquina.

Na tradução é gerado o programa objeto para a execução do programa(Java, C++)

Já na interpretação o programa fonte é executado diretamente(Java Script, Ruby, Python)

Características de um programa- Legibilidade, redigibilidade, confiabilidade, custo

### Analise de um código 

Léxica - Faz leitura do programa fonte e agrupa em lexemas. Particionar- tokens, classificar- identificadores, strings, entre outros e eliminar espaços em brancos e comentários.

Sintática -  Interliga os constituintes da sentença atribuindo-lhe uma estrutura

Semântica - Incide sobre a relação entre os significados

## Paradigmas  

Forma de resolução de problemas com diretrizes e limitações especificas de cada paradigma utilizando linguagem de programação

Estruturado - Ênfase de sequência

Orientação à objeto - Paradigma de programação baseado na utilização de objetos e suas interações - Análogo ao mundo real.

Herança, Encapsulamento, Polimorfismo, abstração

Portugol- Pratica

## Git e github

O git é um software desenvolvido em 2005, por Linus Torvalds, para a construção de projetos, como sites, códigos ou softwares, onde vários desenvolvedores podem trabalhar ao mesmo tempo, de maneira rápida, inteligente e eficiente.

A funcionalidade que se destaca no git é o seu sistema de controle de alterações. Quando alguém muda o código, por exemplo, é gerada uma nova versão do projeto, sem ter o risco de perder qualquer informação. Todas essas versões são salvas em um repositório, sobre o qual explicaremos com mais detalhes, ainda neste artigo.

Mesmo o trabalho eficiente em equipe sendo a maior característica do software, muitos desenvolvedores também o utilizam para fins individuais, pelo fato de oferecer diversos recursos que permitem a construção de ótimos projetos.

### Comandos básicos

Windows

CD - entrar na pasta 

DIR - Listar (ls-linux)

MKDIR - Criar pasta

CD .. - voltar

Echo - criar arquivo

del - deletar arquivo

rmdir - deletar pasta (rm-rf em Linux)

Para instalar git no linux usar comando e no MAC usar gerenciador de pacote como o Homebrew.

#### Objetos internos

- Blobs- Tipo, tamanho,/0 e conteudo 
-  Trees - Armazena blobs -  tamanho,/0, blobs, sha1, nome_arquivo- estrutura onde está o arquivo
-   Commits - Arvore, parente, autor, mensagem, sha1, temstamp - O sha1 deste commit é o hash de toda informação

### Chave SSH e Token

12 de agosto - autenticação por nome e datas foram desativadas

SSH é um protocolo que permite a conexão com servidores remotos, de forma criptografada e mais segura, usando um par de chaves RSA -  As SSH Keys funcionam no modo chave pública e privada (sempre em pares), onde a conexão SFTP/SSH só é autorizada se a chave privada do usuário do computador cliente bater com a chave pública do usuário do servidor

 O token é um certificado digital, fornecido por um dispositivo físico que gera uma senha temporária para que o usuário possa realizar movimentações financeiras com maior segurança e tranquilidade.
