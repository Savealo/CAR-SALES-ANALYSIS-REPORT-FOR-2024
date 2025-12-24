# CAR-SALES-ANALYSIS-REPORT-FOR-2024
INTRODUCTION

Objective of the Project
To analyze car sales data in order to understand how vehicle specifications, pricing, and performance characteristics influence sales volume and market competitiveness across different automobile manufacturers.
Problem Being Addressed
The core problem addressed by this dataset is:
What vehicle features and specifications most influence car sales performance and pricing across different manufacturers and models?
More specifically, the data set helps answer:
•	How do engine size, horsepower, and power performance affect sales volume?
•	What is the relationship between vehicle price and fuel efficiency?
•	Which manufacturers and models achieve the highest sales?
•	How do vehicle dimensions (length, width, wheelbase) relate to market performance?
•	Are higher-priced vehicles justified by better performance and specifications?
•	How do fuel capacity and efficiency impact consumer demand?
Answering these questions helps manufacturers, dealers, and analysts optimize vehicle design, pricing strategies, inventory planning, and market positioning.

Key Datasets
The project utilizes a Car Sales dataset that contains detailed information on automobile manufacturers, vehicle models, sales performance, pricing, and technical specifications. Each record represents a distinct car model, allowing for comparison across brands and categories.
Dataset Components
1. Manufacturer & Model Information
•	Manufacturer: Name of the automobile manufacturer (e.g., Acura, Audi, BMW).
•	Model: Specific vehicle model produced by the manufacturer.
2. Sales Performance Data
•	Sales in thousands: Total number of vehicles sold, measured in thousands of units.
•	Year resale value: Estimated resale value of the vehicle after a period of use.
3. Pricing Information
•	Price in thousands: Market price of the vehicle, expressed in thousands.
4. Vehicle Classification
•	Vehicle type: Category of vehicle (e.g., Passenger car).
5. Engine & Performance Specifications
•	Engine size: Engine displacement size.
•	Horsepower: Power output of the engine.
•	Power perf factor: Composite index measuring overall vehicle performance.
6. Vehicle Dimensions & Weight
•	Wheelbase: Distance between the front and rear wheels.
•	Width: Overall width of the vehicle.
•	Length: Overall length of the vehicle.
•	Curb weight: Weight of the vehicle without passengers or cargo.
7. Fuel Characteristics
•	Fuel capacity: Maximum fuel tank capacity.
•	Fuel efficiency: Indicator of fuel consumption or mileage.
8. Time Variable
•	Latest Launch: Date the vehicle model was introduced to the market.

STORY OF DATA
This dataset represents a collection of automotive data combining sales performance, vehicle specifications, and market value retention. It provides insights into how car features and launch timing affect sales performance and resale value. The dataset can help uncover trends in consumer preferences, manufacturer performance, and market dynamics in the automotive industry.
Data Source: The data was obtained from Kaggle.com
Data Collection Process: This data was obtained from Kaggle.com 
Data Structure: The data contains 158 rows with each representing a distinct transaction and 16 columns representing Manufacturer, Model, Sales in thousands, Year resale value, Vehicle type, Price in thousands, Engine size, Horsepower, Wheelbase, Width, Length, Curb weight, Fuel capacity, Fuel efficiency, Latest launch, and Power performance factor.

