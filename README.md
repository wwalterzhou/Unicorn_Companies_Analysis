# 🦄 Unicorn Companies Analysis

## 📚 About Data

Unicors are private companies valued at over US$1 billion.

The dataset used in this analysis contains records of 1,074 unicorn companies up to March 2022
Information on the dataset include:
- `Company` : Company name
- `Valuation` : Company valuation in billions of dollars
- `Date Joined` : The date in which the company reached $1 billion in valuation
- `Industry` : Company industry
- `City` : City the company was founded in
- `Country` : Country the company was founded in
- `Continent` : Continent the company was founded in
- `Year Founded` : Year the company was founded
- `Funding` : Total amount raised across all funding rounds in billions (B) or millions (M) of dollars
- `Select Investors` : Top 4 investing firms or individual investors (some have less than 4)

## ✏️ Data Cleaning

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned `Valuation` and `Funding` columns and cast as float
- Exclude rows with "Unknown" `Funding` values
- Explode `Select Investors` column into individual rows for categorical analysis


## 💡 Highlights

- On average, it takes 7 years for a startup to reach a $1 billion valuation and achieve unicorn status.
- The United States dominates the unicorn landscape with 562 unicorns, and San Francisco is the global hub for unicorns, boasting 152.
- Accel and Tiger Global Management are the leading venture capital firms in terms of funding the most unicorns.
- The combined valuations of US and Chinese unicorns account for 72% of the global unicorn valuation, significantly outperforming other regions.
- Bytedance, SpaceX, SHEIN, and Stripe are the top-performing unicorns, with valuations exceeding the average unicorn by a significant margin at $71 billion.
- AI, E-commerce, Fintech, and Edtech industries have emerged as high-value sectors for unicorns, with average valuations surpassing the global average by $3.5 billion.

## 📊 Visualization

![Unicorns](https://github.com/wwalterzhou/Unicorn-Companies-Analysis/blob/main/Unicorn%20Companies%20Analysis.png)




