# Descrição.
 
Uma determinada cidade fictícia contratou um cientista de dados para criar um modelo de machine learning que prevê a qualidade do ar. Os dados foram obtidos através 
de uma matriz de sensores que mede as  seguintes informações: 
 
 
* Date (DD/MM/YYYY)
* Time (HH.MM.SS)
* True hourly averaged concentration CO in mg/m^3 (reference analyzer)
* PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
* True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
* True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
* PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
* True hourly averaged NOx concentration in ppb (reference analyzer)
* PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
* True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
* PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
* PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
* Temperature in  °C
* Relative Humidity (%)
* AH Absolute Humidity
 
# Objetivo.
 
Logo este trabalho visa criar um modelo de machine learning que estime a concentração de CO de hora em hora. Sendo que a predição será feita da seguinte forma:
 
* Caso seja desejado prever a concentração de CO às 14 horas, o modelo criado vai utilizar os dados que foram obtidos do sensor às 13 horas para prever o valor de CO. Caso alguém deseja 
prever a concentração de carbono as 15 horas, ele vai ter que esperar os dados das 14 horas ser adquirido.
 
# Metodologia
 
Este projeto será baseado no processo padrão Cross-industry para mineração de dados (CRISP-DM). Uma ideia padrão sobre projeto de ciência de dados pode ser linear: preparação de dados, modelagem, avaliação e implantação. No entanto, quando usamos a metodologia CRISP-DM, um projeto de ciência de dados se torna uma forma circular. Mesmo quando termina em Deployment, o projeto pode ser reiniciado novamente por Business Understanding. Como isso pode ajudar?
 
 
<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/b/b9/CRISP-DM_Process_Diagram.png" alt="Kitten" title="A cute kitten" width="430" height="430" />
</p>
 
Pode ajudar a evitar que o cientista de dados pare em uma etapa específica e perca tempo com ela. Quando todo o projeto estiver concluído, o cientista de dados pode retornar à etapa inicial e fazer todas as etapas novamente. Portanto, o objetivo principal é seguir círculos conforme a necessidade. 
 
# Pipeline
 
* Tratamento dos dados.
* Análise dos dados.
* Preparação dos dados.
* Feature Engineering.
* Modelagem dos modelos de Machine Learning.
* Ajuste dos hiperparâmetros.
* Avaliação do melhor modelo. 
* Deploy do modelo (Construção).
 
# Aquisição dos dados.
 
* Os dados foram adquiridos do repositório https://archive.ics.uci.edu/ml/datasets/Air+quality.
 
# Descrição das partes do projeto
 
Essa primeira parte do projeto está encarregada de tratar os dados, avaliá-los e criar o modelo de machine learning. Esse estudo foi dividido nas seguintes partes:
* Parte 1: Nesta parte foi realizado o tratamento dos dados faltantes.
* Parte 2: Análise dos dados e a criação de algumas variáveis.
* Parte 3: Melhor maneira vista para codificar as variáveis categóricas.
* Parte 4: Criação de novas variáveis.
* Parte 5: Modelagem do modelo de machine learning, interpretação dos seus resultados e foi visto como cada variável impacta no modelo criado.  
 
**A segunda parte é o deploy do modelo que está em construção.**
 
 
