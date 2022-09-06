# Caso de uso
## 1. Versionamento

<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>

| Versão | Autor                                     | Alterações                          | Revisor     |
|:------:| ----------------------------------------- | ----------------------------------- | ----------- |
|  1.0   | Matheus Soares  & Pedro Henrique Nogueira | Reunião de formação de caso de uso  | Iago Cabral |
|  1.1   | Matheus Soares                            | Documentação dos casos de uso e UML | Iago Cabral |
|  1.2   | Matheus Soares                            | Adição dos UC01 | Iago Cabral |
| 1.3       |      Pedro Henrique Nogueira                                     |          Adição dos UC02, UC03, UC04 e UC05                            |     Iago Cabral        |

<div style="text-align: center">
<p>Fonte: Grupo 7</p>
</div>

## 2. Introdução
<p style="text-indent: 20px; text-align: justify">
Na Linguagem de modelagem unificada (UML), o diagrama de caso de uso resume os detalhes dos usuários do seu sistema (também conhecidos como atores) e as interações deles com o sistema (Douglas em Diagrama de caso de uso UML: O que é, como fazer e exemplos - LucidChart) .
</p>

## 3. Metodologia
<p style="text-indent: 20px; text-align: justify">
Por meio do estudo do que foi levantado no processo de elicitação os membros se reuniram por meio da ferramente discord para sintetizar o que será as versões do diagrama de uso UML do TikTok. A ferramenta utilizada para composição do UML foi o LucidChart. 
</p>

## 4. Casos de uso - Diagrama UML

### 4.1. Componentes

#### 4.1.1. Atores
<p style="text-indent: 20px; text-align: justify"> Bonecos palito, representando as pessoas que realmente implementam os casos de uso.</p>



<center>

<div style="text-align: center">
<p>Imagem 1: Ator</p>
</div>

<img width="95px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/Actor.png?raw=true">
</center>

<div style="text-align: center">
<p>Fonte: Milene Serrano, Requisitos </p>
</div>

#### 4.1.2. Casos de uso

<p style="text-indent: 20px; text-align: justify"> 
Formato oval na horizontal e que representam os diferentes usos que um usuário pode ter.
</p>

<div style="text-align: center">
<p>Imagem 2: Caso de Uso</p>
</div>

<center>
<img width="200px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/Use-Case.png?raw=true">
</center>
<div style="text-align: center">
<p>Fonte: Milene Serrano, Requisitos </p>
</div>

#### 4.1.3. Caixa de limite do sistema
<p style="text-indent: 20px; text-align: justify"> 
Caixa que define um escopo do sistema para os casos de uso. Todos os casos de uso fora da caixa são considerados fora do escopo do sistema.
</p>

<div style="text-align: center">
<p>Imagem 3: Caixa de limite do sistema</p>
</div>

<center>
<img width="100px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/System.png?raw=true">
</center>


<div style="text-align: center">
<p>Fonte: Milene Serrano, Requisitos </p>
</div>


#### 4.1.4. Inclusão
<p style="text-indent: 20px; text-align: justify"> 
Quando o caso de uso A “inclui” o caso de uso B, significa que sempre que o caso de uso A for executado o caso de uso B também será executado
</p>

<div style="text-align: center">
<p>Imagem 4: Inclusão</p>
</div>

<center>
<img width="400px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/includs.png?raw=true">
</center>


<div style="text-align: center">
<p>Fonte: Milene Serrano, Requisitos </p>
</div>

#### 4.1.5. Extensão

<p style="text-indent: 20px; text-align: justify"> 
Quando o caso de uso B estende o caso de uso A, significa que quando o caso de uso A for executado o caso de uso B poderá (poderá – talvez não seja) ser executado também. 
</p>

<div style="text-align: center">
<p>Imagem 5: Extensão</p>
</div>

<center>
<img width="400px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/EXTENDS.png?raw=true">
</center>


<div style="text-align: center">
<p>Fonte: Milene Serrano, Requisitos </p>
</div>

## 4.2. Diagrama UML

<div style="text-align: center">
<p>Imagem 6: Diagrama UML</p>
</div>

<center>
<img width="800px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/diagramaUMLTiktok.png?raw=true">
</center>


<div style="text-align: center">
<p>Fonte: Grupo 7 </p>
</div>
<hr>
<div style="text-align: center">
<p>Tabela 2: UC01</p>
</div>

|       UC01        | Consumir Conteúdo                                                                                                                                                     |
| :---------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     Descrição     | O usuário deve ser capaz de consumir conteúdo de forma fácil.                                                                                                                                        |
|       Ator        | Usuário |
|   Pré-condições   | Aplicativo instalado                                                    |
|  Fluxo Principal  | O usuário apenas deve abrir o aplicativo e o conteúdo deve estar presente em sua homepage                                                                           |
| Fluxo Alternativo | O usuário pode pesquisar um conteúdo desejado, e caso seja de sua vontade ele pode curtir, fazer comentário ou até mesmo salvar o vídeo em sua pasta de favoritos. Para essas 3 condições o usuário será obrigado a se autenticar ou criar conta                                                                                       |
|   Pós-condições   | Caso não tenha conexão com a internet o aplicativo vai se encontrar em idle|
|  Rastreabilidade  | RF05 RF04 RF09 RF11 RF02 RF01 RF06                                                                                                                             |



<div style="text-align: center">
<p>Fonte: Grupo 7 </p>
</div>
<hr>

<div style="text-align: center">
<p>Tabela 3: UC02</p>
</div>

