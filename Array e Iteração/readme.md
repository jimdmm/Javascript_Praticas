##**[].foreach()**##
<p>[].forEach(callback(itemAtual, index, array)) a função de callback é executada para cada item da array. Ela possui três argumentos, itemAtual (valor do item da array), index (index do valor na array) e array (array original).
</p>

<h3><strong>[].map()</strong></h3>
<p>[].map(callback(itemAtual, index, array)) funciona da mesma forma que o forEach(), porém ao invés de retornar undefined, retorna uma nova array com valores atualizados de acordo com o return de cada iteração.
</p>

<h3><strong>[].reduce()</strong></h3>
<p>[].reduce(callback(acumulador, valorAtual, index, array), valorInicial) executa a função de callback para cada item da Array. Um valor especial existe nessa função de callback, ele é chamado de acumulador, mas é na verdade apenas o retorno da iteração anterior.
</p>

<h3><strong>[].some()</strong></h3>
<p>[].some(), se pelo menos um return da iteração for truthy, ele retorna true.</p>

<h3><strong>[].every()</strong></h3>
<p>[].every(), se todos os returns das iterações forem truthy, o método irá retornar true. Se pelo menos um for falsy, ele irá retornar false.
</p>

<h3><strong>[].find()</strong><strong>[]findindex()</strong></h3>
<p>[].find(), retorna o valor atual da primeira iteração que retornar um valor truthy. Já o [].findIndex(), ao invés de retornar o valor, retorna o index deste valor na array.
</p>

<h3><strong>[].filter()</strong></h3>
<p>[].filter(), retorna uma array com a lista de valores que durante a sua iteração retornaram um valor truthy.
</p>
