# Forward-from
## 1. Versionamento
<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>


| Versão | Autor             | Alterações                                     | Revisor           |
|:------:| ----------------- | ---------------------------------------------- | ----------------- |
|  1.0   | Iago Cabral       | Abertura do documento do artefato forward from | Mateus Caltabiano |
|  1.1   | Mateus Caltabiano | Alteração da introdução e metodologia          | Pedro Henrique Nogueira   |
|  1.2   | Iago Cabral       |    Alteração dos requisitos                    | Mateus Caltabiano |
|  1.3   | Pedro Henrique Nogueira       |   Adição da demonstração           | Mateus Caltabiano |
|  1.4   | Pedro Henrique Nogueira       |   Remoção da funcionalidade        | Iago Cabral |
|  1.5   | Mateus Caltabiano       |   Adição de requisitos não implementados        | Pedro Henrique Nogueira |
|  1.6   | Iago Cabral      |  Adição de Hyperlinks  | Pedro Henrique Nogueira |

## 2. Introdução

<p style="text-indent: 20px; text-align: justify">
    &emsp;"O rastreamento de requisitos é utilizado para prover relacionamentos entre requisitos, arquitetura e implementação final do sistema e possibilita uma adequada compreensão dos relacionamentos de dependência entre requisitos e através dos artefatos de requisitos, de arquitetura e de implementação." (SAYÃO; LEITE, 2005)<br>
    &emsp;Apresentaremos nesse documento a técnica de pós-rastreabilidade "Forward-from", que tem como objetivo "ligar requisitos a artefatos de desenho e implementação" (SAYÃO; LEITE, 2005)
</p>

## 3. Metodologia

<p style="text-indent: 20px; text-align: justify">
    &emsp;Faremos a rastreabilidade dos requisitos priorizados como "Must" na nossa tabela de priorização MoSCoW, fazendo uma demonstração da sua funcionalidade e elaborando uma tabela para cada requisito para explicitar seu épico, feature, por que meio foi elicitado e sua identificação<br>
    &emsp; Para os requisitos propostos pelo grupo, tivemos a ideia de elaborar protótipos de alta fidelidade para demonstrar seu funcionamento.
</p>

## 4. Pré-Rastreabilidade

### 4.1. Matriz de Rastreabilidade

**Legenda:**

> - RF: Requisito funcional
> - ST: Storytelling
> - BS: Brainstorm
> - ENT: Entrevista
> - INT: Instrospecção

<div style="text-align: center">
<p>Tabela 2: Matriz de Requisitos</p>
</div>

| ID   | Requisito |
| ---- | ------------------------------------------------------------------------------------------------------------------------ |
|<a href="#RF01">RF01(BS01)</a> | O aplicativo deve mostrar os vídeos na timeline.
| <a href="#RF02">RF02</a>| Eu, como usuário regular, desejo poder buscar conteúdos, para facilitar o acesso a conteúdos que eu me identifico
| <a href="#RF03">RF03</a>| Eu, como criador de conteúdo, desejo poder postar meus vídeos para meus seguidores 
| <a href="#RF05">RF05</a>| Eu, como usuário regular, quero favoritar um vídeo para ter acesso rápido em outro momento
| <a href="#RF09">RF09(ST09, ENT05)</a>| Eu, como usuário regular, quero curtir um vídeo para dar feedback ao criador de conteúdo e poder acessá-los com mais facilidade depois
| <a href="#RF15">RF15</a> | Eu, como usuário regular, desejo poder filtrar conteúdos para uma experiência mais imersiva
| <a href="#RF17">RF17</a>| Eu, como usuário regular, quero poder editar os dados do meu perfil para que fiquem o mais atualizado possível
| <a href="#RF20">RF20</a> |  Eu, como produtor de conteúdo, quero sinalizar a faixa etária do meu vídeo para facilitar o direcionamento para o público correto
| <a href="#RF24">RF24(ST05)</a>| Eu, como usuário regular, quero visualizar os dados dos vídeos(curtidas, visualizações, etc) para fazer analises que achar necessário
| <a href="#RF27">RF27(ST08)</a>| Eu, como usuário regular, desejo de passar de um vídeo para o outro com o movimento de "arrastar pra cima" para facilitar o uso da plataforma
| <a href="#RF28">RF28 (ST11, ENT06)</a> | Eu, como usuário regular, quero poder comentar em vídeos para dar minha opinião e interagir
| <a href="#RF35">RF35(ENT07)</a> | Eu, como usuário regular, desejo poder escolher que os vídeos passem automaticamente, para maior facilidade no uso
| <a href="#RF37">RF37(INT02)</a>|  Eu, como usuário regular, quero poder silenciar o vídeo para poder assistir sem fazer barulho






### 3.2. Especificações

<a id="RF01">**RF01**</a>

|         RF01(BS01)         | O aplicativo deve mostrar os vídeos na timeline. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Visualizar |
|       Feature       | Ver vídeo  |
| História de Usuário | [US01](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/1o18GREbXTj3Np_BVqqROkl6_kzt35ZCZ/view?usp=sharing) |

<a id="RF02">**RF02**</a>

|         RF02         | Eu, como usuário regular, desejo poder buscar conteúdos, para facilitar o acesso a conteúdos que eu me identifico |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Criação |
|       Feature       | Postar vídeos  |
| História de Usuário | [US26](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/1PQe9ua50cxKrItT1UyvK_ndAVulxtJ6w/view?usp=sharing) |

<a id="RF03">**RF03**</a>

