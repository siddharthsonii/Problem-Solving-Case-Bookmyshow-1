## **Objective:**

Bookmyshow is a ticketing platform where you can book tickets for a movie show. The image attached represents that for a given theatre we can see the next 7 dates. As one chooses the date, we get list of all shows running in that theatre along with the show timings.

## **Problem 1:**

As part of this assignment, we need to list down all the entities, their attributes and the table structures for the scenario mentioned in the previous slide. You also need to write the SQL queries required to create these tables along with few sample entries. Ensure the tables follow 1NF, 2NF, 3NF and BCNF rules.

# BookMyShow Ticketing Platform Database Design

## Entities and Attributes:

1. **Theatre:**
   - TheatreID (Primary Key)
   - TheatreName
   - Location

2. **Movie:**
   - MovieID (Primary Key)
   - MovieName
   - Genre
   - Language

3. **Show:**
   - ShowID (Primary Key)
   - TheatreID (Foreign Key referencing Theatre)
   - MovieID (Foreign Key referencing Movie)
   - ShowDate
   - ShowTime

4. **Booking:**
   - BookingID (Primary Key)
   - ShowID (Foreign Key)
   - UserID
   - BookingDate
   - TotalSeats
   - Amount

5. **User:**
   - UserID (Primary Key)
   - UserName
   - Email
   - Phone

All other Queries were added in the Doc.

## **Problem 2:**

Write a query to list down all the shows on a given date at a given theatre along with their respective show timings.

- All Queries were added in the Doc.

