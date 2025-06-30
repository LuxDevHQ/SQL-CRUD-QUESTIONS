# SQL Practice Questions for food_prod Table

## 1. CREATE Operations

### a. Insert new Maize record
Insert a new record for Maize harvested on 2025-05-10. Include all required fields such as quantity harvested, average temperature, rainfall amount, soil pH level, pesticide used, organic certification, market price per kg, and export destination with appropriate sample values.

### b. Insert multiple crop records
Insert two separate records for Wheat and Tea crops with different export destinations and organic certification statuses. Ensure each record has complete information including harvest dates, environmental conditions, and market details.

## 2. READ Operations

### a. Retrieve all table data
Display the complete contents of the food_prod table showing all columns and rows.

### b. Filter organic crops by region
List all crops that are organic-certified and destined for export to European countries.

### c. Recent harvest data
Show only the crop type and quantity harvested for all entries that were harvested after January 1, 2025.

### d. Highest value crops
Identify and display the top 3 crops with the highest market price per kilogram.

### e. Pesticide-free crops
Find and display all crop records where no pesticide was used during cultivation.

### f. Record count
Calculate and display the total number of records currently stored in the food_prod table.

### g. Price analysis by destination
Calculate the average market price for crops grouped by their export destination.

### h. Acidic soil conditions
Retrieve all records where the soil pH level is below 5.5 and the crop is not organically certified.

### i. High-volume exports to specific regions
Identify crops with quantity harvested greater than 1000 kg that are exported to countries whose names start with the letter 'G'.

## 3. UPDATE Operations

### a. Price adjustment for older Maize
Update the market price per kg to 50.00 for all Maize crops that were harvested before January 1, 2025.

### b. Organic certification correction
Change the organic certification status to "No" for all records where pesticide was used during cultivation.

### c. Local market redirection
Update the export destination to "Local" for all records where the market price per kg is below 20.00.

## 4. DELETE Operations

### a. Remove outdated records
Delete all records where the harvest date is before the year 2023.

### b. Clean invalid quantity data
Remove all records where the quantity harvested is either null or equal to zero.

---

**Practice Tips:**
- Start with simple SELECT statements before attempting complex operations
- Always backup your data before running UPDATE or DELETE operations
- Use WHERE clauses carefully to avoid unintended modifications
- Test your queries with small datasets first
- Consider using transactions for multiple related operations
