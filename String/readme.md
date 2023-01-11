<h3>str.<span style="color:red;">length</span></h3>
<p>Propriedade com o tal de caracteres da string</p>

<h3>str.<span>charAt</span>(n)</h3>
<p>Retorna o caracter de acordo com o index de (n).</p>

<h3>str.<span>concat</span>(str2, str3, ...)</h3>
<p>Concatena as strings e retorna o resultado.</p>

<h3>str.<span>includes</span>(search, position)</h3>
<p>Procura pela string exata dentro de outra string. A procura é case sensitive.</p>

<h3>str.<span>endwith</span>(search) e str.<span>startwith</span>(search)</h3>
<p>Procura pela string exata dentro de outra string. A procura é case sensitive.</p>

<h3>str.<span>slice</span>(start, end)<h3>
<p>Corta a string de acordo com os valores de start e end.</p>

<h3>str.<span>substring</span>(start, end)</h3>
<p>Corta a string de acordo com os valores de start e end. Não funciona com valores negativos como o slice.</p>

<h3>str.<span>indexof</span>(search) e str.<span>lastindexof</span>(search)</h3>
<p>Retorna o index da string, assim que achar o primeiro resultado ele já retorna. No caso do lastIndexOf ele retorna o último resultado.</p>

<h3>str.<span>padstart</span>(n, str) e str.<span>padend</span>(n, str)</h3>
<p>Aumenta o tamanho da string para o valor de n. Ou seja, uma string com 8 caracteres, se passarmos n = 10, ela passará a ter 10 caracteres. O preenchimento é feito com espaços, caso não seja declarado o segundo argumento.</p>

<h3>str.<span>repeat</span>(n)</h3>
<p>Repete a string (n) vezes.</p>

<h3>str.<span>replace</span>(regexp|substr, newstr|function)</h3>
<p>Troca parte da string por outra. Podemos utilizar uma regular expression ou um valor direto. Se usarmos um valor direto ele irá trocar apenas o primeiro valor que encontrar.</p>

<h3>str.<span>split</span>(padrao)</h3>
<p>Divide a string de acordo com o padrão passado e retorna uma array.</p>

<h3>str.<span>toLowerCase</span>() e str.<span>toUpperCase</span>()</h3>
<p>Retorna a string em letras maiúsculas ou minúsculas. Bom para verificarmos input de usuários.</p>

<h3>str.<span>trim</span>(), str.<span>trimstart</span>(), str.<span>trimend</span>()</h3>
<p>Remove espaço em branco do início ou final de uma string.</p>
