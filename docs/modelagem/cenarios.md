# Cenários

## 1. Versionamento



| Versão | Data       | Autor             | Alterações                         | Revisor         |
| ------ | ---------- | ----------------- | ---------------------------------- | --------------- |
| 1.0    | 19/07/2022 | Mateus Caltabiano | Abertura do documento de cenários  | Matheus Perillo |
| 1.1    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 01               | Matheus Perillo |
| 1.2    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 02               | Matheus Perillo |
| 1.3    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 03               | Matheus Perillo |
| 1.4    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 04               | Matheus Perillo |
| 1.4.1  | 19/07/2022 | Mateus Caltabiano | Adição de revisor no versionamento | Matheus Perillo |
| 1.5    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 05               | Matheus Perillo |
| 1.6    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 06               | Matheus Perillo |
| 1.7    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 07               | Matheus Perillo |
| 1.8    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 08               | Matheus Perillo |
| 1.9    | 19/07/2022 | Mateus Caltabiano | Adição do cenário 09               | Matheus Perillo |
| 1.10   | 19/07/2022 | Mateus Caltabiano | Adição do cenário 10               | Matheus Perillo |

## 2. Introdução

&emsp;&emsp;Cenários são basicamente cenas que ilustram um propósito, uma funcionalidade do sistema. É uma ferramenta importante para exemplificar o sistema como se fosse visto de fora, por exemplo por um usuário, utilizando exemplos específicos. É uma estratégia reconhecida para que se torne mais fácil a compreensão das interações entre ambientes e sistemas.

## 3. Metodologia

&emsp;&emsp;Foi definido um template para ser utilizado na definição de cada cenário com o intuito de deixar o documento padronizado. Apresentaremos os cenários de alguns dos requisitos funcionais definidos como "Must" em nossa priorização.

## 4. Template

<div style="text-align: center">
<p>Tabela 1: Template para os cenários</p>
</div>

### Cenário XX

| Abstração | Descrição                |
| --------- | ------------------------ |
| Título    | Descrição do título      |
| Objetivo  | Descrição do objetivo    |
| Contexto  | Descrição do contexto    |
| Atores    | Descrição dos atores     |
| Recursos  | Descrição dos recursos   |
| Episódios | Descrição dos episódios  |
| Restrição | Descrição das restrições |
| Exceção   | Descrição das exceções   |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

## 5. Cenários

<div style="text-align: center">
<p>Tabela 2: Cenário 01</p>
</div>

### Cenário 01

| Abstração | Descrição                                                                              |
| --------- | -------------------------------------------------------------------------------------- |
| Título    | Assistir um vídeo na timeline                                                          |
| Objetivo  | Utilizar o TikTok para assistir um vídeo na timeline                                   |
| Contexto  | Pré-condição - Ter um celular<br>Pré-condição - Ter o aplicativo instalado             |
| Atores    | Usuário                                                                                |
| Recursos  | Celular<br>Internet                                                                    |
| Episódios | Usuário está entediado<br>Usuário pega o celular<br>Usuário abre o TikTok              |
| Restrição | Celular estar com bateria<br>Usuário quer assistir TikTok<br>Celular estar funcionando |
| Exceção   | Celular sem bateria<br>Celular cai no chão<br>Celular sem conexão com a internet       |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 02

<div style="text-align: center">
<p>Tabela 3: Cenário 02</p>
</div>

| Abstração | Descrição                                                                                                                                   |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Título    | Buscar um vídeo                                                                                                                             |
| Objetivo  | Procurar por vídeos utilizando texto                                                                                                        |
| Contexto  | Pré-condição: Ter um celular com app instalado<br>Pré-condição: Saber o que quer encontrar                                                  |
| Atores    | Usuário                                                                                                                                     |
| Recursos  | Celular<br>Internet                                                                                                                         |
| Episódios | Usuário quer encontrar um vídeo<br>Usuário abre a ferramenta de busca<br>Usuário digita um texto                                            |
| Restrição | Usuário saber o que pesquisar<br>Algoritmo de busca encontrar vídeos relacionados<br>Celular estar com bateria<br>Celular estar funcionando |
| Exceção   | Celular sem conexão com a internet                                                                                                          |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 03

