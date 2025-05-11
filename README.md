# Airbnb Listings SQL Script

This project contains a SQL script to create and populate a sample table named `airbnb_listings`. The table includes listings from various cities around the world, along with information such as the number of rooms and the year the listing was added.

## 📂 Files Included

- `SQLQuery1.sql` – Contains SQL commands to:
  - Create a database (`work`)
  - Switch to that database
  - Create a table (`airbnb_listings`)
  - Insert 5 sample records

## 🧱 Table Schema

| Column Name       | Data Type | Description                        |
|------------------|-----------|------------------------------------|
| id               | INT       | Unique ID for each listing         |
| city             | VARCHAR   | Name of the city                   |
| country          | VARCHAR   | Country of the listing             |
| number_of_rooms  | INT       | Total rooms available in the listing |
| year_listed      | INT       | Year the listing was added         |

## 🛠️ How to Use

1. Open your SQL environment (e.g., MySQL Workbench, phpMyAdmin, or terminal).
2. Run the contents of `SQLQuery1.sql`.
3. The database `work` and table `airbnb_listings` will be created with the sample data.

## 💡 Notes

- This is a basic example for practice or demonstration purposes.
- You can extend this project by adding more columns or connecting it to a front-end app.

## 🧑‍💻 Author

Irshad Ali  
Trainee in Data Science & AI | Political Science Student | GitHub: [Irshad463](https://github.com/Irshad463)
