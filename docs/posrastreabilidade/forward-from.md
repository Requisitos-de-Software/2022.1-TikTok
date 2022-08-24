# Backward From
## 1. Versionamento
<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>


| Versão | Autor                                     | Alterações                          | Revisor     |
|:------:| ----------------------------------------- | ----------------------------------- | ----------- |
|  1.0   | Iago Cabral | Elaboração do documento do artefato forward from |  |

## 2. Introdução

<p style="text-indent: 20px; text-align: justify">
Existem dois tipos de rastreabilidade Forward: Forward-to e Forward-from. Ambos são usados para verificar se o projeto avança na direção desejada e para o produto certo. Ademais, garantem que cada requisito seja aplicado ao produto e que cada requisito seja testado minuciosamente. Este documento trata da rastreabilidade Forward From, a qual rastreia relacionamentos entre requerimentos e artefatos correspondentes, incluindo casos de teste. Esse tipo de rastreamento garante que cada requerimento, além de satisfeito, foi verificado e validado.¹
</p>

## 3. Metodologia

<p style="text-indent: 20px; text-align: justify">
A partir dos artefatos construídos até agora, foi possível elaborar uma Matriz de Rastreabilidade para conectar os Requisitos, Épicos, Features, História de Usuário e Funcionalidade.
</p>

## 4. Pré-Rastreabilidade

### 4.1. Matriz de Rastreabilidade

**Legenda:**

- RF: Requisito funcional
- ST: Storytelling
- BS: Brainstorm

<div style="text-align: center">
<p>Tabela 2: Matriz de Requisitos</p>
</div>

| ID   | Requisito |
| ---- | ------------------------------------------------------------------------------------------------------------------------ |
| RF01(BS01)  | O aplicativo deve mostrar os vídeos na timeline.
| RF02| Eu, como usuário regular, desejo poder buscar conteúdos, para facilitar o acesso a conteúdos que eu me identifico
| RF04| Eu, como usuário regular, desejo ter um perfil para interagir com outros na plataforma  
| RF05| Eu, como usuário regular, quero favoritar um vídeo para ter acesso rápido em outro momento
| RF06(ST06)| Eu, como usuário regular, quero ser capaz de trocar mensagens com meus contatos para manter uma relação social
| RF08| Eu,como usuário regular, desejo acessar os outros perfis existentes para ver o conteúdo deles
| RF09(ST09, ENT05)| Eu, como usuário regular, quero curtir um vídeo para dar feedback ao criador de conteúdo e poder acessá-los com mais facilidade depois
| RF17| Eu, como usuário regular, quero poder editar os dados do meu perfil para que fiquem o mais atualizado possível
| RF24(ST05)| Eu, como usuário regular, quero visualizar os dados dos vídeos(curtidas, visualizações, etc) para fazer analises que achar necessário
| RF27(ST08)| Eu, como usuário regular, desejo de passar de um vídeo para o outro com o movimento de "arrastar pra cima" para facilitar o uso da plataforma
| RF28(ST11, ENT06)| Eu, como usuário regular, quero poder comentar em vídeos para dar minha opinião e interagir
| RF29(ST12)|Eu,como usuário regular, quero poder ter acesso aos vídeos que eu curti dentro do meu perfil para que possa encontra-lós de forma rápida
| RF30(ST13)| Eu, como usuário regular, quero poder curtir um vídeo clicando duas vezes para facilitar a interação com o aplicativo
| RF31(ST14)|Eu, como usuário regular, quero poder pausar o vídeo para poder desviar minha atenção e voltar de onde estava depois
| RF39| Eu, como usuário regular, desejo poder escutar músicas pelo aplicativo para que eu não precise de aplicativos terceiros






### 3.2. Especificações
**RF01**

|         RF01(BS01)         | O aplicativo deve mostrar os vídeos na timeline. |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Visualizar |
|       Feature       | Ver vídeo  |
| História de Usuário | [US01](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF01]() |

**RF02**

