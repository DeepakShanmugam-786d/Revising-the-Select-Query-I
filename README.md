# 🌆 Querying American Cities with Large Populations

## 📌 Problem Description

We have a table called **CITY** that stores information about different cities around the world. Our goal is to find all cities in **America (CountryCode = 'USA')** that have a population **greater than 100,000**.

---

## 📊 CITY Table Structure
| Column Name  | Data Type |
|-------------|----------|
| ID          | int      |
| Name        | varchar  |
| CountryCode | varchar  |
| District    | varchar  |
| Population  | int      |

### 📖 What do the columns mean?
- **ID**: A unique number assigned to each city.
- **Name**: The name of the city.
- **CountryCode**: A three-letter code for the country (e.g., USA for America).
- **District**: The district where the city is located.
- **Population**: The number of people living in the city.

---

## 🎯 Goal: Find Large American Cities
We need to **find all cities in America (CountryCode = 'USA') where the population is greater than 100,000**.

### ✅ Expected Output
The output should include **all columns** for the matching cities.

---

## 🔥 How to Solve
Here’s how we can do it:

1️⃣ **Look at the COUNTRYCODE column** to filter only cities in America (`USA`).  
2️⃣ **Check the POPULATION column** to find cities with more than 100,000 people.  
3️⃣ **Return all columns for these cities.**

---

## 🏆 Why is this important?
- Helps analyze **large cities in the USA** 🏙️
- Useful for **population studies and urban planning** 📊
- Shows how to filter **specific data from a large database** 🔍

🚀 Now you’re ready to write a query and find the largest cities in America!

