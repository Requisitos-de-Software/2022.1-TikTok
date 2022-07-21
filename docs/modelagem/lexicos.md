# Léxicos

## Histórico de Versão

| Versão |    Data    |                   Descrição                   |    Autor     | Revisor |
| :----: | :--------: | :-------------------------------------------: | :----------: | :-----: |
|  1.0   | 20/07/2022 | Criação do documento com todas as informações | Iago Cabral | Pedro Henrique |
|  1.1   | 21/07/2022 | Adição de lexicos | Iago Cabral | Pedro Henrique |
|  1.1   | 21/07/2022 | Adição de lexicos faltantes | João Victor Correia |


## 1. Introdução

<p style="text-align: justify;"> O Léxico é uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo dos engenheiros de requisitos é buscar frases e símbolos do domínio da aplicação. Cada um desse símbolo é descrito com uma noção e um impacto, sendo a noção relacionada com o símbolo e o impacto com a descrição do efeito do símbolo na aplicação ou do efeito de algo na aplicação sobre o símbolo.
</p>

<p style="text-align: justify;"> Essas descrições seguem o princípio circular e o princípio do vocabulário mínimo. O princípio da circularidade torna cada extensão da descrição ou a conotação, referindo-se a outros símbolos da linguagem. A parte não simbólica da descrição deve vir de um subconjunto reduzido de palavras com significado claro (vocabulário mínimo).
</p>

## 2. Metodologia

<p style="text-align: justify;"> Os símbolos do Tik Tok foram identificados a partir do uso do aplicativo e dos requisitos elicitados na etapa anterior. Após identificados eles foram ordenados e descritos como: noção, impacto e sinônimos. Afim de facilitar a compreensão dos símbolos apresentados, dispomos os léxicos que foram divididos em ordem de manipulação do aplicativo, seguindo a tabela abaixo: </p>

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       |
| :--------------: | :--------: | :-------: | :-------------------: | :-------------------: |
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado |

## 3. Léxicos


### L01 - Amigos

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Amigos |Colega, conhecido,  | Seguir um usuário e ele te seguir de volta | Os vídeos postados aparecem em destaque para seus amigos, podendo ter uma seção privada e as menagens ficam em destaque |     Objeto     |

### L02 - Assitir

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Assistir    |   Observar, presenciar, ver      |   Ver um vídeo postado na plataforma por algum usuário     |    O número de visualizações do vídeo aumenta e quanto mais ele tiver, mais será recomendado para outros usuários      |        Verbo       |

### L03 - Caixa de entrada

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Caixa de entrada    |   Mensagens recebidas      |   Sistema de mensageria do aplicativo      |  É possível enviar, mensagens e vídeos entre usuários        |       Objeto        |

### L04 - Coleção

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Coleção    |   Acervo, agrupamento, galeria      |    Reunião de vídeos de acordo com a vontade do usuário     |     Vídeos podem ser adicionados a esse agrupamento para que os usuários possam assistí-los depois     |      Objeto         |

### L05 - Compartilhar

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Compartilhar    |   Partilhar, dividir      |    O usuário pode compartilhar as mídias contidas no aplicativo dentro e em aplicativos terceiros    |    Ao compartilhar dentro do aplicativo deve aparecer para os outros usuários na caixa de entrada.  Em outros aplicativos deve ser feita a integração para seguir o sistema deles     |        Verbo       |

### L06 - Curtir

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Curtir    |   Apreciar, desfrutar      |  O usuário pode curtir os vídeos como forma de feedback  | O número de curtidas do vídeo aumenta e quanto mais ele tiver, mais será recomendado para outros usuários   |       Verbo        |

### L07 - Dueto

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Dueto    |    Dupla, Duo     | Ao gravar um vídeo o usuário pode fazer um dueto com um outro vídeo já postado na plataforma dividindo a tela | Os dois vídeos compartilham as métricas de visualização e curtidas | Objeto |

### L08 - Entrar

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Entrar |Acessar, logar, conectar | A partir da senha gerada no cadastro e os dados pessoais, o usuário consegue acessar com sua conta o aplicativo para utilizar os recursos do aplicativo sincronizado com suas informações. | O usuário pode acessar o Tik Tok pelo navegador. </br> O usuário pode acessar o Tik Tok pelo aplicativo mobile em qualquer celular. |     Verbo     |

