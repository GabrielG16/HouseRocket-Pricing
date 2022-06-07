# HouseRocket-Pricing
<img src="https://youimg1.tripcdn.com/target/fd/tg/g3/M04/BB/BB/CggYGVaMcXuAHn8cACGBzc2mJR0522_C_640_320_R5_Q70.jpg_.webp?proc=source%2Ftrip" alt="MarineGEO circle logo" style="height: 200px; width:600px;"/>

Esse projeto teve como objetivo a análise e precificação de casas da região de King County entre os anos de 2014 e 2015.

A análise levou em consideração tanto características inerentes aos imóveis como número de quartos, banheiros, área útil, etc quanto fatores de localização e vizinhança que também poderiam exercer algum impacto.

Ficou evidenciado que o fator da localização do imóvel tem forte influência no preço médio das residências, possivelmente devido à vizinhança próxima, com pessoas de alto prestígio social morando no entorno. Em relação às características inerentes ao imóvel, o fator principal de valorização revelou-se ser a área interna útil. 

Seguido disso, estão fatores como a condição do imóvel, tendo alguns já passado por reformas para melhorar sua valorização. O resultado pode indicar que imóveis de baixo preço podem adquirir uma valorização signfiicativa mediante reforma, o que pode ser utilizado como estratégia pelas empresas imobiliárias.

Foi observado flutuações no preço médio das casas durante o ano estudado, o que pode indicar um fator de sazonalidade nas vendas que pode ser interessante para o vendedor/comprador.

Na etapa de modelagem, foram aplicadas algumas técnicas de pré-processamento dos dados como scaling e Polynomial featuring. Os resultados melhor alcançados foram obtidos pelo algoritmo Random Forests, chegando a atingir um coeficiente de determinação (R²) de 87% após a tunagem dos hiperparametros do modelo.

No entanto, também foi testado o modelo de Regressão Linear, que atingiu 80% no coeficiente de determinação, podendo ser melhorado ainda ao aplicar técnicas de regularização (Ridge/Lasso). Esse modelo pode ser uma alternativa viável à Random Forest visto a sua maior intuitividade na explicabilidade dos resultados. A escolha final do modelo dependeria dos objetivos da empresa.

O modelo final poderia ser utilizado por empresas imobiliárias para identificar oportunidades de casas que podem ser compradas por um preço menor e vendidas com uma margem de lucro maior ao realizar os ajustes necessários nos fatores que mais influenciam na valorização do imóvel.
