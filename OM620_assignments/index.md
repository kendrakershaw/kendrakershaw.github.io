# OM 620 Assignments

[Click to view the project notebooks and data](https://github.com/kendrakershaw/OM-620-Assignments)

## Assignment 1
This focuses on the data cleaning and preparation of the transaction data. In Python I corrected column names, corrected data types, and missing values. I also engineered a country feature by extracting the country code from manufacturing site codes. 

**Important Findings:**

- Performed data cleaning and data preprocessing, corrected data types.
![screenshot](/assets/img/data_type.png)
- Found 10 transactions with 2,800 day lead time and corrected it to 28 days, assuming it was a data-entry error.
- Corrected about 40,000 negative order quantities to positive values.
- Changed the remaining NA values to "Missing".
- Created a column that tells us if the item is manufactured in the United States, Poland, Canada, or Japan.
- Identified we are working with 368 SKU's, 19 different manufacturing sites, 54 known divisions, and item BB9C0690 has the greatest demand.

## Assignment 2
This focuses on make to stock (MTS) items and calculating the safety stock for each SKU.

**Important Findings:**
- Calculated the service level coefficients for 75%, 90% and 95% with a standard normal distribution.
![screenshot](/assets/img/ss_calculation.png)
- Calculated the safety stock for each SKU at all 3 service levels.
- Identified which SKU's have highest and lowest safety stock, as well as the average.


  **Safety Stock = Service Level Coefficients x Standard Deviation of Order Quantity x Square Root of Average Lead Time**
  
