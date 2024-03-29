# NFR Framework

##  Versionamento

| Versão |    Data    |       Modificação        |        Autor         | Revisor |
| :----: | :--------: | :----------------------: | :------------------: | :--------: |
|  1.0  | 02/08/2022 | Abertura do documento | Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.1  | 02/08/2022 | Adicionar introdução | Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.2  | 02/08/2022 | Explicação da metodologia | Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.3  | 02/08/2022 | Adição da legenda do NFR | Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.4  | 02/08/2022 | Adição dos RNFs| Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.5  | 02/08/2022 | Adição dos NFRs| Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.6  | 02/08/2022 | Adição de legendas nas figuras| Pedro Henrique Nogueira, Iago Cabral e Matheus Perillo | Matheus Soares |
|  1.7  | 02/08/2022 | Adição dos links RES| Matheus Perillo | Matheus Soares |


## 1. Introdução
&emsp;&emsp;Proposto por Chung, University of Toronto, o NFR Framework é uma maneira de representar de forma sistemática e global os Requisitos Não-Funcionais, com uma abordagem qualitativa e orienta a processo. Seu objetivo é ajudar os desenvolvedores a implementar soluções customizadas, levando em consideração as características dos campos e sistemas relacionados. Essas características incluem requisitos não funcionais, requisitos funcionais, prioridades e cargas de trabalho. Essas condições determinam a escolha de alternativas de desenvolvimento para um determinado sistema. 
  

&emsp;&emsp;Além disso, essa implementação representa o NFR como um softgoal, os quais são unidades básicas para representar requisitos não-funcionais. Ele possui uma relação de interdependência entre seus softgoals, oferece técnicas de operacionalização e fornece catálogos para inferir possíveis interações. 

## 2. Metodologia
&emsp;&emsp;Após levantar os Requisitos Não-Funcionais e entender o NFR Framework, o grupo decidiu utilizar Softgoal Interdependency Graph(SIG) para a implementação do NFR Framework. 

## 3. Legenda
<center>

<p style="font-size: 15px">
Imagem 1: Legenda do NRF
</p>
    
![NFR](https://cdn.discordapp.com/attachments/744698026462937211/1004542201604349962/unknown.png)

<p style="font-size: 12px">
Fonte: NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados por Reinaldo Antônio da Silva
</p>

    
</center>
<center>
<br>
<br>

<p style="font-size: 15px">
Imagem 2: Tipos de rótulos utilizados pelos Softgoals
</p>

![Rot](https://cdn.discordapp.com/attachments/744698026462937211/1004510204131553400/unknown.png)

<p style="font-size: 12px">
Fonte: NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados por Reinaldo Antônio da Silva
</p>

</center>
<br>

## 4. Requisitos não funcionais.

&emsp; A seguir estão os Requisitos Não-Funcionais levantados a partir das técnicas de elicitação utilizadas pelo grupo no projeto.

| Número | Requisito |
| :------: | ---------- |
| RNF1 | O aplicativo deve operar em sistemas mobile mais tradicionais(Android/IOS). | 
| RNF2 | O app deve ser otimizado para a experiência mobile. |
| RNF3 |O app deve ter um design bonito e familiar | 
| RNF4 | O aplicativo deve ser capaz de se recuperar de falhas. | 
| RNF5 | O aplicativo deve demonstrar boa usabilidade. | 
| RNF6 | Os vídeos devem possuir boa qualidade. |
| RNF7 | O aplicativo deve ter boa performace nos aparelhos com SO(ANDROID/IOS). |
| RNF8 | O aplicativo deve suportar multiplataformas. | 
| RNF9 |O aplicativo deve impedir que a tela bloqueie automaticamente | 

### 5. NFR
&emsp; A seguir estão os SIG feitos pela equipe sobre Usabilidade, Desempenho, Confiabilidade, Portabilidade e Segurança

### 5.1 NFR de Usabilidade

<center>
<figcaption style="font-size: 15px">Imagem 3: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#32-usabilidade">Usabilidade</a></figcaption>

![nfr_uso](https://cdn.discordapp.com/attachments/744698026462937211/1004557547207938058/unknown.png)

</center>

### 5.1.1 NFR de Usabilidade com propagação

<center>
<figcaption style="font-size: 15px">Imagem 4: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#32-usabilidade">Usabilidade</a> com propagação</figcaption>

![nfr_uso](https://cdn.discordapp.com/attachments/744698026462937211/1004545354299088957/unknown.png)
</center>

<br>

### 5.2 NFR de Desempenho
<center>
<figcaption style="font-size: 15px">Imagem 5: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#34-desempenho">Desempenho</a></figcaption>

    
![nfr_Dev](https://cdn.discordapp.com/attachments/744698026462937211/1004524863232413866/unknown.png)


</center>

### 5.2.1 NFR de Desempenho com propagação

<center>
  
<figcaption style="font-size: 15px">Imagem 6: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#34-desempenho">Desempenho</a> com propagação</figcaption>

![nfr_Dev](https://cdn.discordapp.com/attachments/744698026462937211/1004541497678516337/unknown.png)

</center>

<br>

### 5.3 NFR de Confiabilidade
<center>
<figcaption style="font-size: 15px">Imagem 7: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#33-confiabilidade">Confiabilidade</a></figcaption>

    
![nfr_Conf](https://cdn.discordapp.com/attachments/744698026462937211/1004537349365039134/unknown.png)


</center>

### 5.3.1 NFR de Confiabilidade com propagação

<center>

<figcaption style="font-size: 15px">Imagem 8: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#33-confiabilidade">Confiabilidade</a> com propagação</figcaption>

![nfr_Conf](https://cdn.discordapp.com/attachments/744698026462937211/1004546682752606258/unknown.png)

</center>

<br>

### 5.4 NFR de Portabilidade

<center>
    
<figcaption style="font-size: 15px">Imagem 9: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#35-suportabilidade">Portabilidade</a></figcaption>
    
    
![nfr_Port](https://cdn.discordapp.com/attachments/744698026462937211/1004540896622153738/unknown.png)


</center>

### 5.4.1 NFR de Portabilidade com propagação

<center>
  
<figcaption style="font-size: 15px">Imagem 10: Diagrama NFR Framework de <a href="https://requisitos-de-software.github.io/2022.1-TikTok/especificacaoSuplementar/#35-suportabilidade">Portabilidade</a> com propagação</figcaption>
  
![nfr_Port](https://cdn.discordapp.com/attachments/744698026462937211/1004542775699705966/unknown.png)

</center>

<br>

### 5.5 NFR de Segurança
<center>
<figcaption style="font-size: 15px">Imagem 11: Diagrama NFR Framework de Segurança</figcaption>
    
    
![nfr_Seg](https://cdn.discordapp.com/attachments/744698026462937211/1004538414764413140/unknown.png)


</center>

### 5.5.1 NFR de Segurança com propagação

<center>

<figcaption style="font-size: 15px">Imagem 12: Diagrama NFR Framework de Segurança com propagação</figcaption>
  
![nfr_Seg](https://cdn.discordapp.com/attachments/744698026462937211/1004544100713893888/unknown.png)

</center>

<br>

## 6. Bibliografia

> - SILVA, Reinaldo Antônio da. NFR4ES:Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Recife, 201

