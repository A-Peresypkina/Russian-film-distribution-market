# Russian-film-distribution-market

Good day, this research was made while I was studying in Yandex.
Purpose: study the Russian film distribution market and identify current trends
Stages: 
1) data loading, EDA
2) study of correlation
3) conclusions

Stack: pandas, numpy, seaborn, matplotlib

Conclusions: 
1) An analysis of categorical data was carried out: duplicates were identified due to input errors: the presence of extra spaces; use of different registers; The data was brought to a uniform form (lower case), extra spaces were removed; fixed data types where necessary;
2) The most films were released in 2010 and 2019. It is worth noting that the fewest rental certificates were issued in 2012 and 2017.
3) According to available data, it has been established that:
    * the maximum amount of fees was in 2018 and amounted to 49,668,403,134,320 rubles
    * the minimum amount of fees was in 2010 and amounted to RUB 2,428,654.00
4) The relationship between the parameters was analyzed. It was revealed:
    * high correlation between the budget and the share of state support
    * low relationship between the amount of receipts from a film and the share of state support, the size of the budget
    * the most profitable films in the "16+" category
5) Data for the period from 2010 to 2014 are not completely filled out/are presented worse in the dataset. Data for the period from 2015 to 2019 is more “complete”
6) Basic data on state support starts in 2013 and the size increases every year.
7) The highest-grossing film is Serf, the gross amount is RUB 3,073,568,690.79
8) It was established that 214 films with state support did not pay off, however, in general, investments in cinema pay off.
