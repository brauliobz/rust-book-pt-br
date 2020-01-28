<!--
# Common Collections

Rust’s standard library includes a number of very useful data structures called
*collections*. Most other data types represent one specific value, but
collections can contain multiple values. Unlike the built-in array and tuple
types, the data these collections point to is stored on the heap, which means
the amount of data does not need to be known at compile time and can grow or
shrink as the program runs. Each kind of collection has different capabilities
and costs, and choosing an appropriate one for your current situation is a
skill you’ll develop over time. In this chapter, we’ll discuss three
collections that are used very often in Rust programs:
-->

# Coleções Comuns


A biblioteca padrão do Rust inclui uma série de estruturas de dados
chamadas *coleções*. A maioria dos tipos de dados representa um valor específico, mas
coleções podem conter múltiplos valores. Diferente dos tipos embutidos array e tupla,
os dados que essas coleções apontam estão guardados na heap, que significa
que a quantidade de dados não precisa ser conhecida em tempo de compilação e pode aumentar ou 
diminuir conforme a execução do programa. Cada tipo de coleção possui capacidades diferentes
e custos, e escolher o apropriada para cada tipo de situação em que se encontra é uma
habilidade que com o tempo você irá adquirir. Nesse capítulo, veremos três 
coleções que são usadas frequentemente em programas Rust:

<!--
* A *vector* allows you to store a variable number of values next to each other.
* A *string* is a collection of characters. We’ve mentioned the `String` type
  previously, but in this chapter we’ll talk about it in depth.
* A *hash map* allows you to associate a value with a particular key. It’s a
  particular implementation of the more general data structure called a *map*.
-->

* Um *vetor* possibilita guardar um número variável de valores um ao lado do outro.
* Uma *string* é uma sequência de caracteres. Já vimos o tipo `String`
  anteriormente, mas falaremos sobre ele em profundidade agora.
* Um *hash map* permite associar um valor a uma chave em particular. É uma
  implementação particular da estrutura de dados mais geral chamada de *map*.

<!--
To learn about the other kinds of collections provided by the standard library,
see [the documentation][collections].
-->
Para aprender mais sobre outros tipos de coleções fornecidas pela biblioteca padrão,
veja [a documentação][collections].

[collections]: ../std/collections/index.html

<!--
We’ll discuss how to create and update vectors, strings, and hash maps, as well
as what makes each special.
-->

Nós iremos discutir como criar e atualizar vetores, strings, e hash 
maps, bem como o que os tornam especiais.
