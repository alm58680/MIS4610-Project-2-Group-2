# MIS4610 Project 2
## Team Name:
24182 Group 2

## Team Members:
1. Andrew Macri 
2. Zach Schiller
3. Irene Jacob
4. Alex Tumen
5. Fawazz Mohdraji

## Description of dataset:
Our dataset focuses on recalls of food and dietary supplements and was obtained from the official FDA website (https://www.fda.gov/safety/recalls-market-withdrawals-safety-alerts). The dataset contains 898 rows and 7 columns, offers comprehensive details regarding recalled products and the causes of such recalls. It includes a range of dimensions with various data kinds that enable insightful analysis. Specifically, the dataset contains the date and time the recall was started, the brand name linked to the product, a comprehensive product description, the product type (such as food, medications, or cosmetics), the reason for the recall (such as contamination or mislabeling), the company in charge of the product, and whether the recall has ended or is still ongoing.  All things considered, this dataset's combination of categorical and time based characteristics allows for the examination of recall trends over time as well as comparisons between product categories, businesses, and recall causes, which helps shed light on trends pertaining to dangers to public health and food safety.

## Question 1:
Question: Are there noticeable spikes or seasonal patterns in food and product recalls and terminations over time, and what might explain these fluctuations?

<img width="1250" height="742" alt="image" src="https://github.com/user-attachments/assets/3a3d566e-0167-4962-b447-79a2555da2b4" />


Importance: Our graph shows the number of food and product recalls over time, along with how many of those recalls were terminated. From the graph we can see that the amount of items recalled is relatively low and stable in earlier years. However starting in around 2023-2024, the amount of recalls starts to spike exponentially. This was super clear in February 2024 when there were a total of 34 recalls. This shows that in this period there are safety issues or regulatory actions that became more frequent. Additionally,. Terminated recalls follow the same pattern, though at a lower level, which suggests that as recall activity increases, more cases are also being resolved or closed out.

The graph also suggests that the spikes don’t appear randomly and suggest seasonal patterns in recall activity. For example, it’s very clear that in recent years there has been higher recall counts which could be driven by stricter regulatory support, improvements in reporting systems, or external factors such as supply chain disruptions. Additionally, in each year there are fluctuations which could be tied to seasonal production cycles in the food industry, where certain products are more widely produced during a specific time (ex: more hot chocolate produced in winter season). After doing additional research, we concluded that a main reason for the spike in recalls was the COVID-19 pandemic, which affected the entire world from 2019 to 2022. After the pandemic subsided, research shows that government agencies took regulatory matters more seriously, which led to an increase in recalls. Overall, the graph highlights that recall activity isn’t constant over time and that understanding these spikes can help regulators and companies better prepare for periods of higher risk.

Source: https://www.governing.com/management-and-administration/why-have-there-been-so-many-food-recalls-recently#:~:text=This%20gray%20area%20is%20where,safety%20practices%2C%E2%80%9D%20he%20said.


## Question 2:
Question: What product categories and recall reasons occur most frequently? Based on the results from Question 1, which showed a spike in recalls from late 2023 to early 2024, we wanted to examine whether these same categories and reasons followed a similar trend.

<img width="632" height="422" alt="Screenshot 2026-04-27 at 2 27 10 PM" src="https://github.com/user-attachments/assets/85bd8bd9-7678-4d4e-9441-c8965759c644" />
Importance:
The graph highlights the most frequent recalled product categories and their recall reasons. Based on the data Food & Beverages clearly account for the highest number of recalls compared to other categories such as Animal & Veterinary and Drugs. Within Food & Beverages, the most common recall reasons are because of contamination and labeling issues, particularly Salmonella, Listeria monocytogenes, and undeclared allergens like milk, eggs, and sesame. Similarly, in the Animal & Veterinary category, recalls were often because of Salmonella contamination and potential foodborne illness risks. Overall, contamination and undeclared allergen labeling were the dominant cause across all categories, which indicated that food safety risk and labeling accuracy are the biggest drivers behind the majority of product recalls. 

<img width="475" height="590" alt="Screenshot 2026-04-27 at 2 27 21 PM" src="https://github.com/user-attachments/assets/78187dd7-f513-4966-93b0-47461dc4fe0b" />



Importance:
Here, we narrowed it down to our two most common recall reasons and wanted to see if they also followed the same overall trend. As gathered from the first graph, the two most common recall reasons were undeclared milk and Salmonella. We created two separate line graphs to see if it will show any spikes throughout the 2020s. What we found was that Salmonella and undeclared milk do contribute to the current trend of a strong uptick in FDA recalls around early 2024. While both increase after 2023, Salmonella has a higher uptick in recalls between the two and we may know the reason why. Historically, salmonella has been a high risk in poultry and illness from salmonella has been an issue for a while. Therefore, as an effort to reduce Salmonella illness in the US, the U.S. Department of Agriculture’s (USDA) Food Safety and Inspection Service (FSIS) announced that it will be declaring Salmonella as an adulterant in breaded and stuffed raw chicken products. This was announced in late 2022, and continues with the trend of an increase in regulations after the pandemic. According to the USDA, “By declaring Salmonella an adulterant in these products, FSIS will be able to ensure that highly contaminated products that could make people sick are not sold to consumers.” This means an increase in Salmonella recalls will occur after 2022 and will probably continue to rise as an effort to reduce foodborne illness. Without knowing the context, one might see the uptick as a bad thing, as manufacturers are being more careless with their products. In reality, with an increase in policies and regulation, it was to help manufacturers keep a high standard with their products and reduce foodborne illness. 

Source: https://www.usda.gov/about-usda/news/press-releases/2022/08/01/usda-announces-action-declare-salmonella-adulterant-breaded-stuffed-raw-chicken-products 

## Manupulations applied to the data set for analysis:
The data set needed to be standardized, but no data manipulation was required. The goal of a standardized data set is to convert unprocessed data into information that can be used for analysis. We have measurable, quantifiable data that meets the criteria for meaningful, interpretable data, therefore our data fulfills that description. Additionally, none of the information in our data is redundant, unnecessary, incorrect, or of poor quality. Additionally, we have cleaned the data, removing any false, irrelevant, or incomplete information. In addition to all of this, our data has been structured and is free of external imports.

## Tableau packaged workbook:
The packaged workbook containing the visualizations shown above is attached to this repository.