<div style="text-align: center">
<p>Tabela 4: Cenário 03</p>
</div>

| Abstração | Descrição                                                                                                                                     |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| Título    | Postar um vídeo                                                                                                                               |
| Objetivo  | Postar um vídeo no perfil                                                                                                                     |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado<br>Pré-condição: Ter um vídeo gravado<br>Pré-condição: Ter uma conta |
| Atores    | Criador de conteúdo                                                                                                                           |
| Recursos  | Celular<br>Internet                                                                                                                           |
| Episódios | Criador de conteúdo tem uma ideia<br>Criador de conteúdo grava um vídeo                                                                       |
| Restrição | Criador de conteúdo gostar do vídeo<br>Celular estar com bateria<br>Celular estar funcionando                                                 |
| Exceção   | TikTok bloquear o vídeo<br>Vídeo ser mais longo do que o suportado<br>Celular sem conexão com a internet                                      |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 04

<div style="text-align: center">
<p>Tabela 5: Cenário 04</p>
</div>

| Abstração | Descrição                                                                                                |
| --------- | -------------------------------------------------------------------------------------------------------- |
| Título    | Favoritar um vídeo                                                                                       |
| Objetivo  | Adicionar um vídeo assistido aos favoritos                                                               |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado<br>                             |
| Atores    | Usuário                                                                                                  |
| Recursos  | Celular<br>Internet                                                                                      |
| Episódios | Usuário pega o celular<br>Usuário abre o TikTok<br>Usuário assiste um vídeo<br>Usuário favoritar o vídeo |
| Restrição | Vídeo ser interessante<br>Celular estar com bateria<br>Celular estar funcionando                         |
| Exceção   | Celular quebrar<br>Usuário mudar de opinião sobre o vídeo<br>Celular sem conexão com a internet          |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 05

<div style="text-align: center">
<p>Tabela 6: Cenário 05</p>
</div>

| Abstração | Descrição                                                                                       |
| --------- | ----------------------------------------------------------------------------------------------- |
| Título    | Curtir um vídeo                                                                                 |
| Objetivo  | Deixar um vídeo marcado como curtido                                                            |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado                        |
| Atores    | Usuário                                                                                         |
| Recursos  | Celular<br>Internet                                                                             |
| Episódios | Usuário abre o TikTok<br>Usuário assiste vídeo<br>Usuário gosta do vídeo                        |
| Restrição | Celular estar com bateria<br>Celular estar funcionando                                          |
| Exceção   | Usuário mudar de ideia sobre o vídeo<br>Vídeo ser apagado<br>Celular sem conexão com a internet |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 06

<div style="text-align: center">
<p>Tabela 7: Cenário 06</p>
</div>

| Abstração | Descrição                |
| --------- | ------------------------ |
| Título    | Filtrar conteúdo      |
| Objetivo  | Retirar a possibilidade de certo tipo de conteúdo aparecer na página principal    |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado    |
| Atores    | Usuário     |
| Recursos  | Celular<br>Internet   |
| Episódios | Usuário abre o aplicativo<br>Usuário vê um conteúdo que não gosta<br>Usuário resolve que não quer ver conteúdos do mesmo tipo  |
| Restrição | Celular estar com bateria<br>Celular estar funcionando<br>Usuário não gostar do conteúdo |
| Exceção   | Celular quebrar<br>Usuário não se importar em ver o conteúdo de novo<br>Usuário gostar do conteúdo   |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 07

<div style="text-align: center">
<p>Tabela 8: Cenário 07</p>
</div>

