# Grafos Metabólicos

Repositório para o projeto final de semestre de Práticas de Ciências de Dados.

Integrantes: Laura Medeiros, Lívia Aragão, Victor Emanuel e Vitor Bairral |
Ilum Escola de Ciência - Centro Nacional de Pesquisa em Energia e Materiais |
Professores Responsáveis: Daniel Roberto Cassar, James Moraes de Almeida e Leandro Nascimento Lemos


## Resumo
O projeto Grafos Metabólicos busca unir os conhecimentos construídos nas aulas de Energia em Sistemas Vivos e Lógica de Programação.
As rotas metabólicas estudadas - glicólise, fermentação, ciclo do ácido cítrico e betaoxidação - são sequências de reações que envolve a conversão de substratos (metabólitos) em energia (catabolismo) ou em móleculas complexas (anabolismo). Os grafos, por sua vez, são estruturas matemáticas utilizadas para representar a conexão de elementos. Nos grafos, cada elemento é um vértice e a conexão entre eles é indicado por uma aresta. Desse modo, podemos utilizar os grafos como uma ferramenta para construir um mapa metabólico, onde os metabólitos como a glicose, piruvato e ATP são interpretados como vértices e as conexões são as reações bioquímicas envolvidas no processo.

O objetivo do nosso código é fornecer uma determinada via metabólica que percorre o intervalo entre um metabólito inicial e final que é informado pelo usuário. Desse modo, o algorítmo pesquisa pelas rotas até encontrar a que se adeque a solicitação e a retorna ao usuário. O intuíto é otimizar a pesquisa por vias metabólicas específicas que são desejadas pelo usuário. 

## Licença

Grafos metabólicos é distribuido sobre a licença GNU. Veja mais informações em: https://github.com/all-licenses/GNU-General-Public-License-v3.0/tree/main

## Orientações
### Como utilizar:
O arquivo principal do projeto é o arquivo Grafos Metabólicos.ipynb presente na pasta principal do projeto. Abra-o com um editor de código jupyter e execute as células na ordem em que aparecem. 
Os arquivos criados durante o desenvolvimento do projeto estão disponíveis nas pastas Processos, para a representação das rotas metabólicas em grafos separados e ALgoritmos, para os algoritmos utilizados.

### Bibliotecas

Para esse projeto foi utilizado somente a biblioteca networkx para a visualização dos grafos. 

### Funcionamento

#### Escolha do Ponto Inicial e Final

O usuário escolhe qual deve ser os metabólitos iniciais e finais do intervalo que ele deseja analisar. Por exemplo, se ele quiser a via que vai desde a glicose até o Acetil-CoA, ele informa isso ao programa.

#### Busca em profundidade:

O algorítmo construído realizará uma busca em profundidade iniciada no vértice que representa o metabólito inicial e finalizada no vértice relacionado ao metabólito final.

#### Definição do Novo Grafo:

Enquanto o algorítmo construído realiza a busca em profundidade, os resultados são adicionados a um novo grafo que será armazenado.

#### Impressão:

O novo grafo do intervalo escolhido pelo usuário será impresso.

## Contribuições Individuais
### Laura Medeiros:
Construção do segmento do grafo correspondente à Beta Oxidação,
Design das visualizações grafo das vias metabólicas,
Edição do README.

### Lívia Aragão:
Construção do segmento do grafo correspondente à Glicólise,
Auxílio na construção do algorítmo de pesquisa,
Mardowns dos Notebooks,
Edição do README.

### Vitor Bairral:
Construção do segmento do grafo correspondente ao Ciclo de Krebs,
Auxílio na construção do algorítmo de pesquisa,
Gerenciamento do Github.

### Victor Emanuel
Construção do segmento do grafo correspondente à Fermentação,
Adaptação dos códigos do mapa metabólico e das rotas para padronizar, 
Algotitmo de modificação (retirar dobros e tornar direcional,
Design dos slides,
Escrita do README.
