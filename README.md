<!-- #region id="cp3A7idIElnQ" -->
# <center>INTRODUÇÃO A LINGUAGEM MARKDOWN</center>


________________________
Por: Juliana A. Santos

🧑 💻 

[LinkedIn](https://www.linkedin.com/in/juliana-a-santos/)


[GitHub](https://github.com/Julibio7)

[Twitter](https://twitter.com/JuSantos7)

______________________


<!-- #endregion -->

<!-- #region id="BVAuEs1Sqcmz" -->
___________________________________
# **Markdown**


> ### O que é?
Markdown é uma linguagem de marcação, assim como o HTML. Ele é um jeito de escrever em texto puro, deixando anotações sobre a formatação.

__________________________________
<!-- #endregion -->

<!-- #region id="hLMP67gtWLFi" -->
# **Formatando texto**

## **Tamanhos de texto**
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
Alternativas, para H1 e *H2*:

```
Alt-H1
======

Alt-H2
------
```
<!-- #endregion -->

<!-- #region id="JMeRuwfMTVcu" -->
## **Cabeçalhos**

```
# Título
## Sub-título
### Sub-sub-título
```
Saída:
# Título
## Sub-título
### Sub-sub-título
<!-- #endregion -->

<!-- #region id="WmzU2JVOrayx" -->
## **Negrito** e *Itálico*

Para formatar o texto como negrito, coloque-o entre dois asteriscos, exemplo:

```
**O Oceano Antártico**
```
saída:

**O Oceano Antártico**

Para usar texto itálico use um underscore (_) ou só um asterisco(*).

```
*Aspergillus*
_Fusarium_
```
saída:

*Aspergillus*
_Fusarium_

Tudo em negrito e itálico

```
***Rosmarinus officinalis, Ocimum basilicum***
```

saída:

## **Negrito** e *Itálico*

Para formatar o texto como negrito, coloque-o entre dois asteriscos, exemplo:

```
**O Oceano Antártico**
```
saída:

**O Oceano Antártico**

Para usar texto itálico use um underscore (_) ou só um asterisco(*).

```
*Aspergillus*
_Fusarium_
```
saída:

***Rosmarinus officinalis, Ocimum basilicum***

<!-- #endregion -->

<!-- #region id="FEcpKpWCdW3H" -->

<!-- #endregion -->

<!-- #region id="FpkJGHZtuzN3" -->
## **Subscrito e  Sobrescrito**

subscrito

Para criar um subscrito, use um símbolo de til ( ~) antes e depois dos caracteres.


    H~2~O

<code>Para escrever H2O
       H~2~O
</code>

Sobrescrito
Para criar um sobrescrito, use um símbolo de acento circunflexo ( ^) antes e depois dos caracteres.

```
X^2^

```
<code> 
helo 
</code>


<!-- #endregion -->

<!-- #region id="NcCOT1qAC0oi" -->
#**Texto Marcado**
Para marcar um texto podemos usar a tag `<mark>`

```
Texto <mark>marcado</mark>

```
<!-- #endregion -->

<!-- #region id="zw-qjBbwEb46" -->
# **Listas**

## **Listas desordenada**


Para criar uma lista não ordenada com o markdown podemos usar tanto *, 

quanto — ou +, todos têm a mesma funcionalidade, 

para criar uma sublista, apenas insira dois espaço ou um tab no item, exemplo:


```
* Bactérias
* Fungos
  * Micro-organismos
  * Micologia
    * Leveduras
    * Fungos Filamentosos
```
A saída fica assim:

* Bactérias
* Fungos
  * Micro-organismos
  * Micologia
    * Leveduras
    * Fungos Filamentosos

<!-- #endregion -->

<!-- #region id="ZV99UMczGB8M" -->
## **Lista ordenada**
Para uma lista ordenada adicione os números:
```
1.  Fungos endofíticos
2.  Fungos micorrízicos
3.  Fungos ectomicorrízicos
```


<!-- #endregion -->

<!-- #region id="dIVt_WlxWq8Z" -->
## **Listas aninhadas**

```
1. Primeiro item da lista
    - Primeiro item da lista aninhada
      - Segundo item da lista aninhada
```
Saída:
1. Primeiro item da lista
    - Primeiro item da lista aninhada
      - Segundo item da lista aninhada
<!-- #endregion -->

<!-- #region id="ClQIsORYGmc0" -->
## **Lista de Tarefas**
Para uma lista de tarefas adicione os colchetes com espaço, para marcar adicione um X para marcar, exemplo:

```
- [ ] Preparar meio de cultivo
- [x] Autoclavar material
- [x] Fazer os inoculos 

```
A saída renderizada fica assim:
- [ ] Preparar meio de cultivo
- [x] Autoclavar material
- [x] Fazer os inoculos 


<!-- #endregion -->

<!-- #region id="VSaN_g40HHSI" -->
# **Link**
Para criar link [texto a ser exibido](link, “título”).

exemplo 1:
```
[Google](https://www.google.com,  "Site do Google")

```
exemplo 2:
```
[Meu link do LinkedIn](https://www.linkedin.com/in/juliana-a-santos/)
```
Saída:

[Meu link do LinkedIn](https://www.linkedin.com/in/juliana-a-santos/)


<!-- #endregion -->

<!-- #region id="KzgA95W5HYtg" -->
# **Imagens**
Também podemos adicionar referência nas imagens, exemplo:

```
Reference-style:
![alt text][logo]
<!-- Referencias -->
[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

```
Se quiser personalizar a altura ou largura da imagem use o html diretamente.

```

<img src="https://media.giphy.com/media/lPoxtQlcX30doRbHTN/giphy.gif" width="42" height="42">
```
<!-- #endregion -->

<!-- #region id="jYPZsxBgINWQ" -->

<!-- #endregion -->

<!-- #region id="EKjeD3gbIkLe" -->
# **Citação**

para adicionar citações adicione o sinal de maior que(>), exemplo:

```
>Texto usando citação
```
```
> 1 
>> 2 
>>> 3
>>>> 4 
>>>>>>>> 8

exemplo:
> "In an honest search for knowledge you quite often have to abide by ignorance for an indefinite period… The steadfastness in standing up to [this requirement], nay in appreciating it as a stimulus and a signpost to further quest, is a natural and indispensable disposition in the mind of a scientist.”
>> Erwin Schrodinger, Nature and the Greeks 

```
Saída:

> "In an honest search for knowledge you quite often have to abide by ignorance for an indefinite period… The steadfastness in standing up to [this requirement], nay in appreciating it as a stimulus and a signpost to further quest, is a natural and indispensable disposition in the mind of a scientist.”
>> Erwin Schrodinger, Nature and the Greeks 
 




<!-- #endregion -->

<!-- #region id="fXusj-LSJAdw" -->
# **Usando códigos**
Usando uma crase `, o texto ficará marcado, exemplo:

```
`code`
```
Saída : `code`


Para usar códigos grande use 3 crases,
 exemplo:


```python
a = python
print("a")
```



<!-- #endregion -->

<!-- #region id="sfjEfURDIP9R" -->
# **Linha Horizontal**

Para criar uma linha horizontal use 3 asteriscos ou sinal de hífen ou underscore.

```
---
***
___

```
<!-- #endregion -->

<!-- #region id="DsT3vnedIlfC" -->
# **Centralizando itens**

Para centralizar itens no markdown é necessário usar a tag `<center>`

```
<center>Item centralizado</center>

```
<!-- #endregion -->

<!-- #region id="fLYICE8uJ3vp" -->
# **Tabelas**
Escolha os títulos das colunas e use  `| ` para delimitar as colunas. Depois, utilize hífen — na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o `| `para delimitar colunas.
Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize : ao lado do campo horizontal de hífens `— -`, na segunda linha da sua tabela. 

Veja abaixo:


- **Alinhado a esquerda**`:` usar `:`no lado esquerdo (alinhamento padrão);
- **Alinhado a direita**`::` usar `:` no lado direito;
- **Centralizado**`:` usar `:` dos dois lados.

```
| Alinhado a esquerda | Centralizado | Alinhado a direita |
| :------------------ | :----------: | -----------------: |
| Valor               | Valor        | Valor              |
| Valor               | Valor        | Valor              |
| Valor               | Valor        | Valor              |

```
Saída:


| Alinhado a esquerda | Centralizado | Alinhado a direita |
| :------------------ | :----------: | -----------------: |
| Valor               | Valor        | Valor              |
| Valor               | Valor        | Valor              |
| Valor               | Valor        | Valor              |
<!-- #endregion -->

<!-- #region id="DzfEGtV-o5ZD" -->
**mais um exemplo de tabela**

<!-- #endregion -->

<!-- #region id="9-NyBF3Vo1w5" -->
Markdown | Preview
--- | ---
`**texto negrito**` | **texto negrito**
`*texto italico*` or `_texto italico_` | *texto italico*
`` `Monospace` `` | `Monospace`
`~~tachado~~` | ~~tachado~~
`[A link](https://www.google.com)` | [A link](https://www.google.com)
`![An image](https://images.vexels.com/media/users/3/152509/isolated/lists/e058e7f53d319e0628763c70ab7dce14-icone-do-planeta-jupiter.png)` | ![An image](https://images.vexels.com/media/users/3/152509/isolated/lists/e058e7f53d319e0628763c70ab7dce14-icone-do-planeta-jupiter.png)

<!-- #endregion -->

<!-- #region id="q33t63HHo4C1" -->

<!-- #endregion -->
