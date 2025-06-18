### RotasMetabolicas
Repositório para o projeto final de semestre de Práticas de Ciências de Dados

## Grafos Metabólicos
O projeto Grafos Metabólicos busca unir os conhecimentos construídos nas aulas de Energia em Sistemas Vivos e Lógica de Programação.
As rotas metabólicas estudadas - glicólise, fermentação, ciclo do ácido cítrico e betaoxidação - são sequências de reações que envolve a conversão de substratos (metabólitos) em energia (catabolismo) ou em móleculas complexas (anabolismo).
Já os grafos são estruturas matemáticas utilizadas para representar a conexão de elementos. Nos grafos, cada elemento é chamato de vértice e cada conexão é nomeada de aresta.

# Relação Entre as rotas metabólicas e os grafos
As rotas metabólicas podem ser interpretadas como grafos, sendo os metabólitos os vértices - como glicose, piruvato ou ATP - e as reações enzimáticas as arestas. (VERIFICAR PONTUAÇÃO!!!)
Essa representação permite analisar o fluxo de matéria e energia, identificar vias alternativas, pontos de regulação e interações entre diferentes vias metabólicas, sendo uma ferramenta fundamental em biologia de sistemas e bioinformática.

## Funcionamento
# Escolha do Ponto Inicial e Final:
O usuário escolhe qual deve ser os metabólitos inicial e final do intervalo que ele deseja analisar.
# Busca em profundidade:
O algorítmo construído realizará uma busca em profundidade inciada no vértice que representa o metabólito inicial e finalizada no vértice relacionado ao metabólito final.
# Definição do Novo Grafo:
Enquanto o algorítmo construído realiza a busca em profundidade, os resultados são adicionados a um novo grafo que será armazenado.
# Impressão:
O novo grafo do intervalo escolhido pelo usuário será impresso.
