# Construindo um Grafo de Deputados em Python

Olá pessoal! 👋🏼 Hoje, estou animado para compartilhar com vocês um código Python que desenvolvi para construir um grafo de deputados utilizando dados da API da Câmara dos Deputados do Brasil. Vamos explorar e entender mais sobre esse projeto que eu criei!

### 📚Visão Geral do Código:

Neste projeto, eu criei duas classes em Python, Graph e AmountVotes, para criar um grafo de deputados e armazenar informações sobre o número de votos que cada deputado fez.

### 📈Classe Graph:

- A classe Graph representa um grafo direcionado de deputados e suas relações de votação.
- Criei métodos para adicionar nós e arestas ao grafo, onde os nós representam os deputados e as arestas representam os votos a favor ou contra entre os deputados.
- O método deputies_graph utiliza a API da Câmara dos Deputados do Brasil para obter os dados de votação e construir o grafo de acordo com essas informações.
- O grafo é construído com os deputados como nós, e uma aresta é adicionada entre os deputados que votaram juntos a favor ou contra um projeto de lei.

### 📈Classe AmountVotes:

- A classe AmountVotes é utilizada para acompanhar o número de votos que cada deputado fez.
- Implementei o método arquive, que escreve os dados contendo o nome do deputado e a contagem de votos correspondente em um arquivo.
- Estou muito satisfeito com o resultado deste projeto, pois ele me permitiu explorar dados reais e entender melhor as interações entre os deputados durante as votações na Câmara. Espero que esta solução também seja útil para outras pessoas interessadas em análise política e visualização de dados.

- Se você tiver alguma dúvida ou sugestão sobre o código que eu criei, fique à vontade para compartilhar nos comentários abaixo. Obrigado por me acompanhar nesta jornada de aprendizado e desenvolvimento! 😊📊🗳️

### Contato:

- 💬 Linkedin: https://www.linkedin.com/in/mateus-santos-16523a1a3
- 📫 Email: mateus_saantos@outlook.com
