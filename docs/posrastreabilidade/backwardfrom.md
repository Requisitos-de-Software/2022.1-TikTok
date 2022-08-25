# Backward From
## 1. Versionamento
<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>


| Versão | Autor                                     | Alterações                          | Revisor     |
|:------:| ----------------------------------------- | ----------------------------------- | ----------- |
|  1.0   | Matheus Soares & Matheus Perillo | Elaboração do documento do artefato backward from | Mateus Caltabiano |
|  1.1   | João Victor Correia & Matheus Soares| Elos | Mateus Caltabiano |

<div style="text-align: center">
<p>Fonte: Matheus Soares</p>
</div>

## Introdução
<p style="text-indent: 20px; text-align: justify">
O objetivo deste documento é deixar explicíto a rastreabilidade de todos os requisitos elicitados durante o desenrolar da matéria, logo serão ligados os requisitos aos seus respectivos métodos de elicitação e modelagem tendo como amparo o método de rastreabilidade Backward From.
</p>


## Metodologia

Os requisitos funcionais e não funcionais previamente [Elicitados](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#1-versionamento) foram organizados de forma a sintetizar a tabela a baixo, desta maneira realizou-se a verificação de elos e seus respectivos artefatos. Os elos foram desenvolvidos baseado no Meta-Modelo de Toranzo.

## Tabelas
### Corpo da tabela
<p style="text-indent: 20px; text-align: justify">
O corpo de tabela a seguir foi baseado no trabalho produzido pelo grupo duolingo, desta forma seguiremos o mesmo template.
</p>

<div style="text-align: left">
<p>Tabela 2: Corpo da Tabela</p>
</div>

| ID | Descrição | Origem |  Elos |
| :------: | -------- | -------- | :------:  |
| Text     | Text     | Text     | Text      |
<div style="text-align: left">
<p>Fonte: Grupo Duolingo</p>
</div>

**Legendas:**

> - RF: Requisito Funcional
> - RNF: Requisito Não Funcional
> - BS: Brainstorm
> - ENT: Entrevista
> - INT: Instrospecção
> - ST: Story Teling
> - C: Cenários
> - E: Épico
> - F: Feature
> - US: Histórias de Usuário
> - UC: Casos de Uso
> - L: Léxicos 

### Requisitos Funcionais

| ID | Descrição | Origem |  Elos |
| :------: | -------- | :--------: | :------:  |
| RF01     | Deve haver uma área de vídeos recomendados | [ENT01](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [L09](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l09-for-youpara-voce) [L20](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l20-usuario-regular) [US23](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |  EF01  |
| RF02     | Deve ser possível filmar utilizando o aplicativo | [ENT02](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST01](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)   |   EF02  |
| RF03     | Deve ser possível editar vídeos utilizando o aplicativo | [ENT03](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST02](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [US28](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |    EF03  |
| RF04     | Deve ser possível enviar vídeos para outras pessoas | [ENT04](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST16](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS12](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L05](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l05-compartilhar) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) |   EF04   |
| RF05     | Deve ser possível curtir vídeos | [ENT05](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST09](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS05](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C05](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-05) [L05](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l06-curtir)| EF05 |
| RF06     | Deve ser possível comentar vídeos | [ENT06](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST10](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS10](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C10](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-10) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) |   EF06   |
| RF07     | Deve ser possível passar vídeos automaticamente | [ENT07](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [US06](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |  EF07    |
| RF08 |	Eu, como produtor de conteúdo, desejo adicionar efeitos aos vídeos para que eles fiquem mais divertidos | [ST03](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|  EF08    |
| RF09 |Eu, como produtor de conteúdo, desejo postar o vídeo no meu perfil para que meus seguidores e os usuários da plataforma possam assistí-los |[ST04](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS03](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C03](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-03) [UC02](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L15](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l15-postar) [L16](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l16-produtor-de-conteudo) [US26](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |  EF09    |
| RF10 |Eu, como produtor de conteúdo, desejo acompanhar as métricas(curtidas,visualizações e comentários) do meu vídeo para ter o feedback dos telespectadores |[ST05](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [C08](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-08) [US10](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |   EF10  |
| RF11 | Eu, como usuário, desejo enviar e receber mensagem de outros usuários para ter uma conversa dentro da plataforma|[ST06](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L03](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l03-caixa-de-entrada) [L11](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l11-mensagem)  |   EF11  |
| RF12 |Eu, como produtor de conteúdo, desejo fazer um dueto (metade da tela meu vídeo e a outra metade de outro produtor) com outros vídeos para utilizá-los em minhas criações |[ST07](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [L07](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l07-dueto)  |  EF12    |
| RF13 |	Eu, como usuário, desejo de passar de um vídeo para o outro com o movimento de "arrastar pra cima" |[ST08](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [C09](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-09) | EF13 |
| RF14 |Eu, como usuário, desejo de seguir perfis de criadores de conteúdo	 |[ST11](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [L01](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l01-amigos) [L19](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l19-seguirseguidor) |   EF14   |
| RF15 |Eu, como usuário, desejo visualizar os vídeos que curti no meu perfil	 |[ST12](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|  EF15    |
| RF16 |Eu, como usuário, desejo curtir um vídeo ao dar um duplo-clique na tela |[ST13](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) |    EF16  |
| RF17 |Eu, como usuário, desejo pausar os vídeos |[ST14](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) |   EF17   |
| RF18 |Eu, como usuário, desejo voltar ou avançar o vídeo |[ST15](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) |   EF18   |
| RF19 |Eu, como usuário, desejo marcar os vídeos que estou respondendo no chat privado para o outro usuário saber de que vídeo estou falando | [ST17](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|  EF19    |
| RF20 |	Eu, como usuário, desejo enviar mensagens privadas para outro usuário |[ST18](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) | EF20  |
|RF21|Deve ser possível manter o vídeo que está sendo exibido ao dar refresh|[INT01](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/)| EF21|
|RF22|Deve ser possível deixar o vídeo mudo|[INT02](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/) [US17](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |EF22 |
|RF23|Deve ser possível buscar efeitos e filtros|[INT03](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/) [US25](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) | EF23|
|RF24|O aplicativo deve mostrar os vídeos na timeline|[BS01](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C01](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-01) [UC01](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L02](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l01-amigos) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) [US01](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |EF24 |
|RF25|O app deve disponibilizar busca|[BS02](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [BS15](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C02](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-02) [L14](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l14-pesquisar) |EF25 |
|RF26|O usuário deve ser capaz de favoritar os vídeos|[BS04](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C04](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-04)|EF26 |
|RF27|O usuário deve ser capaz de filtrar o conteúdo que lhe é apresentado|[BS06](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C06](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-06) | EF27|
|RF28|O usuário deve ser capaz de editar o seu perfil|[BS07](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C07](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-07) [L13](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l13-perfil) |EF28 |
|RF29|O usuário deve ser capaz de ver o próprio perfil|[BS08](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L08](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l08-entrar) [L13](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l13-perfil) | EF29|
|RF30|O usuário deve ser capaz de acessar perfis públicos|[BS09](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/)| EF30|
|RF31|O usuário deve ser capaz de salvar vídeos|[BS11](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L18](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l18-salvar) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) |--|
|RF32|O usuário deve ser capaz de sacar o dinheiro das visualizações|[BS13](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [US41](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |-- |
|RF33|O usuário deve ser capaz de sinalizar o faixa etária de seu conteúdo|[BS14](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [US13](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |-- |
|RF34|O usuário deve ser capaz de privar o seu perfil|[BS16](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L13](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l13-perfil) |-- |
|RF35|O usuário deve ser capaz de criar pasta de vídeos favoritos|[BS17](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L04](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l04-colecao)|-- |
|RF36|O usuário deve ser capaz de convidar seus amigos|[BS18](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)|-- |
|RF37|O usuário deve ser capaz de saber quem visualizou seu perfil|[BS20](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)|-- |
|RF38|O usuário deve ser capaz de escutar música|[BS21](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [UC05](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L12](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l12-musica) |-- |
| RF39 | O usuário deve ser capaz de criar o seu perfil | [UC03](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) | -- |
| RF40 | O usuário pode começar uma transmissão para que outros possam participar e interagir | [L10](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l10-live) [L16](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l16-produtor-de-conteudo) | --  |
| RF41 | A partir da ferramenta o usuario pode denunciar/reportar videos | [L17](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l17-reportar) |-- |

## Requisitos Não Funcionais

| ID | Descrição | Origem |  Elos |
| :------: | -------- | :--------: | :------:  |
| RNF01     | O aplicativo deve impedir que a tela bloqueie automaticamente | [ENT08](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados)|ENF01  |
| RNF02 |	Eu, como usuário, desejo utilizar o aplicativo em dispositivos Android e iOS |[ST19](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) |  ENF02    |
|RNF03|O aplicativo deve ser capaz de se recuperar de falhas|[BS23](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)|ENF03 |
|RNF04|O aplicativo deve demonstrar boa usabilidade|[BS24](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| ENF04|
|RNF05|Os vídeos devem possuir boa qualidade|[BS25](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| ENF05|
|RNF06|O aplicativo deve ter boa performace nos aparelhos com SO (ANDROID/IOS)|[BS26](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) [US32](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) | ENF06|
|RNF07|O app deve ser otimizado para a experiência mobile|[BS27](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) [US31](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) | ENF07|
|RNF08|O app deve ter um design bonito e familiar|[BS28](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)|ENF08 |
|RNF09|O aplicativo deve suportar multiplataformas|[BS29](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) [US35](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) |ENF09 |


## Elos Funcionais
### EF01
**Categoria:** Desenvolvimento

**Elos:**
Agrega: [ST01](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) agrega o [US23](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/)

### EF02
**Categoria:** Desenvolvimento

**Elos:**
Satisfaz: [ENT02](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) satisfaz o [ST01](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) 

### EF03
**Categoria:** Desenvolvimento

**Elos:**
Representa: [ENT03](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) representa o [US28](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/)

Agrega: [ST01](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) agrega o  [US28](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/)

### EF04
**Categoria:** Desenvolvimento

**Elos:**
Recurso: [ST16](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) é recurso [ST06](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) 

Satisfaz: [ENT04](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) satisfaz o [ST16](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

### EF05
**Categoria:** Desenvolvimento

**Elos:**

Recurso: [ST09](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) é recurso [C08](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-08) 

### EF06
**Categoria:** Desenvolvimento

**Elos:**

Recurso: [BS10](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) é recurso [C08](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-08)  

Alocação: [US02](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) aloca [ST10](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) 

### EF07
**Categoria:** Desenvolvimento

**Elos:**

Satisfaz: [US06](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) satisfaz [ENT07](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados)

### EF08
**Categoria:** Desenvolvimento

**Elos:**

Recurso: [INT03](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/) é recurso de [ST03](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

Satisfaz: [ST03](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) satisfaz [INT03](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/)

### EF09
**Categoria:** Desenvolvimento

**Elos:**

Recurso: [ST04](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) é recurso de [UC03](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/)

Recurso: [BS03](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) é recurso de [ST11](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

Agregação: [L09](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l09-for-youpara-voce) agrega [C03](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-03) 

### EF10
**Categoria:** Desenvolvimento

**Elos:**

Recurso: [ST05](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) é recurso de [ST09](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

Recurso: [US10](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/) é recurso de [ST10](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

Alocação: [C08](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-08) aloca [ST04](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

### EF11
**Categoria:** Desenvolvimento

**Elos:**
Representa: [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) representa o [ST06](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) 

### EF12
**Categoria:** Desenvolvimento

**Elos:**
Agrega: [ST07](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) agrega o [ENT03](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados)

### EF13
**Categoria:** Desenvolvimento

**Elos:**
Representação: [C09](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-09) representa o [ST08](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

### EF14
**Categoria:** Desenvolvimento

**Elos:**
Agrega: [ST11](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) agrega o [BS09](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)

### EF15
**Categoria:** Desenvolvimento

**Elos:**
Agrega: [ST12](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) agrega o [BS08](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)


### EF16
**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [ST13](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) satisfaz [ST12](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

### EF17
**Categoria:** Desenvolvimento

**Elos:**

Responsabilidade: [ST14](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) tem responsabilidade em [BS01](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)

### EF18
**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [ST15](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) satisfaz [ST08](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) e [C09](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-09)

### EF19
**Categoria:** Desenvolvimento

**Elos:**

Recurso: [ST17](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) é recurso de [ST18](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados), [BS19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/)

### EF20
**Categoria:** Desenvolvimento

**Elos:**

Representação: [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) representa [ST18](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) e [ST06](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)

## Elos Não Funcionais

### ENF01
**Categoria:** Desenvolvimento

**Elos:** 

[ENT08](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados)

### ENF02
**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [ST19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) satisfaz [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)

Satisfação: [ST19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) satisfazem [BS26](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [US32](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/#4-historia-de-usuario)

Agregação: [ST19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) agregam [BS29](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [US35](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/#4-historia-de-usuario)

### ENF03
**Categoria:** Desenvolvimento

**Elos:**

Agregação: [BS23](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) agrega [BS26](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [US32](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/#4-historia-de-usuario)

### ENF04
**Categoria:** Desenvolvimento

**Elos:**

Agregação: [BS24](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) agrega [BS28](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)

### ENF05
**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [BS25](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) satisfaz [BS28](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)


### ENF06
**Categoria:** Desenvolvimento

**Elos:**

Satisfação: [ST19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) satisfazem [BS26](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [US32](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/#4-historia-de-usuario)

### ENF07
**Categoria:** Desenvolvimento

**Elos:**

Agrega: [BS27](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) satisfaz [BS26](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) e [US32](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/#4-historia-de-usuario)

### ENF08
**Categoria:** Desenvolvimento

**Elos:**

Agrega: [BS28](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) agrega o [BS28](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)

### ENF09
**Categoria:** Desenvolvimento

**Elos:** 

Agrega: [US35](https://requisitos-de-software.github.io/2022.1-TikTok/userStories/#4-historia-de-usuario) agrega o [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)

##  Referências
> - Backward From - Duolingo. Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/posrastreabilidade/BackwardFrom/>. Acesso em: 23 ago. 2022.
> - SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. Acesso em: 21 de ago. de 2022. Disponível em: Aprender3.