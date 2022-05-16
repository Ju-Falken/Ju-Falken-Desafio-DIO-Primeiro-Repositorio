# Introdução a Criação de Websites com HTML5 e CSS3

### HTML5

- HTML foi criado em 1991 e sua última versão, a 5, saiu em 2014  - Tim Berners-Lee
- **ELEMENTO**
  - Elemento é a base do HTML, tudo é um elemento
  - Elemento inicia com a tag de abertura que diz o que o elemento será na tela
  - Elemento pode conter um atributo que vai ser uma diferenciação de como será apresentado, aparência
  - Conteúdo 
  - Tag de fechamento
- **ESTRUTURA BÁSICA**
  - DOCTYPE html - não é um elemento html, diz ao navegador o que está sendo escrito;
  - tag html, no início e no fim, dentro de <> - que diz que tudo que está entre esses dois, faz parte do documento html

##### Semântica

- Antigamente todos os elementos eram <divs, mudou em 2014
  - section - seção genérica
  - header - CABEÇALHO da página ou de uma seção da página
  - article - conteúdo relevante dentro da página
  - aside - conteúdo relacionado ao assunto da página
  - footer - rodapé da página ou de uma seção da página
  - h1 - h6 - Importância de um título na página - única regra é que só pode ter um h1 por página;

#### Como usar textos e links em HTML

- <p- suporta textos maiores, mas não é só sobre textos, pode imagens, códigos, videos, imagens
- elemento 'a' (âncora) tem vários atributos, mas no curso foca só em href e target
  - href - hiperlink para onde a ancora aponta 
    - aponta para email - _tem que usar_ **<a href=mailto:julianafalkenbach@gmail.com">E-mail</a>**
    - Também pode apontar para telefone, daí usa o tel
    - target - indica como o link deve ser aberto _blank - em nova pagina

#### Imagens

- Tag img, não tem tag de fechamento.
- Dois atributos próprios
  - source - "src" - indica o local do arquivo, caminho da imagem, e é **OBRIGATÓRIO**
    - pode ser em seu próprio site ou em outro lugar
  - Alt - "alt" - não é obrigatório mas é recomendável porque indica o que é aquela foto, e mostra para o usuário o que a imagem significa

#### Listas

- Tags
  - li - é cada item da lista
  - ul - lista com pontos, a ordem dos fatores não altera o viaduto -fica com as bolinhas
  - ol - é uma lista ordenada, a ordem altera o viaduto - fica com números



# CSS3

- Linguagem utilizada para formatar páginas

- Você cria regra para elementos ou grupo de elementos

- Elementos (como o a, p, h1,h3) são seletores

- e dentro das chaves estão as declarações - propriedade (cor, fonte) e valor (14px, bold)

- **Classes e IDs**
  - ID é representado por **#** 
  - Classe representada por **.**
  - ID pode ser usado uma vez na página HTML
  - Classe não tem limite de uso

- Para inserir o CSS usa o elemento <link que não tem tag de fechamento então fica tudo assim <...> na HEAD - 
  - rel - qual tipo de arquivo está adicionando
  - href - com o caminho pro doc stylesheet

- ### **Box-model**

  - é a forma do layout no HTML, uma caixa retangular.
  - formada:
    - Margin
    - Border
    - Padding - espaço entre bordar e conteúdos
    - Content
    - ![image-20220513150541524](C:\Users\USUARIO\AppData\Roaming\Typora\typora-user-images\image-20220513150541524.png)

  #### Estilizando elementos do Box-model

  - **Padding e Margin** pode ser feito de três formas:
    - cima-baixo apenas um valor, esquerdo-direito apenas um valor: "10px 5px;" Eixo x - lateral e y - altura
    - cada lado com um valor diferente, segue sempre a mesma ordem **TOP - RIGHT - BOTTOM - LEFT**
    - escrevendo cada elemento: padding-TOP, padding-right, padding-bottom, padding-left  EM CADA LINHA;

  - **Background**
    - é um atalho para alterar várias informações do background como: imagens, posição (**Estudar no MDN**)
    - No quesito cor pode ser usado:
      - background-color com o nome da cor em inglês;
      - background-color com o código HEXADECIMAL #008800;
      - background: nome da cor OU  código HEXADECIMAL;
  - **Border**
  - Pode colocar na sequência ou como o padding para cada lado border-top...
  - Na sequência: largura, estilo e cor;
    - Largura - pixels, cm, mm
    - cor: nome inglês ou #
    - estilo: sólida - **solid**, pontilhada - **dotted**, tracejada -  **dashed**...;
  - Pode também usar uma propriedade específica pra cada ASPECTO da borda
    - border-width - largura
    - border-color
    - border-style
  - Pode somar os aspectos:
    - border-top-width: 8px, border-top-color: yellow; border-top-style dotted;
  - Border radius: ARREDONDAR
    - usa ou px ou % - de QUADRADO para CÍRCULO - border-radius: 50%;
    - border-radius

#### Estilizando textos:

- **font-family**: Fonte do texto
  - podem ser usadas fontes da web (_web safe fonts_ - encontradas na maioria dos dispositivos)ou instaladas no computador;
  - pode colocar duas: verdana, arial - caso não tenha a verdana, vai ser usada a arial **E SE NÃO TIVER COLOCADO DUAS, E NÃO TIVER A FONTE ESCOLHIDA?***
- **font-size**: tamanho da fonte
  - existem várias unidades, pixel é mais simples;
- **font-style** 
  - normal = padrão, como a fonte é escrita
  - italic - deitada - EXISTEM FONTES QUE NÃO TEM SUPORTE AO ITALICO, se não tiver o navegador força a inclinação e fica feio;
- **font-weight** peso do texto
  - normal e bold são os mais comuns;
  - várias palavras chaves e pesos; usado para fontes mais complexas
- **text-transform** Maiúsculo e minúsculo
  - uppercase
  - lowercase
  - capitalize - cada primeira letra maiúscula
- **text-decoration**
  - underline
  - overline
  - line-through

#### Estilizando listas

- **list-style-type**
  - existem tipos referentes a listas ordenadas **ol**:
    - upper-roman;
  - tipos para **ul**
    - square
    - "/1F44D"
    - list-style-image: url ("nomearquivo.png")

#### Dimensão e Alinhamento

- Width - largura; height - 	altura; de ELEMENTOS
  - pixels, porcentagem - em relação ao elemento que vem de fora	
- Max-width OU Max-height -
  -  se refere a largura e altura maxima dos elementos todos
  - se ajustam de acordo com as situações;
- Margin - 
  - auto - alinha automaticamento
- Text align
  - right
  - left
  - center
  - justify







