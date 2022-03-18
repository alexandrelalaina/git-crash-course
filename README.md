# Markdown Tutorial

## Indice

1. Headers

2. Itálicos, Negritos e Negritos Itálicos

3. Paragrafos com destaque 

4. Criação de Hyperlinks

5. Criação referencia

6. Criando Snippets de código

7. Listas não ordenadas

[8. Listas ordenadas](#listas-ordenadas)

[9. Sub-listas](#sub-listas)

[10. Figuras](#figuras)

## Headers

Sempre que escrevermos headers, devemos deixar linhas em branco entre eles. Os headers são representados pelo símbolo #.

Os headers têm 6 níveis que são representados pela quantidade de símbolos escritos. Exemplo:

# h1 teste edição

## h2

### h3

#### h4

##### h5

###### h6

## Itálicos, Negritos e Negritos Itálicos

Os negritos e itálicos são representados pelo símbolo * ou _.

Uma palavra cercada por 1 asterisco em cada lado terá seu formato modificado para *itálico*.

Uma palavra cercada por 2 asteriscos em cada lado terá seu formato modificado para **negrito**.

Uma palavra cercada por 3 asteriscos em cada lado terá seu formato modificado para ***negrito/itálico***.

## Parágrafo com destaque



Para escrever um parágrafo com destaque, utilizamos o símbolo >.



> Esse é um parágrafo destacado do resto do texto.
> Esse aqui também.
> e assim por diante.



Os paragráfos acima estão destacados do restante do texto escrito.


## Criação de hyperlinks



A criação de hyperlinks é feita através dos símbolos [](). Onde o conteúdo dos colchetes é o texto que será exibido e o conteúdo do parênteses é o link a ser redirecionado.
Ex: [Google](www.google.com)

[Voltar ao índice](#índice)



## Criando snippets de código
Para criar snippets de código (partes de código) basta utilizar o símbolo de crase 3 vezes junto com a linguagem do snippet.



```java
public static void main(String[] args){
System.out.println("Teste de snippet");
}
```



```python
def teste(){



}
```



```javascript
function bla(){
document.getElementById("teste");
}
```



```json
{
"firstName": "John",
"lastName": "Smith",
"age": 25
}
```


## Criação de auto-referências
Para criar uma referência a capítulos do próprio Markdown, utiliza-se os símbolos de hyperlink [](). Porém, diferente de hyperlinks externos onde dentro do parênteses, acrescenta-se a url desejada, para links internos colocamos o título do capítulo desejado --- se houver espaço no nome do capítulo, substitua-o por hífen --- com o símbolo # o precedendo.
Ex: [Tutorial Markdown](#tutorial-markdown)



[Voltar ao índice](#índice)



## Sub-listas
Para criação de sublistas utilizamos ambas a anotações explicadas acima junto com uma tabulação.
1. linha 1
- sub-item1
- sub-item2
2. linha 2
1. sub-linha2.1
2. sublinha2.2
3. linha 3



[Voltar ao índice](#índice)

## Figuras

Para acrescentar imagens no texto utiliza-se o símbolo ![](). Onde a exclamação indica uma figura, o conteúdo do colchetes indica o texto alternativo caso a imagem não seja carregada e entre parênteses temos o link da imagem.

![Logo do Git](https://www.bing.com/th?id=OIP.WUm5hluypRntFU9N0_j6ygHaHa&w=212&h=212&c=8&rs=1&qlt=90&o=6&dpr=1.35&pid=3.1&rm=2)

![Logo do Git Local](#indice)