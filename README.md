# StockApp
A lightweight .NET Web API that exposes endpoints to view stock profiles (company info, fundamentals). Built with ASP.NET Core, Entity Framework Core (Code-First), SQL Server, and Swagger UI for interactive exploration.

Features
-RESTful endpoints to list/get stock profiles (with optional search & paging)
-EF Core (Code-First) with migrations, seeding, and repository pattern
-SQL Server as the data store
-Swagger UI for live docs & try-it-out requests
-Input validation, problem details, and sensible HTTP status codes
Tech Stack
-.NET 7 (or .NET 6)
-ASP.NET Core Web API
-Entity Framework Core (SqlServer)
-SQL Server (SQL on Docker/Azure Data Studio)
-Swashbuckle/Swagger

API Endpoints
GET    /api/stocks          # List stocks 
GET    /api/stocks/{id}     # Get a single stock by id 
POST   /api/stocks          # Create a stock profile
PUT    /api/stocks/{id}     # Update a stock profile
DELETE /api/stocks/{id}     # Delete a stock profile
