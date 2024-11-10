# Power-BI
# Power BI Dashboards Repository

## Overview

This repository contains two Power BI dashboards:

1. [Sales Analytics Dashboard]
2. [Netflix Dataset Dashboard]
3. [Smartphone Price & Feature Comparison]

---

## Sales Analytics Dashboard

### Project Overview

This Power BI dashboard analyzes the historical sales data of a supermarket company with branches in three different cities. The data covers a three-month period from January 2019 to March 2019.

### Dataset Information

The dataset includes attributes such as invoice ID, branch, city, customer type, gender, product line, unit price, quantity, tax, total, date, time, payment method, cost of goods sold (COGS), profit, and customer ratings.

### Visualizations

- **Order Counts**: A card visual showing the count of orders.
- **Number of Units Sold**: A card visual showing the total number of units sold.
- **City**: A bar chart showing sales by `City`.
- **Unit Price**: A column chart showing the distribution of `Unit price`.
- **Price After Tax**: A measure visual showing the price after including tax.
- **Total Cost**: A card visual showing the sum of the `Total` column.
- **Total Profit**: A card visual showing the sum of the `Profit` column.
- **Payment Types**: A pie chart showing the distribution of sales by `Payment`.
- **Order Times**: A line chart showing the number of orders by `Time`.
- **Product Types**: A column chart showing total sales by `Product line`.
- **Profit by Country**: A map visual showing profit by `Country`.
- **Customer Type**: A pie chart showing the distribution of sales by `Customer type`.
- **Profit by Month**: A bar chart showing profit by month.
- **Time Period Slicer**: A slicer visual to filter data by `Date` for different time periods.

# Netflix Dataset Power BI Dashboard

## Project Overview

This Power BI dashboard provides an interactive analysis of TV Shows and Movies available on Netflix. The dataset is sourced from IMDB and contains metadata for around 7,000 titles, including information such as title, rating, genre, country of origin, and more. The dashboard visualizes various insights like ratings, genres, country distribution, and yearly trends.

## Dataset

### Source

The dataset is collected from the IMDB website. Data was gathered through web scraping of IMDB's ranking pages, filtered to show Netflix-related content, and then detailed information was collected for each title.

### Content

The dataset (`netflix_list.csv`) contains the following columns:

- **imdb_id**: Unique show identifier.
- **title**: Title of the show.
- **popular_rank**: Ranking as given by IMDB when filtered by popularity.
- **certificate**: Contains the age certifications received by the show. (Many null values)
- **startYear**: Year when the show was first broadcasted.
- **endYear**: Year of the show's ending.
- **episodes**: Number of episodes in the show. (1 for movies)
- **type**: Movie or Series.
- **orign_country**: Country of origin of the show.
- **language**: Language of the show.
- **plot**: Synopsis of the show.
- **summary**: Summary of the story of the show.
- **rating**: Average rating given to the show.
- **numVotes**: Number of votes received by the show.
- **genres**: Genre the show belongs to.
- **isAdult**: 1 if adult content is present, 0 if not.
- **cast**: Main cast of the show in list format.
- **image_url**: Link to the poster image.

## Dashboard Overview

### Visualizations

1. **Total Number of Titles**:
   - Card visual showing the total count of movies and series.

2. **Type Distribution**:
   - Pie chart showing the distribution between movies and series.

3. **Average Rating**:
   - Card visual displaying the average rating of all titles.

4. **Titles by Rating Group**:
   - chart showing the distribution of titles by rating groups.

5. **Ratings of Television vs. Movies**:
   - pie chart comparing the ratings of television shows versus movies.

6. **Show Types**:
   - Donut chart showing the distribution of different types of shows (e.g., Movies, TV Series).

7. **Number of Titles by Country**:
   - Table showing the number of titles from each country.

8. **Number of Titles by Language**:
   - Table showing the distribution of titles by language.

9. **Avg Ratings and Titles by Genre**:
   - Clustered column chart showing the average ratings and number of titles per genre.

10. **Rating Over Time**:
    - Line chart showing the average rating over the years.

11. **Country Distribution**:
    - table visual showing the number of titles from each country.

   




