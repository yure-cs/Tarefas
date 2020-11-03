# Filtro de Faixas de Loteria
---

## 1. Escolha de loteria
   
O primeiro passo para filtra dezenas Ã© escolha a loteria das combinaÃ§Ãµes que serÃ£o utilizadas na operaÃ§Ã£o. Segue a baixa a imagem das opÃ§Ãµes de loteria:

![Escolha de loteria](https://imagens-publicas-yure.s3.amazonaws.com/escolha-de-loteria.png)

## 2. DefiniÃ§Ã£o da quantidade de faixas e dezenas da loteria

ApÃ³s ter escolhido a loteria escolha a quantidade de faixas que as dezenas da loteria serÃ£o divididas, prencha o intervalo de cada faixa e clique no botÃ£o "Gerar dezenas". Segue abaixa a imagem do campo de quantidade:

![Dezenas das faixas](https://imagens-publicas-yure.s3.amazonaws.com/gerar-dezenas-faixas.png)

> **Exemplificando**:  
> Se no campo da faixa F1 forem definidos 1 e 10 como inicio e fim respectivamente, o intervalo de dezenas criado serÃ¡: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]. E estas serÃ£o as dezenas da faixa F1.


## 3. Filtragem da quantidade min. e mÃ¡x. de faixas (opcional).

Para definir a quantidade mÃ­nima e mÃ¡xima de faixas das combinaÃ§Ãµes que serÃ£o filtradas selecione o checkbox do filtro "Qtd. de Faixas" e preenche os valores dos respectivos limites. Segue abaixo a imagem dos campos:

![Quantidade de faixas](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-maxima-faixas.png)

> **Exemplificando**:  
> Se considerarmos uma combinaÃ§Ã£o qualquer e definirmos que desejamos ter no mÃ­nimo 5 e no mÃ¡ximo 6 faixas por combinaÃ§Ã£o:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 35, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 12, 13, 35, 39 ] ou seja, [ F1, F1, F2, F2, F4, F4 ] :x:

## 4. Filtragem da quantidade min. e mÃ¡x. de dezenas (opcional).

Para filtar a quantidade especifica de dezenas desejadas em cada faixa coloque o valor mÃ­nimo e mÃ¡ximo para cada faixa, se quiser gerar um intervalo default preencha o valor mÃ­nimo e mÃ¡ximo e clique no botÃ£o "Preencher faixas". Segue abaixo a imagem dos campo:

![Quantidade de dezenas por faixa](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-dezenas-faixas.png)

> **Exemplificando**:  
> Se considerarmos uma combinaÃ§Ã£o qualquer e definirmos que desejamos ter no mÃ­nimo 2 e no mÃ¡ximo 3 dezenas na faixa F2 por combinaÃ§Ã£o:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 35, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 05, 13, 35, 39 ] ou seja, [ F1, F1, F1, F2, F4, F4 ] :x:

## 5. Filtragem da quantidade de dezenas consecutivas (opcional).

Para filtrar a quantidade de dezenas consecutivas, selecione o checkbox do filtro e preencha o valor mÃ­nimo e mÃ¡ximo geral e/ou especÃ­fico de cada faixa. Segue abaixo a imagem dos campos:

![Quantidade de dezenas consecutivas](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-dezenas-consecutivas.png)

> **Exemplificando**:  
> Se considerarmos uma combinaÃ§Ã£o qualquer e definirmos que desejamos ter no mÃ­nimo 2 e no mÃ¡ximo 3 dezenas consecutivas em geral por combinaÃ§Ã£o:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 35, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, [ F1, F1, F2, F2, F4, F5 ] :x:  
>
> Se considerarmos uma combinaÃ§Ã£o qualquer e definirmos que desejamos ter no mÃ­nimo 2 e no mÃ¡ximo 3 dezenas consecutivas em geral e no minÃ­mo 2 e no mÃ¡ximo 3 na faixa F3 por combinaÃ§Ã£o: 
>
> **_Exemplo #2_**:  
> [ 01, 11, 26, 27, 35, 60 ] ou seja, [ F1, F2, F3, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, [ F1, F1, F2, F2, F4, F5 ] :x:

## 6. Filtragem da quantidade de dezenas pares/impares (opcional).

Para filtrar a quantidade de dezenas pares e impares, preencha o valor mÃ­nimo e mÃ¡ximo de dezenas pares e impares, respectivamente. Segue abaixo a imagem dos campos:

![Quantidade de dezenas pares/impares](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-dezenas-pares-impares.png)

> **Exemplificando**:  
> Se considerarmos uma combinaÃ§Ã£o qualquer e definirmos que desejamos ter no mÃ­nimo 3 e no mÃ¡ximo 3 dezenas pares e no mÃ­nimo 3 e no mÃ¡ximo 3 impares por combinaÃ§Ã£o:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 32, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, [ F1, F1, F2, F2, F4, F5 ] :x:  

## 7. Filtragem da quantidade min. e mÃ¡x do somatÃ³rio de dezenas (opcional).

Para filtrar o somatÃ³rio de dezenas de cada combinaÃ§Ã£o, selecione o checkbox do filtro e preencha os limites, minimo e mÃ¡ximo respectivamente. Segue abaixo a imagem dos campos:

![Quantidade min/mÃ¡x do somatÃ³rio de dezenas](https://imagens-publicas-yure.s3.amazonaws.com/somatorio-dezenas.png)

> **Exemplificando**:  
> Se considerarmos uma combinaÃ§Ã£o qualquer e definirmos que desejamos ter o somatÃ³rio de dezenas de valor mÃ­nimo de 140 e  valor mÃ¡ximo de 150 por combinaÃ§Ã£o:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 32, 60 ] ou seja, 143 :heavy_check_mark:  
> [ 10, 14, 15, 28, 34, 49 ] ou seja, 150 :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, 122 :x:  

## 8. Escolha da origem das dezenas.

ApÃ³s definir os filtro que serÃ£o usados Ã© preciso escolhar a fonte de ondem serÃ£o captadas as combinaÃ§Ãµes. Existem duas possibilidades, atravÃ©s de upload de um arquivo CSV ou buacando os resultados da Caixa Economica no banco de dados. Segue abaixo a imagem dos campos:

![Origem das dezenas](https://imagens-publicas-yure.s3.amazonaws.com/origem-dezenas.png)

Via upload de arquivo(csv):

![Origem das dezenas](https://imagens-publicas-yure.s3.amazonaws.com/origem-dezenas-arquivo.png)

Via resultados da Caixa no banco de dados: 

![Origem das dezenas](https://imagens-publicas-yure.s3.amazonaws.com/origem-dezenas-caixa.png)
