# Book Store Analysis
Used SQL to solve analytical questions related to a book store, extracting key insights on sales and customer behavior. The analysis aimed to provide a clearer understanding of the store's performance. These insights help the owner make more informed, data-driven decisions for future growth.

## Files Used:
<li><a href="https://github.com/HemangTaori/Book_Store_Analysis/blob/main/Books.csv">books</a></li>
<li><a href="https://github.com/HemangTaori/Book_Store_Analysis/blob/main/Orders.csv">orders</a></li>
<li><a href="https://github.com/HemangTaori/Book_Store_Analysis/blob/main/Customers.csv">customers</a></li>
<li><a href="https://github.com/HemangTaori/Book_Store_Analysis/blob/main/Schema.png">Schema</a></li>

## Technology Used:
<li>SQL</li>
<li>Excel</li>

## Overview:
In this SQL project, the primary objective was to provide the business owner with actionable insights into the store’s performance, customer behavior, and product trends to support better decision-making. To accomplish this, we worked with three key csv files: *Customers*, *Orders*, and *Books*. These files were imported into a SQL environment where the data was cleaned, structured, and analyzed. The *Customers* file contained important customer details like customer ID, name, phone number, city, and country. The *Books* file stored information about each book, including book ID, title, genre, and price. The *Orders* file acted as a bridge between the two, linking customers to the books they had purchased via customer IDs and book IDs.

Using these datasets, we created meaningful relationships through SQL joins to extract comprehensive insights. For instance, we utilized **inner joins** to fetch matched records across tables, **left joins** to ensure we didn’t miss out on customers or books without orders, and employed **WHERE** clauses to filter records based on specific conditions like location or genre. We also implemented **GROUP BY** and **ORDER BY** clauses to summarize data and present it in a structured and sorted manner. By doing this, we were able to identify top-selling books, frequent customers, popular genres in certain cities, and customer distribution across different countries.

Throughout the project, we made use of several SQL functions to enhance the analysis. Functions like **SUM** and **COUNT** helped in calculating total revenue and number of orders, while **COALESCE** was used to handle null values gracefully. We used **ASC** and **DESC** for sorting data in ascending and descending order, and **LIMIT** to fetch a set number of top results, such as top 5 customers or best-selling books. These techniques allowed us to transform raw data into clear, valuable insights that the business owner could use to identify trends, optimize inventory, and tailor marketing strategies based on customer behavior and geographic patterns.

## Summary:
