# Nashville-Housing-Data-Cleaning
This project uses SQL to demonstrate the cleaning and transformation of the Nashville housing dataset. The process includes:
- Standardizing date formats.
- Populating missing property addresses using self-joins.
- Splitting addresses into separate columns (Address, City, State).
- Updating values in categorical fields (e.g., "Y" and "N" to "Yes" and "No").
- Removing duplicate records.
- Dropping unused columns.

## Key Highlights
1. Standardized `SaleDate` column to `Date` format.
2. Split and extracted parts of addresses for better analysis.
3. Ensured data consistency by updating categorical values.
4. Removed duplicate rows based on key columns.
5. Optimized table structure by dropping unnecessary columns.
