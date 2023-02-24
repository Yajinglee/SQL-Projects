
# About this project

This project aims to use SQL queries to explore the DVD rental dataset to gain an understanding of inventory level, consumer behavior, store sales and performance.

Dataset was connected in MySQL Workbench, and then Jupyter Notebook was set up to access data from MySQL databases by loading the sql magic jupyter notebook extension.
# Sakila Database

The Sakila database is a nicely normalised schema modelling a DVD rental store, featuring things like films, actors, film-actor relationships, and a central inventory table that connects films, stores, and rentals.

The Sakila MySQL sample database is available from http://dev.mysql.com/doc/index-other.html. 


## Sakila Database Entity Relationship Diagram(ERD)

<img src="https://www.jooq.org/img/sakila.png">


## Problem Description
   
- **Inventory summary**:
    - What's the total value of all the inventory and total inventory value of each store?
    - How many film are there in each category of each store, and the total inventory count?
    - How many films are there in each rating?
    - How's the film inventory level looks like?
    - Which actor/actress is in the most films in store inventory?

        
- **Consumer behavior**:
    - How many days do customer usually rent?
    - Do customer usually rent on weekdays or weekends?
    - What are the top films that customers rented for the longest days accumulatively, and rented for the most times?
    - Among the films that rented most frequently, are they usually rented on weekday or weekends?
    - What is the average rental period?
    - Which genres are most popular? 
    - Who are identified as loyalty customers?
    - Were there customers who did not return the film?
    - Which actors/actresses are most popular given our rental history?
    

- **Store performance**:
    - How many stores are there and how many staff in each store?
    - What's the number of transaction each month for both store?
    - Which store has more customer rented the film?
    - Which store makes the most money? 
  
  
- **Sales summary**:
    - What's the total revenue for the time period and for each month?
    - What's the most profitable move genres/rating?
    - Do we make the most money from long or short rentals?
