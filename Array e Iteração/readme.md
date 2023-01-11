<h3>Array.from()</h3>
<p><strong>Array.from()</strong> é um método utilizado para transformar array-like objects, em uma array.</p>

<h3>Array.isarray()</h3>
<p>Verifica se o valor passado é uma array e retorna um valor booleano.
</p>

<h3><strong>Array.of()</strong>, <strong>Array()</strong> e <strong>new Array()</strong></h3>
<p>A palavra chave new não é necessária para utilizar o construtor Array.
</p>

<h3>[].sort()</h3>
<p>Os próximos métodos que vamos falar sobre, são métodos modificadores (mutator methods). Além de retornarem um valor, eles modificam a array original. <strong>[].sort()</strong> organiza a pelo unicode.
</p>

<h3>[].unshift() e [].push()</h3>
<p><strong>[].unshift()</strong> adiciona elementos ao início da array e retorna o length da mesma. <strong>[].push()</strong> adiciona elementos ao final da array e retorna o length da mesma.
</p>

<h3>[].shift e [].pop</h3>
<p><strong>[].shift()</strong> remove o primeiro elemento da array e retorna o mesmo. <strong>[].pop()</strong> remove o último elemento da array e retorna o mesmo.
</p>

<h3>[].reverse</h3>
<p><strong>[].reverse()</strong> inverte os itens da array e retorna a nova array.
</p>

<h3>[].splice()</h3>
<p><strong>[].splice(index, remover, item1, item2, ...)</strong> adiciona valores na array a partir do index. Remove a quantidade de itens que for passada no segundo parâmetro (retorna esses itens).
</p>

<h3>[].copywithin()</h3>
<p><strong>[].copyWithin(alvo, inicio, final)</strong> a partir do alvo, ele irá copiar a array começando do inicio até o final e vai preencher a mesma com essa cópia. Caso omita os valores de início e final, ele irá utilizar como inicio o 0 e final o valor total da array.
</p>

<h3>[].fill()</h3>
<p><strong>[].fill(valor, inicio, final)</strong> preenche a array com o valor, do início até o fim.
</p>

<h3>[].concat()</h3>
<p>Os métodos abaixo não modificam a array original, apenas retornam uma array modificada. <strong>[].concat()</strong> irá concatenar a array com o valor passado.</p>

<h3>[].includes(), [].indexof() e [].lastindexof()</h3>
<p><strong>[].includes(valor) verifica se a array possui o valor e retorna true ou false. <strong>[].indexOf(valor)</strong> verifica se a array possui o valor e retorna o index do primeiro valor na array. Já o <strong>[].lastIndexOf(valor)</strong> retorna o index do último.
</p>

<h3>[].join()</h3>
<p><strong>[].join(separador)</strong> junta todos os valores da array e retorna uma string com eles. Se você passar um valor como parâmetro, este será utilizado durante a junção de cada item da array.
</p>

<h3>[].slice()</h3>
<p><strong>[].slice(inicio, final)</strong> retorna os itens da array começando pelo início e indo até o valor de final.
</p>

