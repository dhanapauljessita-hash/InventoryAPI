# Inventory Management Web API System

An enterprise-grade, high-performance inventory tracking backend engine built natively using **C#**, **.NET 8/9**, and **Entity Framework Core** with relational database persistence.

## 🚀 Key System Features
* **RESTful CRUD Operations:** Secure endpoints designed to track live warehouse assets, product inventory, and stock parameters.
* **Database Resiliency:** Configured with decoupled Entity Framework Core mappings linked to a production SQL Server database layer.
* **Data Validations:** Robust business domain model assertions preventing illegal input sequences, inventory overflow, or critical null metrics.
* **Asynchronous Operations:** All computational database tasks and query expressions follow efficient `async/await` processing routines to scale request concurrency.

## 🏗️ Technical Stack & Architecture
* **Language & Core Runtime:** C# (.NET 8.0 / 9.0 Web API)
* **Data Access Framework:** Entity Framework Core (EF Core) 
* **Database Storage:** Microsoft SQL Server
* **Design Strategy:** Repository Pattern & Asynchronous Query Processing Flow

## 🛠️ Step-by-Step Local Installation Setup
1. **Clone the project repository to your machine:**
   ```bash
   git clone https://github.com
   cd InventoryAPI
   ```
2. **Apply Database Migration Scripts:**
   Open Visual Studio Package Manager Console and run:
   ```bash
   Update-Database
   ```
3. **Execute the Backend API Engine:**
   ```bash
   dotnet run
   ```
   Open `http://localhost:5000/swagger` in your local web browser to execute and test all integrated relational controller endpoints.
