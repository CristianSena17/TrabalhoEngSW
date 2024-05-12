# Proposta de Arquitetura - Trabalho Engenharia de Software - 2024/1
**Escolhas de tecnologias:**

Para o desenvolvimento desse projeto, será utilizado um conjunto de tecnologias padrão para desenvolvimento web. No front-end, vamos utilizar HTML, CSS e JavaScript. Do lado do servidor, Python com o framework Django será usado para lidar com requisições e fornecer respostas.

HTML, CSS e JavaScript são as tecnologias fundamentais para a construção de páginas web e são suportadas por todos os navegadores modernos. Desta forma, garantimos que nosso site seja acessível a uma ampla gama de usuários. 

**Projeto arquitetural elaborado:**

O modelo arquitetural será composto por uma combinação de front-end e back-end (também conhecido como modelo cliente-servidor). O usuário (cliente) interage com a interface de usuário no front-end, que é construída com HTML, CSS e JavaScript. 

Quando o usuário realiza uma ação que requer uma resposta do servidor (como recuperar informações), um pedido é enviado ao back-end. O back-end, construído com Python e Django, processa o pedido e retorna uma resposta ao front-end. 

A página principal serve como a porta de entrada para o site e dá acesso a diversas áreas de conteúdo, incluindo Notícias Ambientais, Artigos e Infográficos, e Práticas Ecológicas. Cada área de conteúdo é composta por várias páginas individuais.

**Justificativa do modelo escolhido:**

A arquitetura de cliente-servidor é uma das mais utilizadas na indústria de desenvolvimento web devido à sua flexibilidade e eficiência. Ela permite o desenvolvimento independente do front-end e do back-end, facilitando a manutenção e possíveis atualizações. 

**Diagramas:**

![Diag1](https://github.com/CristianSena17/TrabalhoEngSW/blob/main/Docs/C4.png)

![Diag2](https://github.com/CristianSena17/TrabalhoEngSW/blob/main/Docs/Rela%C3%A7%C3%A3o%20p%C3%A1ginas.png)
