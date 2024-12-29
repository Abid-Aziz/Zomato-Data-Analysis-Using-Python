

# Zomato Data Analysis Project

## Project Overview

This project focuses on analyzing a dataset related to Zomato, a popular restaurant discovery and food delivery service. The goal was to analyze customer behavior, restaurant ratings, and spending patterns, using the data to uncover valuable insights. This analysis was done through **Exploratory Data Analysis (EDA)** and **data visualizations**, answering key questions relevant to Zomato's business strategy. The dataset includes columns such as `online_order`, `book_table`, `rate`, `votes`, `approx_cost(for two people)`, and `listed_in(type)` representing restaurant characteristics and customer preferences.

## Key Questions and Insights

### 1. **What Type of Restaurant Do the Majority of Customers Order From?**

   - **Analysis**: By analyzing the `listed_in(type)` column, we observed that the most popular types of restaurants are **Buffet**, **Cafes**, and **Dining**.
   - **Insight**: Buffet and Cafes are the most commonly preferred restaurant types for online orders. Cafes have a significant presence in the dataset, with many customers preferring this type.

### 2. **How Many Votes Has Each Type of Restaurant Received From Customers?**

   - **Analysis**: A count of votes per restaurant type shows that **Dining** and **Cafes** have received the highest number of votes across the dataset.
   - **Insight**: Restaurants in the **Dining** and **Cafes** categories are the most popular among customers, with **Dining** restaurants consistently receiving more votes.

### 3. **What Are the Ratings That the Majority of Restaurants Have Received?**

   - **Analysis**: Most of the restaurants in the dataset fall within a rating range of **3.0 to 4.5**. The most common rating is **4.0**, which indicates that most customers rate their experience positively.
   - **Insight**: The majority of restaurants have an average rating of around **4.0**, with a few exceptions scoring higher or lower.

### 4. **Zomato Observes That Most Couples Order Food Online. What Is Their Average Spending on Each Order?**

   - **Analysis**: We examined the `approx_cost(for two people)` column and found that the **average spending** for customers ordering food online is around **₹300**.
   - **Insight**: Couples are most likely to spend around ₹300 per order, which suggests they prefer affordable dining options. This insight could be useful for Zomato to offer targeted discounts or offers for this price range.

### 5. **Which Mode (Online or Offline) Has Received the Maximum Rating?**

   - **Analysis**: Comparing ratings between **online** and **offline orders**, it was found that **online orders** tend to receive slightly higher ratings on average.
   - **Insight**: Online orders generally receive better ratings than offline orders. This could indicate that online customers have better experiences, possibly due to faster service or convenience.

### 6. **Which Type of Restaurant Received More Offline Orders, So Zomato Can Provide Those Customers with Good Offers?**

   - **Analysis**: By filtering for offline orders and analyzing the restaurant types, it was found that **Dining** restaurants receive more offline orders than others.
   - **Insight**: Since **Dining** restaurants have more offline customers, Zomato can focus on offering these customers promotions or discounts to boost sales or increase engagement.

## Data Analysis Process

- **Data Cleaning**: The dataset was cleaned to remove irrelevant or missing data, ensuring that we could perform accurate analysis.
- **Exploratory Data Analysis (EDA)**: The main steps included summary statistics, grouping by restaurant type, and aggregating data based on customer ratings, votes, and cost.
- **Data Visualization**: Various types of visualizations were created to better understand the distribution of data, relationships between variables, and key trends. This included bar charts, box plots, and pie charts to represent restaurant types, ratings, and costs.

## Visualizations

- **Box Plot**: The box plot showed the distribution of ratings across **online** and **offline** orders. It revealed that online orders tend to have higher ratings than offline orders, indicating better customer satisfaction for online orders.
- **Bar Chart**: A bar chart was used to visualize the number of votes received by each restaurant type. It was clear that **Dining** and **Cafes** received the most votes, reflecting their popularity.
- **Cost Distribution**: A pie chart demonstrated that most customers prefer to order food in the ₹300 cost range, particularly couples, which was further confirmed by analysis.

## Conclusion

- **Restaurant Preferences**: The majority of customers prefer **Dining** Restaurent as compare to **Buffet** and **Cafes** restaurants. The **Dining** category received more offline orders, while **Cafes** tend to be more popular for online orders.
- **Customer Behavior**: Couples typically prefer affordable meals around ₹300. Zomato can use this insight to create targeted offers for this price segment.
- **Online vs Offline**: Online orders receive better ratings on average, suggesting that Zomato might want to focus on improving the offline experience.
- **Strategic Insights**: Zomato can focus on offering special promotions for offline **Dining** restaurants and consider incentivizing online orders with better features or offers.

This analysis highlights important trends in Zomato’s business model, customer preferences, and areas for potential improvement in both restaurant offerings and customer satisfaction.





