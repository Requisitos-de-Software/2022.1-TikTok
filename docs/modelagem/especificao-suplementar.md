# Especificação suplementar

##  1. Versionamento

| Versão |    Data    |       Modificação        |        Autor         | Revisor |
| :----: | :--------: | :----------------------: | :------------------: | :--------: |
|  1.0  | 19/07/2022 | Abertura do documento | Matheus Perillo | Matheus Soares |
|  1.1  | 19/07/2022 | Adicionar introdução | Matheus Perillo | Matheus Soares |
|  1.2  | 19/07/2022 | Explicação da metodologia | Matheus Perillo | Matheus Soares |
|  1.3  | 20/07/2022 | Adição da especificação suplementar| Matheus Perillo | Matheus Soares |

## 2. Introdução

<p style=" text-align: justify">
&emsp; O objetivo deste documento é explicitar os requisitos não funcionais do aplicativo TikTok, pegando todos aqueles requisitos que não foram facilmente capturados pelo Caso de uso. Dessa forma, em conjunto com a modelagem de Casos de uso definir todos os requisitos da aplicação.
</p>

## 3. Metodologia

<p style=" text-align: justify">
&emsp; Este documento utilizou o sistema FURPS+ para definir os requisitos. Esse sistema tem como objetivo classificar os requisitos de acordo com os atributos de qualidade de software. O acrônimo representa as possíveis categorias para os requisitos, são elas:

</p>

<div style="text-align: justify">

<ul>
<li>
 <b>Funcionalidade:</b> Capacidade (generalidade do conjunto de recursos), reutilização (compatibilidade, interoperabilidade, portabilidade), segurança e explorabilidade;
</li>

<li>
 <b>Usabilidade:</b> Resposividade, documentação, consistência, estética, fatores humanos em geral;
</li>

<li>
 <b>Confiabilidade:</b> Disponibilidade (Frequência de Falhas    (Robustez/Durabilidade/Responsividade)), Extensão e Duração da Falha (Recuperabilidade/Sobrevivência), Previsibilidade/Estabilidade;
</li>

<li>
 <b>Desempenho:</b> Velocidade, Eficiência, Consumo de Recurso, Rendimento, Capacidade, Escalabilidade;
</li>

<li>
<b> Suportabilidade:</b> Manutenabilidade, Testabilidade, Flexibilidade, Instabilidade, Localizabilidade;
</li>

<li>
<b> Design:</b> Restringe o design do sistema com padrões de design, uso de ferramentas de desenvolvimento, etc;
</li>

<li>
<b> Implementação:</b> Restringe o código ou a construção do sistema como, limites de recurso, sistemas operativos, etc;
</li>

<li>
<b> Interface:</b> Restringe as funcionalidades referentes às interfaces dos diferentes componentes;
</li>

<li>
<b> Físico:</b> Restringe o hardware no qual o sistema será suportado;
</li>

</ul>
</div>

## 4. Especificação suplementar

### 4.1 Funcionalidades

<div style="text-align: justify">

<ul><li> Os requisitos funcionais estão definidos por meio dos Casos de uso.</li></ul>

</div>

<div style="text-align: center">
<p>Tabela 1: Requisitos de usabilidade</p>
</div>

### 4.2 Usabilidade

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES01`  | O usuário deve conseguir de favoritar os vídeos. |
|  `ES02`  | O aplicativo deve disponibilizar busca. |
|  `ES03`  | O usuário deve ser capaz de postar seus vídeos. |
|  `ES04`  | O usuário deve conseguir de curtir os vídeos. |
|  `ES05`  | O aplicativo deve demonstrar boa usabilidade. |
|  `ES06`  | O usuário deve ser capaz de editar o seu perfil |
|  `ES07`  | O usuário deve ser capaz de comentar nos vídeos |
|  `ES08`  | O usuário deve ser capaz de compartilhar vídeos. |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

### 4.3 Confiabilidade

<div style="text-align: center">
<p>Tabela 2: Requisitos de confiabilidade</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES09`  | O aplicativo deve ser capaz de se recuperar de falhas. |
|  `ES10`  | O usuário deve ser capaz de sacar o dinheiro das visualizações. | 
|  `ES11`  | O usuário deve ser capaz de privar o seu perfil. |
|  `ES12`  | O usuário deve ser capaz de filtrar o conteúdo que lhe é apresentado. |
|  `ES13`  | O usuário deve ser capaz de sinalizar o faixa etária de seu conteúdo. |
|  `ES14`  | O usuário deve ser capaz de sacar o dinheiro das visualizações. |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

### 4.4 Desempenho

<div style="text-align: center">
<p>Tabela 3: Requisitos de desempenho</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES15`  | O aplicativo deve suportar multiplataformas. |
|  `ES16`  | O app deve ser otimizado para a experiência mobile. |
|  `ES17`  | O aplicativo deve ter boa performace nos aparelhos com SO (ANDROID/IOS). |
|  `ES18`  | O app deve ser otimizado para a experiência mobile. |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

### 4.5 Suportabilidade

<div style="text-align: center">
<p>Tabela 4: Requisitos de suportabilidade</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES19`  | O aplicativo deve ser disponibilizado em todas as lojas oficiais de dispositivos |
|  `ES20`  | O aplicativo deve operar em sistemas mobile mais tradicionais(Android/IOS). |
|  `ES21`  | O aplicativo deve suportar mais 1 bilhão de usuários simultâneos.

<div style="text-align: center">
<p>Fonte: Mateus Perillo</p>
</div>

### 4.6 Design

<div style="text-align: center">
<p>Tabela 5: Requisitos de design</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES22`  | O aplicativo deve seguir a paleta de cores definida |
|  `ES23`  | O aplicativo deve utilizar ícones que representem bem sua funcionalidade |
|  `ES24`  | O app deve ter um design bonito e familiar |
|  `ES25`  | Os vídeos devem possuir boa qualidade. |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

### 4.7 Implementação

<div style="text-align: center">
<p>Tabela 6: Requisitos de impementação</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES26`  | O aplicativo deve ser compatível com os sistemas Android e IOS |
|  `ES27`  | Deve ser possível limpar o cache do aplicativo |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

### 4.8 Interface

<div style="text-align: center">
<p>Tabela 7: Requisitos de interface</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES28`  | A interface dos diferentes componentes devem seguir o mesmo padrão para não confundir o usuário |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

### 4.9 Físico

<div style="text-align: center">
<p>Tabela 1: Requisitos de físico</p>
</div>

| Identificador | Descrição   |
| :----: | :--------: |
|  `ES29`  | O dispositivo Android deve estar em uma versão 5.0 ou posterior |
|  `ES30`  | O dispositivo IOS deve estar em uma versão 10.0 ou posterior |
|  `ES31`  | O dispositivo computador deve ser Windows 10 em uma versão 19041.0 ou posterior |

<div style="text-align: center">
<p>Fonte: Matheus Perillo</p>
</div>

## 5. Referências

> GAMBLE, S. Example: Supplementary Specification. [S. l.]: Pace University, 21 dez. 1998. Disponível em: <https://csis.pace.edu/~marchese/SE616_New/Samples/Example%20%20Supplementary%20Specification.htm>. Acesso em: 19 jul. 2022.'
>
> Samily Rocha Gois: Especificação Suplementar, 27 out. 2012. Disponível em: <https://aprender3.unb.br/pluginfile.php/2124482/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf>. Acesso em: 19 jul. 2022.'
