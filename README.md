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

## First Iteration Prototypes (w/ no category coloring)
I’ve created a [Cholesterol vs Sodium proof of concept visualization](https://vizhub.com/pbruss/cs573-final-project) of this data.

![Prototype View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/prototype.png?raw=true)

Sugar vs Sodium:
[![image](https://github.com/user-attachments/assets/5420132b-55b7-416d-9a07-8fb8ab5a90f2)
](https://vizhub.com/pbruss/sugar_vs_sodium_v1)

Saturated Fat vs Sodium:
[![image](https://github.com/user-attachments/assets/9f94fb48-8924-4872-be4b-ba110ec17488)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v1)

## Second Iteration Prototypes (w/ category coloring)
Cholesterol vs Sodium:
[![image](https://github.com/user-attachments/assets/e608502d-8bb7-4a37-9da7-d00883e7ced8)
](https://vizhub.com/pbruss/cholesterol-vs-sodium)

Sugar vs Sodium:
[![image](https://github.com/user-attachments/assets/40c07f62-4abe-4646-b6ef-bf6fe5dc482b)
](https://vizhub.com/pbruss/sugar-vs-sodium)

Saturated Fat vs Cholesterol:
[![image](https://github.com/user-attachments/assets/fa76b0b7-59be-413c-8c54-c1e0e78170ba)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v2)

## Third Iteration Prototypes (w/ legend)
Cholesterol vs Sodium:
[![image](https://github.com/user-attachments/assets/1983dea2-95ef-4e42-a7ec-95df97678b14)
](https://vizhub.com/pbruss/cholesterol_vs_sodium_v3)

Saturated Fat vs Sodium:
[![image](https://github.com/user-attachments/assets/66413edd-e733-4d6d-b788-7f00edf29809)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v3)

Sugar vs Sodium: 
[![image](https://github.com/user-attachments/assets/e7128554-63bb-419c-a25a-c91c7f145d2f)
](https://vizhub.com/pbruss/sugar_vs_sodium_v3)

## Fourth Iteration Prototypes (w/ interactive color display)
Cholesterol vs Sodium: McDonald's Sample View
[![image](https://github.com/user-attachments/assets/c045af05-b51c-4ac8-aab6-5775ccee4f19)
](https://vizhub.com/pbruss/cholesterol_vs_sodium_v4)

Saturated Fat vs Sodium: McDonald's Sample View
[![image](https://github.com/user-attachments/assets/a42a10df-5ca9-4567-b45b-7df01224b6eb)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v4)

Sugar vs Sodium: McDonald's Sample View
[![image](https://github.com/user-attachments/assets/377e9166-bbd4-4b2c-8ee7-509873fdce86)
](https://vizhub.com/pbruss/sugar_vs_sodium_v4)

## Analysis Phase 2 (Bar Chart Prototypes - Iteration 1) --> Week 12 (11/15/2024)
For each fast food restaurant, the following responsive and interactive  bar charts were made:

Average Sodium (mg):
[![image](https://github.com/user-attachments/assets/9b8b24c7-ce16-4261-8463-95394c1ffd7a)
](https://vizhub.com/pbruss/avg_sodium_barchart_v1)

Average Cholesterol (mg):
[![image](https://github.com/user-attachments/assets/70df5898-2c1b-4d93-88e2-ac24719fbd40)
](https://vizhub.com/pbruss/avg_cholesterol_barchart_v1)

Average Saturated Fat (g):
[![image](https://github.com/user-attachments/assets/17b74beb-bbea-4b9c-a16c-1a52b94c33c4)
](https://vizhub.com/pbruss/avg_satfat_barchart_v1)

Average Sugar (g):
[![image](https://github.com/user-attachments/assets/13668b0c-6ab4-48e2-b684-dfcf0ae41c29)
](https://vizhub.com/pbruss/avg_sugar_barchart_v1)

Average Calories:
[![image](https://github.com/user-attachments/assets/e8bd2348-aef9-41fa-b1f9-174363ed236f)
](https://vizhub.com/pbruss/avg_calories_barchart_v1)

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

The clustering distribution of saturated fat and sodium values for Burger King's menu items is generally very dispersed with some, but not significant, positive correlation being displayed. I.e. there is a trend showing that as sodium increases, so does saturated fat. It is also possible to see that the more calories a menu item has, the greater the amount of sodium and saturated it can have. The data for Wendy's menu items behaves in a very similar manner with higher calories menu tending to be located towards the upper-right side of the graph where sodium and saturated values are noticeably higher. Overall, 

Wendy's distribution is also quite similar to Burger King in that it displays a somewhat positive correlation between the two attributes. In multiple instances, as sodium values increase, so does saturated fat. Like Burger King, Wendy's menu items with higher calories tend to be located towards the upper-right side of the graph where sodium and saturated values are noticeably higher.

Taco Bell's menu items tend to cluster in the center of the chart where sodium ranges 800-1400 mg and saturated fat 5-15 g. This indicates a general tendency towards moderate sodium and high saturated fat levels in Taco Bell's menu items which can be problematic. However, there is no correlation between the two attributes for this particular fast food chain.

Finally, KFC's menu items display no noticeable clustering pattern, with varied distribution in values for both attributes.

<b>Sugar-Sodium:</b> 

For this particular set, it was interesting to note that nearly every chain had very similar patterns regarding the cluster distributions. With the exception of Pizza Hut, every restaurant had two major clusters. The first cluster, generally located on the left side of the plot, consists of with menu items that are high in sugar but relatively low in sodium. The second cluster is horizontal in shape and positioned right along the x-axis. This second cluster features items with sugar levels that are less than 50 g but increasing sodium levels. 

For all chains, most of the items belonging to the first cluster included flavored soda beverages, shakes, etc... all of which have, as expected, very high sugar levels in them. Most items belonging to the second cluster were non-beverage items. 

For McDonald's first cluster on the left hand-side, it is possible to see a strong-positive correlation between sugar and sodium as a straight line-of-best-fit can plotted right in the middle of the along the pink bubbles. It is also possible to see that as sodium and sugar levels increase, so does the calories, as seen by the size of the bubbles which get progressively bigger. 

Overall, the McDonald's cluster on the left hand offered the biggest indication of a relationship between sugar and sodium. 

From Phase 2, the following results for the four key attributes were obtained: 
- Sodium:<br /> Highest average: Burger King (508.84 mg) <br /> Lowest average: McDonald's (338.46 mg)
- Cholesterol:<br /> Highest average: Taco Bell (56.88 mg) <br /> Lowest average: KFC (19.64 mg)
- Saturated Fat:<br /> Highest average: Burger King (5.24 g)<br /> Lowest average: KFC (1.52 g)
- Sugar:<br /> Highest average: McDonald's (28.1 g)<br /> Lowest average: Pizza Hut (2.16 g)
- Calories:<br /> Highest average: Burger King (338.39)<br /> Lowest average: KFC (215.23)

## Milestones
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
