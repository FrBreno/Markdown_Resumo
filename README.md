# Markdown para iniciantes

![markdownIcon](https://grafxflow.co.uk/storage/app/uploads/public/5ad/e5b/d9b/thumb_891_266_0_0_0_auto.png)

## Observações

Este arquivo apresenta um pequeno **RESUMO/TUTORIAL** sobre alguns conceitos importantes do Markdown que produzi a partir de algumas pesquisas na internet. Como ainda sou iniciante, e acredito que exista muitas pessoas na mesma situação que a minha, resolvi postar este documento no GitHub para caso alguém precise.

Lembrando que as fontes utilizadas para pesquisa estão no final do arquivo.

## Introdução

Markdown é uma linguagem de marcação leve e simples criada por John Gruber em 2004 com a colaborações de Aaron Swartz na sintaxe, e que hoje em dia é uma das linguagens de marcação mais populares do mundo.

&nbsp;

## Linguagens de marcação

Linguagens de marcação são uma forma de anotação de um texto simples sem formatação de modo que ele se torne sintaticamente distinguível e possa ser manipulado por algum software.

O Markdown é uma linguagem de marcação bastante leve e simples, criada originalmente para escreitores web, para ser convertido em **HTML** válido, mas cuja sintaxe é muito menos _verbosa_ e muito mais legível.

&nbsp;

## Markdown

A sintaxe de formatação do Markdown foi criada com o objetivo de ser o mais legível possível. Nessa linguagem não é necessário usar _tags_ de abertura e fechamento como em **HTML**, nem é preciso criar estilos de formatação.

### Vantagens do Markdown

- Markdown pode ser usado para tudo

  Para criar sites, documentos, notas, livros, documentação técnica, documentação acadêmica, etc.

- Markdown é portátil

  Arquivos escritos em Markdown podem ser abertos com praticamente qualquer aplicativo.

- Markdown é independente de plataforma

  Texto formatado em Markdown pode ser criado em qualquer dispositivo que execute qualquer sistema operacional.

- Markdown é à prova de futuro

  Se o aplicativo que você está usando parar de funcionar em algum momento no futuro, um texto formatado em Markdown ainda poderá ser lido e editado usando qualquer outro aplicativo de edição de texto.

- Markdown está em toda parte

  Inúmeros sites da Web suportam Markdown, e muitos aplicativos de desktop e baseados na Web o suportam.

&nbsp;

## Como o Markdown funciona?

Quando escrevemos em Markdown o texto é armazenada em um arquivo de texto simples com extensão _.md_ ou _.markdown_.

Para que um arquivo Markdown seja convertido em **HTML** ou em um documento pronto para impressão precisamos de um aplicativo Markdown capaz de processar o arquivo.

Os aplicativos Markdown usam algo chamado de processador Markdown para ler o texto Markdown e reescrevê-lo no formato **HTML**. E então o documento pode ser visualizado em um navegador da Web ou combinado com uma folha de estilos e ser impresso.

&nbsp;

## Sintaxe básica

Assim como no **HTML**, no Markdown os elementos são separados entre elementos bloco (_Block_) e elementos em linha (_inline_ ou _span_).

**Elementos bloco** ocupam todo o espaço horizontal disponível e iniciam uma nova linha no documento. Novos elementos irão começar na próxima linha livre. Elementos bloco podem conter elementos em linha e, às vezes, outros elementos bloco.

**Elementos em linha** ocupam apenas o espaço necessário e não iniciam uma nova linha. Geralmente, elementos em linha podem conter apenas conteúdo e outros elementos em linha. Não é possível colocar elementos bloco dentro de elementos em linha.

&nbsp;

## Elementos bloco

### Títulos

```
  # Título 1
  ## Tírulo 2
  ### Tírulo 3
  #### Tírulo 4
  ##### Tírulo 5
  ###### Tírulo 6
```

RESULTADO:

# Título 1

## Tírulo 2

### Tírulo 3

#### Tírulo 4

##### Tírulo 5

###### Tírulo 6

&nbsp;

Ainda existe uma sintaxe alternativa para os títulos de nível 1 e nível 2, com sinais de `=` e de `-` na linha de baixo do texto do título, da seguinte maneira:

```
  Título 1
  ========

  Título 2
  --------
```

&nbsp;

### Parágrafos

Consiste em separar um parágrafo de outro ou de qualquer elemento bloco com uma linha vazia.

```
  Este é um parágrafo.

  Este é outro parágrafo.
  Este ainda é o segundo parágrafo.
```

&nbsp;

### Quebras de linha

Basta deixar dois espaços em branco (teclar space duas vezes) ao fim da primeira linha e nenhuma linha vazia entre elas.

```
  Este é um parágrafo.
  Esta é a segunda linha do mesmo parágrafo.
```

&nbsp;

### Listas

1. Listas não ordenadas

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

2. Listas ordenadas

   Basta adicionar um número seguido de um ponto e de um espaço antes do texto de cada item da lista. Pode ser qualquer número em qualquer ordem, ou pode mesmo ser sempre o mesmo número.

   ```
     1. Primeiro da lista.
     1. Segundo da lista.
     1. Terceiro da lista.

     3. Primeiro da lista.
     7. Segundo da lista.
     2. Terceiro da lista.
   ```

   RESULTADO:

   1. Primeiro da lista.
   1. Segundo da lista.
   1. Terceiro da lista.

&nbsp;

### Aninhamento de listas

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

### Bloco de citação

Basta inserir um sinal de `>` antes de cada linha que faça parte do bloco e também na linha em branco, caso o bloco de citação possua mais de um parágrafo.

```
  Este é um parágrafo antes da citação:

  > Este é um bloco de citação com dois parágrafos. Lorem Ipsum é simplesmente uma simulação de texto da indústria tipográfica e de impressos, e vem sendo utilizado desde o século XVI.
  >
  > Lorem Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica, permanecendo essencialmente inalterado.
```

RESULTADO:

Este é um parágrafo antes da citação:

> Este é um bloco de citação com dois parágrafos. Lorem Ipsum é simplesmente uma simulação de texto da indústria tipográfica e de impressos, e vem sendo utilizado desde o século XVI.
>
> Lorem Ipsum sobreviveu não só a cinco séculos, como também ao salto para a editoração eletrônica, permanecendo essencialmente inalterado.

&nbsp;

### Blocos de código

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

### Linhas Horizontais

Basta colocar três ou mais sinais de `***`, `---` ou `___`.

RESULTADO:

&nbsp;

### Tabelas

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

Podemos ainda, utilizar `:` ao lado do campo horizontal de hífens `---`, na segunda linha da tabela, para especificar o tipo de alinhamento de texto.

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

## Elementos em Linha

### Ênfase

#### 01. Itálico

Basta envolver o texto com `*` ou `_`.

```
  *TEXTO* ou _TEXTO_
```

RESULTADO:

_TEXTO_

&nbsp;

#### 02. Negrito

Basta envolver o texto com dois `**` ou com dois `__`.

```
  **TEXTO** ou __TEXTO__
```

RESULTADO:

**TEXTO**

&nbsp;

#### 03. Itálico e negrito

Basta envolver o texto com três `***` ou com três `___`.

```
  ***TEXTO*** ou ___TEXTO___
```

RESULTADO:

**_TEXTO_**

&nbsp;

### Código em linha (liretal)

Basta envolver o código em sinais de crase.

```
  `Código`
```

RESULTADO:

`Código`

### Links

Basta colocar o texto âncora do link entre `[]` e, na sequência, colocar o URL do link entre `()`. Opcionalmente, se quiser colocar o atributo HTML `title` ao link, basta colocar o texto do `title` entre `""`, após o URL, ainda dentro dos parêntesis.

```
  [Google](https://www.google.com "Acesse o Google!")
```

RESULTADO:

[Google](https://www.google.com 'Acesse o Google!')

Também é possível inserir _links_ com identificadores de referêcia, uma funcionalidade bastante útil quando se precisa inserir um mesmo _link_ diversas vezes na mesma página ou documento.

A referência do _link_ pode ser inderida em qualquer parte do documento. Basta definir um identificador único, colocado entre `[]`, seguido do sinal de `:`, um espaço e o URL do _link_. Opcionalmente o atributo pode ser colocado entre `""` após o URL.

```
  [Twitter]: https://twitter.com "Acesse o Twitter!"
```

RESULTADO:

[twitter]: https://twitter.com 'Acesse o Twitter!'

1.  [Twitter]
2.  [Twitter]

Uma terceira forma de inserir _link_, quando o texto âncora puder ser a própria URL do _link_ é simplismente colocar a URL entre `<>`.

```
  <https://www.google.com>
```

RESULTADO:

<https://www.google.com>

&nbsp;

### Imagens

Basta utilizar a mesma sintaxe dos _links_ precedida por um sinal de `!`. No lugar do texto âncora do link vai o atributo `alt` da imagem, e a URL pode ser simplesmente o caminho para o arquivo da imagem.  
Assim como com os links, as imagens também podem receber o atributo `title` e também podem ser inderidas diretamente ou via identificador de referência.

```
  Imagem 01: Inserida diretamente:

  ![Imagem 01](https://i.pinimg.com/originals/e3/f3/a2/e3f3a29bbb76785fb51c17b55c97a5d0.jpg "Nobara")

  Imagem 02: Inserida via identificador de referência:

  ![Imagem 02][idimg02]

  [idimg02]: https://i.pinimg.com/originals/fe/8f/dd/fe8fdddae012f456043cb8551645b4fa.jpg "Tatakae"
```

RESULTADO:

Imagem 01: Inserida diretamente:

![Imagem 01](https://i.pinimg.com/originals/e3/f3/a2/e3f3a29bbb76785fb51c17b55c97a5d0.jpg 'Nobara')

&nbsp;

Imagem 02: Inserida via identificador de referência:

![Imagem 02][idimg02]

[idimg02]: https://i.pinimg.com/originals/fe/8f/dd/fe8fdddae012f456043cb8551645b4fa.jpg 'Tatakae'

&nbsp;

## Escape de simbolos

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

## HTML

Vale lembrar que podemos utilizar as tags **HTML** para qualquer marcação que não seja coberta pelo Markdown.

```
  Este é um termo **em negrito** e este é um termo <strong>em negrito também</strong>.
```

RESULTADO:

Este é um termo **em negrito** e este é um termo <strong>em negrito também</strong>.

&nbsp;

## Dialetos (ou sabores) de Markdown

O Markdown possuí variantes que são chamadas de "sabores" ou dialetos. Cada dialeto de Markdown, além de umas pequenas diferenças de sintaxe em relação a esta sintaxe básica, às vezes um pouco arbitrárias e aleatórias, também apresentam funcionalidades adicionais com uma sintaxe própria para estas "extensões", mas em geral, seguindo a mesma filosofia.

Alguns dialetos diferentes tem foco em propósitos diferentes, e portanto, apresentam funcionalidades estendidas um pouco diferentes.

Alguns exemplos de dialetos Markdown com sintaxe estendida são:

- CommonMark Markdown;
- Github-Flavored Markdown;
- MultiMarkdown;
- Markdown PHP Extra;
- Pandoc's Markdown.

&nbsp;

---

Fontes de pesquisa:

- <https://www.inteligenciaurbana.org/2021/04/markdown-parte1.html>
- <https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open>
