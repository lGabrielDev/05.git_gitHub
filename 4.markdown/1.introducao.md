<!--
https://learn.getgrav.org/17/content/markdown

(Não precisa decorar. Quando voce for criar o seu README.md voce consulta aqui.)

markdown é uma linguagem de marcacao de texto;

Geralmente é usado para formatar arquivos README.md;

Aquivos markdown tem a extensão ".md";
    README.md


------------------------------------------------------------------------------------------------------------------------------------------
Igual no html, aqui podemos colocar títulos
no html eu tenho os headings (h1,h2,h3...h6)

#   ->   <h1>  </h1>
##  ->   <h2>  </h2>
### ->   <h3>  </h3>

Uma hashtag representa um heading <h1>
Duas hashtag representa um heading <h2>
etc...

1- Altere o arquivo README.md do repositorio Git_Github. Coloque todos os headings(h1,h2,h3...h6);
        git add ./;
        git commit -a -m "testando markdown";
        git push;
------------------------------------------------------------------------------------------------------------------------------------------
italic and bold

**palavra**  -> negrito
*palavra*    -> italic

------------------------------------------------------------------------------------------------------------------------------------------
listas

unordered list (<ul> no html)

* Item tal
* Item tal
* Item tal


ordered list (<ol> no html)
1. Item tal
2. Item tal
3. Item tal


1- Crie uma lista das linguagens e ferramentas que voce esta aprendendo. Crie uma <ul> e uma <ol>

    ### linguagens e ferramentas do projeto:

    * HTML and CSS
    * SQL
    * JAVA
    * Linux
    * GIT

    ## linguagens e ferramentas do projeto:

    1. HTML and CSS
    2. SQL
    3. JAVA
    4. Linux
    5. GIT


2- Acrescente subitems:
    1. HTML and CSS
        1. flexbox
        2. img
    2. SQL
    3. JAVA
    4. Linux
    5. GIT

------------------------------------------------------------------------------------------------------------------------------------------

Imagem

![Alt da imagem](URL da imagem)


Igual no html, vamos usar o alt.
Se uma pessoa com deficiencia visual estiver lendo o site, ele consegue ler a imagem.
E também, se a imagem não carregar o usuario consegue saber o que é a imagem;



Imagem local
1- Coloque uma imagem do seu pc no README.md;




Imagem da web
2- Coloque uma imagem da web no README.md

------------------------------------------------------------------------------------------------------------------------------------------
Links  
tag <a> no html;



Para colocar imagem fazemos com exclamacao
![alt](caminhoDaImagem)

Links fazemos assim:
[alt](caminhoDaURL)


1- Coloque um link para o google e um link para o seu perfil no GitHub:

    [Google](https://google.com.br)

    GitHub do desenvolvedor: https://github.com/lGabrielDev;

Links do github ele reconhece automaticamente;





<hr>

## Criando um link para um heading do próprio arquivo

[final da paǵina](#heading_tal)

Basta criar um link normal, só que na hora de passar o link, passamos um #heading.

1- Crie um link para o último heading do arquivo.

Na hora de passar o link, dê um ctrl + space.
------------------------------------------------------------------------------------------------------------------------------------------
Usando uma imagem como link

![]()   -> coloca uma imagem
[]()    -> coloca um link

Basta eu colocar uma imagem primeiro e depois envelopar essa imagem com um link:

    [![alt](caminhoDaImagem)](caminhoDaURL)

------------------------------------------------------------------------------------------------------------------------------------------

Destacando um código (highlitar um código)

```java

código

```

Voce pode especificar a linguagem ou não.


1- Crie um method simples que vai retonar a soma de 2 numeros.;


    ```java

    public Integer soma(Integer a, Integer b){
        return a + b;
    }

    ```



2- Faça um highlight desse method, mas não especifique a linguagem:

    ```

    public Integer soma(Integer a, Integer b){
        return a + b;
    }

    ```

Viu?? Easy!


Para highlitar um código do terminal, use "bash"

```bash

    ls -lh;
    git status;

```
------------------------------------------------------------------------------------------------------------------------------------------
Citação:

>   texto
>>  texto
>>> texto

1- Crie algumas citações

------------------------------------------------------------------------------------------------------------------------------------------
Table

| name    | age   | favorite_color |
| :----   | :---: | ---:           |
| Marcelo | 44    | Black          |
| Amanda  | 36    | Purple         |

Perceba que os dois pontos ":" determina como vai ficar centralizado os dados de cada campo


:---   -> left
:---:  -> center
---:   -> right


Não precisa ficar perfeitinho...

| name  | age   | favorite_color |
| :---: | :---: | :---:|
| Marcelo | 44    | Black |
| Amanda  | 36    | Purple |


Assim também funiciona.

1- Crie uma table. 
------------------------------------------------------------------------------------------------------------------------------------------
-->