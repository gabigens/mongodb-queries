# Sprint 5.01 — MongoDB Queries

## 📌 Project Overview

This project is part of the Data Analytics specialization at Barcelona Activa IT Academy. It focuses on querying and exploring a movie database using MongoDB.

The exercises cover document filtering, logical operators, regular expressions, aggregation pipelines, and geospatial data visualization using MongoDB Compass.

## 🎯 Objectives

- Explore collections and retrieve documents using MongoDB queries.
- Apply filtering conditions and logical operators.
- Count documents that match specific criteria.
- Use regular expressions to filter email addresses.
- Aggregate data by grouping documents and calculating totals.
- Filter movies by directors, IMDb ratings, awards, release years, and genres.
- Visualize theater locations using geospatial data in MongoDB Compass.

## 🛠️ Tools & Technologies

- **MongoDB** — NoSQL database and document queries.
- **MongoDB Compass** — Database exploration, query execution, schema analysis, and geospatial visualization.
- **JavaScript / MongoDB Query Language (MQL)** — Query syntax and aggregation pipelines.

## 🗂️ Project Structure

```text
sprint5-mongodb-queries/
├── README.md
├── Tasca S5.01. Consultes amb MongoDB
└── data/
```

## 📚 Exercises

### Level 1 — Basic Queries

- Retrieve the first two comments from the database.
- Count registered users.
- Count theaters located in California.
- Explore user documents.
- Count comedy movies.
- Combine logical operators to filter movies released in 1932.

### Level 2 — Filtering and Aggregation

- Count comments written using the `gameofthron.es` email domain.
- Group theaters by ZIP code and count the theaters located in Washington, D.C.

### Level 3 — Advanced Queries and Geospatial Analysis

- Find movies directed by John Landis with IMDb ratings between 7.5 and 8.
- Visualize theater locations on a map using MongoDB Compass Schema Analysis.

## 🔍 Key Learnings

- Querying nested fields in MongoDB documents.
- Combining multiple filtering conditions with implicit `AND` and explicit `OR`.
- Using comparison operators such as `$gte` and `$lte`.
- Applying regular expressions to filter text fields.
- Building aggregation pipelines with `$match` and `$group`.
- Counting documents with `countDocuments()` and grouped records with `$sum`.
- Exploring geospatial data represented in GeoJSON format.

## 📄 Documentation

The `docs/` folder contains the exercise report, including query explanations, results, and screenshots.

The `data/` folder documents the datasets used in the exercises. Original datasets are not included in this public repository.

## 👩‍💻 Author

Data Analytics student at Barcelona Activa IT Academy, with a background in Finance and an interest in using data to support business analysis and decision-making.
