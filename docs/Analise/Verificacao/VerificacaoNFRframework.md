# Inspeção (NFR Framework)
## 1. Versionamento
<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>


| Versão | Autor                                     | Alterações                          | Revisor     |
|:------:| ----------------------------------------- | ----------------------------------- | ----------- |
|  1.0   | Matheus Soares | Criação da inspeção  | Mateus Caltabiano |

<div style="text-align: center">
<p>Fonte: Matheus Soares</p>
</div>

## 2. Introdução
<p style="text-indent: 20px; text-align: justify">
O NFR Framework é uma maneira de representar de forma sistemática e global os Requisitos Não-Funcionais, com uma abordagem qualitativa e orienta a processo. Seu objetivo é ajudar os desenvolvedores a implementar soluções customizadas, levando em consideração as características dos campos e sistemas relacionados. Essas características incluem requisitos não funcionais, requisitos funcionais, prioridades e cargas de trabalho. Essas condições determinam a escolha de alternativas de desenvolvimento para um determinado sistema. A inspeção do NFR Framework possibilita verificar os requisitos não funcionais, suas softgoals, objetivos e as relações entre eles.
</p>


## 3. Metodologia
<p style="text-indent: 20px; text-align: justify">
O foco da inspeção é que um membro que não fez parte do desenvolvimento do artefato adote a postura de "inspetor" do mesmo, sendo assim foi escolhido o membro Matheus Soares para inspeção e o Mateus Caltabiano para Revisão.
</p>

### 3.1 Corpo da tabela de inspeção
<div style="text-align: center">
<p>Tabela 2: Corpo da Tabela</p>
</div>

|Codigo|Item|Total|Sim|Não|Ocorrência de Erros|Tipos de erro|Pontos a serem ajustados|
|:------:|----|-----|---|---|------------------------|-------------|---|
| 1 |  |   |     |     |                          |               |     |
| 2 |  |   |     |     |                          |               |     |
| 3 |  |   |     |     |                          |               |     |
| 4 |  |   |     |     |                          |               |     |
<div style="text-align: center">
<p>Fonte: Grupo 7</p>
</div>

## 4. Inspeção (NFR Framework)
### 4.1 Detecção de Defeitos
Para detecção de defeitos elaborou-se um checklist com a própria ferramenta Mkdown.
<div style="text-align: center">
<p>Tabela 3: Tabela de defeitos</p>
</div>

|Codigo|Item|Total|Sim|Não|Ocorrência de Erros|Tipos de erro|Pontos a serem ajustados|
|:------:|:----:|:-----:|:---:|:---:|:------------------------:|:-------------:|:---:|
| 1 | Os softgoals estão bem definidos |34|34|0|0.00%|         |     |
| 2 | Os softgoals são decompostos em operacionalizações |34|34|0|0.00%|     |     |
| 3 | Os objetivos estão decompostos em uma hierarquia AND/OR de softgoals |34|34|0|0.00%| |     |
| 4 | 	Os graus de satisfação foram definidos corretamente |34|33 | 1 |0.34%| Defeito de desconformidade |  5.2.1 NFR de Desempenho com propagação possui defeito de desconformidade no grau de satisfação   |
| 5 | 	As setas possuem sentido coerente |  34 |  34   |   0  |  0.00%                        |               |     |
| 6 | 	As linhas contínuas e tracejadas foram utilizadas corretamente | 34  |   34  |   0  |        0.00%                  |               |     |
| 7 | 	Existem claims | 34 |  0  | 34 |      100%                    |      Defeito de omição         | É relevante adicionar as claims para apoiar ou negar as justificativas  |
| 8 | 	Impactos contribuem apenas entre softgoals | 34  | 34    |   0  |      0.00%                    |               |     |
| 9 | 	Existem legendas para cada símbolo utilizado |  15 | 15    |  0   |       0.00%                   |               |     |

<div style="text-align: center">
<p>Fonte: Matheus Soares</p>
</div>

<br>
<br>
<br>
<br>


<div style="text-align: center">
<p>Imagem 1: Gráfico de Erros</p>
</div>
<center>
<img width="800px" src="https://github.com/Requisitos-de-Software/2022.1-TikTok/blob/main/docs/img/NFRframeInspecao.png?raw=true">
</center>
<div style="text-align: center">
<p>Fonte: Matheus Soares</p>
</div>

### 4.2 Correção de defeitos
<p style="text-indent: 20px; text-align: justify">
O objetivo da desta fase é que o autores relacionados ao NFR Framework estejam cientes do que será corrigido, garantindo que as falhas identificadas sejam eliminadas.
</p>

### 4.4 Acompanhamento
<p style="text-indent: 20px; text-align: justify">
A fim de garantir que as modificações necessárias no NFR Framework foram feitas em conformidade, o autor e o inspetor são responsáveis por isso. O objetivo do processo de acompanhamento é garantir que o(s) autor(es) do NFR Framework tenha(m) retificado todos os requisitos declarados incompletos e/ou inconsistentes ou os defeitos detectados.

- [ ] - NFR Framework Corrigido
</p>

##  Referências
> - SILVA, Reinaldo Antônio da. NFR4ES:Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Recife, 201
> - NFR - MedSUS. Disponível em: <https://requisitos-de-software.github.io/2021.2-MedSUS/verification/inspection_nfr/>. Acesso em: 17 ago. 2022.
