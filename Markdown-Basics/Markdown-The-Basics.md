## What is Markdown?
# Estudos e tutorial pessoal sobre esta poderosa ferramenta 

Source: https://www.markdownguide.org/getting-started/
https://www.markdownguide.org/basic-syntax/

O que é o Markdown?
Markdown é uma linguagem leve de marcação que podemos usar para adicionar elementos de formatação à documentos de texto simples. Criado por John Gruber, em 2004, Markdown é agora uma das linguagens de marcação mais famosas do mundo.

Porquê usar markdown
Markdown pode ser usado para tudo: websites, documentos, notas, livros, apresentações, mensagens de e-mai, e documentação técnica.
Markdown é portatil: arquivos podem ser abertos virtualmente usando qualquer aplicativo. Se não gostar do aplicativo markdown que está usando, é só trocar por outro. Um forte contraste com arquivos de extensão .doc por exemplo.
Markdown independe de plataforma: você por criar textos de formato Markdown de qualquer dispositivo rodando qualquer sistema operacional.
Markdown é à prova do futuro: mesmo que o aplicativo Markdown que você está usando agora pare de funcionar, você ainda será capaz de abrí-lo usanto um aplicativo editor de texto. Isso é extremamente importante quando consideramos documentos que precisam ser preservados por tempo indefinido, como livros, teses de universidades, etc.
Markdown está em todo lugar: Reddit, GitHub e muito mais.

Mas vamos ao que interessa...

---

Sintaxe Básica

Headings/Cabeçalhos ou Títulos

Markdown                    HTML                        Rendered Output
# Heading Level 1           <h1>Heading level 1</h1>    Do maior título
## Heading Level 2          <h2>Heading level 2</h2>    
### Heading Level 3         <h3>Heading level 3</h3>    
#### Heading Level 4        <h4>Heading level 4</h4>    
##### Heading Level 5       <h5>Heading level 5</h5>    
###### Heading level 6      <h6>Heading level 6</h6>    ao menor

Alternatively, you can do:

Heading level 1
===============

or 

Heading level 2
---------------

Important Notes: use a space between the number signs and the heading name.. You should also put blank lines before and after a heading for compatibility.

---

Paragraphs/Parágrafos

Just use a blank line. For HTML, use <p>Your paragraph.</p>

Important Notes: don't use tabs or spaces in front of your paragraphs. Keep lines left-aligned like this one.

---

Line Break:
First line with two spaces after.  
And the next line

or

First line with the HTML tag after it. <br>
And the next line.

---

Bold/Negrito
Use **yourtext** or __yourtext__. For HTML, use <strong>youtext</strong>.

Italic/Itálico
Use *yourtext* or _youtext_. For HTML, use <em>youtext</em>.

Bold and Italic/Negrito e Itálico
Use ***yourtext*** or ___yourtext___. For HTML, use <em><strong>yourtext</strong></em>

---

Blockquote
Use a > in front of a paragraph

>Dorothy followed her through many of the beautiful rooms in her castle.

Blockquotes can contain multiple paragraphs. Just keep adding > to the lines.

>Dorothy followed her through many of the beautiful rooms in her castle.
>
>The Witch made her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Nested Blockquotes
Blockquotes can be nested. Add >> in front of the paragraph you want to nest.

>Dorothy followed her through many of the beautiful rooms in her castle.
>>The Witch made her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.

---

Lists
you can organize items into ordered and unordered lists

Ordered Lists
Markdown            HTML
                    <ol>
1. First Item           <li>First Item</li>
2. Second Item          <li>Second Item</li>
3. Third Item           <li>Third Item</li>
4. Fourth Item          <li>Fourth Item</li>
                    </ol>

In Markdown, it doesn't really matter if the number of the item are in order or not.

You can also indent items.

Markdown            HTML
                    <ol>
1. First Item           <li>First Item</li>
2. Second Item          <li>Second Item</li>
3. Third Item           <li>Third Item</li>
    1. Indented Item        <ol>
    2. Indented Item            <li>Indented Item</li>    
4. Fourth Item                  <li>Indented Item</li>
                            </ol>
                        </li>    
                        <li>Fourth Item</li>
                    </ol>

Unordered Lists
Markdown            HTML
                    <ul>
- First Item           <li>First Item</li>
- Second Item          <li>Second Item</li>
- Third Item           <li>Third Item</li>
- Fourth Item          <li>Fourth Item</li>
                    </ul>

You can also indent items.

Markdown            HTML
                    <ul>
- First Item           <li>First Item</li>
- Second Item          <li>Second Item</li>
- Third Item           <li>Third Item</li>
    - Indented Item        <ul>
    - Indented Item            <li>Indented Item</li>    
- Fourth Item                  <li>Indented Item</li>
                            </ul>
                        </li>    
                        <li>Fourth Item</li>
                    </ul>                    

Code Blocks
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

Inserting Images

1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/assets/images/tux.png)

3. Close the file.

You can also nest an unordered list in an ordered list, or vice versa.