# Public-Library-Management-System
Database Management System Project (PostgreSQL &amp; PGadmin)


Introduction:

This project is dedicated to the creation of a highly efficient database tailored for a comprehensive library system, with a primary focus on optimizing the management of resources, members, and borrowing operations. The system's core functionality revolves around maintaining extensive records of various library materials, including books, magazines, e-books, and audiobooks. Its design facilitates seamless member interactions, allowing borrowing and reservation of materials while empowering library staff to efficiently oversee resources and assist members.

The entities in the database encompass:

- **Material:** Representing individual library items with attributes such as Material_ID, Title, Publication_Date, Catalog_ID, and Genre_ID.

- **Catalog:** Serving as a record of library materials, with attributes including Catalog_ID, Name, and Location.

- **Genre:** Representing various genres or categories of library materials, featuring attributes like Genre_ID, Name, and Description.

- **Borrow:** Capturing the borrowing activity, with attributes such as Borrow_ID, Material_ID, Member_ID, Staff_ID, Borrow_Date, Due_Date, and Return_Date.

- **Author:** Representing authors of library materials, characterized by Author_ID, Name, Birth_Date, and Nationality.

- **Authorship:** Establishing relationships between authors and materials, defined by Authorship_ID, Author_ID, and Material_ID.

- **Member:** Representing library members with attributes Member_ID, Name, Contact_Info, and Join_Date.

- **Staff:** Representing library staff members, featuring attributes Staff_ID, Name, Contact_Info, Job_Title, and Hire_Date.

The subsequent Entity-Relationship (ER) diagram visually articulates the relationships and attributes of these entities, providing a comprehensive schema for the library management system database. The diagram illustrates the one-to-many and many-to-many relationships, guiding the design and implementation of the database structure for effective management of library resources.