| Abstração | Descrição                                                                                                                                                                                     |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Título    | Editar perfil                                                                                                                                                                                 |
| Objetivo  | Alterar uma informação no perfil                                                                                                                                                              |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado<br>Pré-condição: Ter um perfil                                                                                       |
| Atores    | Usuário ou criador de conteúdo                                                                                                                                                                |
| Recursos  | Celular<br>Internet                                                                                                                                                                           |
| Episódios | Usuário ou criador de conteúdo abre o TikTok<br>Usuário ou criador de conteúdo acessa seu perfil<br>Usuário ou criador de conteúdo verifica alguma informação errada                          |
| Restrição | Celular estar funcionando<br>Celular estar com bateria<br>Caso usuário: Possuir um perfil                                                                                                     |
| Exceção   | Preguiça de alterar a informação errada<br>Ocorrer um erro em algum campo de alteração do perfil<br>TikTok não permitir a edição por alguma parte do perfil violar as políticas do aplicativo |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 08

<div style="text-align: center">
<p>Tabela 9: Cenário 08</p>
</div>

| Abstração | Descrição                                                                                                                                                                 |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Título    | Acompanhar métricas                                                                                                                                                       |
| Objetivo  | Verificar em tempo real número de curtidas, visualizações e comentários nos vídeos                                                                                        |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado<br>Pré-condição: Ter um perfil<br>Pré-condição: Ter ao menos um vídeo postado                    |
| Atores    | Criador de conteúdo                                                                                                                                                       |
| Recursos  | Celular<br>Internet                                                                                                                                                       |
| Episódios | Criador de conteúdo abre o aplicativo<br>Criador de conteúdo entra em seu perfil<br>                                                                                      |
| Restrição | Celular estar funcionando<br>Celular estar com bateria<br>Criador de conteúdo ter ao menos um vídeo postado no perfil<br>Vídeos do perfil terem ao menos uma visualização |
| Exceção   | Vídeos listados como privados<br>TikTok excluir o vídeo por ferir a política do aplicativo                                                                                |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 09

<div style="text-align: center">
<p>Tabela 10: Cenário 09</p>
</div>

| Abstração | Descrição                                                                                  |
| --------- | ------------------------------------------------------------------------------------------ |
| Título    | Arrastar pra cima                                                                          |
| Objetivo  | Passar parao próximo vídeo com o movimento de deslizar o dedo para cima na tela do celular |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado                   |
| Atores    | Usuário                                                                                    |
| Recursos  | Celular<br>Internet                                                                        |
| Episódios | Usuário abre o aplicativo<br>Usuário termina de ver o vídeo                                |
| Restrição | Usuário querer passar o vídeo<br>Usuário continuar utilizando o aplicativo                 |
| Exceção   | Internet cair<br>Usuário fechar o aplicativo<br>Celular travar                             |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

### Cenário 10

<div style="text-align: center">
<p>Tabela 11: Cenário 10</p>
</div>

| Abstração | Descrição                |
| --------- | ------------------------ |
| Título    | Comentar em vídeos      |
| Objetivo  | Postar um comentário em um vídeo    |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado    |
| Atores    | Usuário<br>Criador de conteúdo     |
| Recursos  | Celular<br>Internet   |
| Episódios | Usuário abre o aplicativo<br>Usuário assiste um vídeo  |
| Restrição | Celular estar funcionando<br>Celular estar com bateria<br>Criador de conteúdo ter postado um vídeo |
| Exceção   | Usuário ter vergonha de comentar<br>Criador de conteúdo apagar o comentário do usuário   |

<div style="text-align: center">
<p>Fonte: Mateus Caltabiano</p>
</div>

## 6. Referências

>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Brasília: Unb-Gama, 2017. 35 slides, color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124471/mod_resource/content/1/Aula%2010.pdf. Acesso em: 18 jul. 2022.
>ARMS, William Y.. CS 5150 Software Engineering Scenarios and Use Cases. Ithaca: Cornell University Computing And Information Science, 2014. 27 slides, color. Disponível em: https://www.cs.cornell.edu/courses/cs5150/2014fa/slides/D2-use-cases.pdf. Acesso em: 18 jul. 2022