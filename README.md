# Framework-Persistence-Simulator
This is a school mini-project, realized in order to get familiar with advanced Java tools and frameworks.

----------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------

The goal of this mini project is to create a simulator that measures Framework Persistence, such as: 
 - JDBC: Java Database Connectivity
 - DAO: Data Access Object Patten
 - Hibernate

The goal is to measure through a series of creation, update and removal operations the fastest framework.

The simulator will be driven by a main class that will use the Thread mechanism to randomly launch CRUD (Create-Read-Update-Delete) operations.

The result of each operation (Operation, execution time and Thread) will be stored in a collection that will support the Thread context.
Once measured, the total and average time for each Framework will be stored in a text file.

Finally, the text files will be analyzed to detect the best optimal framework.


----------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------

project realized By:
        - EL KHAOUI MAROUA
        - TAIFOUR MOUAD
        - AZOUGAY R'KIA
