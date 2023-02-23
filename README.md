# Introdução à Programação Concorrente em Java

A programação concorrente, em que diversas atividades ou fios de execução num mesmo programa colaboram na resolução de um problema comum, tem uma importância crescente no contexto de sistemas distribuídos e da exploração do paralelismo existente em todos os sistemas de computação.

A programação concorrente com memória partilhada é, no entanto, reconhecidamente difícil, uma vez que os programas podem apresentar comportamentos que violam a sua especificação sequencial e escapam à intuição do programador.

Este texto tem como objetivo dar a conhecer, de uma forma prática, os problemas fundamentais da programação concorrente num modelo de memória partilhada, bem como as soluções baseadas em primitivas de monitores – trincos e variáveis de condição – no contexto da linguagem Java. É dada ênfase a um conjunto de idiomas e padrões que permitem a construção de programas corretos e com algumas preocupações quanto ao seu desempenho.

## Disponibilidade

A ultima versão deste texto está disponível aqui: [https://concjava.github.io/concjava.pdf](https://concjava.github.io/concjava.pdf)

Pode ser distribuído livremente de acordo com a licença [Creative Commons By-NC-ND](http://creativecommons.org/licenses/by-nc-nd/4.0/)

Agradecemos que nos [comuniquem quaisquer incorreções ou sugestões](https://github.com/concjava/concjava.github.io/issues).

## Utilizadores

Este texto é recomendado nos seguintes cursos:

* [Sistemas Distribuídos](https://www4.di.uminho.pt/~jno/sitedi/uc_J305N4.html) na LEI da [U. Minho](https://www.uminho.pt)
* [Sistemas Distribuídos](https://www4.di.uminho.pt/~jno/sitedi/uc_J605N2.html) na LETI/MIETI da [U. Minho](https://www.uminho.pt)
