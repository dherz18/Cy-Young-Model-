Cy Young Model

This project aims to build a model that can predict the winners of the American League (AL) Cy Young award in Baseball, using a vast amount of pitching data collected over the years. The Cy Young award is given annually to the best pitchers in Major League Baseball (MLB), one each for the American League (AL) and National League (NL).

The strategy for building this model involves collecting historical data on past winners and players' pitching data. The data was sourced from "baseball-reference.com," spanning the years 2008 to 2021. Different data types were obtained, including the voter data for Cy Young, all pitchers' data, team record data, and various stats that are believed to influence a pitcher's chances of winning the award. Selenium and BeautifulSoup libraries were used to scrape this data, and Pandas was used for organizing the collected data into DataFrames.

The data was then cleaned and processed, removing unnecessary columns, handling missing values, and transforming specific data types. To discern potential predictors for the Cy Young award, correlation analysis was conducted between players' performance stats and their voting shares.

A Linear Regression model was employed to establish a relationship between the predictors and the outcome variable. The model was trained on the data up to the year 2020, while the data for the year 2021 served as the testing data. Finally, the model's performance was evaluated based on the mean squared error between the actual and predicted voting shares.
