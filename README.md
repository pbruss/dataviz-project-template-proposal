# Data Visualization Project

## Data

The data I propose to visualize for my project is the [Fast Food Nutrition dataset](https://www.kaggle.com/datasets/joebeachcapital/fast-food), which contains nutritional values, including calories and micro-nutrients from six of the largest and most popular fast food restaurants: McDonald's, Burger King, Wendy's, Kentucky Fried Chicken (KFC), Taco Bell and Pizza Hut. The data has been [loaded and parsed as CSV](https://vizhub.com/pbruss/fast-food-nutrition-dataset-v3).

The dataset consists of 1071 unique menu items (rows) and is organized with the following attributes:
- Categorical attributes:
    - Company
    - Item
- Quantitative attributes:
  - Calories
  - Calories from Fat
  - Total Fat (g)
  - Saturated Fat (g)
  - Trans_Fat (g)
  - Cholesterol (mg)
  - Sodium (mg)
  - Carbs (g)​
  - Fiber (g)​
  - Sugars (g)​
  - Protein (g)​
  - Weight Watchers Pnts

## Questions & Tasks
Nutrition experts agree that hypertension, a prevalent condition worldwide, is directly influenced by dietary factors such as excessive consumption levels of sodium, cholesterol, saturated fat, and added sugar. This project aims to analyze these key nutritional components within the menu items of six major fast-food chains, examined through the lens of the Dietary Approaches to Stop Hypertension (DASH) guidelines. The DASH diet, specifically designed to combat high blood pressure, emphasizes low intake of sodium, cholesterol, and saturated fats while limiting added sugars. The following tasks and questions will drive the visualization and interaction decisions for this project.
 * I want to discover outliers or extremes with regard to Sodium (mg) and Item attributes. 
 * I want to understand the distribution of Sodium (mg), Cholesterol (mg) and Calorie values for different fast food restaurants.
 * I want to visualize the correlation between Sodium (mg) and Cholesterol (mg), Saturated Fat (g) and Sugar (g).

Additionally, which fast food items are above the recommended daily intake ranges for sodium, cholesterol, saturated fat, sugar and calories? Are there any patterns that can be observed by food served at specific restaurants with regard to the sodium, cholesterol, saturated fat, sugar and calories?

## Sketches

![Sketch View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/sketch.png?raw=true)

This is the sketch of the viz I intend to present for this project. The data is visualized in 2D space, where each colored circle represents an individual fast food item plotted according to its sodium (x-axis) and cholesterol values (y-axis). When a user/viewer hovers over a particular bubble, they will be able to see the names of the item and the restaurant/company as well as the numerical values for sodium, cholesterol and calorie levels. Since there is a lot of overlap with the data points, one of my objectives is to implement a zoom-in/zoom-out interaction feature. This sketch and associated user interactions can give users/viewers a sense of how they can simultaneously see which items have the highest or lowest amounts of sodium as well as the overall correlation between Sodium and Cholesterol for menu items. 

![Sketch View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/sketch_2.png?raw=true)
This is an extension of the first sketch. It introduces categorical groupings by restaurant name. The goal of this sketch is to address the question - are there any patterns that can be observed by food served at specific restaurants with regard to the sodium and cholesterol? Interactions also include hovering and zooming.

## First Iteration Prototypes (bubble chart with no category coloring)
I’ve created a [Cholesterol vs Sodium proof of concept visualization](https://vizhub.com/pbruss/cs573-final-project) of this data.

![Prototype View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/prototype.png?raw=true)

Sugar vs Sodium:
[![image](https://github.com/user-attachments/assets/5420132b-55b7-416d-9a07-8fb8ab5a90f2)
](https://vizhub.com/pbruss/sugar_vs_sodium_v1)

Saturated Fat vs Sodium:
[![image](https://github.com/user-attachments/assets/9f94fb48-8924-4872-be4b-ba110ec17488)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v1)

## Second Iteration Prototypes (updated bubble chart w/ category coloring)
Cholesterol vs Sodium:
[![image](https://github.com/user-attachments/assets/e608502d-8bb7-4a37-9da7-d00883e7ced8)
](https://vizhub.com/pbruss/cholesterol-vs-sodium)

Sugar vs Sodium:
[![image](https://github.com/user-attachments/assets/40c07f62-4abe-4646-b6ef-bf6fe5dc482b)
](https://vizhub.com/pbruss/sugar-vs-sodium)

Saturated Fat vs Cholesterol:
[![image](https://github.com/user-attachments/assets/fa76b0b7-59be-413c-8c54-c1e0e78170ba)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v2)

## Third Iteration Prototypes (updated bubble chart w/ legend)
Cholesterol vs Sodium:
[![image](https://github.com/user-attachments/assets/1983dea2-95ef-4e42-a7ec-95df97678b14)
](https://vizhub.com/pbruss/cholesterol_vs_sodium_v3)

Saturated Fat vs Sodium:
[![image](https://github.com/user-attachments/assets/66413edd-e733-4d6d-b788-7f00edf29809)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v3)

Sugar vs Sodium: 
[![image](https://github.com/user-attachments/assets/e7128554-63bb-419c-a25a-c91c7f145d2f)
](https://vizhub.com/pbruss/sugar_vs_sodium_v3)

## Fourth Iteration Prototypes (updated bubble chart with with interactive linked hightlighting color display and tooltip features)
Cholesterol vs Sodium: McDonald's Sample View
[![image](https://github.com/user-attachments/assets/c045af05-b51c-4ac8-aab6-5775ccee4f19)
](https://vizhub.com/pbruss/cholesterol_vs_sodium_v4)

Cholesterol vs Sodium - Tooltip Screenshot:
![Screenshot (70)](https://github.com/user-attachments/assets/3d25f95f-ef1d-42e5-882b-dc47110253be)

Saturated Fat vs Sodium: McDonald's Sample View
[![image](https://github.com/user-attachments/assets/a42a10df-5ca9-4567-b45b-7df01224b6eb)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v4)

Saturated Fat vs Sodium: Tooltip Screenshot
![Screenshot (74)](https://github.com/user-attachments/assets/f3eaea4a-9929-4e13-bb3c-6cb58e8f6fa7)

Sugar vs Sodium: McDonald's Sample View
[![image](https://github.com/user-attachments/assets/377e9166-bbd4-4b2c-8ee7-509873fdce86)
](https://vizhub.com/pbruss/sugar_vs_sodium_v4)

Sugar vs Sodium: Tooltip Screenshot
![Screenshot (75)](https://github.com/user-attachments/assets/4721ee3e-d9e7-42e3-bc20-809a7a54fd1a)

## Analysis Phase II (Bar Chart Prototypes with tooltip features) --> Week 12 (11/15/2024)
For each fast food restaurant, the following responsive and interactive  bar charts were made:

Average Sodium (mg):
[![image](https://github.com/user-attachments/assets/9b8b24c7-ce16-4261-8463-95394c1ffd7a)
](https://vizhub.com/pbruss/avg_sodium_barchart_v1)

Average Sodium (mg) - tooltip screenshot:
![Screenshot (76)](https://github.com/user-attachments/assets/4d16ce5d-3f2c-45c9-92bd-4c911b9c871e)

Average Cholesterol (mg):
[![image](https://github.com/user-attachments/assets/70df5898-2c1b-4d93-88e2-ac24719fbd40)
](https://vizhub.com/pbruss/avg_cholesterol_barchart_v1)

Average Cholesterol (mg) - tooltip screenshot:
![Screenshot (77)](https://github.com/user-attachments/assets/d3cb5f37-2bdc-4408-94da-d026785ad1e3)

Average Saturated Fat (g):
[![image](https://github.com/user-attachments/assets/17b74beb-bbea-4b9c-a16c-1a52b94c33c4)
](https://vizhub.com/pbruss/avg_satfat_barchart_v1)

Average Saturated Fat (g) - tooltip screenshot:
![Screenshot (78)](https://github.com/user-attachments/assets/5911c973-d43b-4c09-87c4-1ce1fa160a25)

Average Sugar (g):
[![image](https://github.com/user-attachments/assets/13668b0c-6ab4-48e2-b684-dfcf0ae41c29)
](https://vizhub.com/pbruss/avg_sugar_barchart_v1)

Average Sugar (g) - tooltip screenshot:
![Screenshot (81)](https://github.com/user-attachments/assets/72d17cc9-52de-49f5-86ff-0888ae66a9ca)

Average Calories:
[![image](https://github.com/user-attachments/assets/e8bd2348-aef9-41fa-b1f9-174363ed236f)
](https://vizhub.com/pbruss/avg_calories_barchart_v1)

Average Calories - tooltip screenshot:
![Screenshot (82)](https://github.com/user-attachments/assets/d280a2e5-04a9-48a5-beb2-3501ab2c126f)

## Summary of Viz Features: Week 14 (11/29/2024)

All Viz charts in this project include the following features and purpose:
- linked highlighting: highlights relevant data clusters within bubble charts when a user hovers over a particular legend item
- tooltip: displays relevant numerical and catecogrical data for both the bar and bubble charts when a user hovers over a particular bubble or bar chart column
- resposnive scales and axes: supports different device screen sizes and manual resize operations​ made by users/viewers

## Preliminary Findings --> Week 13 (11/15/2024)

<b>Cholesterol-Sodium:</b>

For McDonalds', there is a very noticeable cluster of menu items near the lower end of both cholesterol and sodium axes (bottom-left corner), indicating relatively moderate levels of both attributes. It is also interesting to note the presence of several large calorie items within this cluster. This some what contradicts one of my original hypothesis that high-calorie items are also high in cholesterol and sodium. On the other hand, there are a small number of outliers with very high levels of both sodium and cholesterol. 

Burger King's items span a broad range of sodium levels, from less than 200 mg to over 2,800 mg. Cholesterol levels also vary significantly, with items ranging from low cholesterol (<50 mg) to extremely high (>400 mg). There is a noticeable cluster of yellow bubbles in the moderate sodium range (800–1,200 mg) and cholesterol range (50–200 mg). Burger King's high-sodium items tend to be predominantly large-calorie meals, as seen by the larger bubble sizes in the higher sodium range (>1,500 mg).

Pizza Hut items primarily cluster within the moderate sodium range (400–1000 mg) and low-to-moderate cholesterol range (25–150 mg). Some bubbles are positioned near the bottom-left corner (low in both cholesterol and sodium). It is interesting to note that the items are almost on a straight horizontal line, meaning no correlation. 

Wendy's menu items also had a wide range in terms of sodium and cholesterol levels, with the higher calorie items clustering around the range of 1000-2000 mg for sodium and 50-300 mg for cholesterol. Larger sized bubbles tend to have higher levels of both sodium and cholesterol with this particular set of data. 

With Taco Bell, there is a large cluster grouping in the 800-1400 mg sodium and 0-200 mg cholesterol range. This particular cluster contains has a larger number of menu items with higher calories when compared to another, smaller-sized cluster located in the bottom-left corner of the graph (100-110 mg sodium and 80-120 mg cholesterol ranges)

KFC's sodium range is very wide, ranging from 60 mg (for menu such as soft drinks) to over 2800 mg (mashed potatoes, bbq fries). On the other hand, the cholesterol levels are rather narrow, ranging from 0-120 mg. This illustrates that high sodium levels does not correspond to  which is rather surprising considering the very high sodium levels for some items.  

Overall, the correlation between sodium and cholesterol levels for the menu items at these six fast food restaurants was generally weak-positive (McDonald's and Wendy's) and no correlation (Pizza Hut, Taco Bell and KFC). Burger King's menu items had a more positive correlation between these two particular attributes when compared to the other fast food chains.  Additionally, when looking at Wendy's and Burger King's data, there are some indications that menu items with higher calories will be positioned in graph quadrants that suggest a higher levels of sodium and cholesterol. 

<b>Saturated Fat-Sodium:</b>

McDonald's menu items has three main clusters. The first cluster is located on the left hand side of the graph and is characterized by items with lower levels of sodium in the 100-600 mg range and moderate-high levels of saturated fat ranging from 5-15 g. The calorie distribution of this first cluster is varied but the higher calories, the higher the levels of saturated fat. The s

The clustering distribution of saturated fat and sodium values for Burger King's menu items is generally very dispersed with some, but not significant, positive correlation being displayed. I.e. there is a trend showing that as sodium increases, so does saturated fat. It is also possible to see that the more calories a menu item has, the greater the amount of sodium and saturated it can have. The data for Wendy's menu items behaves in a very similar manner with higher calories menu tending to be located towards the upper-right side of the graph where sodium and saturated values are noticeably higher.

Wendy's distribution is also quite similar to Burger King in that it displays a somewhat positive correlation between the two attributes. In multiple instances, as sodium values increase, so does saturated fat. Like Burger King, Wendy's menu items with higher calories tend to be located towards the upper-right side of the graph where sodium and saturated values are noticeably higher.

Taco Bell's menu items tend to cluster in the center of the chart where sodium ranges 800-1400 mg and saturated fat 5-15 g. This indicates a general tendency towards moderate sodium and high saturated fat levels in Taco Bell's menu items which can be problematic. However, there is no correlation between the two attributes for this particular fast food chain.

Finally, KFC's menu items display no noticeable clustering pattern, with varied distribution in values for both attributes.

<b>Sugar-Sodium:</b> 

For this particular set, it was interesting to note that nearly every chain had very similar patterns regarding the cluster distributions. With the exception of Pizza Hut, every restaurant had two major clusters. The first cluster, generally located on the left side of the plot, consists of with menu items that are high in sugar but relatively low in sodium. The second cluster is horizontal in shape and positioned right along the x-axis. This second cluster features items with sugar levels that are less than 50 g but increasing sodium levels. 

For all chains, most of the items belonging to the first cluster included flavored soda beverages, shakes, etc... all of which have, as expected, very high sugar levels in them. Most items belonging to the second cluster were non-beverage items. 

For McDonald's first cluster on the left hand-side, it is possible to see a strong-positive correlation between sugar and sodium as a straight line-of-best-fit can plotted right in the middle of the along the pink bubbles. It is also possible to see that as sodium and sugar levels increase, so does the calories, as seen by the size of the bubbles which get progressively bigger. 

Overall, the McDonald's cluster on the left hand offered the biggest indication of a relationship between sugar and sodium. 

## Phase I - Result findings and highlights --> Week 14 (11/29/2024)
- Cholesterol vs Sodium:​
    - Weak-positive correlation: McDonald's, Burger King, Wendy's​
    - No correlation: Pizza Hut, Taco Bell, KFC​

- Saturated Fat vs Sodium: ​
    - Weak-positive correlation: McDonald's, Burger King Wendy's, Pizza Hut, Taco Bell​
    - No correlation: KFC​

- Sugar vs Sodium:​ Most restaurant chains exhibited two main clusters for their menu items:​
    - high in sugar, low in sodium (beverages): Strong-Positive correlation seen in McDonalds data points with this cluster
    - low in sugar, high in sodium (non-beverages)​

## Phase II - Result findings and highlights --> Week 14 (11/29/2024)

From Phase II, the following results for the four key attributes were obtained: 
- Sodium:<br /> Highest average: Burger King (508.84 mg) <br /> Lowest average: McDonald's (338.46 mg)
  
- Cholesterol:<br /> Highest average: Taco Bell (56.88 mg) <br /> Lowest average: KFC (19.64 mg)
  
- Saturated Fat:<br /> Highest average: Burger King (5.24 g)<br /> Lowest average: KFC (1.52 g)
  
- Sugar:<br /> Highest average: McDonald's (28.1 g)<br /> Lowest average: Pizza Hut (2.16 g)
  
- Calories:<br /> Highest average: Burger King (338.39)<br /> Lowest average: KFC (215.23)
  
## Data Limitations & Main Project Challenges --> Week 14 (11/29/2024)
Data Limitations: 
The original dataset from Kaggle had somewhat of an uneven count of menu items, especially for Pizza Hut: 
- McDonald's – 328​
- Burger King – 189​
- Wendy's – 153​
- KFC – 217​
- Taco Bell - 182​
- Pizza Hut – 73

This may have affected the final averages that were found in Phase II.

Challenges: 
For Phase I, I initially had some difficulties finding the appropriate mathematical function to represent the bubble radii (i.e. the calories). There was a need to balance encoding bubble visibility with size proportionality. With some functions, the bubbles representing menu items with higher calorie values ended up obscuring those items that were lower in calories, especially if they were part of the same clusters. With other funtions, the lower calorie items ended would simly vanish

## Future Work & Implementations​ --> Week 14 (11/29/2024)
Possible improvements can be made to this project and the results with the following approaches:
- Calculate weighted average instead of just the general, unweighted average​.
- Implement a parallel coordinates plot for further multi-attribute analysis.
- Search for larger fast food datasets.
- Formulate a more systematic approach to tracking and recording the mathematical functions used in order to achieve the optimal bubble radii visibility.

## Project Links & External References​​ --> Week 14 (11/29/2024)
- [Project Viz Summary:](https://vizhub.com/pbruss/cs573_project_viz_summary)
- VizHub Coding References (by Prof. Curran Kelleher):​
    - [Responsive Axes:](https://vizhub.com/curran/responsive-axes)
    - [Axis Labels:](https://vizhub.com/curran/axis-labels)
    - [Scales and Axes:](https://vizhub.com/curran/62cd7e49825448cda908ef84e492df7e)
    - [Responsive Scatter Plot:](https://vizhub.com/curran/responsive-scatter-plot)
    - [Bar Char with Basic Hover:](https://vizhub.com/curran/668bdd63bc2f4e03aa624e4aa65c095f)

## Preliminary Milestones
- Week 2: Select 3 candidate datasets
- Week 3: Identify 5 dataset tasks for each candidate dataset
- Week 4: Present 3-5 visualization ideas through rough sketches
- Week 5: Iterate the sketches from Week 4 based on peer and instructor feedback
- Week 6: Record and present a project proposal video
- Week 7: Prepare and present a first draft project proposal document
- Week 8: Iterate on bubble chart visualization
- Week 9: Begin work on cluster groupings of bubble chart focusing on categorical analysis
- Week 10: Prepare and present a second draft project proposal document
- Week 11: Iterate on cluster groupings of bubble chart focusing on categorical analysis
- Week 12: Analyze quantitative findings
- Week 13: Continue analyzing quantitative findings and begin work on final paper
- Week 14: Finalize final project paper
- Week 15: Record and present final project findings and takeaways
