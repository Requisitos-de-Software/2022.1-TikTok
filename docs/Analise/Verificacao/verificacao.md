# Verificação

## 1. Versionamento

| Versão | Autor             | Descrição                               | Revisor           |
| ------ | ----------------- | --------------------------------------- | ----------------- |
| 1.0    | Mateus Caltabiano | Abertura do documento                   | João Victor       |
| 1.1    | Pedro Henrique    | Adição da tabela base                   | Mateus Caltabiano |
| 1.2    | Mateus Caltabiano | Adição de itens base para os checklists | Iago Cabral       |

## 2. Introdução

<p style="text-indent: 20px; text-align: justify">
A verificação é uma parte do processo de desenvolvimento de software que não necessita do cliente presente. Ela consiste basicamente em verificar se "tem algo de errado com nosso modelo em termos de notação, processo, procedimentos. Se está de acordo com o que se espera dele." (SERRANO; SERRANO, 2017).
</p>

## 3. Metodologia

<p style="text-indent: 20px; text-align: justify">
Será utilizada a verificação por meio de inspeção, que, segundo Fagan, consiste em seis passos principais. São eles: Planejamento, Visão Geral, Preparação, Inspeção, Correção e Acompanhamento.
</p>

### 3.1 Planejamento

<p style="text-indent: 20px; text-align: justify">
Conforme reunião em sala de aula, serão elaboradas "checklists" para cada artefato individualmente, com o intuito de verificar ponto a ponto em busca de erros.
</p>

### 3.2 Visão Geral

<p style="text-indent: 20px; text-align: justify">
    A visão geral pode ser omitida do processo já que todos os integrantes tem o conhecimento necessário para avaliar os artefatos individualmente, por serem conteúdos ministrados em sala de aula.
</p>

### 3.3 Preparação

<p style="text-indent: 20px; text-align: justify">
    Foram designados para os membros do grupo os artefatos que serão inspecionados por cada um conforme a tabela abaixo. Os Inspetores são responsáveis por elaborarem seus checklists e realizarem a inspeção antes de passar para o revisor.
</p>
   
<table>
    <tr>
        <th>Inspetor</th>
        <th>Artefato</th>
        <th>Revisor</th>
    </tr>
    <tr>
        <td rowspan = "3">Iago Cabral</td>
        <td>Entrevista</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Especificação suplementar</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Storytelling</td>
        <td>X</td>
    </tr>
    <tr>
        <td rowspan = "3">Mateus Caltabiano</td>
        <td>Casos de uso</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Introspecção</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Persona</td>
        <td>X</td>
    </tr>
    <tr>
        <td rowspan = "3">Matheus Perillo</td>
        <td>Brainstorm</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Cenários</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Priorização</td>
        <td>X</td>
    </tr>
    <tr>
        <td rowspan = "2">Matheus Soares</td>
        <td>Histórias de usuário</td>
        <td>Matheus Perillo</td>
    </tr>
    <tr>
        <td>NFR framework</td>
        <td>Mateus Caltabiano</td>
    </tr>
    <tr>
        <td rowspan = "3">Pedro Henrique</td>
        <td>Backlog</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Léxicos</td>
        <td>X</td>
    </tr>
    <tr>
        <td>Rich picture</td>
        <td>Iago Cabral</td>
    </tr>
</table>

<div style="text-align: center">
    <p>
        Tabela 1: Artefatos designados para os membros
    </p>
</div>

### 3.4 Inspeção

<p style="text-indent: 20px; text-align: justify">
    Consiste em analisar o artefato com base no checklist elaborado e preenchê-lo conforme erros ou acertos
</p>

#### 3.4.1 Tabela base

<p style="text-indent: 20px; text-align: justify">
    Esta tabela será utilizada como base para todos os checklists. Utilizamos como inspiração o trabalho desenvolvido pelo grupo do MedSUS. (https://github.com/Requisitos-de-Software/2021.2-MedSUS/tree/main/docs/verification)
</p>

| Código | Item                           | Total          | Sim                  | Não                    | Ocorrência <br> de Erros | Tipos de erro           | Pontos a serem ajustados |
| ------ | ------------------------------ | -------------- | -------------------- | ---------------------- | ------------------------ | ----------------------- | ------------------------ |
| 1      | Descrição dos itens analisados | Total de itens | N° de itens corretos | N° de itens incorretos | Porcentagem de erros     | Tipo do erro em questão | Descrição do erro        |

<div style="text-align: center">
    <p>
        Tabela 2: Tabela base
    </p>
</div>

#### 3.4.2 Itens padrão

Todos os checklists devem conter os itens presentes na tabela a seguir.

<div>
    <p style="text-align: center">
        Tabela 3: Tabela com os itens padrão
    </p>
</div>

|       Código        | Item                                                                   |
|:-------------------:| ---------------------------------------------------------------------- |
|          1          | Possui versionamento com versão, descrição, autor e revisor?           |
|          2          | Possui introdução?                                                     |
|          3          | Possui explicação da metodologia?                                      |
|          4          | Possui referências bibliográficas?                                     |
|          5          | As referências estão citadas no artefato?                              |
|          6          | Possui legenda nas tabelas e figuras?                                  |
|          7          | Possui fonte nas tabelas e figuras?                                    |
|          8          | Há registro do processo?                                               |
| 9 (caso elicitação) | Possui tabela com os requisitos elicitados com ID, descrição e título? |

<div>
    <p style="text-align: center">
        fonte: Mateus Caltabiano
    </p>
</div>

### 3.5 Correção

<p style="text-indent: 20px; text-align: justify">
    Consiste em fazer a correção dos erros encontrados em uma nova versão do documento original, para manter um relatório de progresso.
</p>

### 3.6 Acompanhamento

<p style="text-indent: 20px; text-align: justify">
    O acompanhamento tem como objetivo verificar, ao longo do tempo, se novos erros não aconteceram ao corrigir os detectados pelos checklist.
</p>

## 4. Referências

>SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 23. Brasília: Unb-Gama, 2017. 52 slides, color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124537/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf. Acesso em: 17 ago. 2022.
>
>SOARES, Adrian; DURSO, João Vitor de Souza; OLIVEIRA, Gabriel Costa de; LUIZ, Gabriel; VARGAS, Fernando; ALVES, Thalisson. MedSUS - Requisitos de Software. 2022. Disponível em: https://requisitos-de-software.github.io/2021.2-MedSUS/. Acesso em: 17 ago. 2022.