Objetivo

O objetivo deste trabalho é analisar os determinantes do alto crescimento do PIB
per capita do município de Ouro Branco, Minas Gerais, entre o período de 2000 a
2021, utilizando modelos de regressão linear múltipla. Em particular, buscamos
entender a influência do natural crescimento do PIB per capita brasileiro, do valor
adicionado da indústria de transformação, do valor adicionado da administração
pública e de outras variáveis econômicas que podem estar relacionadas o PIB per
capita do município de Ouro Branco.

Introdução

Ouro Branco é uma cidade do estado de Minas Gerais que foi elevado a município
em 1953, está localizado na região central do estado e ocupa uma área de cerca de
260km², sendo 11 km² em perímetro urbano. Houve vários ciclos econômicos em
Ouro Branco que foram determinantes para o que é hoje a economia ouro
branquense, iniciado com o ciclo do ouro, depois, o ciclo da uva e posteriormente
o da batata, até chegar, atualmente, onde a atividade preponderante é a industrial.
Iniciada com a instalação da então empresa estatal Aço Minas Gerais S.A em 1976
e posteriormente adquirida pela Gerdau -maior multinacional brasileira produtora
de aço- em 1997 se tornando, esta, a maior usina da empresa no mundo, iniciando-
se assim em Ouro Branco o ciclo do Aço.

A unidade produtora de aço localizada em Ouro Branco de posse da GERDAU é
considerada a terceira mais importante aquisição da siderúrgica sendo a maior
unidade de fornecimento de aço da mesma no mundo. Nela há mais de 8000
colaboradores empregados o que representa mais do que um quinto da população
ouro branquense que, segundo o censo de 2022, se concentrava em 38.724
habitantes e mais de um quarto da quantidade de colaboradores da usina.

Sendo assim fica evidente que havendo variações no PIB e/ou PIB per capita ouro
branquense, importantes indicadores econômicos, pode-se haver e de fato há
correlação com o desenvolvimento da indústria de transformação sendo essa a
hipótese primordial do presente trabalho. Estudos anteriores indicam que o
desenvolvimento econômico de municípios é frequentemente impulsionado por
atividades industriais e pelo setor público. Segundo Menezes et al. (2019), o valor
adicionado pela indústria de transformação é um dos principais determinantes do
PIB municipal em regiões industriais. De fato, a relação entre o crescimento do PIB
per capita de ouro branco e o valor adicionado pela indústria de transformação
pode ser corroborada com dados do IMRS e Data SUS.
<p align="center">
  Figura 1. Regressão linear simples entre o PIB per de Ouro Branco e o valor adicionado
  da indústria de transformação.
</p>
<p align = "center">
  <img width="633" height="444" alt="image" src="https://github.com/user-attachments/assets/18d6e65e-04b6-4d82-8605-dd4b38ac0f0b" /><br>
  <span style="font-size:12px;"><i>Fonte: Elaboração própria, a partir de dados do IMRS (2002 - 2021) e do Data SUS (2000-2001).</i></span>
</p>

O gráfico acima mostra que à medida que se cresceu a indústria de transformação
dentro do município de Ouro Branco houve também um crescimento do seu PIB per
capita sendo essa relação quase perfeita, sendo a variável explicativa significativa
à 0,1% quando rodado o modelo de regressão linear simples.

Metodologia e resultados

Usando os dados no decorrer dos anos como unidade amostral, reuni uma
relevante quantidade de variáveis para poder buscar dentre estas quais teriam
efeito significativo para explicar a evolução do PIB per capita ouro branquense.

Dentre as quais, destaco:
• Evolução do PIB per capita brasileiro – IPEA data;
• Evolução do PIB per capita ouro branquense – IMRS e DATA SUS;
• Valor Adicionado – Agropecuária – IMRS;
• Valor Adicionado – Industria de transformação – IMRS;
• Valor Adicionado – administração pública – IMRS;
• Empregados – Extrativa mineral – IMRS;
• Empregados – Industria de transformação – IMRS;
• População de Ouro Branco – IMRS

