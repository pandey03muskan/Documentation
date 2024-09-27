---
title: "Database Overview"
description: ""
---

# Database
   <span className="mediumFont">With diverse storage products, you can efficiently manage key-value data, transactional data and more.</span>
   <div className="smallFont mediumMarginTop">
   Initializ provides a collection of managed, serverless databases designed to seamlessly integrate with your frontend framework.
   </div>
   <span className="smallFont">
   - **MongoDb** -  A document-oriented database.
   - **Postgresql** - A relational database that also supports key-value storage.
   - **Redis** -  A key-value store known for its exceptional speed in handling operations with key-value pairs.

   ## Choosing a database
   Selecting the right storage solution depends on your requirements for latency, durability, consistency, and various other factors.

   To assist you in making this decision, we’ve provided a table below that summarizes the benefits of each storage option in relation to one another.
   

   |  Features  |  MongoDB                                                  |  PostgreSQL                                                 |  Redis                                              |
|------------|-----------------------------------------------------------|-------------------------------------------------------------|-----------------------------------------------------|
| Read Time  | Fast For simple queries;can vary for complex aggregation. | Generally fast optimized for complex queries.               | Extremely Fast(in memory)                           |
| Write Time | Fast write operation;handles high write load well         | Moderate ; optimized for ACID compliance                    | Extremely Fast(in memory)                           |
| Use Cases  | Document storage, real time analytics, content management | Relational data,complex quries, transactional applications  | Caching,real time analytics, session management     |
| Limits     | Size limit of 16 MB per document, horizontal scalability  | Maximum database size of 32TB (varies by version)           | Limited by available memory (data stored in-memory) |




   ## Access the Database tab 
   To access the database tab, select the "Database" option in the sidebar. This section provides a comprehensive list of existing databases, including the database name, status, workspace (where the database was created), creation time, and type of database. To view detailed information about a specific database, simply click on its entry.

         ![create_app](/assets/Database/Database_access.png)

   </span>






