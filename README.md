Overview

This project is a Multi-Tenancy implementation in .NET 8, utilizing Entity Framework Core with a dynamic database connection per tenant. It is designed to support multiple tenants with isolation at the database level.

Features

Dynamic Database Connection: Configures the database connection based on the tenant.

Tenant-Specific Data Filtering: Applies a global query filter for tenant-based entity separation.

Middleware-Based Tenant Resolution: Uses middleware to determine the tenant from the request.

Supports Multiple Database Providers: Can be configured to work with SQL Server, PostgreSQL, or other providers.

Authentication & Authorization: Secure access to tenant-specific resources.

EF Core Support: Uses Entity Framework Core for ORM operations.

Technologies Used

.NET 8

ASP.NET Core

Entity Framework Core

 SQL Server 

Dependency Injection

Middleware
