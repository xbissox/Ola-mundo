# Olá mundo
  **Primeiro repositório de Git e Github**
 
 Adicionei este parágrafo diretamente no site! QUE IMPRESSIONANTE!

**Formatações de textos**
```
*itálico* **negrito** ~~tachado~~ e ***~~mesclado~~*** 
```

 Teste de *itálico* **negrito** ~~tachado~~ e pode-se mesclar ***~~todos~~***

**HEADERS**
```
 
# Título 1
## Título 2
### Título 3

Alt-H1
======

Alt-H2
------


```

# Título 1
## Título 2
### Título 3

Alt-H1
======

Alt-H2
------

**Listas**
```
1. Primeira item da lista ordenada
2. Outro item
⋅⋅* Sublista sem ordem
1. Não importa o numero atual
⋅⋅1. Sublista ordenada
4. E outro item

⋅⋅⋅Você consegue identar paragrafos sem itens de lista. Observe os espaços a esquerda e a cima que usaremos 3 aqui, para tabular os itens.

⋅⋅⋅Para ter uma quebra de linha de um grande parágrafo, utilizara desta forma com dois espaços a direita.⋅⋅
⋅⋅⋅Note que esta linha está separada, porem, sem ser o mesmo parágrafo.⋅⋅
⋅⋅⋅(Este é contrário ao típico GFM quebra de linha, onde não requer seguir espaços.)

* Não ordenada lista usando os asteriscos
- Ou o sinal de menos
+ Ou o sinal de mais
```
1. Primeira item da lista ordenada
2. Outro item
⋅⋅* Sublista sem ordem
1. Não importa o numero atual
⋅⋅1. Sublista ordenada
4. E outro item

⋅⋅⋅Você consegue identar paragrafos sem itens de lista. Observe os espaços a esquerda e a cima que usaremos 3 aqui, para tabular os itens.

⋅⋅⋅Para ter uma quebra de linha de um grande parágrafo, utilizara desta forma com dois espaços a direita.⋅⋅
⋅⋅⋅Note que esta linha está separada, porem, sem ser o mesmo parágrafo.⋅⋅
⋅⋅⋅(Este é contrário ao típico GFM quebra de linha, onde não requer seguir espaços.)

* Não ordenada lista usando os asteriscos
- Ou o sinal de menos
+ Ou o sinal de mais

1. Numerador 1
1. Numerador 2
1. Numerador 3
   1. Subnumerador 1
   1. Subnumerador 2
   1. Subnumerador 3

Marcadores simples
* Marcador 1
* Marcador 2
   * Submarcador 1
   * Submarcador 2
   
[ ] Outro tipo de marcadores   

**LINKS**
```
[Eu estou na linha de estilo do link](https://www.google.com)

[Eu estou na linha de estilo do link com título](https://www.google.com "Google's Homepage")

[Eu estou na referência de estilo do link][Arbitrary case-insensitive reference text]

[Eu estou numa referência relativa do repositorio de arquivo](../blob/master/LICENSE)

[Você consegue usar números para referencias de estilo do link de definição][1]

Ou leva vazio para usar ao próprio link [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
[Eu estou na linha de estilo do link](https://www.google.com)

[Eu estou na linha de estilo do link com título](https://www.google.com "Google's Homepage")

[Eu estou na referência de estilo do link][Arbitrary case-insensitive reference text]

[Eu estou numa referência relativa do repositorio de arquivo](../blob/master/LICENSE)

[Você consegue usar números para referencias de estilo do link de definição][1]

Ou leva vazio para usar ao próprio link [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

**Imagens**
```
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

**Code and Syntax Highlighting***
```
Inline `code` has `back-ticks around` it.
```
Inline `code` has `back-ticks around` it.

```
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
```
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

**Tabelas**
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

**Blockquotes**
```
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
```

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

**Inline HTML**
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

**Horizontal Rules**
```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores

**Line Breakers**
```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

**Youtube Videos**
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

OR

```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

**Finally!!**
