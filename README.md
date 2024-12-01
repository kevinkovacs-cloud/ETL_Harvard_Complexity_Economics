# ETL_Harvard_Complexity_Economics
ETL Project for Harvard's Economic Complexity Database

In the ETL notebook, you’ll find two approaches (one failed and one successful) to extracting the database composed of 60 .dta files. Once loaded, I attempted to merge them but encountered an error due to differing data types across columns. I iterated through each file to identify and fix these issues. Finally, I exported two datasets: one containing all countries and another focused on countries of interest for analysis (Argentina, Brazil, Indonesia, Thailand, South Korea, and Malaysia). Both datasets include six selected products from international trade in the secondary sector.

In the ETL2 notebook, I performed data transformation processes to calculate total values for each country.
