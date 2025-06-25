# Grafos Metabólicos

Repositório para o projeto final de semestre de Práticas de Ciências de Dados.

**Integrantes:** Laura Medeiros, Lívia Aragão, Victor Emanuel e Vitor Bairral

**Professores Responsáveis:** Daniel Roberto Cassar, James Moraes de Almeida e Leandro Nascimento Lemos

_**Ilum Escola de Ciência - Centro Nacional de Pesquisa em Energia e Materiais**_


## Resumo
O projeto Grafos Metabólicos busca unir os conhecimentos construídos nas aulas de Energia em Sistemas Vivos e Lógica de Programação.
As rotas metabólicas estudadas, Glicólise, Fermentação, Ciclo de Krebs e Beta-Oxidação, são sequências de reações que envolvem a conversão de substratos (metabólitos) em energia (catabolismo) ou em móleculas complexas (anabolismo). Os grafos, por sua vez, são estruturas matemáticas utilizadas para representar a conexão de elementos. Nos grafos, cada elemento é um vértice e a conexão entre eles é indicado por uma aresta. Desse modo, podemos utilizar os grafos como uma ferramenta para construir um mapa metabólico, onde os metabólitos como a glicose, piruvato e ATP são interpretados como vértices e as conexões são as reações bioquímicas envolvidas no processo.

O objetivo do nosso código é tentar fornecer uma determinada via metabólica que percorre o intervalo entre um metabólito inicial e final, fornecidos pelo usuário. Desse modo, o algoritmo pesquisa pelas rotas até encontrar a que se adeque a solicitação e a retorna ao usuário. O intuito é otimizar a pesquisa por vias metabólicas específicas que são desejadas pelo usuário. 


## Licença
Grafos metabólicos é distribuido sobre a licença GNU. Veja mais informações em: https://github.com/all-licenses/GNU-General-Public-License-v3.0/tree/main


## Orientações
O arquivo principal do projeto é o arquivo Grafos Metabólicos.ipynb presente na pasta principal do projeto. Abra-o com um editor de código jupyter e execute as células na ordem em que aparecem. Siga as orientações descritas no Notebook para conseguir obter as rotas desejadas.

### Bibliotecas e Software
Para que a representação visual seja impressa corretamente com os metabólitos e as enzimas, será necessário importar a biblioteca `networkx`, para conseguir criar e modular estruturas de grafos; a classe `AGraph` do sistema `Graphviz`, para estruturar a visualização dos grafos, e o módulo `IPython.display`, para exibir essa imagem diretamente no notebook e salvá-la em `.png`.

### Funcionamento
A função principal do algoritmo é `procurar_rota`. A partir dos inputs fornecidos pelo usuário, chama funções que, em sequência, modificam o mapa metabólico para retirar dobros e torná-lo direcional; buscar uma possível rota por uma adaptação de busca por profundidade em grafos; a partir da lista do passo anterior, um novo grafo é feito especificamente da rota, retomando informações do mapa metabólico (pós-alterações); esse grafo pode também terá uma representação visual com o uso do software `Graphviz`; e, por fim, é impresso o processo de interconversão, destacando os metabólitos e enzimas envolvidas nessa rota.


## Referências
NELSON, D. L.; COX, M. M. Princípios de Bioquímica de Lehninger. [s.l: s.n.].
PyGraphviz — PyGraphviz documentation. Disponível em: <http://pygraphviz.github.io/>. Acesso em: 25 jun. 2025.


## Contribuições Individuais
### Laura Medeiros
Construção do segmento do grafo correspondente à Beta-Oxidação
Design das visualizações grafo das vias metabólicas
Edição do README

### Lívia Aragão
Construção do segmento do grafo correspondente à Glicólise
Auxílio na construção do algorítmo de pesquisa
Mardowns dos Notebooks
Edição do README

### Vitor Bairral
Construção do segmento do grafo correspondente ao Ciclo de Krebs
Auxílio na construção do algorítmo de pesquisa
Gerenciamento do Github

### Victor Emanuel
Construção do segmento do grafo correspondente à Fermentação
Adaptação dos códigos do mapa metabólico e das rotas para padronizar 
Algotitmo de modificação (retirar dobros e tornar direcional
Design dos slides
Escrita do README