Data Limitations or Biases
1.	Incomplete or missing values
Some variables, such as year resale value or sales figures, may contain missing entries, which can affect the accuracy of analysis and reduce the reliability of conclusions.
2.	Limited time coverage
The dataset represents vehicle models launched within a specific period, limiting the ability to analyze long-term trends or changes in consumer preferences over time.
3.	Geographical bias
The data appears to reflect sales from a specific market or region, which may not accurately represent global automobile sales patterns.
4.	Model-level aggregation
Sales data is aggregated at the model level, which masks variations across different trims, regions, or dealership-level performance.
5.	Exclusion of external factors
Important influences such as marketing expenditure, economic conditions, fuel prices, and consumer income levels are not included, potentially biasing sales-performance interpretations.
6.	Price variability not captured
Listed prices may not reflect discounts, promotions, or dealer incentives, leading to potential inaccuracies when analyzing price–sales relationships.
7.	Measurement bias in performance indicators
Composite metrics like power performance factor may be based on predefined formulas that favor certain vehicle types over others.
8.	Survivorship bias
Vehicles included in the dataset are mostly successful or notable models, which may underrepresent discontinued or poorly performing models.
DATA SPLITTING AND PREPROCESSING
Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. 
To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”. 
To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to  “Go to Special” and select “Blanks”, finally click on OK. 
Handling Missing Values: There are no missing values in the data.  
Data Transformations: No data transformations were performed. 
Tool used: TABLEAU








DATA SPLITING

Independent data
Manufacturer
Model
Vehicle_type
Price_in_thousands
Engine_size
Horsepower
Wheelbase
Width
Length
Curb_weight
Fuel_capacity
Fuel_efficiency
Latest_Launch
Power_perf_factor

Dependent Data
These are the variables we may aim to predict or explain:
Sales_in_thousands
year_resale_value

Industry Type
Industry: Automotive
Sector: Manufacturing & Retail (Automobile Sales & Marketing)


  Stakeholders for the project
Car dealers, Car manufactures and manufacturing companies, Stakeholders. 
  What Success Means in This Industry
Success in the automotive industry, as reflected in this data, is likely defined by:
Higher Sales in thousands
Strong Resale value (good value retention)
Competitive performance metrics (Power performance factor, Horsepower, Fuel efficiency)
Optimal product-market fit (vehicle specs align with market demand)





PRE-ANALYSIS

Potential Analysis Questions and insights 
1.	Sales & Market Performance
•	Top / bottom sellers: Rank sales by manufacturer and model to see which products drive or drag overall volume.
•	Sales by vehicle type: Compare sales across vehicle types to identify the strongest and weakest segments.
•	Sales per model: Calculate average sales per model for each brand to measure how efficiently each lineup performs.
2. Pricing & Demand
•	Price vs. sales: Analyze whether higher prices reduce sales or if some price bands sell best.
•	Premium justification: Check if higher prices are backed by better specs or mainly by brand power.
3. Performance & Engineering
•	Engine power relationship: Examine how engine size, horsepower, and performance factor move together.
•	Power vs. efficiency: Quantify how much fuel economy is sacrificed as performance increases.
•	Size vs. power: Test whether larger/heavier cars receive proportionally more power or feel underpowered.
4. Fuel Economy & Capacity
•	Size/weight vs. fuel economy: See how vehicle dimensions and curb weight impact fuel efficiency.
•	Tank size vs. range: Compare fuel capacity with efficiency to identify models with unusually short or long driving range.
5. Resale Value & Total Cost of Ownership
•	Best value keepers: Rank models by resale value relative to purchase price to find the strongest long term value.
•	Price vs. resale percentage: Determine if more expensive cars hold a higher or lower percentage of their value.
6. Brand & Segment Positioning
•	Brand profiles: Summarize each manufacturer’s typical price, performance, and efficiency to define its market position.
•	Within segment positioning: Identify which brands are budget, mid range, or premium inside each vehicle type.
7. Product Portfolio & Gaps
•	Natural segments: Cluster cars into groups (e.g., economy, family, performance, luxury) based on specs and price.
•	White spaces: Detect unserved combinations of price, performance, and efficiency that could be future product opportunities.
8. Outliers & Anomalies
•	Spec strong but sales weak: Flag models with good attributes but poor sales as potential marketing or positioning problems.
•	Spec weak but sales strong: Highlight models that outperform expectations due to brand strength or design appeal.
9. Launch Timing & Lifecycle
•	Freshness effect on sales: Compare sales of newer vs. older launches controlling for specs to gauge lifecycle impact.
•	Resale over time: Assess how quickly resale value drops as models age to inform redesign and replacement timing.







