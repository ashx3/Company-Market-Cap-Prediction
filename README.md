## Context
Every year Fortune, an American Business Magazine, publishes the Fortune 500, which ranks the top 500 corporations by revenue. This dataset includes the entire Fortune 1000, as opposed to just the top 500.

## Tasks

### Company Market Cap Prediction
Given data about big companies, let's try to predict the market capitalization of a given company.
We will use a variety of regression models to make our predictions.<br>

__DataSource__ -  _[KAGGLE DATASET LINK](https://www.kaggle.com/winston56/fortune-500-data-2021)_

![Market Cap](/images/marketcap.jpg)

Data

## Content
The Fortune 1000 dataset is from the Fortune website, collected by the processes outlined in this notebook. It contains U.S. company data for the year 2021. The dataset is 1000 rows and 18 columns.

## Features
- Company - values are the name of the company
- Rank - The 2021 rank established by Fortune (1-1000)
- Rank Change - The change in the rank from 2020 to 2021. There is only a rank change listed if the company is currently in the top 500 and was previously in the top 500.
- Revenue - Revenue of each company in millions. This is the criteria used to rank each company.
- Profit - Profit of each company in millions.
- Num. of Employees - The number of employees each company employs.
- Sector - The sector of the market the company operates in.
- City - The city where the company's headquarters is located.
- State - The state where the company's headquarters is located
- Newcomer - Indicates whether or not the company is new to the top Fortune 500 ("yes" or "no"). No value will be listed for companies outside of the top 500.
- CEO Founder - Indicates whether the CEO of the company is also the founder ("yes" or "no").
- CEO Woman - Indicates whether the CEO of the company is a woman ("yes" or "no").
- Profitable - Indicates whether the company is profitable or not ("yes" or "no").
- Prev. Rank - The 2020 rank of the company, as established by Fortune. There will only be previous rank data for the top 500 companies.
- CEO - The name of the CEO of the company
- Website - The url of the company website
- Ticker - The stock ticker symbol of public companies. Some rows will have empty values because the company is a private corporation.
- Market Cap - The market cap (or value) of the company in millions. Some rows will have empty values because the company is private. Market valuations were determined on January 20, 2021.