|         RF03         |Eu, como criador de conteúdo, desejo poder postar meus vídeos para meus seguidores |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  filtro |
|       Feature       |Disponibilizar busca  |
| História de Usuário | [US21](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/12rohhH7F7ADW7sQyJv86SYhElhGVwXWI/view?usp=sharing) |

<a id="RF05">**RF05**</a>

|         RF05         | Eu, como usuário regular, quero favoritar um vídeo para ter acesso rápido em outro momento |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Favoritar vídeos  |
| História de Usuário | [US07](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/1Df0I1CyGdGHUWl4VNEBmtaX49xYJj130/view?usp=sharing) |

<a id="RF09">**RF09**</a>

|        RF09 (ST09, ENT05)      |Eu, como usuário regular, quero curtir um vídeo para dar feedback ao criador de conteúdo e poder acessá-los com mais facilidade depois|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Curtir vídeos  |
| História de Usuário | [US08](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) | |
|   Demonstração    |  [Video](https://drive.google.com/file/d/12mDx_NUUgyVoqNCgJJgpYSq9SWztyrUc/view?usp=sharing) |

<a id="RF15">**RF15**</a>

|        RF15      |Eu, como usuário regular, desejo poder filtrar conteúdos para uma experiência mais imersiva|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Filtro |
|       Feature       | Filtrar conteúdo  |
| História de Usuário | [US22](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/12n9lQi1OXBTqSuJGRromcW3IL1epfJAe/view?usp=sharing) |

<a id="RF17">**RF17**</a>

|        RF17      |Eu, como usuário regular, quero curtir um vídeo para dar feedback ao criador de conteúdo e poder acessá-los com mais facilidade depois|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Editar perfil |
| História de Usuário | [US09](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/1rQ3-fqbM8el77KOIes4AXuNhE9I49WF4/view?usp=sharing) |

<a id="RF24">**RF24**</a>

|        RF24(ST05)     |Eu, como usuário regular, quero visualizar os dados dos vídeos(curtidas, visualizações, etc) para fazer analises que achar necessário|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Visualizar métricas |
| História de Usuário | [US10](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Imagem](https://cdn.discordapp.com/attachments/744698026462937211/1019010713081086033/unknown.png) e [Imagem2](https://media.discordapp.net/attachments/744698026462937211/1019010732043550770/unknown.png?width=380&height=676) |

<a id="RF27">**RF27**</a>

|        RF27(ST08)     |	Eu, como usuário regular, desejo de passar de um vídeo para o outro com o movimento de "arrastar pra cima" para facilitar o uso da plataforma|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Arrastar para cima |
| História de Usuário | [US11](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/1E16884QYtB0zMXIIzd-valyGjk3zfC5j/view?usp=sharing) |

<a id="RF28">**RF28**</a>

|       	RF28 (ST11, ENT06)    |Eu, como usuário regular, quero poder comentar em vídeos para dar minha opinião e interagir	|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Comentar vídeos |
| História de Usuário | [US12](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Demonstração    |  [Video](https://drive.google.com/file/d/1l9LSZ2dbb4O3IVNq0LTB5W_-BaNu1usG/view?usp=sharing) |

### 3.3 Requisitos não implementados

<a id="RF20">**RF20**</a>

| RF20  | Eu, como produtor de conteúdo, quero sinalizar a faixa etária do meu vídeo para facilitar o direcionamento para o público correto.|
|:-------------------:|:-------------------------------------------------------------------------------------------:|
|        Épico        |                                          Interação                                          |
|       Feature       |                                       Sinalizar faixa etária                                      |
| História de Usuário |       [US13](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/)       |
|    Demonstração     | [Imagem](https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/imagem_2022-08-24_193339992.png?raw=true) |

<a id="RF35">**RF35**</a>

| RF35(ENT07)  | Eu, como usuário regular, desejo poder escolher que os vídeos passem automaticamente, para maior facilidade no uso|
|:-------------------:|:-------------------------------------------------------------------------------------------:|
|        Épico        |                                          Visualizar                                          |
|       Feature       |                                       Passar vídeos automaticamente                                      |
| História de Usuário |       [US06](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/)       |
|    Demonstração     |  [Imagem](https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/imagem_2022-08-24_193300103.png?raw=true)|

<a id="RF37">**RF37**</a>

| RF37(INT02)  | Eu, como usuário regular, quero poder silenciar o vídeo para poder assistir sem fazer barulho|
|:-------------------:|:-------------------------------------------------------------------------------------------:|
|        Épico        |                                          Interação                                          |
|       Feature       |                                       Silenciar vídeo                                      |
| História de Usuário |       [US17](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/)       |
|    Demonstração     | [Imagem](https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/imagem_2022-08-24_193421753.png?raw=true) |


## Referências bibliográficas

> 1 - MedSUS Introdução. Disponível em: https://requisitos-de-software.github.io/2021.2-MedSUS/post_traceability/forward_from/. Acesso em: 23 de agosto de 2022.
>
> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 23 de agosto 2022.
>
> POHL, Klaus; RUPP, Chris. Requirements Engeneering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam Foundation Level / IREB compliant. 1. ed. [S. l.]: O'Reilly Media, Inc., 2011. 183 p.
>
> SAYÃO, Miriam; LEITE, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. 2005. 26 f. Tese (Doutorado) - Curso de Ciência da Computação, Pontifícia Universidade Católica do Rio de Janeiro, Rio de Janeiro, 2005. Disponível em: https://aprender3.unb.br/pluginfile.php/2253364/mod_resource/content/3/05_20_sayao.pdf. Acesso em: 23 ago. 2022.