IN-ANALYSIS
IN ANALYSIS OBSERVATIONS AND INSIGHTS
IN ANALYSIS INSIGHTS
Market & Sales Performance
•	Ford is the dominant player: about $45.8K in revenue, more than 2× Dodge and over 3× Toyota among the top 3 manufacturers.
•	By sales volume, Ford (2,023K) leads comfortably, followed by Dodge (910K), Toyota (740K), Chevrolet (554K), and a distant Mercedes B (117K).
•	The Neon model is a clear outlier in performance, generating about $108.8K, far ahead of other highlighted models (300M, 323i, 3 Sep, 3000GT).

Vehicle Type Mix
•	Passenger vehicles generate more revenue ($101.9K) than Cars ($78.1K), indicating stronger commercial weight in the passenger segment.

Launch Timing, Price & Sales
•	Both average price and sales by year of latest launch increase steadily from 2008 to 2012.
•	Newer launches (2011 to 2012) command higher prices and higher sales, suggesting that fresh models are better monetized and more in demand.

Performance (Horsepower & Engine Size)
•	Dodge has the highest total/average horsepower (2.20K) and the largest engine size (0.04K), confirming a strong performance oriented positioning.
•	Ford offers substantial horsepower (1.87K) but not as extreme as Dodge, while Chevrolet has the lowest horsepower (1.54K) of the three shown.
•	Engine size chart (Dodge > Chevrolet > Toyota) reinforces Dodge’s emphasis on larger engines.




Fuel Capacity & Efficiency
•	Chevrolet, Ford, and Toyota show relatively high fuel efficiency with moderate to high fuel capacity, indicating a more balanced design between range and economy.
•	Dodge appears tilted toward larger fuel capacity but comparatively lower efficiency, fitting its large engine, performance profile.
•	Mitsubishi sits lower on both capacity and efficiency, suggesting smaller or more economical models with shorter range.

Combined Brand Story
•	Ford combines highest sales and revenue with mid to high horsepower and efficiency, suggesting a strong all round value proposition.
•	Dodge focuses on powerful, large engine vehicles with strong but not market leading sales more of a performance niche than a volume leader.
•	Passenger segment dominance and the strong performance of models like Neon indicate where most commercial opportunity currently lies.

POST-ANALYSIS AND INSIGHTS
1. Market & Brand Strategy
•	Ford is the clear volume and revenue leader; maintaining this position should focus on protecting core models and ensuring enough production and dealer support.
•	Dodge and Toyota are strong but clearly second tier; they represent the main competitive threat/opportunity. Ford can target their segments specifically with pricing or feature packs.
•	The Neon model is an outlier in revenue; it should be treated as a flagship product (priority marketing, careful inventory and price management).

2. Product & Portfolio
•	Newer launches (2011–2012) both sell more and command higher prices, indicating that refresh cycles directly impact revenue. Aging models are likely dragging performance and should be prioritized for redesign.
•	Dodge’s portfolio is heavily performance oriented (high horsepower and large engines); this creates a gap for efficient but still powerful vehicles where Ford/Chevrolet/Toyota can differentiate.
•	Passenger vehicles generate more total revenue than “Car” category models, so new product development should prioritize passenger type designs and trims.

3. Performance vs. Efficiency Positioning
•	Dodge’s combination of large engines and relatively lower fuel efficiency suggests a muscle/performance brand image; messaging should lean into performance rather than economy.
•	Chevrolet, Ford, and Toyota show a better balance of fuel efficiency and capacity, giving them a stronger position for value and daily use ideal for cost conscious or fleet buyers.

4. Tactical Actions
•	Use Neon’s performance as a benchmark: analyze its price, spec, and marketing mix to replicate its success in adjacent models/segments.
•	For manufacturers with lower horsepower or efficiency but decent sales, explore value added trims or engine upgrades to increase price without heavy redesign.
•	Highlight fuel efficient passenger vehicles in marketing campaigns, as they sit in the largest revenue segment and appear competitively strong.

