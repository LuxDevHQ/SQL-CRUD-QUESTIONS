#### SQL Practice Questions on food_prod Table

Below are 16 SQL-based questions designed to help you practice all CRUD (Create, Read, Update, Delete) operations using the food_prod table.

1. CREATE Operations

a. Insert a new record for Maize harvested on 2025-05-10, including quantity harvested, average temperature, rainfall amount, soil pH level, pesticide used, organic certification, market price per kg, and export destination.

b. Insert two different crop records (e.g., Wheat and Tea) into the table with different export destinations and organic certifications.

2. READ Operations

a. Retrieve all details of the food_prod table.

b. List all organic-certified crops that are exported to France.

c. Display the crop type and quantity harvested for all entries harvested after January 1, 2025.

d. Show the top 3 crops with the highest market price per kg.

e. Find all crops that used no pesticide.

f. Count the total number of records in the food_prod table.

g. Retrieve the average market price for each export destination.

h. List all records where the soil pH level is below 5.5 and not organic certified.

i. Identify crops with quantity harvested greater than 1000 kg and exported to countries starting with the letter G.

3. UPDATE Operations

a. Update the market price per kg to 50.00 for all Maize crops harvested before 2025-01-01.

b. Change the organic_certified status to "No" where pesticide_used is not null.

c. Update the export destination to "Local" for all records where the market price per kg is below 20.00.

4. DELETE Operations

a. Delete all records where the harvest date is before the year 2023.

b. Remove all records where quantity harvested is null or equal to zero.
