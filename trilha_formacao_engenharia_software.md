# Trilha de Formação em Engenharia de Software

## Do conhecimento que você já tem à primeira oportunidade profissional — e depois à profundidade técnica

**Versão:** 1.0  
**Atualizada em:** 15 de novembro de 2026  
**Idioma dos materiais principais:** português (Brasil)  
**Formato:** roteiro progressivo, com aulas, livros, documentação, exercícios, projetos e critérios de avanço.

---

## Como usar este documento

Este arquivo é um currículo de longo prazo, não uma lista para consumir rapidamente. Siga a ordem das etapas, mas não espere dominar uma área inteira antes de tocar nas seguintes. Algumas disciplinas — especialmente matemática, algoritmos e prática de programação — devem caminhar em paralelo.

O objetivo tem duas partes:

1. **Conseguir começar a trabalhar com desenvolvimento de software:** aproveitar o que você já sabe, fechar lacunas práticas e montar projetos que demonstrem que você consegue entregar algo utilizável.
2. **Evoluir para um engenheiro de software realmente sólido:** dominar fundamentos de computação, engenharia, arquitetura, qualidade, sistemas e tomada de decisões técnicas.

Não existe um curso ou uma playlist que transforme alguém em profissional. O desenvolvimento profissional vem da combinação de teoria, prática deliberada, projetos, revisão, manutenção e experiência com problemas reais.

### Seu ponto de partida considerado

Este roteiro considera que você já teve contato com:

- HTML, CSS e JavaScript;
- PHP e bancos de dados;
- Python;
- Java, incluindo um projeto bancário de terminal e estudos de orientação a objetos;
- React, Node.js, Firebase e SQL;
- projetos próprios, especialmente GamerWiki e NihilDynamics.

Portanto, **não vamos tratar você como alguém que nunca viu código**. Vamos revisar os fundamentos desde o começo onde necessário, mas sem obrigá-lo a reaprender toda a sintaxe de cada linguagem.

### Regra principal

Não marque um assunto como aprendido só porque assistiu à aula. Considere que aprendeu quando consegue:

1. explicar o conceito sem copiar a definição;
2. resolver um exercício sem acompanhar uma solução passo a passo;
3. implementar uma aplicação pequena usando o conceito;
4. testar casos normais, extremos e inválidos;
5. comparar alternativas e justificar a escolha feita.

---

# PARTE I — ESTRATÉGIA GERAL

## 1. Não espere dominar toda a Ciência da Computação para procurar trabalho

É importante separar **empregabilidade inicial** de **formação profunda**. Você pode começar a oferecer serviços pequenos ou concorrer a vagas iniciais antes de estudar sistemas distribuídos, compiladores ou matemática avançada.

A estratégia recomendada é ter duas trilhas paralelas:

| Trilha | Objetivo | Prioridade |
|---|---|---|
| Desenvolvimento profissional inicial | Construir, testar, publicar e manter aplicações web pequenas | Alta no começo |
| Fundamentos de Engenharia de Software | Algoritmos, matemática, arquitetura, sistemas, qualidade e teoria | Contínua, desde o começo |

Para o primeiro trabalho, concentre-se em entregar bem coisas delimitadas: páginas institucionais, landing pages, catálogos, painéis administrativos simples, formulários, integrações e sistemas CRUD. Evite assumir sozinho pagamentos, dados altamente sensíveis, sistemas financeiros ou infraestrutura crítica antes de ter experiência e supervisão adequadas.

## 2. Escolha uma stack principal para conseguir entregar

Você já conhece várias linguagens. O risco agora é dispersar o estudo em muitas tecnologias.

**Sugestão para a trilha de trabalho web:**

- Front-end: HTML semântico, CSS responsivo e JavaScript moderno.
- Biblioteca de interface: React, quando fizer sentido.
- Back-end: escolha **um** caminho principal por alguns meses — Node.js ou PHP. Não tente aprofundar os dois ao mesmo tempo.
- Banco de dados: SQL e PostgreSQL ou MySQL.
- Ferramentas: Git, GitHub, terminal, testes e publicação.

**Sugestão para a trilha de fundamentos:** mantenha Java como linguagem principal para praticar algoritmos, estruturas de dados, orientação a objetos, concorrência e organização de sistemas. Python pode ser usado para experimentos, scripts e disciplinas em que a linguagem não é o foco.

Você não precisa abandonar as outras linguagens. Apenas defina uma stack de entrega e uma linguagem de estudo para não dividir a atenção sem necessidade.

## 3. Ritmo semanal sugerido

Um ritmo inicial sustentável é de **8 a 10 horas por semana**. Aumente ou reduza conforme sua rotina; a consistência vale mais que uma semana intensa seguida de abandono.

| Atividade | Tempo semanal sugerido |
|---|---:|
| Curso, livro e teoria | 3 h |
| Exercícios de programação | 2 h |
| Matemática | 1,5 h |
| Projeto prático / portfólio | 2 h |
| Revisão, documentação e planejamento | 0,5–1 h |

Se tiver apenas 5 horas, reduza a quantidade de conteúdo, não elimine os exercícios. Se tiver 15 horas, aumente sobretudo a prática e o projeto — não apenas a velocidade de reprodução de videoaulas.

## 4. Organização do seu ambiente de estudo

Crie um repositório privado ou público chamado `formacao-engenharia-software`. Sugestão de estrutura:

```text
formacao-engenharia-software/
├── README.md
├── diario/
│   ├── 2026-11.md
│   └── revisoes.md
├── matematica/
├── logica-algoritmos/
├── estruturas-dados/
├── engenharia-software/
├── bancos-dados/
├── sistemas-operacionais/
├── redes/
└── projetos/
```

Para cada disciplina, mantenha:

- `resumo.md`: explicações com suas próprias palavras;
- `exercicios/`: enunciados, código e testes;
- `experimentos.md`: medições, hipóteses e resultados;
- `referencias.md`: livros, aulas e documentação consultados.

Não transforme o repositório em um depósito de anotações copiadas. Registre decisões, dúvidas, erros encontrados e conclusões.

---

# PARTE II — ROTEIRO DE APRENDIZAGEM

# ETAPA 0 — Diagnóstico e reorganização da base

**Duração indicativa:** 1 a 2 semanas.  
**Objetivo:** descobrir quais fundamentos você lembra e quais precisa reconstruir.

## Conteúdo para revisar

- Tipos de dados, variáveis e expressões;
- condições e laços;
- funções, parâmetros e retorno;
- arrays/listas e matrizes;
- objetos, classes e interfaces;
- leitura e escrita de arquivos;
- tratamento de erros;
- SQL básico;
- HTTP, requisições e respostas;
- Git: `clone`, `status`, `add`, `commit`, `push`, `pull`, branches e merge.

## Materiais

