# project2 - sales predictions
# Predicting Future Sales
## Using preprocessing and data modelling

Jerry Qian

### Business problem:

The goal is to help the retailer by using machine learning to make predictions about future sales in certain categories and regions based on the data provided.


### Data:
I provide visualizations for the data, detailed below. I also examine the data using preprocessing and regression modeling.


## Methods
- Preprocessing and data modelling to examine the training data and testing data accuracy
- Visualizations to help understand the data

## Results


#### Visual 1 Title
![(Screenshot 2022-07-29 at 3.02.14 PM.png)](https://github.com/JQ100/project2/blob/75c514e7255094201bd6403f18beae54f2b5531e/Screenshot%202022-07-29%20at%203.02.14%20PM.png)

> According to the bar chart, we have the most sales in the technology sector and the least sales in the furniture sector.

#### Visual 2 Title
![(Screenshot 2022-07-30 at 2.56.15 PM.png)](https://github.com/JQ100/project2/blob/98198bd29822c9a1e65ddc299c997d56457637db/Screenshot%202022-07-30%20at%202.56.15%20PM.png)

After our PCA step, we can see our training and test data have slight changes, and are still close together. However, the accuracy scores of the training/test data are concerning, as they're both near to none. I choose the post-PCA decision tree as my production model because the training and test scores are very close together, a sign we have reduced overfitting. To use this model for sales predictions, it is important to divide up the regions in the analysis. 

### For further information


For any additional questions, please contact jerryqian123@gmail.com