5. Next Analytical Steps (to strengthen decisions)
•	Incorporate resale value and curb weight/size into the dashboards to understand long term value and true efficiency.
•	Build scatter plots (price vs sales, horsepower vs efficiency) to identify more precise white space opportunities and under/over performing models.


DATA VISUALIZATIONS & CHARTS

1.	BRAND BY SALES

 <img width="975" height="461" alt="image" src="https://github.com/user-attachments/assets/2285fd2d-fb71-4818-b70f-9072f53e2982" />


Ford sells about 2,023K units, accounting for roughly 47% of total sales among these five brands.
Dodge sells 910K units (21% share), and Toyota 740K units (17% share).
Chevrolet contributes 554K units (~13%), while Mercedes B is very small at 117K units (3%).
Ford sells over twice as many units as Dodge and almost four times as many as Chevrolet.









2.	MODEL BY SALES


 <img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/948b192b-64c6-4a5c-bf7a-3fd039e3ae38" />

Neon generates about $108.77K, which is roughly 64% of the total revenue of the top 5 models.
300M brings in $30.70K (18% of the top 5 total), and 323i $19.75K (12%).
3 Sep contributes $12.12K (7%), while 3000GT is almost negligible at $0.11K (less than 1%).
Neon’s revenue is over 3.5× that of 300M and more than 9× that of 323i, making it a standout model.

3.	PRICE & SALES BY YEAR OF LAUNCH


 <img width="975" height="452" alt="image" src="https://github.com/user-attachments/assets/ea2fc6b0-b930-4ccb-adab-e35556557dd3" />

In 2008–2009, both price in thousands and sales in thousands are close to zero, indicating minimal impact from older launches.
From 2010 onward, both lines rise sharply:
2010 shows a big step up, with both price and sales jumping into the hundreds to low thousands range.
By 2011–2012, average prices are above 1,500–2,000 (in thousands) and total sales exceed 4,000 (in thousands).
Newer launch years (2011–2012) command higher prices and higher sales, suggesting that fresh models are significantly more successful.


4. TOP 3 MANUFACTURERS BY REVENUE


 <img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/c6ed88fc-f1d6-4659-aa69-dbfd891a5f0e" />

Ford leads with about $45,776.13,
Dodge follows with $18,000.61,
Toyota has $13,288.56.
Among just these three, Ford holds roughly 59% of revenue, Dodge about 23%, and Toyota 17%.
Ford’s revenue is about 2.5× Dodge’s and 3.4× Toyota’s.



5.	VEHICLE TYPE BY REVENUE


 <img width="727" height="454" alt="image" src="https://github.com/user-attachments/assets/bf5d58ad-b67e-4aa6-b60f-fd0f0c4efe71" />

Passenger vehicles generate roughly $101,911.22 in revenue.
Cars generate about $78,081.08.
Passenger vehicles account for around 57% of combined revenue, with Cars at 43%, showing that Passenger type is the financially larger segment.

6.	FUEL CAPACITY & EFFICIENCY BY MANUFACTURER


 <img width="798" height="454" alt="image" src="https://github.com/user-attachments/assets/17be7cac-8aad-41da-bc98-6575a6cc1e57" />

Chevrolet:
Fuel capacity is around the 140 mark;
Fuel efficiency is near 260, the highest efficiency among the brands shown.
Dodge:
Highest fuel capacity, about 240;
Fuel efficiency closer to 200, lower than Chevrolet/Ford/Toyota.
Ford:
Fuel capacity roughly 210;
Fuel efficiency around 250, close to Chevrolet and higher than Dodge/Mitsubishi.
Mitsubishi:
Lowest fuel capacity, around 130, and efficiency about 160.
Toyota:
Fuel capacity about 160;
Efficiency near 230, better than Dodge and Mitsubishi but slightly below Chevrolet/Ford.
This shows Dodge trades fuel economy for capacity and performance, while Chevrolet and Ford achieve both higher efficiency and decent tank sizes.

