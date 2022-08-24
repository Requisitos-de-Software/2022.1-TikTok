# Backward From
## 1. Versionamento
<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>


| Versão | Autor                                     | Alterações                          | Revisor     |
|:------:| ----------------------------------------- | ----------------------------------- | ----------- |
|  1.0   | Matheus Soares | Elaboração do documento do artefato backward from |  |

<div style="text-align: center">
<p>Fonte: Matheus Soares</p>
</div>

## Introdução
<p style="text-indent: 20px; text-align: justify">
O objetivo deste documento é deixar explicíto a rastreabilidade de todos os requisitos elicitados durante o desenrolar da matéria, logo serão ligados os requisitos aos seus respectivos métodos de elicitação e modelagem tendo como amparo o método de rastreabilidade Backward From.
</p>


## Metodologia

Foi organizados os Requisitos Funcionais e Não Funcionais previamente [Elicitados](https://requisitos-de-software.github.io/2019.2-Duolingo/elicitacao/RequisitosElicitados/) formando as tabelas abaixo com os rastros dos mesmo, assim, realizou-se uma verificação dos elos relacionados a cada artefatos.

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

### Requisitos Funcionais e Não Funcionais

| ID | Descrição | Origem |  Elos |
| :------: | -------- | :--------: | :------:  |
| RF01     | Deve haver uma área de vídeos recomendados | [ENT01](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [L09](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l09-for-youpara-voce) [L20](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l20-usuario-regular) |      |
| RF02     | Deve ser possível filmar utilizando o aplicativo | [ENT02](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST01](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)   |      |
| RF03     | Deve ser possível editar vídeos utilizando o aplicativo | [ENT03](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST02](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|      |
| RF04     | Deve ser possível enviar vídeos para outras pessoas | [ENT04](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST16](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS12](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L05](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l05-compartilhar) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) |      |
| RF05     | Deve ser possível curtir vídeos | [ENT05](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST09](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS05](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C05](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-05) [L05](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l06-curtir)|  |
| RF06     | Deve ser possível comentar vídeos | [ENT06](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados) [ST10](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS10](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C10](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-10) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) |      |
| RF07     | Deve ser possível passar vídeos automaticamente | [ENT07](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados)|      |
| RNF01     | O aplicativo deve impedir que a tela bloqueie automaticamente | [ENT08](https://requisitos-de-software.github.io/2022.1-TikTok/entrevista/#4-requisitos-elicitados)|      |
| RF08 |	Eu, como produtor de conteúdo, desejo adicionar efeitos aos vídeos para que eles fiquem mais divertidos | [ST03](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|      |
| RF09 |Eu, como produtor de conteúdo, desejo postar o vídeo no meu perfil para que meus seguidores e os usuários da plataforma possam assistí-los |[ST04](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS03](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C03](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-03) [UC02](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L15](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l15-postar) [L16](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l16-produtor-de-conteudo) |      |
| RF10 |Eu, como produtor de conteúdo, desejo acompanhar as métricas(curtidas,visualizações e comentários) do meu vídeo para ter o feedback dos telespectadores |[ST05](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [C08](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-08)|      |
| RF11 | Eu, como usuário, desejo enviar e receber mensagem de outros usuários para ter uma conversa dentro da plataforma|[ST06](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L03](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l03-caixa-de-entrada) [L11](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l11-mensagem)  |      |
| RF12 |Eu, como produtor de conteúdo, desejo fazer um dueto (metade da tela meu vídeo e a outra metade de outro produtor) com outros vídeos para utilizá-los em minhas criações |[ST07](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [L07](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l07-dueto)  |      |
| RF13 |	Eu, como usuário, desejo de passar de um vídeo para o outro com o movimento de "arrastar pra cima" |[ST08](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [C09](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-09) |  |
| RF14 |Eu, como usuário, desejo de seguir perfis de criadores de conteúdo	 |[ST11](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [L01](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l01-amigos) [L19](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l19-seguirseguidor) |      |
| RF15 |Eu, como usuário, desejo visualizar os vídeos que curti no meu perfil	 |[ST12](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|      |
| RF16 |Eu, como usuário, desejo curtir um vídeo ao dar um duplo-clique na tela |[ST13](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) |      |
| RF17 |Eu, como usuário, desejo pausar os vídeos |[ST14](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) |      |
| RF18 |Eu, como usuário, desejo voltar ou avançar o vídeo |[ST15](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) |      |
| RF19 |Eu, como usuário, desejo marcar os vídeos que estou respondendo no chat privado para o outro usuário saber de que vídeo estou falando | [ST17](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados)|      |
| RF20 |	Eu, como usuário, desejo enviar mensagens privadas para outro usuário |[ST18](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS19](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [UC04](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) |   |
| RNF02 |	Eu, como usuário, desejo utilizar o aplicativo em dispositivos Android e iOS |[ST19](https://requisitos-de-software.github.io/2022.1-TikTok/storytelling/#requisitos-elicitados) [BS22](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais) |      |
|RF21|Deve ser possível manter o vídeo que está sendo exibido ao dar refresh|[INT01](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/)| |
|RF22|Deve ser possível deixar o vídeo mudo|[INT02](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/)| |
|RF23|Deve ser possível buscar efeitos e filtros|[INT03](https://requisitos-de-software.github.io/2022.1-TikTok/instrospeccao/)| |
|RF24|O aplicativo deve mostrar os vídeos na timeline|[BS01](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C01](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-01) [UC01](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L02](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l01-amigos) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) | |
|RF25|O app deve disponibilizar busca|[BS02](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [BS15](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C02](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-02) [L14](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l14-pesquisar) | |
|RF26|O usuário deve ser capaz de favoritar os vídeos|[BS04](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C04](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-04)| |
|RF27|O usuário deve ser capaz de filtrar o conteúdo que lhe é apresentado|[BS06](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C06](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-06) | |
|RF27|O usuário deve ser capaz de editar o seu perfil|[BS07](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [C07](https://requisitos-de-software.github.io/2022.1-TikTok/cenarios/#cenario-07) [L13](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l13-perfil) | |
|RF28|O usuário deve ser capaz de ver o próprio perfil|[BS08](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L08](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l08-entrar) [L13](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l13-perfil) | |
|RF29|O usuário deve ser capaz de acessar perfis públicos|[BS09](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/)| |
|RF30|O usuário deve ser capaz de salvar vídeos|[BS11](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L18](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l18-salvar) [L21](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l21-video) | |
|RF31|O usuário deve ser capaz de sacar o dinheiro das visualizações|[BS13](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)| |
|RF32|O usuário deve ser capaz de sinalizar o faixa etária de seu conteúdo|[BS14](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)| |
|RF33|O usuário deve ser capaz de privar o seu perfil|[BS16](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L13](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l13-perfil) | |
|RF34|O usuário deve ser capaz de criar pasta de vídeos favoritos|[BS17](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [L04](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l04-colecao)| |
|RF35|O usuário deve ser capaz de convidar seus amigos|[BS18](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)| |
|RF36|O usuário deve ser capaz de saber quem visualizou seu perfil|[BS20](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais)| |
|RF37|O usuário deve ser capaz de escutar música|[BS21](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#51-requisitos-funcionais) [UC05](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) [L12](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l12-musica) | |
|RNF03|O aplicativo deve ser capaz de se recuperar de falhas|[BS23](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
|RNF05|O aplicativo deve demonstrar boa usabilidade|[BS24](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
|RNF06|Os vídeos devem possuir boa qualidade|[BS25](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
|RNF07|O aplicativo deve ter boa performace nos aparelhos com SO(ANDROID/IOS)|[BS26](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
|RNF08|O app deve ser otimizado para a experiência mobile|[BS27](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
|RNF09|O app deve ter um design bonito e familiar|[BS28](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
|RNF10|O aplicativo deve suportar multiplataformas|[BS29](https://requisitos-de-software.github.io/2022.1-TikTok/brainstorm/#52-requisitos-nao-funcionais)| |
| RF38 | O usuário deve ser capaz de criar o seu perfil | [UC03](https://requisitos-de-software.github.io/2022.1-TikTok/casodeUso/) |  |
| RF39 | O usuário pode começar uma transmissão para que outros possam participar e interagir | [L10](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l10-live) [L16](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l16-produtor-de-conteudo) |   |
| RF40 | A partir da ferramenta o usuario pode denunciar/reportar videos | [L17](https://requisitos-de-software.github.io/2022.1-TikTok/lexicos/#l17-reportar) | |



##  Referências
> - Backward From - Duolingo. Disponível em: <https://requisitos-de-software.github.io/2019.2-Duolingo/posrastreabilidade/BackwardFrom/>. Acesso em: 23 ago. 2022.
> - SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 26. Acesso em: 21 de ago. de 2022. Disponível em: Aprender3.
