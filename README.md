Esse .md significa "markdown", que é uma linguagem de estruturação de estilos 
em que podemos configurar nossas fontes de forma bem simples.

E esse arquivo readme (leia-me) é muito comum. Todo mundo que trabalha com projetos de desenvolvimento já viu, na hora que baixar esse repositório 
na minha máquina, eu já vou querer saber o que fica em cada diretório, como executo, se eu preciso de um banco de dados, etc. 
Normalmente, as informações principais estarão nesse arquivo readme. É lá que alguém vai ter definido o passo a passo para você poder colaborar nesse projeto.

# Markdown syntax guide

## Headers

# This is a Heading h1
## This is a Heading h2 
###### This is a Heading h6

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered

* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered

1. Item 1
1. Item 2
1. Item 3
  1. Item 3a
  1. Item 3b

## Images

![This is a alt text.](/image/sample.png "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.
