**1. They should use the same test all the time, but there are at least four different test sets in the result. The same test achieved from the real data should be used for all the methods (undersampling and oversampling).**

**2. After implementing SMOTE, they have splitted the oversampled data to train and test. So, the test has synthetic data as well, which should not have (test set must include only real data).**

**3. I did not understand the reason for oversampling the whole data.**

**4. The imbalance ratio is 1 to 99. I would suggest trying more moderate ratios like 1 to 9, so the results would reflect a better comparison of the models for their understanding, especially since they are using data with only 2 features.**

**5. To compare the oversampling methods, the number of generated samples should be the same. Also, I would suggest trying a different desired ratio. In the code, they mostly tried to balance the data to be 50-50 for the two classes. Other balanced ratios like 40-60 can be explored.**

**Generally, since the test set is not the same, the comparison doesn't make sense. However, the overall process is almost fine.**

**Please let me know if I can be of any help."**