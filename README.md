Project Details -
1. Housing data standardization and enhancement project -
### 1. **Data Cleaning and Standardization:**
   - Developed SQL queries to standardize date formats in the Nashville Housing dataset.
   - Utilized the `CONVERT` function to transform date columns.
   - Handled cases where updates did not proceed smoothly by implementing additional steps.

### 2. **Address Data Enhancement:**
   - Populated missing property addresses by merging data from similar records.
   - Segregated address details into individual columns (`Address`, `City`, `State`) for improved clarity and analysis.
   - Demonstrated proficiency in string manipulation functions (e.g., `SUBSTRING`, `CHARINDEX`, `LEN`).

### 3. **Owner Address Parsing:**
   - Extracted components (address, city, state) from the `OwnerAddress` field using `PARSENAME` and `REPLACE` functions.
   - Created separate columns for parsed owner address details (`OwnerSplitAddress`, `OwnerSplitCity`, `OwnerSplitState`).

### 4. **Data Transformation:**
   - Transformed binary data in the "Sold as Vacant" field to user-friendly values ('Yes', 'No').
   - Utilized `CASE` statements for conditional transformations.

### 5. **Duplicate Handling:**
   - Implemented a Common Table Expression (CTE) to identify and handle duplicate records based on multiple criteria.
   - Utilized the `ROW_NUMBER()` window function to assign row numbers for duplicates.

### 6. **Column Removal:**
   - Deleted unused columns to streamline the dataset.
   - Executed SQL statements to drop specific columns (`OwnerAddress`, `TaxDistrict`, `PropertyAddress`, `SaleDate`).

### 7. **Data Import Strategies:**
   - Demonstrated knowledge of different data import methods, including `BULK INSERT` and `OPENROWSET`.
   - Provided commented-out scripts for using advanced import techniques, such as importing data from an Excel file.

### 8. **Documentation:**
   - Documented each section of the script using comments, enhancing readability and understanding for others.

### 9. **Database Manipulation:**
   - Executed ALTER TABLE statements to add new columns for data manipulation purposes.

### 10. **Technical Skills:**
   - SQL, T-SQL, Database Management

### 11. **Tools:**
   - Microsoft SQL Server Management Studio (SSMS)

### 12. **Best Practices:**
   - Demonstrated adherence to best practices in data cleaning and manipulation.

### Example Bullet Points for Resume:

- Implemented SQL queries for standardizing date formats and ensuring data consistency.
- Enhanced data quality by populating missing property addresses through strategic merging.
- Employed advanced string manipulation techniques to separate address components (Address, City, State).
- Utilized CASE statements for transforming binary data into user-friendly values ('Yes', 'No').
- Applied Common Table Expression (CTE) and ROW_NUMBER() for identifying and handling duplicate records.
- Demonstrated proficiency in data import strategies, including BULK INSERT and OPENROWSET.
- Streamlined datasets by removing unused columns through ALTER TABLE statements.
- Documented and commented on each section of the SQL script for enhanced readability.
- Applied best practices in database manipulation, ensuring efficiency and data integrity.
