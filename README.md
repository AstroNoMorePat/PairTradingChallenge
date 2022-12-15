# Agnostiq Pair Trading Investment Challenge

Agnostiq Pair Trading Investment Challenge

AgnostiqExecutiveSummary.pdf -- A write-up of the project and summary of its primary results and practical recommendations

DataGathering.ipynb -- Notebook used for collecting historic trading data using yfinance

IdealizedPairTradingModel.ipynb -- Coded up example of the idealized pair trading model utilized in this project

ConventionalPairIdentification.ipynb -- Notebook that explores pair trading based on simple heuristics like whether pair stocks were profitable in prior years

LikelyPairStocks.txt -- List of potential pair trading stocks selected because they were profitable in all three of the test years

MachineLearning.ipynb -- Notebook that utilizes machine learning classifiers to identify pair stocks likely to be profitable in the future

LikelyPairStocks_ML.txt -- List of potential pair trading stocks identified using the best machine learning classifier from MachineLearning.ipynb

FinalStrategyTest.ipynb -- Takes the target pairs from LikelyPairStocks.txt and LikelyPairStocks_ML.txt and computes how they perform in practice during the final year of test data

Note that the project also includes several large csv files and a SQL db file too large to host here.
Running the included notebooks without these pre-computed files will be a fairly lengthy process (probably about 36 hours of wall time), so if you have need to replicate these results don't hesitate to reach out.
I would be happy to provide you with the pre-computed files and save you a good bit of time.
