# Entrevista

## 1. Versionamento

| Versão | Data       | Autor             | Alterações                                          | Revisor        |
| ------ | ---------- | ----------------- | --------------------------------------------------- | -------------- |
| 1.0    | 12/07/2022 | Mateus Caltabiano | Abertura do documento de entrevista                 | Matheus Soares |
| 1.1    | 08/09/2022 | Mateus Caltabiano | Adição de dados da entrevistada e fonte nas tabelas | Matheus Soares |

## 2. Introdução

&emsp; &emsp; A técnica de entrevista é bastante utilizada para encontrar os requisitos de um sistema. Para isso, os responsáveis pelas entrevistas devem elaborar perguntas com o intuito de auxiliar na definição dos requisitos. As entrevistas podem ser abertas ou fechadas.

* ### Entrevistas abertas:

&emsp; &emsp; São entrevistas que possuem um roteiro, mas podem ser improvisadas baseando-se nas respostas do usuário entrevistado para tentar compreender melhor as necessidades do mesmo.

* ### Entrevistas fechadas:

&emsp; &emsp; Ao contrário das entrevistas abertas, as perguntas são todas definidas previamente e devem ser feitas da maneira como foram planejadas. 

## 3. Entrevista

&emsp; &emsp; Entrevistamos uma usuária que tem completo domínio do aplicativo e o utiliza diariamente para entretenimento. A princípio, o script abaixo foi feito para uma entrevista fechada, mas ao longo do tempo pensei em maneiras de explorar melhor as perguntas e busquei respostas mais detalhadas da usuária.

<div style="text-align: center">
<p>Tabela 1: Dados da entrevista</p>
</div>

| Entrevistador     | Entrevistado    | Duração | Data       |
| ----------------- | --------------- | ------- | ---------- |
| Mateus Caltabiano | Mariana Alencar |   3 minutos      | 12/07/2022 |
<div style="text-align: center">
<p>Fonte: Grupo 7</p>
</div>

### 3.1 Dados da entrevistada

<div style="text-align: center">
<p>Tabela 2: Dados da entrevistada</p>
</div>

| Nome            | Idade   | Gênero   | Ocupação  | Cidade/Estado |
| --------------- | ------- | -------- | --------- | ------------- |
| Mariana Alencar | 18 anos | Feminino | Estudante | Brasília/DF   |

<div style="text-align: center">
<p>Fonte: Grupo 7</p>
</div>

### 3.2 Perguntas

1.  Por qual motivo você utiliza o TikTok?
2.  Quanto tempo você costuma passar diariamente no aplicativo?
3.  Como o aplicativo te traz entretenimento?
4.  Que funcionalidade do aplicativo você utiliza mais?
5.  Que funcionalidade do aplicativo você utiliza menos?
6.  Você cria vídeos na plataforma?
7.  Como você utiliza o chat do TikTok?
8.  Com que frequência você costuma curtir e/ou comentar vídeos?
9.  Você encontra alguma dificuldade ao utilizar o aplicativo?
10.  Consegue pensar em alguma coisa que possa ser melhorada no aplicativo?

### 3.3 Respostas

1. Por qual motivo você utiliza o TikTok?<br></br>
    
    "Eu uso para entretenimento"<br></br>

2. Quanto tempo você costuma passar diariamente no aplicativo?<br></br>
    
    "Diariamente? Uma hora, uma hora e meia"<br></br>
3. Como o aplicativo te traz entretenimento?<br></br>
    
    "Ah, quando estou entediada ele me diverte". <br></br>

    Logo após, pergunto: "No seu dia a dia, quais as horas que você mais costuma abrir o TikTok? Por exemplo se está fazendo alguma coisa você usa de plano de fundo ou usa apenas para assistir TikTok?"<br></br> 

    Resposta: "Quando estou fazendo outra coisa também".<br></br>

    Pergunto: "Então os dois?" <br></br>

    Resposta: "Os dois."<br></br>
4. Que funcionalidade do aplicativo você utiliza mais?<br></br>

    "A página principal, vídeos recomendados"<br></br>
5. Que funcionalidade do aplicativo você utiliza menos?<br></br>

    "A parte de amigos, que colocaram na última atualização"<br></br>
6. Você cria vídeos na plataforma?<br></br>

    "Crio, mas não posto"<br></br>

    Pergunto: "Então você grava os vídeos, usando efeitos, mas nunca posta no seu perfil"<br></br>

    Resposta: "É, exatamente"<br></br>
7. Como você utiliza o chat do TikTok?<br></br>

    "Eu uso para enviar os vídeos que eu gosto para as pessoas"<br></br>

    Pergunto: "Você costuma utilizar como um chat mesmo para conversar?"<br></br>
    
    Resposta: "Não, só para enviar vídeos"<br></br>
8. Com que frequência você costuma curtir e/ou comentar vídeos?<br></br>

    "Sempre"<br></br>

    Pergunto: "Até os que você não gosta?"<br></br>
    
    Resposta: "Não, só os que eu gosto"<br></br>
    
    Pergunto: "E comentar? É na mesma frequência?"<br></br>
    
    Resposta: "Bem menos"<br></br>
    
    Pergunto: "Por que você comenta nos vídeos?"<br></br>
    
    Resposta: "Porque eu gosto dos vídeos"<br></br>
9. Você encontra alguma dificuldade ao utilizar o aplicativo?<br></br>

    "Não"<br></br>

    Pergunto: "Tem alguma coisa que te incomoda no aplicativo? Alguma coisa que poderia ser retirada?"<br></br>

    Resposta: "Poderia ser retirada a parte de amigos (Feed onde só aparecem vídeos de amigos), que falei"<br></br>

10. Consegue pensar em alguma coisa que possa ser melhorada no aplicativo?<br></br>

    "Acho que poderia ter uma opção de reproduzir os vídeos automaticamente, sem precisar passar manualmente, porque as vezes, igual falei, fico vendo enquanto faço outra coisa e tenho que parar de fazer essa outra coisa para passar o vídeo, então poderia ter a opção de passar sozinho"

## 4. Requisitos elicitados

### Legenda

* ENT: Entrevista
* RF: Requisito Funcional

<div style="text-align: center">
<p>Tabela 3: Tabela de requisitos elicitados</p>
</div>

| ID    | Descrição                                                     | Tipo  |
| ----- | ------------------------------------------------------------- | ----- |
| ENT01 | Deve haver uma área de vídeos recomendados                    | RF01  |
| ENT02 | Deve ser possível filmar utilizando o aplicativo              | RF02  |
| ENT03 | Deve ser possível editar vídeos utilizando o aplicativo       | RF03  |
| ENT04 | Deve ser possível enviar vídeos para outras pessoas           | RF04  |
| ENT05 | Deve ser possível curtir vídeos                               | RF05  |
| ENT06 | Deve ser possível comentar vídeos                             | RF06  |
| ENT07 | Deve ser possível passar vídeos automaticamente               | RF07  |
| ENT08 | O aplicativo deve impedir que a tela bloqueie automaticamente | RNF01 |
<div style="text-align: center">
<p>Fonte: Grupo 7</p>
</div>

## 5. Referências

>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 07. Brasília: Unb-Gama, 20--. Color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124453/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 12 jul. 2022.
>AVELINO, Luis Gustavo. 2019.2-Duolingo. 2019. Disponível em: https://github.com/Requisitos-de-Software/2019.2-Duolingo/blob/master/docs/elicitacao/Entrevista.md. Acesso em: 12 jul. 2022.
