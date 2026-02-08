# Introduction to databases and SQL

Designing effective databases is a crucial step in software development, all software requires somekind of a database to save and retrieve information from. If the database isn't designed based on the requirements of the software system you can run into unwanted errors and issues like disorganized data or queries that take too long and too many resources to run which make using your software a bad experience for the user. If you're database is built based on the system's requirements and in an effective manner it could make using the software a pleasant experience for the user.

If you only need to store small amounts of data, you can use a spreadsheet like Excel as the tables in which a relational database stores data is similar to that of a spreadsheet. Databases are a solid choice when you need to implement access control and maintain the consistency and integrity of the data while making sure the data storage is scalable.

## Relational Databases

A relational database is a collection of tables, each representing an entity or a relationship between entities, with each row representing a single data record of that entity and each column representing an attribute of that entity.

> [!NOTE]
> An entity is an object or concept that can be described by many attributes. Like a car or a book.

A simple table that lists the products of a store can have the following the columns

- Name
- Price
- Manufacturer
- Description

In addition to these four columns, we add another column named id or product_id, all values in the product_id column are unique and can be used to identify an individual row. In a proper relational database, we would have 2 more columns for our customers and to keep track of orders. The relations between these 3 tables can be visualized as such:

$$
\text{Customer} \xrightarrow{1:1} \text{Order} \xrightarrow{1:n} \text{Product}
$$

## Relational Database Management Systems

A relational database management system is a tool to manage relational databases, the first RDBMS was devloped by Edgar Codd at IBM in 1970

An RDBMS is a software that allows you to interact with the underlying hardware and operating system to physically store and manage data in relational databases using tools that it provides to create, modify, and query databases along with security controls.

The most important tool in an RDBMS is SQL, the programming language for relational databases. Different database vendors have different syntax for SQL but the core features of the language remain same all across.

![[rdbms_flow.webp]]