### L09 - For You(Para você)

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    For You(Para você)    |  Recomendados  |  Os vídeos mostrados para o usuário são de acordo com as suas preferências  | O sistema deve colher métricas para direcionar os vídeos que fazem mais sentido para cada usuário de acordo com os gostos individuais         |        Objeto       |

### L10 - Live

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Live    |    Livestream, transmissão ao vivo     |   O usuário pode começar uma transmissão para que outros possam participar e interagir      |    O sistema deve suportar esse tipo de gravação, notificar os seguidores e possibilitar as interações entre os usuários em tempo real      |       Estado        |

### L11 - Mensagem

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|    Mensagem    | Comunicado, SMS |    Forma de comunicação por texto dentro do próprio aplicativo     |    O usuário pode mandar mensagens para outros, tendo destaque caso seja amigo dele. Para usuários com perfil privado, esse sistema só é permitido caso sejam amigos      |         Objeto | 

### L12 - Música

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Música | escutar, pausar | A partir da timeline "Música" os usuarios conseguem escutar músicas| O usuario pode escutar mesmo fora do aplicativo, em segundo plano | Objeto |

### L13 - Perfil

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Perfil | visualizar, editar | O usuario pode visualizar, editar ou privar o seu perfil| O usuario pode escolher os dados a serem exposto no perfil, assim como privar os dados|  Objeto        |

### L14 - Pesquisar

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Pesquisar | procurar, explorar | A partir da ferramenta de pesquisa, o usuario consegue achar videos especificos |   O usuario pode pesquisar temas especificos e navegar pelos videos do tema | Verbo    |

### L15 - Postar

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Postar  | publicar, enviar | A partir da ferramenta de postar, o usuario consegue publicar videos|  O usuario pode publicar video em estado publico, onde qualquer pessoa pode ver ou privado onde apenas ele pode visualizar| Verbo |

### L16 - Produtor de conteúdo

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Produtor de conteúdo | influencer | Usuario que Cria video, faz lives | Usuario que cria conteudo para a plataforma, sendo videos ou lives, podendo ser remunerado por tal| Estado  |

### L17 - Reportar

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|Reportar| Denunciar| A partir da ferramenta o usuario pode denunciar/reportar videos| O usuario pode reportar videos com conteudos que ele acredita que não deveria estar no TikTok| Verbo  |

### L18 - Salvar

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Salvar | reservar| A partir da ferramenta o usuario pode salvar o video em um local especifico| O usuario pode salvar videos de maneira de facil visualização posterior | Verbo |

### L19 - Seguir/seguidor

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Seguir | acompanhar| A partir dessa ferramenta o usuario consegue ver os videos de uma pessoa de forma mais pratica  | Os videos de uma pessoa que voce segue possui prioridade na "for you" e possui uma timeline diferenciada, assim vendo mais videos dessa pessoa| Estado |

### L20 - Usuário regular

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
|  Usuário regular | utilizador| Classe padrão de utilizadores do tiktok| Os usuarios possuim uma experiência diferenciada o algoritmo cria uma "for you" com videos indicados de acordo com seu gosto | Estado    |

### L21 - Vídeo

| Léxico | Sinônimo|  Noção  |  Impacto | Classificação |
| :----: | :-----: | :------:| :------: | :-----------: |
| Video  | clipe   | Artefato principal do Tik Tok | Os videos são a parte principal do aplicativo, os usuario podem assitir, salva, comentar e compartilha-los   |   Objeto |





## 4. Conclusão 
Portanto, os léxicos encontrados foram buscados e reconhecidos através do uso do aplicativo, identificando o que poderia ser visto como uma figura de linguagem que passa a descrição de algo ou como um simples ícone. Com isso concluímos que alguns deles tem rastreablidade conexa com a atividade de cenários estipulando uma conexão entre os artefatos e permitindo ainda mais a rastreabilidade entre eles.

## Bibliografia
> CONSTRUÇÃO do léxico de aplicações. Proceedings of the International Joint Conference IBERAMIA/SBIA/SBRN 2006 : 4th Workshop in Information and Human Language Technology, Ribeirão Preto, Brazil, 23 out. 2006. CD-ROM.

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/1668162/mod_resource/content/1/Aula%2010.pdf). Acesso em: 04 de março de 2022.

> ConecteSUS. Disponível em : https://github.com/Requisitos-de-Software/2021.2-ConecteSUS/blob/main/docs/Modelagem/lexicos.md . Acesso em: 20/07/2022.




