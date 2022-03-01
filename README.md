# Markdown para iniciantes

![markdownIcon](https://grafxflow.co.uk/storage/app/uploads/public/5ad/e5b/d9b/thumb_891_266_0_0_0_auto.png)

## Observações

Este arquivo apresenta um pequeno **RESUMO/TUTORIAL** sobre alguns conceitos importantes do Markdown que produzi a partir de algumas pesquisas na internet. Como ainda sou iniciante, e acredito que exista muitas pessoas na mesma situação que a minha, resolvi postar este documento no GitHub para caso alguém precise.

Lembrando que as fontes utilizadas para pesquisa estão no final do arquivo.

&nbsp;

## Sumário  

1. [Introdução](https://github.com/FrBreno/Markdown_Resumo#1-introdução)
2. [Linguagens de marcação](https://github.com/FrBreno/Markdown_Resumo#2-linguagens-de-marcação)
3. [Markdown](https://github.com/FrBreno/Markdown_Resumo#3-markdown)  
3.1. [Vantagens](https://github.com/FrBreno/Markdown_Resumo#31-vantagens)
4. [Como o Markdown funciona?](https://github.com/FrBreno/Markdown_Resumo#4-como-o-markdown-funciona)
5. [Sintaxe básica](https://github.com/FrBreno/Markdown_Resumo#5-sintaxe-básica)
6. [Elementos bloco](https://github.com/FrBreno/Markdown_Resumo#6-elementos-bloco)  
6.1. [Títulos](https://github.com/FrBreno/Markdown_Resumo#61-títulos)  
6.2. [Parágrafos](https://github.com/FrBreno/Markdown_Resumo#62-parágrafos)  
6.3. [Quebras de linha](https://github.com/FrBreno/Markdown_Resumo#63-quebras-de-linha)  
6.4. [Listas](https://github.com/FrBreno/Markdown_Resumo#64-listas)  
  6.4.1. [Listas não ordenadas](https://github.com/FrBreno/Markdown_Resumo#641-listas-não-ordenadas)  
  6.4.2. [Listas ordenadas](https://github.com/FrBreno/Markdown_Resumo#642-listas-ordenadas)  
6.5. [Aninhamento de listas](https://github.com/FrBreno/Markdown_Resumo#65-aninhamento-de-listas)  
6.6. [Bloco de citação](https://github.com/FrBreno/Markdown_Resumo#66-bloco-de-citação)  
6.7. [Blocos de código](https://github.com/FrBreno/Markdown_Resumo#67-blocos-de-código)  
6.8. [Linhas Horizontais](https://github.com/FrBreno/Markdown_Resumo#68-linhas-horizontais)  
6.9. [Tabelas](https://github.com/FrBreno/Markdown_Resumo#69-tabelas)  
7. [Elementos em linha](https://github.com/FrBreno/Markdown_Resumo#7-elementos-em-linha)  
7.1. [Ênfase](https://github.com/FrBreno/Markdown_Resumo#71-ênfase)  
7.1.1. [Itálico](https://github.com/FrBreno/Markdown_Resumo#711-itálico)  
7.1.2. [Negrito](https://github.com/FrBreno/Markdown_Resumo#712-negrito)  
7.1.3. [Itálico e negrito](https://github.com/FrBreno/Markdown_Resumo#713-itálico-e-negrito)  
7.2. [Código em linha (literal)](https://github.com/FrBreno/Markdown_Resumo#72-código-em-linha-literal)  
7.3. [Links](https://github.com/FrBreno/Markdown_Resumo#73-links)  
7.4. [Imagens](https://github.com/FrBreno/Markdown_Resumo#74-imagens)  
8. [Escape de símbolos](https://github.com/FrBreno/Markdown_Resumo#8-escape-de-símbolos)  
9. [HTML](https://github.com/FrBreno/Markdown_Resumo#9-html)  
10. [Dialetos de Markdown](https://github.com/FrBreno/Markdown_Resumo#10-dialetos-de-markdown)  
11. [Conclusão](https://github.com/FrBreno/Markdown_Resumo#11-conclusão)  

&nbsp;

## 1. Introdução

Markdown é uma linguagem de marcação leve e simples criada por John Gruber em 2004 com a colaborações de Aaron Swartz na sintaxe, e que hoje em dia é uma das linguagens de marcação mais populares do mundo.

&nbsp;

## 2. Linguagens de marcação

Linguagens de marcação são uma forma de anotação simples de um texto sem formatação de modo que ele se torne sintaticamente distinguível e possa ser manipulado por algum software.

A principal diferença entre a linguagem de marcação e a linguagem de programação é que uma linguagem de marcação define um conjunto de regras para codificação de documentos em um formato legível. As linguagens de marcação são projetadas para criar uma estrutura, identificar dados ou apresentar dados, em vez de executar uma ação.

O Markdown é uma linguagem de marcação bastante leve e simples, cuja sintaxe é muito menos _verbosa_ e muito mais legível do que outras linguagens, como o **HTML**, por exemplo.

&nbsp;

## 3. Markdown

A sintaxe de formatação do Markdown foi criada com o objetivo de ser o mais legível possível. Nessa linguagem não é necessário usar _tags_ de abertura e fechamento como em **HTML**, nem é preciso criar estilos de formatação.

### 3.1. Vantagens

- Praticidade

  O Markdown pode ser utilizado de diversas formas, como para criar sites, documentos, notas, livros, documentação técnica, documentação acadêmica, etc.

- Portabilidade

  Arquivos escritos em Markdown podem ser abertos com praticamente qualquer aplicativo.

- Independente de plataforma

  Texto formatado em Markdown pode ser criado em qualquer dispositivo que execute qualquer sistema operacional.

- Usabilidade

  Inúmeros sites da Web suportam Markdown, e muitos aplicativos de desktop e baseados na Web o suportam.

&nbsp;

## 4. Como o Markdown funciona?

Quando escrevemos em Markdown o texto é armazenada em um arquivo de texto simples com extensão _.md_ ou _.markdown_.

Para que um arquivo Markdown seja convertido em **HTML** ou em um documento pronto para impressão precisamos de um aplicativo Markdown capaz de processar o arquivo.

Os aplicativos Markdown usam algo chamado de processador Markdown para ler o texto Markdown e reescrevê-lo no formato **HTML**. E então o documento pode ser visualizado em um navegador da Web ou combinado com uma folha de estilos e ser impresso.

&nbsp;

## 5. Sintaxe básica

Assim como no **HTML**, no Markdown os elementos são separados entre elementos bloco (_Block_) e elementos em linha (_inline_ ou _span_).

**Elementos bloco** ocupam todo o espaço horizontal disponível, iniciam uma nova linha no documento e os novos elementos inseridos irão começar na próxima linha livre (elementos bloco podem conter elementos em linha e, às vezes, outros elementos bloco).

**Elementos em linha** ocupam apenas o espaço necessário e não iniciam uma nova linha. Geralmente, elementos em linha podem conter apenas conteúdo e outros elementos em linha (não é possível colocar elementos bloco dentro de elementos em linha).

&nbsp;

## 6. Elementos bloco

### 6.1. Títulos

```
  # Título 1
  ## Título 2
  ### Título 3
  #### Título 4
  ##### Título 5
  ###### Título 6
```

RESULTADO:

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

&nbsp;

Existe também uma sintaxe alternativa para os títulos de nível 1 e 2, com sinais de `=` e de `-` na linha de baixo do texto do título, da seguinte maneira:

```
  Título 1
  ========

  Título 2
  --------
```

&nbsp;

### 6.2. Parágrafos

Consiste em separar um parágrafo de outro ou de qualquer elemento bloco com uma linha vazia.

```
  Este é um parágrafo.

  Este é outro parágrafo.
  Este ainda é o segundo parágrafo.
```

&nbsp;

### 6.3. Quebras de linha

Basta deixar dois espaços em branco (teclar space duas vezes) ao fim da primeira linha e nenhuma linha vazia entre elas.

```
  Este é um parágrafo.
  Esta é a segunda linha do mesmo parágrafo.
```

&nbsp;

### 6.4. Listas

#### 6.4.1. Listas não ordenadas

Há três opções: `-`, `+` ou `*`.

```
 - Primeiro item da lista.
 - Segundo item da lista.

 + Primeiro item da lista.
 + Segundo item da lista.

 * Primeiro item da lista.
 * Segundo item da lista.
```

RESULTADO:

- Primeiro item da lista.
- Segundo item da lista.

* Primeiro item da lista.
* Segundo item da lista.

- Primeiro item da lista.
- Segundo item da lista.

&nbsp;

#### 6.4.2. Listas ordenadas

Basta adicionar um número seguido de um ponto e de um espaço antes do texto de cada item da lista. Pode ser qualquer número em qualquer ordem, ou pode até mesmo ser sempre o mesmo número.

```
  1. Primeiro da lista.
  1. Segundo da lista.
  1. Terceiro da lista.

  3. Primeiro da lista.
  7. Segundo da lista.
  2. Terceiro da lista.
```

RESULTADO:

1.  Primeiro da lista.
1.  Segundo da lista.
1.  Terceiro da lista.

&nbsp;

### 6.5. Aninhamento de listas

Basta indentar a lista aninhada com um tab ou quatro espaços. Isto vale tanto para listas ordenadas quanto para listas não ordenadas, e também é possível aninhar listas ordenadas em listas não ordenadas e vice versa.

```
  - Primeiro da lista não ordenada.
    - Sibitem
  - Segundo item da lista não ordenada.
```

RESULTADO:

- Primeiro da lista não ordenada.
  - Subitem
- Segundo item da lista não ordenada.

```
  1. Primeiro item da lista ordenada.
    1. Subitem.
  1. Segundo item da lista ordenada.
```

RESULTADO:

1. Primeiro item da lista ordenada.
   1. Subitem.
1. Segundo item da lista ordenada.

```
  - Primeiro item da lista não ordenada.
    1. Subitem ordenado.
    1. Outro subitem ordenado.
  - Segundo item da lista não ordenada.
```

RESULTADO:

- Primeiro item da lista não ordenada.
  1. Subitem ordenado.
  1. Outro subitem ordenado.
- Segundo item da lista não ordenada.

&nbsp;

### 6.6. Bloco de citação

Basta inserir um sinal de `>` antes de cada linha que faça parte do bloco e também na linha em branco, caso o bloco de citação possua mais de um parágrafo.

```
  Este é um parágrafo antes da citação:

  > Este é um bloco de citação aleatório com dois parágrafos. Lorem Ipsum é simplesmente uma simulação de texto da indústria tipográfica e de impressos, e vem sendo utilizado desde o século XVI.
  >
  > Lorem Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica, permanecendo essencialmente inalterado.
```

RESULTADO:

Este é um parágrafo antes da citação:

> Este é um bloco de citação aleatório com dois parágrafos. Lorem Ipsum é simplesmente uma simulação de texto da indústria tipográfica e de impressos, e vem sendo utilizado desde o século XVI.
>
> Lorem Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica, permanecendo essencialmente inalterado.

&nbsp;

### 6.7. Blocos de código

Utiliza-se ` ``` ` ou `~~~` para formar uma caixa de código (Pode-se colocar o nome da linguagem utilizada para uma melhor conversão de sintaxe).

```
  ` ` `
    Caixa de
    código
  ` ` `

  ~~~JavaScript
    console.log()
  ~~~
```

RESULTADO:

```
  Caixa de
  código
```

```JavaScript
  console.log()
```

&nbsp;

### 6.8. Linhas Horizontais

Basta colocar três ou mais sinais de `***`, `---` ou `___`.

RESULTADO:

---

&nbsp;

### 6.9. Tabelas

Utiliza-se `|` para delimitar as colunas. Depois, utilize hífen `-` na segunda linha para indicar que acima estão os títulos das colunas e adicione `|` novamente para delimitar colunas.

```
  Exemplo    | Valor do exemplo
  ---------- | ----------
  Exemplo 01 | R$ 10,00
  Exemplo 02 | R$ 8,00
  Exemplo 03 | R$ 7,50
```

RESULTADO:

| Exemplo    | Valor do exemplo |
| ---------- | ---------------- |
| Exemplo 01 | R$ 10,00         |
| Exemplo 02 | R$ 8,00          |
| Exemplo 03 | R$ 7,50          |

Podemos ainda, utilizar `:` ao lado do campo horizontal de hifens `---`, na segunda linha da tabela, para especificar o tipo de alinhamento de texto.

```
  Alin. a esquerda | Centralizada | Alin. a direita
  :----------- | :----: | -----------:
  valor | valor | valor
```

RESULTADO:  
Alin. a esquerda | Centralizada | Alin. a direita
:----------- | :----: | -----------:
valor | valor | valor

---

&nbsp;

## 7. Elementos em Linha

### 7.1. Ênfase

#### 7.1.1. Itálico

Basta envolver o texto com `*` ou `_`.

```
  *TEXTO* ou _TEXTO_
```

RESULTADO:

_TEXTO_

&nbsp;

#### 7.1.2. Negrito

Basta envolver o texto com dois `**` ou com dois `__`.

```
  **TEXTO** ou __TEXTO__
```

RESULTADO:

**TEXTO**

&nbsp;

#### 7.1.3. Itálico e negrito

Basta envolver o texto com três `***` ou com três `___`.

```
  ***TEXTO*** ou ___TEXTO___
```

RESULTADO:

**_TEXTO_**

&nbsp;

### 7.2. Código em linha (literal)

Basta envolver o código em sinais de crase.

```
  `Código`
```

RESULTADO:

`Código`

### 7.3. Links

Basta colocar o texto âncora do link entre `[]` e, na sequência, colocar o URL do link entre `()`. Opcionalmente, se quiser colocar o atributo HTML `title` ao link, basta colocar o texto do `title` entre `""`, após o URL, ainda dentro dos parêntesis.

```
  [Google](https://www.google.com "Acesse o Google!")
```

RESULTADO:

[Google](https://www.google.com 'Acesse o Google!')

Também é possível inserir _links_ com identificadores de referência, uma funcionalidade bastante útil quando se precisa inserir um mesmo _link_ diversas vezes na mesma página ou documento.

A referência do _link_ pode ser inserida em qualquer parte do documento. Basta definir um identificador único, colocado entre `[]`, seguido do sinal de `:`, um espaço e o URL do _link_. Opcionalmente o atributo `title` pode ser colocado entre `""` após o URL.

```
  [Twitter]: https://twitter.com "Acesse o Twitter!"

  [Twitter]
```

RESULTADO:

[twitter]: https://twitter.com 'Acesse o Twitter!'

[Twitter]

Uma terceira forma de inserir _link_, quando o texto âncora puder ser a própria URL do _link_ é simplesmente colocar a URL entre `<>`.

```
  <https://www.google.com>
```

RESULTADO:

<https://www.google.com>

&nbsp;

### 7.4. Imagens

Basta utilizar a mesma sintaxe dos _links_ precedida por um sinal de `!`. No lugar do texto âncora do link vai o atributo `alt` da imagem, e a URL será inserida entre `()`.  
Assim como com os links, as imagens também podem receber o atributo `title` e também podem ser inseridas diretamente ou via identificador de referência.

```
  Imagem 01: Inserida diretamente:

  ![Imagem 01](https://i.pinimg.com/originals/ed/5a/a4/ed5aa4d221acce68906e39287a41533d.jpg "Nobara")

  Imagem 02: Inserida via identificador de referência:

  ![Imagem 02][idimg02]

  [idimg02]: https://i.pinimg.com/originals/fe/8f/dd/fe8fdddae012f456043cb8551645b4fa.jpg "Tatakae"
```

RESULTADO:

Imagem 01: Inserida diretamente:

![Imagem 01](https://i.pinimg.com/originals/ed/5a/a4/ed5aa4d221acce68906e39287a41533d.jpg 'Nobara')

&nbsp;

Imagem 02: Inserida via identificador de referência:

![Imagem 02][idimg02]

[idimg02]: https://i.pinimg.com/originals/fe/8f/dd/fe8fdddae012f456043cb8551645b4fa.jpg 'Tatakae'

&nbsp;

## 8. Escape de símbolos

O Markdown permite que você use "escapes" com o sinal de `\` para gerar caracteres literais que teriam algum significado especial na sintaxe de formatação.

```
  Este é um termo *em itálico* e este é um termo \*entre asteriscos\*
```

RESULTADO:

Este é um termo _em itálico_ e este é um termo \*entre asteriscos\*

Os seguintes símbolos podem ser "escapados" com o uso da `\`:

- \
- `
- \*
- \_
- {}
- []
- <>
- ()
- \#
- \+
- \-
- .
- !
- |

&nbsp;

## 9. HTML

Vale lembrar que podemos utilizar as tags **HTML** para qualquer marcação que não seja coberta pelo Markdown.

```
  Este é um termo **em negrito** e este é um termo <strong>em negrito também</strong>.
```

RESULTADO:

Este é um termo **em negrito** e este é um termo <strong>em negrito também</strong>.

&nbsp;

## 10. Dialetos de Markdown

O Markdown possuí variantes que são chamadas de "sabores" ou dialetos. Cada dialeto de Markdown, além de umas pequenas diferenças de sintaxe em relação a esta sintaxe básica, também apresentam funcionalidades adicionais com uma sintaxe própria para estas "extensões", mas em geral, seguindo a mesma filosofia.

Alguns dialetos diferentes tem foco em propósitos diferentes, e portanto, apresentam funcionalidades estendidas um pouco diferentes.

Alguns exemplos de dialetos Markdown com sintaxe estendida são:

- CommonMark Markdown;
- Github-Flavored Markdown;
- MultiMarkdown;
- Markdown PHP Extra;
- Pandoc's Markdown.

&nbsp;

## 11. Conclusão

Chegamos ao fim, e agora é hora de praticar. O link abaixo irá redirecionar você à um site que possuí um tutorial bem intuitivo do que foi abordado neste documento.

- <https://www.markdowntutorial.com>

Mãos à obra! :)

---

Fontes de pesquisa:

- <https://www.inteligenciaurbana.org/2021/04/markdown-parte1.html>
- <https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open>
- <https://pt.strephonsays.com/what-is-the-difference-between-markup-language-and-programming-language>
