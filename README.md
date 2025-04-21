# 📊 Importing CSV Data to MySQL using Python

Hi there! 👋  
This notebook was created as part of my journey to improve my skills in **Data Analysis**. My goal was to learn how to load real-world CSV data into a **MySQL** database using Python, so I can later explore and analyse the data using SQL.

I used a public dataset from **Kaggle** (Amazon Products 2023) and wrote a simple script in **Jupyter Notebook** to handle the full process.

---

## 🛠️ What This Notebook Does

1. **Install Required Libraries**  
   Using `pip` to install the libraries needed for working with data and MySQL.

2. **Import Python Libraries**  
   `pandas` for data manipulation and `sqlalchemy` for connecting to the database.

3. **Create a Connection to MySQL**  
   Using `create_engine` to connect to a local MySQL instance.

4. **Load CSV Data into a DataFrame**  
   Reading the CSV files with `pandas`.

5. **Preview the Data**  
   Checking the first rows of the dataset to understand its structure.

6. **Upload Data to MySQL**  
   Saving the data from the DataFrame into MySQL tables using `.to_sql()`.

---

## 🗃️ Dataset Used

📂 **Dataset**: [Amazon Products Dataset 2023 – 1.4M Products](https://www.kaggle.com/datasets/asaniczka/amazon-products-dataset-2023-1-4m-products?select=amazon_products.csv)

- `amazon_products.csv` — contains product details like titles, ratings, prices, reviews, categories, etc.
- `amazon_category.csv` — contains the mapping of category IDs to category names.

---

## 🧠 Why I Did This

I'm currently learning tools and skills required to work as a Data Analyst. This small project helped me practice:

- Handling and exploring real-world CSV files
- Using `pandas` to manipulate data
- Connecting Python to a MySQL database
- Uploading data into MySQL for analysis with SQL

---

## 💬 Notes

- Make sure your MySQL server is running and that the target database (e.g., `amazon_db`) already exists.
- Update the credentials in the connection string (`username`, `password`, and `database`) based on your local setup.
- The `.to_sql()` method with `if_exists='replace'` will overwrite any existing tables with the same name.

---

## 🚀 What’s Next?

With the data now available in MySQL, the next step is to practice SQL queries!  
I plan to explore:
- Top-rated or most-reviewed products
- Category performance
- Price analysis
- Monthly trends (if date data is available)

This is one step closer to building a complete Data Analyst portfolio 🚀

---

Thanks for stopping by!  
Feel free to fork or reuse this if you're learning too. Let's grow together! 🙌