|       UC02        | Enviar Vídeo                                                                                                                                                    |
| :---------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     Descrição     | O usuário deve ser capaz de enviar seu vídeo de forma fácil.                                                                                  |
|       Ator        | Usuário |
|   Pré-condições   | Aplicativo instalado, conexão com a internet e estar conectado na sua conta.                                                 |
|  Fluxo Principal  | O usuário após abrir o aplicativo, deverá fazer login e clicar no ícone de enviar vídeo (Imagem 7).                                                                            |
| Fluxo Alternativo | O usuário pode gravar o vídeo pelo próprio aplicativo ou selecionar um da galeria do seu aparelho celular. Para essas 2 condições o usuário será obrigado a se autenticar.                                                                                       |
|   Pós-condições   | O vídeo enviado ficara disponível para que outros usuários da plataforma o assistam, curtam, comentem e compartilhem.  Caso não tenha conexão com a internet o aplicativo vai se encontrar em idle.|
|  Rastreabilidade  | RF03  RNF06 RF23 RF24 RF19 RF20 RF21  RF22  RF25 RF26                                                                                                                    |



<div style="text-align: center">
<p>Fonte: Grupo 7 </p>
</div>



<center>
    <p>Imagem 7: Icone de enviar vídeo</p>
    <img height="350px" width="200" src="https://media.discordapp.net/attachments/744698026462937211/999424128174010398/unknown.png?width=265&height=473">


<div style="text-align: center">
<p>Fonte: TikTok </p>
</div>

</center>

<hr>

<div style="text-align: center">
<p>Tabela 4: UC03</p>
</div>

|       UC03       | Criar perfil                                                                                                                                                      |
| :---------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     Descrição     | O usuário deve ser capaz de criar o seu perfil .                                                                                  |
|       Ator        | Usuário |
|   Pré-condições   | Aplicativo instalado, conexão com a internet e estar conectado na sua conta.                                                 |
|  Fluxo Principal  | O usuário após abrir o aplicativo, deverá fazer login e clicar no ícone de perfil (Imagem 8).                                                                            |
| Fluxo Alternativo | O usuário pode editar o perfil. Para isso o usuário será obrigado a se autenticar.                                                                                        |
|   Pós-condições   | O usuário poderá ver o seu perfil, nele é possível ver os vídeos enviados, número de seguidores, curtidas e seguindo, navegar pelos seus vídeos curtidos e pelas suas pastas de favoritos. Caso não tenha conexão com a internet o aplicativo vai se encontrar em idle.|
|  Rastreabilidade  | RF04 RF11 RF13 RF14 RF16 RF17 RF29 



<div style="text-align: center">
<p>Fonte: Grupo 7 </p>
</div>

<center>

<p>Imagem 8: Icone de perfil</p>

<img height="350px" width="200" src="https://media.discordapp.net/attachments/827361619611877407/999434496862597170/unknown.png?width=267&height=473">


<div style="text-align: center">
<p>Fonte: TikTok </p>
</div>

</center>

<hr>

<div style="text-align: center">
<p>Tabela 5: UC04</p>
</div>

|       UC04       | Trocar Mensagens                                                                                                                                                      |
| :---------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     Descrição     | O usuário deve ser capaz  de se comunicar com outros usuarios .                                                                                  |
|       Ator        | Usuário |
|   Pré-condições   | Aplicativo instalado, conexão com a internet e estar conectado na sua conta.                                                |
|  Fluxo Principal  | O usuário após abrir o aplicativo, deverá fazer login e clicar no ícone de caixa de entrada(Imagem 9) e selecionar a conversa que deseja respondem.                                                                            |
| Fluxo Alternativo |O usuário pode acessar um perfil da comunidade e enviar uma mensagem direta ou pode enviar mensagens ou vídeos para usuários na sua lista de amigos. |
|   Pós-condições   | O usuário poderá ver as mensagens que foram enviadas ou recebidas. Caso não tenha conexão com a internet o aplicativo vai se encontrar em idle.|
|  Rastreabilidade  | RF06 RF12 RF18



<div style="text-align: center">
<p>Fonte: Grupo 7 </p>
</div>

<center>
   <p>Imagem 9: Icone da caixa de entrada</p>
    <img height="350px" width="200" src="https://cdn.discordapp.com/attachments/827361619611877407/999443277176655872/unknown.png">


<div style="text-align: center">
<p>Fonte: TikTok </p>
</div>

</center>

<hr>

<div style="text-align: center">
<p>Tabela 6: UC05</p>
</div>

|       UC05      | Escutar Música                                                                                                                                                      |
| :---------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     Descrição     | O usuário deve ser capaz  de ouvir musica no aplicativo .                                                                                  |
|       Ator        | Usuário |
|   Pré-condições   | Aplicativo instalado e conexão com a internet.                                                |
|  Fluxo Principal  | O usuário após abrir o aplicativo pode acessar a aba "música" no canto superior esquerdo                                                                           |
| Fluxo Alternativo |Não há  |
|   Pós-condições   | O usuário poderá ver as mens O usuário poderá escutar a música desejada, mesmo com o aplicativo minimizado. Caso não tenha conexão com a internet o aplicativo vai se encontrar em idle.  |
|  Rastreabilidade  | RF39



<div style="text-align: center">
<p>Fonte: Grupo 7 </p>
</div>

<hr>

##  Referências
> - Milene Serrano, Requisitos - Aula 13. Acesso em: 19 de jul. de 2022. Disponível em: Aprender3.
> -  LUCIDCHART. Diagrama de caso de uso UML: O que é, como fazer e exemplos: por que usar um diagrama uml?. Por que usar um diagrama UML?. 2019. Lucidchart. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml. Acesso em: 19 jul. 2022.
