Title: Hello World com Apache Jena
Date: 2017-08-30 7:30
Category: jena
Tags: rdf, jena
Authors: Elizabete Reis
Summary: Hello World com Apache Jena

#Hello World com Apache Jena


----------
Para realizar esta etapa foi utilizada a IDE Eclipse e a framework RDF. Inicialmente foi criado um projeto Java e as bibliotecas da framework foram importadas. A figura 1 ilustra o código do hello world e sua respectiva saída no console. 

![Hello World com RDF](content/images/jenatutorial.png)

Primeiramente é criado um recurso, não existe definição exata sobre o que é um recurso, alguns autores conceituam que é tudo que pode ser identificado. Um recurso é identificado por uma URI (Identificador Uniforme de Recurso) representada pela *String* NS, ele possui propriedades que para o exemplo anterior é um literal "hello world" do tipo *XSDstring*.

Por fim o model criado na linha 13 é utilizado na escrever numa *Outputstream* num formato pré definido, para o exemplo a saída é *System.out* e o formato *Turtle*. A saída pode ser vista no console.
