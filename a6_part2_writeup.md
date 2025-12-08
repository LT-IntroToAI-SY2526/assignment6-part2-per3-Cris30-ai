# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.  

**YOUR ANSWER:**
1. Most Important:Bedrooms(6648.97) 
2. Bathrooms(3858.90)
3. Square Feet(121.11)
4. Least Important:Age(-950.35) 

**Explanation:** I ordered the features by their absolute size of their coefficients. Then realized Bedrooms(6648.97) had the largest coefficient, while Age(-950.35) had the smallest.



---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:** SquareFeet; every new square foot increases the preicted price by $(121.11)


**Feature 2:** Age; every new year of age decreases the predicted price by $(-950.35)


---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:** My model's R^2 score is 0.9936. This tell me that my model explains 99.36% of the different various house prices. There is room for improvement due to the fact that the dataset is not that large and the dataset is missing vaulable features like location and lot size. 




---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:** Location(neighborhood/zip code)


**Why it would help:** House location is the biggest determination in price level. For example it cost more to live downtown than in a suburb. 


**Feature 2:**Lot Size


**Why it would help:** The lot size is important because if the houses are the same size, the next determination of price would be the area/land size that it sits on. 


---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**
I would not trust this model 100% to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old because these features are outside of the training data range. Therefore, the model's predict will be less accurate because its prediction with be extrapolation. 