7.	MANUFACTURER BY HORSE POWER


 <img width="824" height="452" alt="image" src="https://github.com/user-attachments/assets/101fcac0-3d4c-4b28-ba4d-3a9b3cf956d7" />

Dodge has about 2.20K total horsepower, the highest of the three.
Ford follows with 1.87K, and Chevrolet with 1.54K.
As a share of total horsepower (≈5.61K):
Dodge holds 39%,
Ford 33%,
Chevrolet 28%.
Dodge clearly positions itself as the most power oriented brand.

8.	ENGINE SIZE BY MANUFACTURER


 <img width="732" height="448" alt="image" src="https://github.com/user-attachments/assets/c61b9300-bc0a-4b3e-8b6a-aa20b718c426" />

Dodge shows the largest combined engine size at about 0.04K (40 units on the chart’s scale).
Chevrolet follows at 0.03K, and Toyota at 0.02K.
Dodge therefore uses engines roughly double the size of Toyota’s and about 33% larger than Chevrolet’s, reinforcing its high performance positioning.














FINAL DASHBOARDS

  
<img width="975" height="392" alt="image" src="https://github.com/user-attachments/assets/2d941436-af5c-4da8-a461-759762a84616" />


<img width="975" height="393" alt="image" src="https://github.com/user-attachments/assets/00425e62-59ec-4915-ad0c-fcc8bd3568fb" />

The final dashboard highlights the combined correlations and relationship between the individual charts with the help of slicers. 


OBSERVATIONS AND ACTIONABLE RECOMMENDATIONS


1. Brand Sales Performance
Observations
•	Ford is the clear volume leader with 2,023K units sold and the highest revenue ($45.8K).
•	Dodge and Toyota are mid tier players with 910K and 740K units, and revenues of ~$18.0K and $13.3K respectively.
•	Chevrolet is smaller in both volume (554K) and revenue, while Mercedes B is a niche player at 117K units.
•	Ford’s revenue is 2.5× Dodge and 3.4× Toyota, indicating much stronger commercial impact.
Recommendations
•	For Ford:
•	Protect this leadership with strong availability and marketing on core models; prioritize Ford in dealer stocking and ad spend.
•	Use market power to negotiate better terms with suppliers and dealers.
•	For competitors (Dodge/Toyota/Chevrolet):
•	Focus on specific niches where Ford is weaker (e.g., fuel efficient compacts, high performance halo cars) rather than trying to compete on total volume.
•	Run targeted campaigns in regions or segments where Ford’s advantage is smaller.

2. Model Level Performance
Observations
•	Neon is a star performer with ~$108.77K in sales, more than 3.5× 300M ($30.70K) and over 9× 323i ($19.75K).
•	3 Sep and especially 3000GT (only $0.11K) are extreme underperformers relative to the other models.
Recommendations
•	For the Neon model:
•	Treat Neon as a flagship: prioritize inventory, promotional campaigns, and new trims (e.g., sport or economy versions) to leverage its popularity.
•	Analyze its customer profile, price point, and feature set as a template for future launches.
•	For weak models (3000GT, 3 Sep, possibly 323i):
•	Conduct margin and customer research—if margins and brand value are low, consider discontinuation or repositioning.
•	If strategically important (e.g., halo car), improve value: refresh design, add features, or re price to stimulate demand.

3. Revenue by Vehicle Type
Observations
•	Passenger vehicles generate about $101,911.22 in revenue vs. $78,081.08 for Cars.
•	Passenger type holds roughly 57% of combined revenue, showing it is the larger money making segment.
Recommendations
•	Increase focus on Passenger segment:
•	Prioritize R&D and new model launches in Passenger type, where revenue pool is larger.
•	Expand trim options (e.g., family oriented, fleet packages) for high demand Passenger models.
•	For Car segment:
•	Keep fewer, stronger models; retire weaker, overlapping nameplates to reduce complexity and cost.
•	Position Cars clearly (e.g., sportier or more affordable than Passenger vehicles) to avoid internal cannibalization.