- [Curso em Vídeo — Algoritmos e Lógica de Programação](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) — use como revisão seletiva, não precisa assistir a tudo se já domina o conteúdo.
- [Bóson Treinamentos — Curso completo de Lógica de Programação com Português Estruturado](https://www.youtube.com/watch?v=XzkZO2qjgec) — curso único, com capítulos de lógica, variáveis, condições, laços, vetores, busca, ordenação, funções e recursividade.
- [Rocketseat Discover](https://www.rocketseat.com.br/discover) — curso gratuito e curto para revisar web, Git/GitHub e construir um projeto inicial. Como você já programa, use apenas os módulos que preencherem lacunas.
- [MDN — Aprendendo desenvolvimento web](https://developer.mozilla.org/pt-BR/docs/Learn_web_development) — referência prática em português para HTML, CSS e JavaScript.

## Exercícios de diagnóstico

Implemente em Java, sem copiar uma solução pronta:

1. Verificar se um número é par ou ímpar.
2. Encontrar o maior e o menor valor de uma lista.
3. Calcular média, mediana e frequência de valores.
4. Verificar se uma palavra é palíndromo.
5. Contar ocorrências de cada caractere em uma frase.
6. Ordenar uma lista sem chamar o método de ordenação pronto.
7. Ler e salvar dados em arquivo.
8. Criar um pequeno cadastro com operações de adicionar, listar, atualizar e remover.

Depois, faça uma versão com testes automatizados simples ou, pelo menos, casos de teste registrados.

## Critério para avançar

Você consegue escrever funções pequenas, decompor um problema, testar entradas inválidas e explicar seu código sem precisar consultar um tutorial a cada passo. Se não conseguir, repita apenas os tópicos fracos da Etapa 0.

---

# ETAPA 1 — Preparação para trabalhos iniciais e entrega de aplicações web

**Duração indicativa:** 6 a 12 semanas, dependendo das lacunas.  
**Objetivo:** transformar seus conhecimentos existentes em capacidade de entregar pequenos projetos de maneira profissional.

Esta etapa vem cedo de propósito. Você não precisa esperar dominar toda a teoria para montar portfólio e procurar serviços de escopo pequeno.

## 1.1. Fundamentos de front-end que precisam estar sólidos

- HTML semântico e estrutura de documentos;
- formulários, validação e acessibilidade básica;
- CSS: cascata, especificidade, flexbox, grid, responsividade;
- JavaScript: escopo, funções, objetos, arrays, módulos;
- DOM e eventos;
- `fetch`, Promises e `async/await`;
- tratamento de falhas de rede;
- armazenamento local e limites de segurança;
- consumo de APIs;
- React: componentes, props, estado, efeitos, formulários e composição, se for sua stack escolhida.

### Materiais

- [MDN — Aprendendo desenvolvimento web](https://developer.mozilla.org/pt-BR/docs/Learn_web_development)
- [MDN — Introdução ao HTML](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Structuring_content)
- [MDN — Primeiros passos com CSS](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Styling_basics)
- [MDN — Guia JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide)
- [React — Início rápido (documentação em português)](https://pt-br.react.dev/learn)
- [Curso em Vídeo — HTML5 e CSS3](https://www.youtube.com/@CursoemVideo/playlists) — procure as playlists de HTML5/CSS3; use como complemento prático.

## 1.2. Fundamentos de back-end e APIs

- HTTP: métodos, códigos de status, cabeçalhos e corpo;
- APIs REST e contratos de requisição/resposta;
- validação de dados no servidor;
- organização de rotas, controladores, serviços e persistência;
- autenticação e autorização em nível introdutório;
- variáveis de ambiente e configuração;
- logs e tratamento de erros;
- paginação, filtros e ordenação;
- documentação de endpoints;
- noções de CORS, cookies e sessões.

### Materiais

- [MDN — HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP)
- [MDN — Guia JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide)
- [Node.js — site oficial em português](https://nodejs.org/pt-br/)
- [Documentação do React em português](https://pt-br.react.dev/learn)
- [Curso completo de Engenharia de Software — Crescencio Lima / IFBA](https://www.youtube.com/watch?v=JbgKl9eIQgY) — assistir mais tarde os capítulos de requisitos, arquitetura, testes e DevOps; não é um curso de back-end, mas ensina o processo de engenharia.

## 1.3. SQL e modelagem inicial

- `SELECT`, `INSERT`, `UPDATE`, `DELETE`;
- `WHERE`, `ORDER BY`, `GROUP BY` e funções de agregação;
- `JOIN`;
- chaves primárias e estrangeiras;
- relacionamentos 1:1, 1:N e N:N;
- restrições e integridade dos dados;
- normalização básica;
- transações introdutórias.

### Materiais

- [Curso em Vídeo — Banco de Dados MySQL](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r)
- [Bóson Treinamentos — Curso de Modelagem de Dados](https://www.youtube.com/playlist?list=PLucm8g_ezqNoNHU8tjVeHmRGBFnjDIlxD)
- [PostgreSQL — tutorial oficial](https://www.postgresql.org/docs/current/tutorial.html) — referência oficial; a versão em português pode ser consultada na [tradução comunitária do PostgreSQL 18.1](https://pgdocptbr18-11aacb.gitlab.io/).

## 1.4. Git, GitHub e fluxo de trabalho

Domine:

- commits pequenos e descritivos;
- branches e merge;
- resolução de conflitos;
- `.gitignore`;
- tags e releases;
- pull requests;
- revisão de código;
- issues e quadro simples de tarefas;
- não enviar senhas, tokens ou arquivos de configuração sensíveis ao repositório.

### Material

- [Pro Git — livro oficial em português](https://git-scm.com/book/pt-br/v2)
- [Documentação de referência do Git em português](https://git-scm.com/docs/git/pt_BR)

## 1.5. Testes e publicação inicial

Aprenda a:

- criar testes para regras importantes;
- testar formulário e validação;
- testar falhas de API;
- verificar layout em telas pequenas;
- publicar uma aplicação;
- configurar variáveis de ambiente;
- criar backup do banco;
- documentar instalação e execução.

Não precisa começar com Kubernetes, microsserviços ou automação complexa. Primeiro publique uma aplicação simples e mantenha-a funcionando.

## Projetos desta etapa

### Projeto A — Site institucional para um negócio fictício ou real

Requisitos:

- layout responsivo;
- seções bem organizadas;
- formulário com validação;
- acessibilidade básica;
- SEO básico;
- carregamento rápido;
- publicação com domínio ou URL pública;
- README com objetivo, funcionalidades, tecnologias e instruções.

### Projeto B — Painel administrativo CRUD

Pode ser um catálogo de produtos, gerenciamento de serviços ou cadastro de clientes fictícios.

Requisitos:

- front-end separado da lógica de dados;
- API;
- banco SQL;
- criar, listar, atualizar e excluir registros;
- paginação ou filtros;
- validação no servidor;
- mensagens de erro compreensíveis;
- testes das regras mais importantes.

### Projeto C — Aplicação com requisito real

Converse com alguém que tenha uma pequena necessidade: controlar ordens de serviço, organizar estoque simples, cadastrar equipamentos ou gerenciar agendamentos. Escreva os requisitos antes de programar e valide o resultado com a pessoa.

## Quando começar a procurar trabalhos

Você já pode testar propostas pequenas quando conseguir:

- receber um pedido e transformá-lo em escopo escrito;
- estimar o que será entregue e o que ficará fora;
- construir uma página responsiva sem tutorial passo a passo;
- usar Git e manter o projeto organizado;
- publicar e testar o resultado;
- explicar limitações e riscos;
- corrigir problemas depois da entrega.

Comece com escopos simples e explícitos. Não aceite prazos impossíveis, não prometa segurança que não sabe garantir e não assuma processamento de pagamentos ou dados críticos por conta própria.

---

# ETAPA 2 — Lógica, algoritmos e resolução de problemas

**Duração indicativa:** 2 a 5 meses, estudando em paralelo com os projetos web.  
**Objetivo:** desenvolver raciocínio independente e aprender a projetar soluções, não apenas escrever sintaxe.

## 2.1. Ordem dos conceitos

1. representação de um problema;
2. entradas, saídas e restrições;
3. decomposição em subproblemas;
4. pseudocódigo e fluxogramas;
5. variáveis e tipos;
6. expressões e operadores;
7. condições;
8. repetições;
9. funções, parâmetros e retorno;
10. arrays e matrizes;
11. busca linear e binária;
12. ordenação básica;
13. recursividade;
14. análise de complexidade inicial;
15. correção e casos de borda.

## 2.2. Aulas e livros gratuitos

- [Curso em Vídeo — Curso de Algoritmos](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV)
- [Bóson — Lógica de Programação do zero ao avançado (8h+)](https://www.youtube.com/watch?v=XzkZO2qjgec)
- [Algoritmos: primeiros passos — UTFPR, e-book gratuito](https://repositorio.utfpr.edu.br/jspui/handle/1/38761)
- [Lógica de Programação — material didático da Rede e-Tec / ProEdu](https://proedu.rnp.br/handle/123456789/704)
- [Algoritmos em Linguagem C — Paulo Feofiloff, IME-USP](https://users.ime.usp.br/~pf/algoritmos-livro/) — inclui versão PDF gratuita e é mais adequado depois de uma primeira experiência de programação. Embora use C, os conceitos de projeto e análise de algoritmos são transferíveis.

## 2.3. Exercícios obrigatórios

Para cada tema, faça primeiro em pseudocódigo e depois em Java:

- calcular média, mínimo, máximo e mediana;
- contar frequência de letras e palavras;
- inverter uma sequência;
- verificar palíndromos;
- encontrar elementos repetidos;
- busca linear e busca binária;
- implementar bubble sort, selection sort e insertion sort;
- implementar Fibonacci iterativo e recursivo;
- encontrar o segundo maior valor;
- mesclar duas listas ordenadas;
- validar datas e intervalos;
- decompor um número em fatores primos;
- resolver problemas com matriz.

Não basta obter a resposta certa. Escreva a complexidade temporal e espacial, teste entradas vazias, valores extremos e casos inválidos.

## 2.4. Onde praticar

- [beecrowd — problemas em português](https://judge.beecrowd.com/pt) — escolha inicialmente os problemas de nível mais baixo e avance gradualmente.
- [Neps Academy — exercícios de programação](https://neps.academy/br/exercises) — boa opção para praticar por assunto e dificuldade.
- [OBI — Olimpíada Brasileira de Informática](https://olimpiada.ic.unicamp.br/) — procure a seção de prática e provas anteriores.
- [GitHub da Loiane — exercícios de estruturas de dados](https://github.com/loiane/estrutura-dados-algoritmos-java)

**Meta de prática:** resolver de 3 a 5 problemas por semana, com solução própria e revisão. Em vez de tentar resolver dezenas copiando respostas, investigue profundamente os que não conseguiu resolver.

## Critério para avançar

Você consegue decompor problemas médios, escolher estruturas básicas, explicar a solução, identificar casos de borda e comparar uma solução simples com outra mais eficiente.

---

# ETAPA 3 — Matemática desde a base, com foco em computação

**A matemática será estudada em paralelo por toda a formação.** Como você comentou que esqueceu conteúdos escolares, o percurso começa desde a aritmética. Não pule diretamente para matemática discreta.

## 3.1. Trilha de recuperação matemática

### Módulo A — Aritmética e fundamentos

Estude nesta ordem:

1. operações com números naturais, inteiros, racionais e decimais;
2. ordem das operações e uso de parênteses;
3. frações: simplificação, soma, subtração, multiplicação e divisão;
4. razão, proporção e regra de três;
5. porcentagem;
6. divisibilidade, números primos, MDC e MMC;
7. potências e raízes;
8. notação científica;
9. conversão de unidades;
10. arredondamento e precisão decimal.

**Aplicações na programação:** cálculos, validações, percentuais, paginação, conversões, limites numéricos e representação de dados.

Materiais:

- [Khan Academy — Matemática](https://pt.khanacademy.org/math)
- [Portal da Matemática / OBMEP](https://portaldaobmep.impa.br/)
- [OBMEP — frações, porcentagem e probabilidade](https://portaldaobmep.impa.br/index.php/modulo/ver?modulo=36)
- [OBMEP — razões e proporções](https://portaldaobmep.impa.br/index.php/modulo/ver?modulo=57)

### Módulo B — Álgebra básica

1. expressões algébricas;
2. simplificação de expressões;
3. equações de primeiro grau;
4. sistemas de equações;
5. equações de segundo grau;
6. produtos notáveis e fatoração;
7. inequações;
8. plano cartesiano;
9. conceito de função;
10. funções afim e quadrática;
11. funções exponenciais e logarítmicas.

**Aplicações:** fórmulas, relações entre variáveis, crescimento, análise de custo e interpretação de complexidade algorítmica.

Materiais:

- [Khan Academy — Álgebra](https://pt.khanacademy.org/math/algebra)
- [OBMEP — equações e inequações](https://portaldaobmep.impa.br/index.php/modulo/ver?modulo=44)
- [OBMEP — funções](https://portaldaobmep.impa.br/index.php/modulo/ver?modulo=101)

### Módulo C — Geometria e trigonometria úteis

1. perímetro, área e volume;
2. ângulos e polígonos;
3. coordenadas no plano;
4. distância entre pontos;
5. semelhança e escala;
6. seno, cosseno e tangente;
7. circunferência e radianos.

Geometria não é a primeira prioridade para desenvolvimento web, mas é útil em computação gráfica, jogos, interfaces espaciais, simulações e análise geométrica.

Material: [Khan Academy — Geometria](https://pt.khanacademy.org/math/geometry) e [Portal OBMEP](https://portaldaobmep.impa.br/).

## 3.2. Matemática discreta — essencial para computação

Só avance para o estudo formal depois de recuperar aritmética, álgebra básica e raciocínio lógico.

Estude:

- proposições e conectivos lógicos;
- tabelas-verdade;
- equivalências e implicações;
- predicados e quantificadores;
- conjuntos e operações;
- relações e funções;
- princípios de contagem;
- permutações e combinações;
- indução matemática;
- recorrências;
- relações de ordem e equivalência;
- grafos e árvores;
- álgebra booleana.

Materiais gratuitos:

- [Matemática Discreta — livro digital UECE no EduCAPES (PDF)](https://educapes.capes.gov.br/handle/capes/432209)
- [Matemática Discreta — IFCE no EduCAPES (PDF)](https://educapes.capes.gov.br/handle/capes/430206)
- [Matemática Discreta — IFCE, registro e licença](https://educapes.capes.gov.br/handle/capes/430194)
- [UNIVESP — Fundamentos Matemáticos da Computação](https://integra.univesp.br/courses/2341/modules) — a página apresenta videoaulas sobre matemática discreta; o acesso pode depender das condições da plataforma.

Livro pago recomendado:

- **Paulo Blauth Menezes — Matemática Discreta para Computação e Informática**, 4ª edição, Bookman. É um livro em português voltado diretamente a computação. [Consultar edição e ISBN](https://biblioteca.iftm.edu.br/acervo/detalhe/19925).

## 3.3. Probabilidade, estatística e álgebra linear

Depois da matemática discreta, estude:

**Probabilidade e estatística:** eventos, probabilidade condicional, distribuições, média, mediana, variância, desvio padrão, amostragem e correlação.

**Álgebra linear:** vetores, matrizes, operações, sistemas lineares, produto escalar, transformações lineares e autovalores em nível introdutório.

Esses assuntos ganham importância em análise de dados, inteligência artificial, aprendizado de máquina, gráficos, jogos, simulações e otimização.

## 3.4. Cálculo: quando estudar?

Cálculo diferencial e integral é importante para certas especializações, mas não é pré-requisito para começar a trabalhar como desenvolvedor web nem para construir a maioria dos sistemas de negócio.

Estude limites, derivadas, integrais e otimização quando avançar para IA/aprendizado de máquina, computação científica, gráficos, simulação ou pesquisa que exija esses métodos.

## 3.5. Como praticar matemática

- Faça exercícios no papel antes de levar o problema ao código.
- Explique o raciocínio em cada etapa.
- Refaça os exercícios errados alguns dias depois.
- Use o teste de módulo da OBMEP para verificar domínio.
- Relacione o conceito a um programa pequeno: porcentagem em um orçamento, matrizes para uma grade, probabilidade em uma simulação ou grafos para rotas.

**Meta:** não é terminar rapidamente o conteúdo escolar; é recuperar segurança para acompanhar disciplinas universitárias e compreender algoritmos.

---

# ETAPA 4 — Estruturas de dados e análise de algoritmos

**Duração indicativa:** 3 a 6 meses, depois da base de lógica; continue praticando ao longo da carreira.  
**Objetivo:** compreender como organizar dados e por que certas soluções escalam melhor que outras.

## 4.1. Conteúdo em ordem

1. arrays e matrizes;
2. listas encadeadas;
3. pilhas e filas;
4. tabelas hash;
5. árvores binárias;
6. árvores de busca e balanceamento;
7. heaps e filas de prioridade;
8. grafos;
9. busca em largura e profundidade;
10. ordenação e busca;
11. recursão e divisão e conquista;
12. algoritmos gulosos;
13. programação dinâmica;
14. análise assintótica e notação Big O;
15. prova informal de corretude, invariantes e análise de casos.

## 4.2. Aulas e prática

- [Loiane Groner — Estruturas de Dados e Algoritmos com Java](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi)
- [UNIVESP — Estrutura de Dados](https://www.youtube.com/playlist?list=PLxI8Can9yAHf8k8LrUePyj0y3lLpigGcl)
- [Repositório da Loiane com exercícios e código](https://github.com/loiane/estrutura-dados-algoritmos-java)
- [Paulo Feofiloff — Algoritmos em Linguagem C, livro e PDFs](https://users.ime.usp.br/~pf/algoritmos-livro/)
- [beecrowd](https://judge.beecrowd.com/pt) e [Neps Academy](https://neps.academy/br/exercises)

## 4.3. Exercícios de implementação

Implemente manualmente, sem usar a estrutura pronta da biblioteca na primeira versão:

- lista encadeada simples e dupla;
- pilha e fila;
- tabela hash com tratamento de colisões;
- árvore binária de busca;
- heap mínimo;
- grafo com lista de adjacência;
- busca em largura e profundidade;
- busca binária;
- três algoritmos de ordenação;
- algoritmo de menor caminho em grafo ponderado.

Depois compare sua implementação com as estruturas prontas da biblioteca padrão do Java. Registre complexidade de busca, inserção, remoção e memória.

## Critério para avançar

Você consegue escolher uma estrutura justificando operações esperadas, volume dos dados, custo de memória e complexidade — e sabe reconhecer quando uma estrutura simples é suficiente.

---

# ETAPA 5 — Orientação a objetos, modelagem e design de software

**Objetivo:** deixar de organizar aplicações apenas em arquivos e funções e aprender a estruturar sistemas com responsabilidades claras.

## 5.1. Orientação a objetos

Estude:

- classes e objetos;
- encapsulamento;
- abstração;
- herança e composição;
- polimorfismo;
- interfaces e contratos;
- classes abstratas;
- generics;
- tratamento de exceções;
- imutabilidade;
- coesão e acoplamento;
- princípios de responsabilidade única.

Materiais:

- [Curso em Vídeo — POO com Java](https://www.youtube.com/playlist?list=PLHz_AreHm4dkqe2aR0tQK74m8SFe-aGsY)
- [UNIVESP — Programação Orientada a Objetos](https://www.youtube.com/playlist?list=PLxI8Can9yAHewZWSrlhpId71bk5N_W7W1)

## 5.2. Princípios de projeto

Estude e pratique:

- SOLID;
- DRY, KISS e YAGNI;
- separação de responsabilidades;
- baixo acoplamento e alta coesão;
- composição sobre herança, quando apropriado;
- encapsulamento de regras de negócio;
- Dependency Injection;
- princípios de design orientado a domínio em nível introdutório.

## 5.3. UML e modelagem

Aprenda a produzir e interpretar:

- diagrama de casos de uso;
- diagrama de classes;
- diagrama de sequência;
- diagrama de atividades;
- diagrama de estados;
- diagrama de componentes;
- diagrama de implantação.

Não faça diagramas por obrigação. Use-os para esclarecer decisões, comunicar o desenho e registrar partes que precisam ser entendidas por outras pessoas.

## 5.4. Padrões de projeto

Comece entendendo o problema e só depois conheça os padrões:

- Strategy;
- Factory Method e Abstract Factory;
- Builder;
- Adapter;
- Decorator;
- Observer;
- State;
- Command;
- Repository;
- Facade.

Exercício: implemente um mesmo requisito usando duas estratégias diferentes, compare a complexidade e explique por que escolheu uma delas. Não force padrões onde uma função simples resolveria melhor.

---

# ETAPA 6 — Engenharia de Software: o processo completo de construir e evoluir sistemas

**Objetivo:** aprender a pensar no ciclo de vida inteiro do produto, não apenas na implementação.

## 6.1. Disciplina principal: Engenharia de Software Moderna

- [Engenharia de Software Moderna — Marco Tulio Valente (livro online gratuito)](https://engsoftmoderna.info/)
- [Capítulo de abertura e abordagem do livro](https://engsoftmoderna.info/cap0.html)
- [Página do DCC/UFMG sobre o livro](https://dcc.ufmg.br/3706/)

Este é o **livro-base recomendado** para a disciplina. Ele tem versão HTML gratuita, 395 páginas, 10 capítulos e 125 exercícios de fixação, além de exemplos e materiais de apoio. Use o índice e resolva os exercícios; não leia passivamente.

## 6.2. Complemento em vídeo

- [Crescencio Lima / IFBA — Engenharia de Software do zero (mais de 7 horas)](https://www.youtube.com/watch?v=JbgKl9eIQgY)
- [UNIVESP — Engenharia de Software, disciplina universitária](https://www.youtube.com/playlist?list=PLxI8Can9yAHfeoA_yMm9iKJVxQprljmL9)

Assista ao Crescencio Lima para obter uma visão organizada de processos, requisitos, arquitetura, configuração, testes, TDD/BDD, evolução, padrões e DevOps. Use o livro de Marco Tulio Valente para aprofundar e praticar.

## 6.3. Requisitos e produto

Estude:

- identificação de usuários e partes interessadas;
- entrevistas e observação;
- requisitos funcionais e não funcionais;
- regras de negócio;
- histórias de usuário;
- casos de uso;
- critérios de aceitação;
- priorização;
- rastreabilidade;
- controle de mudanças;
- validação com usuários.

Exercício: antes de alterar o GamerWiki ou iniciar um módulo do NihilDynamics, escreva o problema, o usuário, os requisitos, as restrições, os casos de uso e os critérios de aceitação.

## 6.4. Processos, métodos e gestão

Estude os fundamentos de:

- ciclo de vida de software;
- desenvolvimento incremental e iterativo;
- cascata e suas limitações;
- Scrum;
- Kanban;
- XP;
- planejamento e estimativas;
- gestão de riscos;
- gestão de configuração;
- dívida técnica;
- comunicação em equipe.

Não decore cerimônias. Entenda que problema cada prática tenta resolver e quando ela é útil.

## 6.5. Documentação e decisões

Pratique:

- README de instalação e uso;
- documentação de API;
- diagramas de arquitetura;
- registro de decisões arquiteturais (ADR);
- notas de versão;
- instruções de backup e recuperação;
- guia de contribuição.

## Exercícios da disciplina

1. Escreva os requisitos de um sistema de biblioteca.
2. Faça casos de uso e critérios de aceitação.
3. Identifique requisitos não funcionais de desempenho, segurança, disponibilidade e acessibilidade.
4. Faça um diagrama de componentes.
5. Registre três decisões arquiteturais com alternativas e consequências.
6. Simule uma mudança de requisito e documente seu impacto.
7. Analise um projeto seu e identifique dívida técnica.

---

# ETAPA 7 — Bancos de dados em profundidade

**Objetivo:** sair de CRUD básico e compreender modelagem, integridade, concorrência e desempenho.

## Conteúdo

- modelagem conceitual, lógica e física;
- normalização e desnormalização;
- chaves, restrições e integridade referencial;
- SQL avançado, subconsultas, CTEs e funções de janela;
- índices e estruturas internas;
- planos de execução;
- transações e propriedades ACID;
- níveis de isolamento;
- locks, deadlocks e concorrência;
- backup e recuperação;
- replicação e particionamento;
- noções de bancos NoSQL e seus casos de uso.

## Materiais

- [Bóson — Modelagem de Dados](https://www.youtube.com/playlist?list=PLucm8g_ezqNoNHU8tjVeHmRGBFnjDIlxD)
- [Curso em Vídeo — MySQL](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r)
- [Tutorial oficial do PostgreSQL](https://www.postgresql.org/docs/current/tutorial.html)
- [Tradução comunitária da documentação do PostgreSQL 18.1](https://pgdocptbr18-11aacb.gitlab.io/)

Livro pago de referência:

- **Ramez Elmasri e Shamkant Navathe — Sistemas de Banco de Dados**, 6ª edição em português. É uma obra extensa e teórica; consulte bibliotecas universitárias antes de comprar. [Consultar registro bibliográfico](https://biblioteca.iftm.edu.br/Acervo/Detalhe/2089).

## Exercícios

1. Modele um sistema com pelo menos seis entidades relacionadas.
2. Explique a cardinalidade de cada relação.
3. Crie o banco e as restrições.
4. Escreva consultas que usem `JOIN`, agrupamentos e subconsultas.
5. Crie índices e compare planos de execução.
6. Simule duas transações concorrentes alterando os mesmos dados.
7. Teste rollback e falhas no meio de operações.
8. Faça backup e restaure em outra instância.

---

# ETAPA 8 — Testes, qualidade, refatoração e manutenção

**Objetivo:** construir software verificável e que possa evoluir sem quebrar o que já funciona.

## Conteúdo

- testes unitários;
- testes de integração;
- testes de sistema e aceitação;
- testes end-to-end;
- testes de regressão;
- testes de carga e desempenho;
- testes de contrato;
- testes baseados em propriedades;
- TDD e BDD;
- mocks e stubs;
- cobertura e limites da cobertura;
- análise estática;
- revisão de código;
- depuração e profiling;
- refatoração e code smells;
- manutenção de código legado.

## Materiais

- [Crescencio Lima / IFBA — Qualidade de Software do zero (mais de 6 horas)](https://www.youtube.com/watch?v=fN3bxqICfvw)
- [Engenharia de Software Moderna — livro gratuito](https://engsoftmoderna.info/)
- [Fundamentos de Manutenção de Software — Marco Tulio Valente](https://manutencaosoftware.org/) — livro online com capítulos e exercícios.

## Exercícios

- Escreva testes antes de corrigir um bug reproduzível.
- Refatore uma função longa em partes menores mantendo os testes verdes.
- Crie testes para entradas nulas, vazias, inválidas e extremas.
- Introduza deliberadamente um defeito e verifique se a suíte detecta.
- Analise um código legado e escreva um plano de refatoração gradual.
- Faça uma revisão de código como se fosse avaliar o trabalho de outra pessoa.

## Livro pago recomendado

- **Martin Fowler — Refatoração: Aperfeiçoando o Design de Códigos Existentes**, 2ª edição. É um livro para quando você já programa e entende testes; não é leitura inicial. [Página da editora Novatec](https://novatec.com.br/livros/refatoracao/).

---

# ETAPA 9 — Arquitetura de computadores, sistemas operacionais e redes

**Objetivo:** compreender o ambiente real em que os programas são executados.

## 9.1. Arquitetura de computadores

Estude:

- representação binária e hexadecimal;
- complemento de dois;
- operações em bits;
- portas lógicas;
- CPU, registradores e instruções;
- ciclo de busca, decodificação e execução;
- memória cache, RAM e armazenamento;
- hierarquia de memória;
- interrupções e entrada/saída;
- noções de paralelismo.

Exercícios:

- converter números entre bases;
- representar números negativos em complemento de dois;
- implementar operações bit a bit;
- medir o impacto de acesso sequencial versus aleatório à memória;
- explicar o percurso de um programa do código-fonte à execução.

## 9.2. Sistemas operacionais

Estude:

- processos e threads;
- escalonamento;
- sincronização e concorrência;
- mutexes e semáforos;
- condições de corrida;
- deadlocks;
- gerenciamento de memória;
- memória virtual;
- pilha e heap;
- sistemas de arquivos;
- permissões;
- chamadas de sistema;
- virtualização e containers.

Material em vídeo:

- [UNIVESP — primeira aula de Sistemas Operacionais](https://www.youtube.com/watch?v=CCHZ_06DoEA) — use a busca do canal UNIVESP para localizar a sequência completa da disciplina.

Livro livre:

- [Wikilivros — Sistemas Operacionais](https://pt.wikibooks.org/wiki/Sistemas_operacionais)

## 9.3. Redes de computadores

Estude:

- modelos OSI e TCP/IP;
- endereçamento IPv4 e IPv6;
- máscara e sub-redes;
- DNS e DHCP;
- TCP e UDP;
- portas e sockets;
- HTTP e HTTPS;
- TLS;
- roteamento;
- NAT, proxy e firewall;
- latência, perda de pacotes e throughput;
- WebSockets e comunicação persistente.

Material em vídeo:

- [UNIVESP — primeira aula de Redes de Computadores](https://www.youtube.com/watch?v=1csTmCZj-io) — use a busca do canal UNIVESP para encontrar as demais aulas da disciplina.

Livro livre:

- [Wikilivros — Redes de Computadores](https://pt.wikibooks.org/wiki/Redes_de_computadores)

Exercícios:

- calcule sub-redes IPv4;
- use `ping`, `traceroute`/`tracert`, `nslookup`/`dig` e `curl`;
- inspecione uma requisição HTTP;
- explique o que acontece quando se abre uma URL no navegador;
- crie um servidor e um cliente TCP simples;
- simule timeout, desconexão e resposta inválida.

---

# ETAPA 10 — Segurança, implantação, DevOps e confiabilidade

**Objetivo:** colocar aplicações no ar com responsabilidade e conseguir mantê-las.

## Segurança de software

Estude:

- autenticação e autorização;
- controle de acesso;
- hashing de senhas;
- criptografia e TLS;
- gestão de sessão;
- gestão de segredos;
- validação de entradas;
- injeção SQL;
- XSS e CSRF;
- SSRF;
- exposição de dados;
- modelagem de ameaças;
- logs e auditoria;
- menor privilégio;
- atualização de dependências.

Material atual em português:

- [OWASP Top 10:2025 — português](https://top10.owasp.org/2025/pt-BR/)

Leia cada risco e, em um projeto local de laboratório, crie uma demonstração segura e controlada da falha e depois corrija-a. Nunca teste vulnerabilidades em sistemas de terceiros sem autorização.

## DevOps e implantação

Estude:

- Linux e shell;
- processos, permissões e serviços;
- variáveis de ambiente;
- Docker e containers;
- imagens e volumes;
- CI e CD;
- pipelines de teste;
- implantação e rollback;
- logs e métricas;
- backup e recuperação;
- infraestrutura como código em nível introdutório.

Materiais:

- [Git — livro Pro Git em português](https://git-scm.com/book/pt-br/v2)
- [GitHub Actions — integração contínua em português](https://docs.github.com/pt/actions/get-started/continuous-integration)
- [GitHub Actions — implantação contínua em português](https://docs.github.com/pt/actions/get-started/continuous-deployment)
- [Docker — documentação de início](https://docs.docker.com/get-started) — pode ser apresentada em inglês; use a tradução automática do navegador como apoio e aprenda os termos técnicos originais gradualmente.

## Confiabilidade e observabilidade

Estude:

- logs estruturados;
- métricas;
- tracing;
- alertas;
- disponibilidade;
- tolerância a falhas;
- recuperação de desastre;
- SLIs, SLOs e SLAs;
- análise de incidentes;
- post-mortem sem caça a culpados.

Exercício: publique uma aplicação, desligue deliberadamente uma dependência em ambiente de teste, observe os erros, registre a causa, recupere o serviço e escreva um relatório do incidente.

---

# ETAPA 11 — Arquitetura avançada e sistemas distribuídos

**Objetivo:** desenvolver capacidade de projetar sistemas maiores, com múltiplos componentes e falhas parciais.

Só aprofunde depois de conhecer APIs, redes, bancos de dados, concorrência e implantação.

## Conteúdo

- monólitos modulares;
- arquitetura em camadas;
- arquitetura hexagonal;
- Clean Architecture;
- arquitetura orientada a eventos;
- mensageria e filas;
- comunicação síncrona e assíncrona;
- idempotência;
- retries e backoff;
- circuit breaker;
- load balancing;
- cache distribuído;
- replicação e particionamento;
- consistência eventual;
- tolerância a falhas;
- consenso e coordenação distribuída em nível conceitual;
- escalabilidade horizontal e vertical;
- observabilidade distribuída.

## Exercícios de arquitetura

1. Projete um sistema de pedidos como monólito modular.
2. Desenhe seus componentes, dados e contratos.
3. Defina métricas de desempenho e requisitos não funcionais.
4. Analise o que acontece se o banco ficar indisponível.
5. Torne operações importantes idempotentes.
6. Simule processamento duplicado de mensagens.
7. Compare uma arquitetura monolítica e uma distribuída: custo, complexidade, equipe, implantação e operação.
8. Registre as decisões em ADRs.

Não transforme todo projeto em microsserviços. A arquitetura deve responder às necessidades observadas, não ao desejo de usar tecnologias famosas.

---

# ETAPA 12 — Especialização e profundidade

Depois de formar uma base geral, escolha uma ou duas áreas para aprofundar por anos. Você pode explorar várias, mas não precisa tentar ser especialista em todas.

| Especialização | Conhecimentos adicionais importantes |
|---|---|
| Backend e arquitetura | APIs, bancos, concorrência, segurança, sistemas distribuídos, observabilidade |
| Front-end | JavaScript profundo, navegador, acessibilidade, desempenho, arquitetura de interfaces, UX |
| Engenharia de sistemas | C/C++, memória, sistemas operacionais, redes, arquitetura de computadores |
| Jogos e motores | C++, matemática linear, geometria, trigonometria, física e desempenho |
| IA e aprendizado de máquina | Python, estatística, probabilidade, álgebra linear, cálculo, avaliação de modelos |
| Segurança | redes, sistemas operacionais, criptografia, engenharia reversa, modelagem de ameaças |
| Compiladores | linguagens formais, autômatos, gramáticas, árvores sintáticas e teoria da computação |
| Dados | SQL avançado, modelagem, estatística, processamento distribuído e governança |

---

# PARTE III — LIVROS: O QUE LER E EM QUE ORDEM

## Livros e materiais gratuitos em português

| Livro/material | Assunto | Acesso |
|---|---|---|
| Algoritmos: primeiros passos — Paulo Augusto Nardi, UTFPR | Algoritmos, pseudocódigo e introdução à programação | [E-book/PDF no repositório da UTFPR](https://repositorio.utfpr.edu.br/jspui/handle/1/38761) |
| Algoritmos em Linguagem C — Paulo Feofiloff, IME-USP | Projeto, implementação e análise de algoritmos | [Página oficial com PDF](https://users.ime.usp.br/~pf/algoritmos-livro/) |
| Lógica de Programação — Victorio Albani de Carvalho, ProEdu/RNP | Lógica e programação | [Material didático com arquivos PDF](https://proedu.rnp.br/handle/123456789/704) |
| Matemática Discreta — UECE, EduCAPES | Matemática discreta | [Livro digital/PDF](https://educapes.capes.gov.br/handle/capes/432209) |
| Matemática Discreta — IFCE, EduCAPES | Lógica, contagem e grafos | [Livro digital/PDF](https://educapes.capes.gov.br/handle/capes/430206) |
| Engenharia de Software Moderna — Marco Tulio Valente | Práticas, projeto, arquitetura, testes e processos | [Livro completo em HTML, gratuito](https://engsoftmoderna.info/) |
| Fundamentos de Manutenção de Software — Marco Tulio Valente | Evolução, manutenção, legado e refatoração | [Livro online](https://manutencaosoftware.org/) |
| Pro Git | Controle de versões e Git | [Livro em português](https://git-scm.com/book/pt-br/v2) |
| Sistemas Operacionais — Wikilivros | Introdução a sistemas operacionais | [Livro livre online](https://pt.wikibooks.org/wiki/Sistemas_operacionais) |
| Redes de Computadores — Wikilivros | Fundamentos de redes | [Livro livre online](https://pt.wikibooks.org/wiki/Redes_de_computadores) |

**Sobre PDFs:** os links acima apontam para repositórios institucionais ou materiais publicados como recursos abertos. Não recomendo baixar cópias de livros comerciais hospedadas sem autorização. Quando um livro pago tiver apenas uma prévia autorizada, use a prévia ou consulte uma biblioteca.

## Livros pagos que valem considerar

Não compre tudo de uma vez. Use os materiais gratuitos primeiro e compre uma obra quando ela resolver uma necessidade concreta.

| Livro | Quando comprar | Por que vale considerar |
|---|---|---|
| **Entendendo Algoritmos — Aditya Bhargava, 2ª edição (2026)** | Etapa 2–4 | Explicação visual e acessível de busca, ordenação, grafos, árvores e análise de desempenho. [Editora Novatec](https://novatec.com.br/livros/entendendo-algoritmos-2ed/) |
| **Matemática Discreta para Computação e Informática — Paulo Blauth Menezes, 4ª edição** | Etapa 3–4 | Texto em português voltado a fundamentos matemáticos para computação. [Registro bibliográfico](https://biblioteca.iftm.edu.br/acervo/detalhe/19925) |
| **Engenharia de Software — Ian Sommerville, 10ª edição brasileira** | Etapa 6 | Referência universitária ampla sobre processos, requisitos, arquitetura, confiabilidade e evolução. [Dados da edição](https://www.touchelivros.com.br/edicoes/engenharia-de-software-ian-sommerville-4c938c8e4eaa/) |
| **Engenharia de Software: uma Abordagem Profissional — Roger Pressman** | Etapa 6–8 | Outra referência abrangente; compare com Sommerville antes de comprar, pois não precisa dos dois imediatamente. [Edições em português](https://www.touchelivros.com.br/edicoes/engenharia-de-software-uma-abordagem-profissional-roger-s-pressman-756fa34043ae/) |
| **Refatoração — Martin Fowler, 2ª edição** | Etapa 8 | Excelente para aprender a melhorar código existente sem alterar seu comportamento. [Editora Novatec](https://novatec.com.br/livros/refatoracao/) |
| **Sistemas de Banco de Dados — Elmasri e Navathe** | Etapa 7 | Tratamento amplo e acadêmico de modelagem e bancos relacionais. Consulte bibliotecas antes de comprar. [Registro bibliográfico](https://biblioteca.iftm.edu.br/Acervo/Detalhe/2089) |
| **Algoritmos — Cormen, Leiserson, Rivest e Stein, 4ª edição** | Etapa 4 ou especialização | Referência extensa e rigorosa. É cara e não é necessária para começar; compre apenas quando quiser estudar algoritmos com profundidade acadêmica. [Editora GEN](https://www.grupogen.com.br/livro-algoritmos-thomas-cormen-9788595159907) |

### Ordem de leitura recomendada

1. **Algoritmos: primeiros passos** — para consolidar a entrada em algoritmos.
2. **Entendendo Algoritmos** — para ganhar intuição sobre estruturas e algoritmos.
3. **Matemática Discreta** — em paralelo com algoritmos mais avançados.
4. **Engenharia de Software Moderna** — livro-base da disciplina de engenharia.
5. **Fundamentos de Manutenção de Software** — depois de já ter um projeto com código que precise evoluir.
6. **Refatoração** — quando já tiver testes e experiência em manter código.
7. **Sommerville ou Pressman** — para aprofundamento acadêmico e consulta.
8. **Cormen** — quando quiser rigor maior em análise de algoritmos.

---

# PARTE IV — EXERCÍCIOS: COMO ENCONTRAR, RESOLVER E AVALIAR

## 1. Plataformas para programação

- [beecrowd](https://judge.beecrowd.com/pt): problemas classificados por dificuldade; bom para lógica e algoritmos.
- [Neps Academy](https://neps.academy/br/exercises): exercícios por assunto e nível.
- [OBI](https://olimpiada.ic.unicamp.br/): provas e problemas de programação competitiva.
- [Repositório de exercícios da Loiane](https://github.com/loiane/estrutura-dados-algoritmos-java): exercícios associados à playlist de estruturas de dados.
- [GitHub — repositórios de exercícios Java](https://github.com/topics/java-exercises): use com critério; prefira repositórios com enunciados, testes e soluções explicadas.

## 2. Como buscar exercícios por assunto

Use pesquisas específicas, por exemplo:

- `exercícios de lógica de programação com gabarito PDF universidade`;
- `lista de exercícios Java arrays e matrizes PDF`;
- `exercícios de recursividade com soluções comentadas`;
- `exercícios de estruturas de dados pilhas filas listas Java`;
- `lista de exercícios matemática discreta lógica proposicional PDF`;
- `exercícios de modelagem entidade relacionamento banco de dados`;
- `exercícios de engenharia de requisitos casos de uso`;
- `exercícios de teste unitário JUnit Java`.

Dê preferência a materiais de universidades, institutos federais, livros didáticos, documentação oficial e repositórios com licença clara.

## 3. Protocolo obrigatório para cada exercício

1. Leia o enunciado e reescreva o problema com suas palavras.
2. Identifique entradas, saídas, restrições e casos especiais.
3. Crie exemplos pequenos manualmente.
4. Escreva uma solução em pseudocódigo ou descreva os passos.
5. Implemente sem olhar uma solução completa.
6. Teste casos normais, limites e entradas inválidas.
7. Analise complexidade e consumo de memória quando aplicável.
8. Se travar, consulte uma dica ou documentação, não copie imediatamente a resposta.
9. Feche a solução e tente reescrevê-la de memória.
10. Registre o erro que cometeu e como o identificou.

## 4. Como usar IA sem prejudicar seu raciocínio

- Primeiro tente sozinho por um período definido.
- Peça uma pista, não o código completo.
- Se receber código, explique cada parte e questione as decisões.
- Reimplemente sem copiar a resposta.
- Peça casos de teste que você não considerou.
- Faça a IA criticar sua solução, mas verifique as críticas.
- Não aceite bibliotecas, padrões ou arquiteturas sem entender por que foram usados.

A IA deve funcionar como tutor, revisor e ferramenta de investigação — não como substituta da sua capacidade de resolver problemas.

---

# PARTE V — PROJETOS DE PORTFÓLIO EM ORDEM CRESCENTE

## Projeto 1 — Página institucional bem acabada

**Demonstra:** HTML, CSS, JavaScript, responsividade, acessibilidade, comunicação com cliente e publicação.

Entrega mínima:

- requisitos curtos;
- layout para celular e desktop;
- formulário validado;
- conteúdo semântico;
- desempenho e acessibilidade básicos;
- URL publicada;
- README e capturas de tela.

## Projeto 2 — Sistema CRUD com banco de dados

Exemplos: catálogo de jogos, estoque simples, cadastro de equipamentos ou gerenciamento de serviços.

**Demonstra:** front-end, back-end, API, SQL, validação, estrutura, testes e tratamento de erros.

Entrega mínima:

- modelo de dados;
- requisitos e critérios de aceitação;
- API documentada;
- validação no servidor;
- testes automatizados;
- paginação e filtros;
- instruções de execução;
- deploy seguro, sem credenciais no código.

## Projeto 3 — Aplicação com usuários e permissões

**Demonstra:** autenticação, autorização, sessões, controle de acesso, auditoria básica e segurança.

Não implemente seu próprio sistema de pagamento. Não armazene senhas em texto puro. Utilize mecanismos e bibliotecas consolidadas e siga suas documentações.

## Projeto 4 — Projeto colaborativo

**Demonstra:** issues, branches, pull requests, revisão de código, resolução de conflitos, documentação e comunicação.

Convide outra pessoa para contribuir ou participe de um projeto open source pequeno e bem definido.

## Projeto 5 — Evolução e desempenho

Pegue uma aplicação existente e:

- estabeleça uma linha de base de desempenho;
- encontre um gargalo mensurável;
- crie testes antes da alteração;
- aplique uma melhoria;
- compare os resultados;
- documente os trade-offs.

## Como usar seus projetos atuais

- **GamerWiki:** laboratório de produto web, requisitos, UX, autenticação, APIs, modelagem de dados, testes e arquitetura.
- **NihilDynamics:** laboratório de modularidade, orientação a objetos, compatibilidade, extensibilidade, gerenciamento de estado, desempenho e manutenção.

Não tente transformar os dois em projetos gigantes ao mesmo tempo. Escolha um foco por ciclo de estudo e registre o que cada projeto está ensinando.

---

# PARTE VI — CHECKPOINTS DE EVOLUÇÃO

## Checkpoint A — Pronto para serviços pequenos / primeira oportunidade inicial

Você consegue:

- transformar uma necessidade simples em escopo;
- construir uma interface responsiva;
- desenvolver CRUD e integrar com banco;
- consumir ou criar uma API;
- validar dados no cliente e no servidor;
- usar Git sem perder o histórico;
- testar os fluxos principais;
- publicar a aplicação;
- escrever README e explicar limitações;
- corrigir problemas depois da entrega.

Isso não garante contratação, mas é um conjunto concreto de capacidades para começar a buscar tarefas pequenas e vagas iniciais.

## Checkpoint B — Base sólida de desenvolvimento

Você consegue:

- resolver problemas de lógica sem tutorial;
- implementar estruturas de dados básicas;
- explicar complexidade;
- modelar bancos de dados;
- escrever testes unitários e de integração;
- refatorar com segurança;
- modelar requisitos;
- justificar decisões de arquitetura;
- ler código de outras pessoas;
- investigar falhas de aplicação.

## Checkpoint C — Profissional de software autônomo

Você consegue:

- assumir uma funcionalidade do requisito até a produção;
- identificar riscos e requisitos não funcionais;
- desenhar componentes e contratos;
- testar casos de falha;
- observar e diagnosticar um sistema em produção;
- avaliar desempenho;
- planejar manutenção e migrações;
- colaborar com uma equipe;
- documentar decisões técnicas.

## Checkpoint D — Profundidade avançada

Você consegue, em sua área de especialização:

- ler e compreender material técnico avançado;
- avaliar decisões arquiteturais complexas;
- identificar trade-offs não óbvios;
- diagnosticar problemas de concorrência, rede, dados ou desempenho;
- propor experimentos e validar hipóteses;
- contribuir para bibliotecas, ferramentas ou projetos relevantes;
- orientar outras pessoas com explicações fundamentadas.

---

# PARTE VII — PLANO DOS PRIMEIROS 90 DIAS

Este é o ponto de partida prático. Não espere concluir todo o currículo para começar.

## Semanas 1–2: diagnóstico e organização

- [ ] Fazer os exercícios da Etapa 0.
- [ ] Identificar os assuntos fracos.
- [ ] Criar o repositório de formação.
- [ ] Revisar Git e GitHub.
- [ ] Escolher uma stack principal de entrega web.
- [ ] Escolher Java como linguagem de prática de fundamentos.
- [ ] Iniciar matemática pela aritmética, sem pular lacunas.

**Entrega:** repositório organizado e relatório pessoal de lacunas.

## Semanas 3–4: consolidar o básico útil para trabalho

- [ ] Revisar HTML semântico e CSS responsivo.
- [ ] Revisar JavaScript, DOM, eventos e chamadas HTTP.
- [ ] Revisar SQL e modelagem básica.
- [ ] Praticar Git com branches e commits.
- [ ] Resolver 6–10 exercícios de lógica, conforme dificuldade.

**Entrega:** página institucional responsiva publicada.

## Semanas 5–8: API, banco de dados e qualidade

- [ ] Criar API para um CRUD.
- [ ] Modelar banco relacional.
- [ ] Implementar validação no servidor.
- [ ] Tratar erros e estados vazios.
- [ ] Escrever testes das regras importantes.
- [ ] Documentar como executar o projeto.
- [ ] Continuar matemática básica.

**Entrega:** aplicação CRUD publicada, com README, banco e testes.

## Semanas 9–12: transformar projeto em portfólio

- [ ] Revisar segurança básica.
- [ ] Corrigir acessibilidade e responsividade.
- [ ] Melhorar mensagens de erro e experiência de uso.
- [ ] Registrar requisitos e decisões.
- [ ] Fazer uma pequena refatoração com testes.
- [ ] Publicar uma demonstração e capturas de tela.
- [ ] Revisar currículo e apresentação do projeto.
- [ ] Começar a procurar oportunidades pequenas e realistas.

**Entrega:** dois projetos apresentáveis e uma descrição honesta do que você sabe fazer.

---

# PARTE VIII — ROTINA DE ESTUDO E REVISÃO

## Modelo de sessão de estudo (60–90 minutos)

1. **10 minutos:** recordar sem olhar as anotações o que estudou anteriormente.
2. **20–30 minutos:** teoria ou videoaula.
3. **25–40 minutos:** exercícios ou implementação.
4. **5–10 minutos:** registrar o que entendeu, onde travou e o próximo passo.

## Revisão semanal

No fim de cada semana, responda:

- O que consigo explicar sem consultar o material?
- Quais exercícios resolvi sozinho?
- Em qual problema precisei de ajuda e por quê?
- Que erro ou conceito me surpreendeu?
- O projeto avançou em algo verificável?
- O que ficou pendente?
- Qual é a próxima entrega pequena?

## Revisão mensal

A cada quatro semanas:

- escolha um exercício antigo e resolva novamente;
- revise o projeto e remova problemas de qualidade que já sabe corrigir;
- registre uma decisão técnica que aprendeu a justificar;
- escolha um conceito para explicar por escrito;
- reduza ou reorganize o plano se estiver acumulando conteúdo sem praticar.

---

# PARTE IX — BIBLIOTECA DE LINKS RÁPIDOS

## Vídeos e playlists

| Tema | Material |
|---|---|
| Lógica e algoritmos | [Curso em Vídeo — Algoritmos](https://www.youtube.com/playlist?list=PLHz_AreHm4dmSj0MHol_aoNYCSGFqvfXV) |
| Lógica aprofundada | [Bóson — curso completo de 8h+](https://www.youtube.com/watch?v=XzkZO2qjgec) |
| Estruturas de dados Java | [Loiane Groner](https://www.youtube.com/playlist?list=PLGxZ4Rq3BOBrgumpzz-l8kFMw2DLERdxi) |
| Estruturas de dados universitárias | [UNIVESP](https://www.youtube.com/playlist?list=PLxI8Can9yAHf8k8LrUePyj0y3lLpigGcl) |
| Orientação a objetos Java | [Curso em Vídeo](https://www.youtube.com/playlist?list=PLHz_AreHm4dkqe2aR0tQK74m8SFe-aGsY) |
| Orientação a objetos universitária | [UNIVESP](https://www.youtube.com/playlist?list=PLxI8Can9yAHewZWSrlhpId71bk5N_W7W1) |
| Engenharia de Software | [UNIVESP](https://www.youtube.com/playlist?list=PLxI8Can9yAHfeoA_yMm9iKJVxQprljmL9) |
| Engenharia de Software | [Crescencio Lima / IFBA — curso completo](https://www.youtube.com/watch?v=JbgKl9eIQgY) |
| Qualidade e testes | [Crescencio Lima / IFBA — curso completo](https://www.youtube.com/watch?v=fN3bxqICfvw) |
| Modelagem de dados | [Bóson Treinamentos](https://www.youtube.com/playlist?list=PLucm8g_ezqNoNHU8tjVeHmRGBFnjDIlxD) |
| MySQL | [Curso em Vídeo](https://www.youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r) |
| Sistemas operacionais | [UNIVESP — primeira aula](https://www.youtube.com/watch?v=CCHZ_06DoEA) |
| Redes de computadores | [UNIVESP — primeira aula](https://www.youtube.com/watch?v=1csTmCZj-io) |

## Documentação e referências

| Tema | Referência |
|---|---|
| HTML, CSS e Web | [MDN em português](https://developer.mozilla.org/pt-BR/docs/Learn_web_development) |
| JavaScript | [Guia MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide) |
| HTTP | [MDN — HTTP](https://developer.mozilla.org/pt-BR/docs/Web/HTTP) |
| React | [React — aprender](https://pt-br.react.dev/learn) |
| Git | [Pro Git em português](https://git-scm.com/book/pt-br/v2) |
| PostgreSQL | [Documentação oficial](https://www.postgresql.org/docs/current/) |
| Segurança Web | [OWASP Top 10 2025 em português](https://top10.owasp.org/2025/pt-BR/) |
| Integração contínua | [GitHub Actions](https://docs.github.com/pt/actions/get-started/continuous-integration) |
| Implantação contínua | [GitHub Actions](https://docs.github.com/pt/actions/get-started/continuous-deployment) |
| Java | [Oracle — downloads e documentação JDK](https://www.oracle.com/br/java/technologies/downloads/) |

## Exercícios

- [beecrowd](https://judge.beecrowd.com/pt)
- [Neps Academy](https://neps.academy/br/exercises)
- [Olimpíada Brasileira de Informática](https://olimpiada.ic.unicamp.br/)
- [Portal da OBMEP](https://portaldaobmep.impa.br/)
- [Exercícios da Loiane](https://github.com/loiane/estrutura-dados-algoritmos-java)

---

# Observações finais

1. Os prazos são estimativas para organizar o estudo, não promessas de empregabilidade nem datas rígidas. Avance pelos critérios de domínio, não apenas pelo calendário.
2. A trilha foi desenhada para manter materiais principais em português. Alguns projetos e documentações técnicas podem oferecer conteúdo parcial em inglês; não deixe isso bloquear o estudo, use a versão traduzida do navegador quando necessário e aprenda os termos técnicos gradualmente.
3. Links de playlists e documentação podem mudar com o tempo. Se um link de vídeo deixar de funcionar, procure o título e o canal indicados no YouTube.
4. Use livros gratuitos de repositórios institucionais e materiais com licença aberta. Não confunda um PDF encontrado em qualquer site com uma cópia legalmente disponibilizada.
5. O objetivo não é acumular certificados. É conseguir demonstrar conhecimento por meio de código, testes, documentação, decisões justificadas e projetos mantidos ao longo do tempo.

**Princípio que deve guiar toda a formação:** não pergunte apenas “como faço isso funcionar?”. Pergunte também “por que funciona, quais são as limitações, como provo que está correto, como falha e como posso evoluí-lo sem quebrar o que já existe?”.