Primeira análise

Em uma primeira análise preocupei-me em verificar se o crescimento do PIB per
capita de Ouro Branco não seria devido apenas ao crescimento natural da
economia brasileira, para isso utilizei dados do PIB per capita brasileiro durante o
mesmo período para estimar uma regressão linear simples e em seguida injetei
outras variáveis no modelo para verificar seu ajuste a mais de uma variável.
<p align="center">
  Figura 2. Regressão linear simples para PIB per capita de Ouro Branco e PIB per capita
  brasileiro
</p>

<p align="center">
  <img width="747" height="227" alt="image" src="https://github.com/user-attachments/assets/490a9a5c-95b5-468c-9e46-73176a3ccffb" /><br>
  <span style="font-size:12px;"><i>Fonte: Elaboração própria, utilizando o software estatístico R.</i></span>
</p>

Com esses resultados em mãos vê-se que para cada aumento em uma unidade no
PIB per capita brasileiro é esperado um aumento de 3,137 unidades de crescimento
no PIB per capita de Ouro Branco o que me levou a crer que haveria outras possíveis
explicações para o crescimento dele.

<p align="center">
  Figura 3. Regressão múltipla para análise do PIB per capita brasileiro
  <img width="656" height="413" alt="image" src="https://github.com/user-attachments/assets/df4c3777-c133-4596-a22c-ad4670d61425"/><br>
  <span style="font-size:12px;"><i>Fonte: Elaboração própria, utilizando o software estatístico R.</i></span>
</p>
Desse modo foi possível identificar uma alta correlação entre as variáveis do PIB
per capita brasileiro e ouro branquense rodado o MQO simples, mas não quando
há a presença de mais variáveis. A alta correlação entre as duas variáveis de
controle iniciais e tanto o R² e o R² ajustado inflados podem ser explicados pela
baixa quantidade de amostras por mais que suficientes para a estimação do
modelo.

Ainda olhando para a figura 3, outra coisa que chama bastante a atenção é que,
apesar da perda de significância da variável que dita o PIB per capita brasileiro, o R²
ainda sim sobe para 98,96% devido a inserção da variável de controle “Valor
Adicionado – Industria de Transformação” que é significativa a 0,1%. Assim,
apresentando os resultados esperados.

A hipótese inicialmente postulada e que se quis demonstrar com estes dois
modelos iniciais e para o restante do trabalho é de que não haveria alta significância
entre a variação do PIB per capita brasileiro e a variável dependente o que se
mostrou verdadeiro quando esta controlada por outras variáveis e correlação
positiva entre o valor adicionado da indústria de transformação e a mesma.
Também é importante frisar que essas duas lógicas se mantiveram inalteradas em
análises posteriores.

Segunda análise

Em uma segunda análise dediquei-me a apanhar uma maior quantidade de dados
que pudessem servir para a explicação da minha variável dependente, dentre elas
posso destacar o “valor adicionado da administração pública” e a “evolução da
população de Ouro Branco” sendo que esta última faz muito sentido dado que
estou trabalhando com PIB per capita.

Destaco estas duas pois ambas tiveram efeito oposto ao que era esperado no
sentido de que a variável que dita a população de Ouro Branco se mostrou não ser
significante quando controlada por mais variáveis e o valor adicionado da
administração pública se tornou uma importante variável a estar no modelo até o
final do trabalho apesar da também baixa significância quando posta junto a outras
variáveis explicativas.
<p align="center">
  Figura 4. Modelo com quatro variáveis<br>
  <img width="594" height="333" alt="image" src="https://github.com/user-attachments/assets/d65ea54b-61f0-4036-8d74-8f88748b3e3e" /><br>
  <span style="font-size:12px;"><i>Fonte: Elaboração própria, com dados do IMRS, data SUS e IPEA data.</i></span>
</p>

