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

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * I want to discover outliers or extremes with regard to Sodium (mg) and Item attributes. 
 * I want to understand the distribution of Sodium (mg), Cholesterol (mg) and Calorie values for different fast food restaurants.
 * I want to visualize the correlation between Sodium (mg) and Cholesterol (mg).
 * Are there any patterns that can be observed by food served at specific restaurants with regard to the sodium and cholesterol?

The overall motivation and central research questions this project seeks to answer are: Which fast food items are above the recommended daily intake ranges for sodium, cholesterol and calories? Are there any patterns that can be observed by food served at specific restaurants with regard to the sodium and cholesterol?

## Sketches

![Sketch View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/sketch.png?raw=true)

This is the sketch of the viz I intend to present for this project. The data is visualized in 2D space, where each colored circle represents an individual fast food item plotted according to its sodium (x-axis) and cholesterol values (y-axis). When a user/viewer hovers over a particular bubble, they will be able to see the names of the item and the restaurant/company as well as the numerical values for sodium, cholesterol and calorie levels. Since there is a lot of overlap with the data points, one of my objectives is to implement a zoom-in/zoom-out interaction feature. This sketch and associated user interactions can give users/viewers a sense of how they can simultaneously see which items have the highest or lowest amounts of sodium as well as the overall correlation between Sodium and Cholesterol for menu items. 

![Sketch View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/sketch_2.png?raw=true)
This is an extension of the first sketch. It introduces categorical groupings by restaurant name. The goal of this sketch is to address the question - are there any patterns that can be observed by food served at specific restaurants with regard to the sodium and cholesterol? Interactions also include hovering and zooming.

## Prototypes

I’ve created a [proof of concept visualization](https://vizhub.com/pbruss/cs573-final-project) of this data.

![Prototype View](https://github.com/pbruss/dataviz-project-template-proposal/blob/master/prototype.png?raw=true)

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
