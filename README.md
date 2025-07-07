# Extrator-De-Palavras-valeria

https://valeriasophiagarcesmujica123.github.io/Extrator-De-Palavras-valeria/

Relatório do Projeto – Criando Unidade de Strings: Extraindo Palavras-chave de um Texto
1. Introdução
Este projeto tem como objetivo principal o desenvolvimento de uma aplicação web capaz de identificar e extrair palavras-chave de um texto fornecido pelo usuário. A proposta consiste em facilitar a análise textual, permitindo que os termos mais relevantes de um conteúdo sejam destacados automaticamente. Para isso, utilizou-se apenas tecnologias front-end: HTML, CSS e JavaScript, sem uso de back-end ou bibliotecas externas.

2. Tecnologias Utilizadas
HTML5: Estruturação da interface e campos de entrada.

CSS3: Estilização da página, com foco em usabilidade e visual limpo.

JavaScript (Vanilla JS): Lógica de extração das palavras-chave e manipulação do DOM.

3. Funcionamento da Aplicação
O usuário insere um texto no campo de entrada. Ao acionar o botão "Extrair Palavras-chave", o JavaScript executa os seguintes passos:

Tokenização: O texto é dividido em palavras com base em espaços e pontuação.

Normalização: As palavras são convertidas para minúsculas e limpas de caracteres especiais.

Remoção de palavras irrelevantes: Palavras muito comuns da língua portuguesa (stopwords), como "de", "e", "a", "o", "que", entre outras, são filtradas e removidas da lista.

Contagem de frequência: As palavras restantes são analisadas quanto à sua frequência no texto.

Seleção das palavras-chave: As palavras mais frequentes são apresentadas como resultado.

4. Resultados Esperados
Ao inserir um texto, o sistema retorna uma lista com as principais palavras-chave, organizadas por relevância (frequência de ocorrência). Por exemplo:

Entrada:

"A inteligência artificial está transformando a tecnologia em diversas áreas, como saúde, educação e transporte."

Saída:

["inteligência", "artificial", "tecnologia", "saúde", "educação", "transporte"]

5. Limitações
Não há lematização nem compreensão semântica (como identificar sinônimos).

O filtro de stopwords é básico e estático.

A análise é puramente baseada em frequência, não em contexto.

6. Conclusão
O projeto demonstrou ser funcional para tarefas simples de extração de palavras-chave, utilizando somente tecnologias de front-end. Ele pode ser útil em contextos educacionais, pequenas ferramentas de estudo, ou como base para sistemas mais robustos com integração de back-end ou bibliotecas de PLN.