|         RF02         | Eu, como usuário regular, desejo poder buscar conteúdos, para facilitar o acesso a conteúdos que eu me identifico |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  filtro |
|       Feature       |Disponibilizar busca  |
| História de Usuário | [US21](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF04**

|         RF04         | Eu, como usuário regular, desejo ter um perfil para interagir com outros na plataforma |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Visualizar |
|       Feature       | Ver perfil  |
| História de Usuário | [US02](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF05**

|         RF05         | Eu, como usuário regular, quero favoritar um vídeo para ter acesso rápido em outro momento |
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Favoritar vídeos  |
| História de Usuário | [US07](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF06**

|         RF06(ST06)       |Eu, como usuário regular, quero ser capaz de trocar mensagens com meus contatos para manter uma relação social|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Social |
|       Feature       | Conversar por mensagem  |
| História de Usuário | [US38](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF08**

|         RF08      |Eu,como usuário regular, desejo acessar os outros perfis existentes para ver o conteúdo deles|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Visualizar |
|       Feature       | Ver perfil  |
| História de Usuário | [US03](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF09**

|        RF09 (ST09, ENT05)      |Eu, como usuário regular, quero curtir um vídeo para dar feedback ao criador de conteúdo e poder acessá-los com mais facilidade depois|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Curtir vídeos  |
| História de Usuário | [US08](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF17**

|        RF17      |Eu, como usuário regular, quero curtir um vídeo para dar feedback ao criador de conteúdo e poder acessá-los com mais facilidade depois|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Editar perfil |
| História de Usuário | [US09](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF24**

|        RF24(ST05)     |Eu, como usuário regular, quero visualizar os dados dos vídeos(curtidas, visualizações, etc) para fazer analises que achar necessário|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Visualizar métricas |
| História de Usuário | [US10](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF27**

|        RF27(ST08)     |	Eu, como usuário regular, desejo de passar de um vídeo para o outro com o movimento de "arrastar pra cima" para facilitar o uso da plataforma|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Arrastar para cima |
| História de Usuário | [US11](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF28**

|       	RF28 (ST11, ENT06)    |Eu, como usuário regular, quero poder comentar em vídeos para dar minha opinião e interagir	|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Comentar vídeos |
| História de Usuário | [US12](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF29**

|       	RF29 (ST12)    |Eu,como usuário regular, quero poder ter acesso aos vídeos que eu curti dentro do meu perfil para que possa encontra-lós de forma rápida	|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Visualizar |
|       Feature       | Visualizar vídeos curtidos no perfil |
| História de Usuário | [US05](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF30**

|       	RF30 (ST13)    |Eu, como usuário regular, quero poder curtir um vídeo clicando duas vezes para facilitar a interação com o aplicativo|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Duplo-clique para curtir vídeo |
| História de Usuário | [US16](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]() |

**RF31**

|       	RF31 (ST14)    |	Eu, como usuário regular, quero poder pausar o vídeo para poder desviar minha atenção e voltar de onde estava depois|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Pausar vídeos |
| História de Usuário | [US18](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]()|

**RF39**

|       	RF39   |	Eu, como usuário regular, desejo poder escutar músicas pelo aplicativo para que eu não precise de aplicativos terceiros|
| :-----------------: | :--------------------------------------------------------------------------------: |
|        Épico        |  Interação |
|       Feature       | Escutar música |
| História de Usuário | [US14](https://requisitos-de-software.github.io/2022.1-TikTok/product-backlog/) |
|   Funcionalidade    |  ![RF02]()|





## Referências bibliográficas

> 1 - MedSUS Introdução. Disponível em: https://requisitos-de-software.github.io/2021.2-MedSUS/post_traceability/forward_from/. Acesso em: 23 de agosto de 2022.

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 23 de agosto 2022.

> POHL, Klaus; RUPP, Chris. Requirements Engeneering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam Foundation Level / IREB compliant. 1. ed. [S. l.]: O'Reilly Media, Inc., 2011. 183 p.