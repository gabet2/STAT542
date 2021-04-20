# STAT542 Final Project 

### Unsupervised Task Research Questions

We consider two "labels" for our unsupervised task: food categories & nutrition score indicator (0 if 'low' 1 if 'high'). We cluster on the three main macronutrients (carbs, fats, and proteins), **including fiber**. A priori, we know fiber will further inform the specific carbohydrate profile of a food product. For example, 100g of a twinkie and 100g strawberries will have very different carbohydrate compositions despite containing similar 


1. Can we identify meaningful clusters of macronutrient profiles *and fiber* across different **food categories**? It is often claimed that plant-based products lack adeqaute protein. We investigate this claim below. 
    

| Category      | Carbs | Fat   | Protein | Fiber |
| :---:        | :---: | :---: | :---:   | :---: |
| "Meat"       | 7.3   | 10.6  | 9.0     | 1.4   |
| "Plant-Based"| 62.9  | 5.6   | 8.9     | 5.2  |

The above table displays the mean macronutrients for each cluster (per 100g). After applying the 'labels', we achieve a **67.5% accuracy**. Interestingly, both clusters have similar protein compositions. IN addtion, the plant-absed cluster contains significantly mroe carbs, which is to be expected given that plant-based products are dominated by high-carb foods such as grains and legumes. 
    
2. Can we identify meaningful clusters of macronutrient profiles across different **nutrition scores**?

    
| Score      | Carbs | Fat   | Protein | Fiber |
| :---:        | :---: | :---: | :---:   | :---: |
| "Low"        | 12.1  | 13.8  | 7.3     | 1.7   |
| "High"       | 63.6  | 10.4  | 7.2    | 4.2  |

The above table displays the mean macronutrients for each cluster (per 100g). After applying the 'labels', we achieve a **67.0% accuracy**. The high score cluster suggests that a higher carb, lower fat, moderate protein, and higher fiber product will yield a higher nutrition score, which all match our intuition. 

### Soft Timeline 

| Week | Task |
| --- | ----------- |
| 4/5 | Literature Review and Preprocess |
| 4/12 | Finalize Dataset |
| 4/19 | Unsupervised (PCA, Clustering) |
| 4/26 | Supervised (Linear, Tree-Based) |
| 5/3 | Begin Final Report (Summary, Lit Review, etc.) |
| 5/10 | Submission Deadline (5/11) |

### Useful Links

[Data Dictionary](https://static.openfoodfacts.org/data/data-fields.txt)

[Kaggle Usage](https://www.kaggle.com/openfoodfacts/world-food-facts/code)

[Original Paper](https://www.nature.com/articles/s41598-020-60948-w.pdf)
