# GeneralKnowledges

# Code first, Database First and Model First
  * Questions
    
    1. Code First = Already have Existing Domain Classes
    2. Database First = Existing Database
    3. Model First = Prefer Visual Designer for Data Modeling

# EF Core Vs Dapper
  1. Abstraction
     
    EF Core

    1. underlying database structure
    2. working with your data using Object-oriented approach
    3. eaiser to work with complex data Model

    Dapper

    1. more control over SQL queries to optimize the performance.
    2. lightweight ORM that provides minimal abstraction over your database.

   2. Performance
      
      Some Case, EF Core is faster than Dapper. But Dapper is less abstraction and can faster than EF core when executing complex queries.
      Update and Delete queries are more powerful in Dapper.

      Note: EF8 support Raw sql queries. So, performance is similar to Dapper.

   3. Features
      
     EF Core

      1. Linq queries
      2. Migrations
      3. Mulitple database providers (Can change any database like mysql,ssms, oracle with connnection string without changing the queries)
      4. Change tracking (unit of work)

     Dapper

      1. focused tools designed for working with SQL databases.
      2. can execute stored procedure.

# DC (Data Center) vs On-Premise Server
  1. Data Center  - may be private data center or third party provider (Cloud)
  2. On-Premise Server - local server that located withing the premises of organization.
      
