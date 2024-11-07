# Data Visualization Project

## Data

The data I propose to visualize for my project is the [Fast Food Nutrition dataset](https://www.kaggle.com/datasets/joebeachcapital/fast-food), which contains nutritional values, including calories and micro-nutrients from six of the largest and most popular fast food restaurants: McDonald's, Burger King, Wendy's, Kentucky Fried Chicken (KFC), Taco Bell and Pizza Hut. The data has been [loaded and parsed as CSV](https://vizhub.com/pbruss/fast-food-nutrition-dataset-v3).

The dataset consists of 1072 unique menu items (rows) and is organized with the following attributes:
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
Cholesterol vs Sodium:
[![image](https://github.com/user-attachments/assets/c045af05-b51c-4ac8-aab6-5775ccee4f19)
](https://vizhub.com/pbruss/cholesterol_vs_sodium_v4)

Saturated Fat vs Sodium:
[![image](https://github.com/user-attachments/assets/a42a10df-5ca9-4567-b45b-7df01224b6eb)
](https://vizhub.com/pbruss/saturatedfat_vs_sodium_v4)

Sugar vs Sodium:
[![image](https://github.com/user-attachments/assets/ee540fe2-8a06-418d-bc90-64b4a164511d)
](https://vizhub.com/pbruss/sugar_vs_sodium_v4)


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
