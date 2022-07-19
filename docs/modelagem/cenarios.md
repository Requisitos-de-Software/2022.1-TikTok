# Cenários

## 1. Versionamento



| Versão | Autor             | Alterações                        |
| ------ | ----------------- | --------------------------------- |
| 1.0    | Mateus Caltabiano | Abertura do documento de cenários |
| 1.1    | Mateus Caltabiano | Adição do cenário 01              |
| 1.2    | Mateus Caltabiano | Adição do cenário 02              |
| 1.3    | Mateus Caltabiano | Adição do cenário 03              |


## 2. Introdução

&emsp;&emsp;Cenários são basicamente cenas que ilustram um propósito, uma funcionalidade do sistema. É uma ferramenta importante para exemplificar o sistema como se fosse visto de fora, por exemplo por um usuário, utilizando exemplos específicos. É uma estratégia reconhecida para que se torne mais fácil a compreensão das interações entre ambientes e sistemas.

## 3. Metodologia

&emsp;&emsp;Foi definido um template para ser utilizado na definição de cada cenário com o intuito de deixar o documento padronizado. Apresentaremos os cenários dos requisitos funcionais definidos como "Must" em nossa priorização.

## 4. Template

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

<p>
    Tabela 2: Template para os cenários
</p>

## 5. Cenários

### Cenário 01

| Abstração | Descrição                                                                              |
| --------- | -------------------------------------------------------------------------------------- |
| Título    | Assistir vídeos na timeline                                                            |
| Objetivo  | Utilizar o TikTok para assistir vídeos na timeline                                     |
| Contexto  | Pré-condição - Ter um celular<br>Pré-condição - Ter o aplicativo instalado             |
| Atores    | Usuário                                                                                |
| Recursos  | Celular                                                                                |
| Episódios | Usuário está entediado<br>Usuário pega o celular<br>Usuário abre o TikTok              |
| Restrição | Celular estar com bateria<br>Usuário quer assistir TikTok<br>Celular estar funcionando |
| Exceção   | Celular sem bateria<br>Celular cai no chão<br>Celular sem conexão com a internet       |

<p>
    Tabela 3: Cenário 01
</p>

### Cenário 02

| Abstração | Descrição                                                                                        |
| --------- | ------------------------------------------------------------------------------------------------ |
| Título    | Buscar vídeos                                                                                    |
| Objetivo  | Procurar por vídeos utilizando texto                                                             |
| Contexto  | Pré-condição: Ter um celular com app instalado<br>Pré-condição: Saber o que quer encontrar       |
| Atores    | Usuário                                                                                          |
| Recursos  | Celular                                                                                          |
| Episódios | Usuário quer encontrar um vídeo<br>Usuário abre a ferramenta de busca<br>Usuário digita um texto |
| Restrição | Usuário saber o que pesquisar<br>Algoritmo de busca encontrar vídeos relacionados<br>            |
| Exceção   | Celular sem conexão com a internet<br>                                                           |

<p>
    Tabela 4: Cenário 02
</p>

### Cenário 03

| Abstração | Descrição                                                                                                      |
| --------- | -------------------------------------------------------------------------------------------------------------- |
| Título    | Postar vídeos                                                                                                  |
| Objetivo  | Postar um vídeo no perfil                                                                                      |
| Contexto  | Pré-condição: Ter um celular<br>Pré-condição: Ter o aplicativo instalado<br>Pré-condição: Ter um vídeo gravado |
| Atores    | Criador de conteúdo                                                                                            |
| Recursos  | Celular<br>Internet                                                                                            |
| Episódios | Criador de conteúdo ter uma ideia<br>Criador de conteúdo gravar um vídeo<br>Criador de conteúdo postar o vídeo |
| Restrição | Criador de conteúdo gostar do vídeo<br>                                                                        |
| Exceção   | TikTok bloquear o vídeo<br>Vídeo ser mais longo do que o suportado                                             |

<p>
    Tabela 5: Cenário 03
</p>

## 6. Referências

>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Brasília: Unb-Gama, 2017. 35 slides, color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124471/mod_resource/content/1/Aula%2010.pdf. Acesso em: 18 jul. 2022.
>ARMS, William Y.. CS 5150 Software Engineering Scenarios and Use Cases. Ithaca: Cornell University Computing And Information Science, 2014. 27 slides, color. Disponível em: https://www.cs.cornell.edu/courses/cs5150/2014fa/slides/D2-use-cases.pdf. Acesso em: 18 jul. 2022