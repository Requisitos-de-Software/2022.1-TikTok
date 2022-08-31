# First Things First
## 1. Versionamento
<div style="text-align: center">
<p>Tabela 1: Versionamento</p>
</div>


| Versão | Autor                                     | Alterações                          | Revisor     |
|:------:| ----------------------------------------- | ----------------------------------- | ----------- |
|  1.0  | Matheus Soares | Elaboração do documento de priorização First Things First | Mateus Caltabiano |


<div style="text-align: center">
<p>Fonte: Matheus Soares</p>
</div>

## Introdução
<p style="text-indent: 20px; text-align: justify">
O First Things First é uma técnica de priorização de requisitos que visa equilibrar, definir, alinhar e estabelecer as tarefas que devem ser feitas dividindo em mais importantes e menos importantes a serem executadas.
</p>

## Metodologia
<p style="text-indent: 20px; text-align: justify">
Para elaborar uma tabela FtF(First Things First) é necessário fazer a retirada de todos os requisitos que são logicamente ligados(ou seja, implementa B apenas se A for implementada) a lista então é formada apenas com os requisitos "A". Em seguida, com valores entre 1 e 9, o benefício que cada recurso oferece ao cliente/negócio é estimado. Depois é estimada a penalidade caso o requisito não for implementado. Desta maneira é sintetizada a coluna valor total, dada pela soma do benefício pela penalidade multiplicada pelos seus respectivos pesos. O custo de implementação com base na complexidade é estimado. Por fim é estimado o grau de risco com base na viabilidade. O calculo da prioridade(p) é dado por:

</p>

<table style="border:1px solid black;margin-left:auto;margin-right:auto;border-spacing:20px;">
    <tr>
        <td><b>valor(%) / (custo(%) * peso do custo relativo + risco(%) * peso do risco relativo)</b></td>
    </tr>
</table>

Este documento foi baseado nas elicitações personas, storytellings, instrospecção, brainstorm e também na técnica já produzida pela equipe: MoSCoW.

## First Things First

  <figcaption>Tabela 1: First Things First </figcaption>
  
<html> 
    <div class="center-card">
        <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS3AZWkXFIrqj21SCa266umur5gXhoxpjr1n_zpK462X4P3esrQP9CRCyEogOP1l1uHQNCha7_v8EDl/pubhtml?gid=0&single=true" width="800" height="500" frameborder="0"></iframe>                 
        <figcaption>Fonte: Matheus Soares</figcaption>
    </div>
</html>




## Referências bibliográficas
> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/2124453/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 31 ago. 2022.