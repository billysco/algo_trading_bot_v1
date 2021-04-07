# algo_trading_bot_v1
First attempt at creating a machine learning trading bot
--
Usage
This model uses machine learning to try to create a profitable trading strategy. To start, a baseline performance is established. The signals used are the 4 day and 100 day SMAs (simple moving averages). Then, the baseline algorithm is tuned and evaluated. Then the model is evaluated with 2 machine learning classifiers, SVC and RandomForestClassifier.  The RandomForestClassifier has a higher accuracy than the SVC model as referenced by the higher f1-score. 
--
Technologies
This model is written in Jupyterlab using Python. The following packages are used: Pandas, sklearn (SVC and RandomForestClassifier), numpy, hvplot, matplotlib, and pathlib. 
--
Contributor
Billy Scolinos
billyscolinos1@gmail.com