Aqui havia o pressuposto de que a variável de população seria significante, mas
logo foi notado o equívoco dado que a população de Ouro Branco não teve uma
variação significativa no período abordado saindo de 30383 habitantes no ano de
2000 passando pela máxima de 40220 em 2021 seguida de uma queda para 38724
em 2022. Essa queda no último ano pode ter contribuído significativamente no
aumento do PIB per capita nesse ano dado que ele mais que dobrou no período.
Mas é interessante notar que o valor adicionado da indústria de transformação
também dobrou nesse último ano.
Seguiu-se a partir daqui diversos testes de modelos para verificar qual teria o
melhor ajuste.

Análise final

Após testes de modelos com diferentes tipos de variáveis procurando o melhor
ajuste que contribui com o modelo no sentido de aumentar R² ajustado, aproximar
mais a média dos resíduos a 0 e reduzir a variância destes. Aqui entrou a
importância da variável do valor adicionado da administração pública pois tendo-a
no modelo, este passou a apresentar uma distribuição mais aleatorizada das
minhas observações com os resíduos, sendo isto o desejável.
<p align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <b>Figura 5. Gráfico da plotagem dos resíduos com as observações sem a variável Valor Adicionado da Administração pública.</b><br>
        <img width="425" height="278" src="https://github.com/user-attachments/assets/42f26e40-7f00-47b9-9919-ea2871d2f26b" /><br>
        <i>Fonte: Elaboração própria utilizando o software estatístico R.</i>
      </td>
      <td align="center" width="50%">
        <b>Figura 6. Gráfico da plotagem dos resíduos com as observações com a variável Valor Adicionado da Administração pública.</b><br>
        <img width="425" height="278" src="https://github.com/user-attachments/assets/890a0639-abae-47e4-aa77-fa17e0f8a4d6" /><br>
        <i>Fonte: Elaboração própria utilizando o software estatístico R.</i>
      </td>
    </tr>
  </table>
</p>

Diminuindo, então, o teor de heterocedasticidade do modelo, mas possivelmente
trazendo um problema relacionado a alta colinearidade que teve de ser corrigido
em passos posteriores.

Para este momento frisei-me em tentar verificar a presença de
heterocedasticidade. Para isto tentei os resíduos ao quadrado conta cada uma das
variáveis independentes e elaborar um gráfico de dispersão para analisar
visualmente o que estava acontecendo. Foram gerados três gráficos, que seguem
abaixo.

<p align="center">
  <table>
    <tr>
      <td align="center" width="33.33%">
        <b>Figura 7. </b><br>
        <img width="350" height="278" src="https://github.com/user-attachments/assets/f6aa79d0-8043-425a-b3f0-ad7205eaf576" /><br>
      </td>
      <td align="center" width="33.33%">
        <b>Figura 8.</b><br>
        <img width="350" height="278" src="https://github.com/user-attachments/assets/99035aa6-93cf-4f6d-8077-1282581a60d9" /><br>
      </td>
      <td align="center" width="33.33%">
        <b>Figura 9.</b><br>
        <img width="350" height="278" src="https://github.com/user-attachments/assets/2c938e49-aec2-4bac-9936-591f018477b6" /><br>
      </td>
    </tr>
  </table>
  <span style="font-size:12px;display:block; text-align:right;"><i>Fonte: Elaboração própria, com dados do IMRS, data SUS e IPEA data.</i></span>
</p>

Talvez por incapacidade técnica ou teórica, eu particularmente não consegui extrair
nenhuma interpretação desses dados. Segui, então, para os testes de Breush-
Pagan e White. Sendo os resultados aqui apresentados nas figuras 7 e 8.

