# Realysis  

## Overview  
**Realysis** is a web application designed to help business owners analyze customer reviews efficiently. Users can upload an Excel spreadsheet containing customer reviews, and the web app will store this data.  

Future iterations will integrate the **OpenAI API** to analyze customer sentiment, compare business-specific complaints against industry benchmarks, and generate actionable insights.  

### This initial version focuses on:  
- 📂 Establishing a structured database with **scaffolded CRUD pages** for customer reviews and industry data.  
- 🖥️ Implementing a **user-friendly interface** with navigation links, filtering, sorting, and pagination.  
- 🏗️ Preparing the foundation for **future AI-driven analysis and dashboard functionality**.  

---

## Technologies Used  
- **Microsoft Visual Studio Enterprise Edition 2022** (ASP.NET and Web Development workload)  
- **.NET 7.0 Runtime**  
- **C# and ASP.NET Core MVC**  
- **HTML and Razor Pages** for UI  
- **Entity Framework Core** for data management  

---

## Features  
✅ **Scaffolded CRUD Operations** – Full create, read, update, and delete functionality for Reviews and Industries.  
✅ **Navigation & UI Enhancements** – Updated title ("Realysis") and intuitive navigation links (Login, Register, Manage Reviews/Industries).  
✅ **Database Seed Data** – Automatically populates the Industries table with test data when the database is empty.  
✅ **Improved Field Names & URLs** – Uses data annotations for readability and removes unnecessary query strings from URLs.  
✅ **Filtering & Sorting** – Implements a text filter and dropdown selection for data refinement.  
✅ **Data Validation** – Ensures required fields are properly validated in model classes.  
✅ **Related Data Display** – Review details pages show associated user information.  
✅ **Pagination & Sorting** – Enables efficient navigation of large datasets.  

---

## Future Enhancements  
🚀 **AI-Powered Sentiment Analysis** – Integrate OpenAI API to analyze reviews and extract insights.  
📊 **Interactive Dashboard** – Develop visual analytics comparing customer complaints across industries.  
