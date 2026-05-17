# MIS_311
# 🔍**DATA OVERVIEW**
   ## Context:
   Market analysis of used car listings to understand pricing drivers and trends.
   ## Data Source: 
   The valuable data was collected through the used car market.
   ## Dimensions: 
   Data includes 187 rows(where duplicates were removed and missing values were processed), and 9 columns
   ## Attributes:
   - Brand(Brand name)
   - Model(Specific model of cars)
   - Year(Year manufactured)
   - Km/h (int): Amount of distance moved
   - Type (object): Automatic or manual car
   - Fuel (object): Type of engine fuel
   - Price (int): price of the car
   ## Columns:
   - Brand
   - Model
   - Year
   - Km/h 
   - Type
   - Fuel
   - Price
# 🪄**DATA CLEANING**
   ## Missing Value: 
   Initial data was cleaned and processed to ensure accuracy and high performance, providing meaningful insights.
   ## Duplicate Rows: 
   The dataset was further audited for redundancy. A total of 5 duplicate records were identified and removed. This step        ensures that data runs accurately and avoids mistakes. After removing duplicate rows, 187 rows remain to analyze.
   ## Detach Value: 
   The initial row name "Model" was used for the formula to detach the value into 2 rows, named "Brand" and "Model."
# 🧩**DESCRIPTIVE DATA**
   ## Descriptive statistics
      - The average vehicle in the dataset was manufactured in 2016, with a median price of 750,000.
      - The average mileage is about 119,000 km, with some vehicles reaching as high as 500,000 km. This suggests that many cars in the dataset have been extensively used but are still actively traded in the market
   <img width="510" height="253" alt="{BF16C9D3-D70F-4BD0-85BC-1B2EA8AF16EC}" src="https://github.com/user-attachments/assets/d62d17d4-f2ec-42df-bb6a-7c69c57140f3" />
   
   ## 🔑Key Insight
   ### Insight 1: Mostly resale cars belong to the automotive type.
   <img width="366" height="122" alt="{B34307D6-36CD-4A7B-956E-B5016B10866E}" src="https://github.com/user-attachments/assets/03db6cd4-a07b-40d4-bb9d-721fbfd1f7ee" />
   <img width="403" height="348" alt="{5FD829C8-CC10-4CCB-8FB7-9E594DFC2BB3}" src="https://github.com/user-attachments/assets/215ee22a-bb13-450a-9d78-052539c12975" />
   
- Automatic transmission accounts for 87.2% of all vehicles, and all cars in the dataset use gasoline engines. This indicates that the used car market is heavily concentrated around automatic gasoline vehicles, reflecting strong consumer preference for convenience and conventional fuel technology. Dealers and sellers should prioritize this vehicle type because it aligns closely with prevailing market demand.

  ### Insight 2: KIA and Hyundai are two of the most popular resale brands of cars.
   <img width="1064" height="498" alt="{4BD86D51-A3AB-47B8-AEA2-DA1EC4A8D74A}" src="https://github.com/user-attachments/assets/fc1468a8-a23a-4cad-8463-2ad76a65c4be" />
   - It can clearly be seen that Kia and Hyundai have the highest number of used prices on the market. It shows that these are popular brands that many families choose to buy.
     <img width="849" height="386" alt="{8A7C26AC-3863-426F-8943-416F03EB84F0}" src="https://github.com/user-attachments/assets/a0ae6164-42f6-4127-9a29-05344519752d" />
   - About Hyundai, Accent, Elantra, and Verna are the top 3 models that have the highest sales.
     <img width="826" height="392" alt="{8882324E-DACF-4F0E-A834-85133A5A36DB}" src="https://github.com/user-attachments/assets/633519fb-e8f7-428d-8e25-69f014c0dd6c" />
   - About KIA, Cerato, Picanto, and Sol are the top 3 models that have the highest sales.
# RECOMMENDATION
- Used car dealers should prioritize stocking automatic vehicles, particularly popular models from Kia and Hyundai, to better match customer preferences and improve sales performance. Buyers looking for reliable and affordable used cars should also consider these brands due to their strong market presence and resale value.
# CONCLUSION
- Automatic transmission vehicles account for 87.2% of the dataset, indicating a strong consumer preference for convenience and ease of driving. In addition, Kia and Hyundai are the most common brands, suggesting they have strong resale demand and popularity in the used car market.