<p align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <b>Figura 10. Teste de Breush-Pagan.</b><br>
        <img width="425" height="278" src="https://github.com/user-attachments/assets/341c9a53-14ae-4084-a5d2-db0a4342f540" /><br>
        <i>Fonte: Elaboração própria utilizando o software estatístico R.</i>
      </td>
      <td align="center" width="50%">
        <b>Figura 11. Resultado do Teste de White.</b><br>
        <img width="425" height="278" src="https://github.com/user-attachments/assets/7e7d9481-59c2-4e01-a490-42b8b5240bcb" /><br>
        <i>Fonte: Elaboração própria utilizando o software estatístico R.</i>
      </td>
    </tr>
  </table>
</p>

Apesar de haver um valor maior do que 5% para o teste de White é possível verificar
a presença de heterocedasticidade no modelo. Além disso, ao tentar corrigir a
heterocedasticidade foi identificado dois possíveis problemas, um de
colinearidade nas variáveis independentes o que torna a matriz do modelo mal
condicionada resultando em uma matriz de covariância estimada que é singular, ou
seja, que não pode ser invertida, o que impede a correta estimação dos erros
padrão robustos ou problemas de escala com as variáveis.

Utilizou-se o fator de inflação da variância para verificar se havia colinearidade
entre as variáveis explicativas por meio da fórmula “vif” da biblioteca “car”. Não foi
verificado um VIF muito alto o que me levou a crer que poderia ser algo relacionado
a um problema de escala com as variáveis.

Para resolver o problema, então, padronizou-se as variáveis subtraindo a média e
dividindo pelo desvio padrão para tentar melhorar o condicionamento do modelo.
Feito isso segue abaixo resultados encontrados.
<p align="center">
  Figura 12. Modelo final ajustado para heterocedasticidade.
  <img width="886" height="445" alt="image" src="https://github.com/user-attachments/assets/ee74c13c-2d2e-4ea3-aa9c-77d69c72e059" /><br>
  <span style="font-size:12px;"><i>Fonte: Elaboração própria, utilizando o software R.</i></span>
</p>

A partir desse modelo chegamos à conclusão de que o valor adicionado da
indústria de transformação não só é altamente significante para explicar o aumento
acentuado do PIB per capita de Ouro Branco durante o período de 2000 – 2021,
como é responsável por explicar algo em torno de 99,45% deste. Porém, existem
algumas limitações no trabalho que dificultam a tomada dessa conclusão como
por exemplo o caso de dados faltantes. Apesar do meu campo amostral abranger
grande parte da existência de Ouro Branco, infelizmente não fui capaz de encontrar
dados de tempos anteriores à chegada da GERDAU no município para termos de
comparativos.

Conclusão
O presente trabalho teve como objetivo principal analisar os determinantes do alto
crescimento do PIB per capita do município de Ouro Branco, Minas Gerais, entre
2000 e 2021, com ênfase no impacto das variáveis econômicas, especialmente o
valor adicionado pela indústria de transformação. Através da aplicação de modelos
de regressão linear múltipla, foi possível verificar que a indústria de transformação
desempenha um papel crucial no crescimento econômico de Ouro Branco.
Os resultados indicam que o crescimento do PIB per capita brasileiro não foi
altamente influente no crescimento local, apesar de ter o seu efeito positivo. Já o
valor adicionado pela indústria de transformação se mostrou uma variável
altamente significativa, corroborando a hipótese inicial. Além disso, a análise
evidenciou a importância da administração pública na explicação das variações no
PIB per capita de Ouro Branco.
No decorrer das análises, foi necessário ajustar o modelo para lidar com problemas
de heterocedasticidade e colinearidade, garantindo assim a robustez dos
resultados. A inclusão de variáveis adicionais, como a população e o valor
adicionado pela administração pública, diferiram das hipóteses inicialmente
postuladas, exigindo uma revisão cuidadosa e ajustes no modelo.
A conclusão fundamental deste estudo é que a industrialização, especialmente
pela presença significativa da GERDAU, é o principal motor do crescimento
econômico de Ouro Branco. Em futuras pesquisas, recomenda-se a análise de
outros setores econômicos e a inclusão de novas variáveis que possam fornecer
uma compreensão mais abrangente do crescimento do PIB per capita em Ouro
Branco.
