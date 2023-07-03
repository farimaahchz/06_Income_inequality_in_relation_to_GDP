# 06_Income_inequality_in_relation_to_GDP

Is there a relation between a country's Gross Domestic Product (GDP) and its income inequality?

To be able to answer this question, we can download the (GDP) and Gini index data set. Once we have the data, we can use Python and Pandas to calculate the correlation coefficient. 

💡Note

Be aware of the difference between correlation and causation here. A might cause B. B might cause A. But both A and B could be caused by an unknown C as well.

One way to express income inequality is to look at a country's "Gini coefficient" (also known as "Gini index"). You can find a dataset of Gini Coefficients here: https://ourworldindata.org/income-inequality#high-income-countries-tend-to-have-lower-inequality

You can find a dataset with historical GDP data here:https://ourworldindata.org/economic-growth#gdp-per-capita-over-the-long-run.

To be able to answer this question you would want to calculate the "correlation coefficient" of the GDP and the Gini coefficient. But before you can do that you may need to resample the data so a correlation coefficient can be calculated.

