# Mete Morris Coding Interview

**Files:**
- metemorris_results.csv: Results of the run
- solution_metemorris.ipynb : notebook used to obtain the results and values below 

Hi!
My solution is is in the python notebook with comments and notes placed as I was going along that expresses the process. If you want to check what I did and the methodology it is explained there. 

## Classifier Choice 

### Random Forest

**Accuracy:** %68.9
**F1 Score:** 0.105

**Confusion Matrix**
107, 5
46, 3

### SVC 

**Accuracy on Test Scores:**  %69.6
**F1 Score:** 0
**Confusion Matrix**
112, 0 
49 , 0
### Reasoning for Choosing Random Forest:
Looking at these predictions, although SVC has a better overall accuracy, it is just predicting 0s for all candidates, as reflected by the 0 F1 score. Due to this I went with predicting the remainder of the data using random forest
## Future Improvements/Tests
- Try different training and testing splits, try a bigger testing split and see if that changes anything for SVC results
- Due to long traininig and testing times, I was not able to do gridsearch for best hyperparameters on SVC, would have kept my computer running for a while to figure out the best hyper parameters

