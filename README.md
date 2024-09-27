ÁRVORES DIGITAIS


Introdução

  A busca digital desempenha um papel fundamental no processamento de
informações e na recuperação de dados. Nesse contexto, a chave de busca é um elemento
essencial, sendo geralmente constituída por um conjunto de caracteres ou dígitos definidos
em um alfabeto específico. A análise individual de cada dígito que compõe as chaves é
crucial ao realizar comparações durante o processo de busca. Quando lidamos com chaves
de tamanhos variáveis e maiores, os métodos digitais de pesquisa se destacam.
As Tries são estruturas de árvores ordenadas e n-árias. Os nós não armazenam as
chaves em si, mas a posição de cada nó na árvore determina a chave correspondente. Os
dados associados às chaves são armazenados nas folhas da Trie, e os índices são
caracteres de um alfabeto definido. Uma variante interessante das Tries é a Árvore Patrícia,
também conhecida como RADIX. Essa estrutura é uma representação compacta da Trie, na
qual os nós que teriam apenas um filho são agrupados em seus antecessores. A Árvore
Patrícia é particularmente útil quando se trabalha com chaves de tamanho variável,
especialmente se forem extremamente longas, como frases ou textos completos.

Desenvolvimento

  Na busca digital a chave não é tratada como um elemento indivisível, ou seja, cada
chave é constituída de um conjunto de caracteres ou dígitos definidos em um alfabeto
apropriado. Quando se faz uma comparação é analisado de forma individual entre os dígitos
que compõem as chaves, um por um. Em geral as chaves são associadas a elementos ou
registros, assim como na tabela hash.
A pesquisa digitar é feita a partir da representação das chaves como uma sequência
de caracteres ou dígitos. Os métodos digitais de pesquisa tem vantagens quando as chaves
são maiores e de tamanhos variáveis
As Tries são estruturas para suportar tarefas de tratamento léxico, como pesquisas
de texto de grande dimensão, construir índices em documentos, manusear dicionários. A
ideia das Tries é utilizar as chaves como caminho de busca, algumas de sua características
são:
● A raiz de uma Trie para qualquer outro nó representa um prefixo de uma string;
● No último nó, o último caractere da palavra sendo procurada deverá ter associação a
palavra no texto;
● As chaves são formadas por palavras sobre um alfabeto, possuindo tamanho
variável e ilimitado;
Sua estrutura é ordenada e n-ária, seus nós não armazenam as chaves, que são
determinadas pela posição na árvore, seus dados são armazenados na folha e seus índices
são caracteres de um alfabeto.


  A Árvore Patrícia, também conhecida como RADIX, é uma representação compacta
de uma Trie, em que os nós que teriam apenas um filho são agrupados nos seus
antecessores. Esse método irá ser melhor aproveitado quando for usar chaves de tamanho
variáveis extremamente longas, como frases.