4. Price & Sales by Year of Launch
Observations
•	From 2010 to 2012, both average price and total sales by year of latest launch rise sharply.
•	Newer launches (2011–2012) achieve higher prices and higher sales volumes than older ones (2008–2009).
Recommendations
•	Shorten product refresh cycles:
•	Plan more regular facelifts or new generations; freshness clearly drives both demand and pricing power.
•	Front load marketing on new launches:
•	Concentrate media, incentives, and dealer events around new model years (especially first 2 years), as this is when models are most profitable.
•	Review older models (pre 2010):
•	Evaluate whether to discontinue, heavily discount, or reposition them as entry level offerings.

5. Horsepower & Engine Size Positioning
Observations
•	Dodge has the highest total horsepower (~2.20K) and largest engines (~0.04K engine size units).
•	Ford is second in horsepower (~1.87K) with slightly smaller engines than Dodge.
•	Chevrolet has the lowest horsepower (~1.54K) and mid range engine size (~0.03K).
•	Toyota uses the smallest engines (~0.02K), suggesting a more efficiency focused lineup.
Recommendations
•	For Dodge:
•	Lean into the performance brand image: emphasize power, acceleration, and driving excitement in messaging.
•	Offer optional efficiency packages (smaller engine or hybrid) to capture buyers who like the brand but worry about fuel costs.
•	For Ford and Chevrolet:
•	Position as balanced brands: “enough power for daily use” plus reasonable efficiency.
•	Create comparison ads highlighting similar power but better fuel economy vs. Dodge.
•	For Toyota:
•	Capitalize on smaller engines with strong fuel economy messaging and total cost of ownership claims.

6. Fuel Capacity & Efficiency by Manufacturer
Observations
•	Chevrolet and Ford have relatively high fuel efficiency (around 250–260 index) with moderate to high fuel capacities (~140–210).
•	Toyota shows good efficiency (~230) with moderate tank size (~160).
•	Dodge has high fuel capacity (~240) but lower efficiency (~200).
•	Mitsubishi is low on both capacity (~130) and efficiency (~160), implying shorter range and not especially low consumption.
Recommendations
•	For Chevrolet and Ford:
•	Market the vehicles as “best blend of power and range” – good efficiency with fewer fuel stops.
•	Use range claims (e.g., “up to X km per tank”) as a differentiator versus Dodge.
•	For Dodge:
•	Since efficiency is weaker, highlight performance and long distance range (big tanks) instead of economy.
•	Consider an efficiency focused sub line or trim to attract fuel sensitive buyers without diluting core performance models.
•	For Mitsubishi:
•	Reevaluate positioning; current data suggests no strong advantage in either range or efficiency.
•	Either improve power/equipment to justify weaker efficiency or redesign for significantly better economy.

7. Overall Strategic Takeaways
Key Cross Chart Observations
•	Ford dominates both in units and revenue while maintaining respectable horsepower and good efficiency—an all round strong brand.
•	Passenger vehicles and newer launches (2010–2012) are where most money and demand are concentrated.
•	Dodge owns the performance niche (largest engines, most horsepower) but pays a penalty on fuel efficiency.
•	A few models (Neon) are carrying a disproportionate amount of revenue, while others contribute almost nothing.
High Level Recommendations
38.	Double down on winners:
•	Invest in Neon and top Passenger models; extend line ups, special editions, and geographic reach.
39.	Rationalize the long tail:
•	Review low performing models and older launches for discontinuation or overhaul to free resources.
40.	Clarify brand roles:
•	Position Dodge as performance; Toyota as efficiency; Ford/Chevrolet as balanced choices.
41.	Use efficiency vs. power smartly:
•	Where you’re strong on efficiency, push total cost of ownership; where you’re strong on power, push performance and experience.
42.	Plan future products around insights:
•	Focus new products in Passenger segment, launched frequently, with a deliberate balance of power and fuel economy to target the biggest revenue pool.
.


 




REFERENCEE: The data for this project was obtained from Kaggle.com 
