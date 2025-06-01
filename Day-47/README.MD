# Topic: Ensemble Models & Evaluation Metrics

## Today's Learning Objectives Completed

- Revised core ensemble models for supervised learning  
- Learned new algorithms for faster and scalable training  
- Deepened understanding of evaluation metrics for imbalanced datasets  

## Detailed Notes

### Model Revision: Ensemble Algorithms

- Random Forest: Revisited the fundamentals of bagging and feature randomness to reduce overfitting  
- Extra Trees: Similar to Random Forest but introduces more randomness for better variance reduction  
- LightGBM: Efficient gradient boosting framework optimized for large-scale data  
- Stochastic Gradient Descent (SGD): Useful for large, sparse datasets with online learning capabilities  

### Evaluation Metrics

- ROC-AUC Curve: Measures the trade-off between true positive and false positive rates  
- Precision-Recall Curve: More effective for evaluating performance on imbalanced datasets  

## Key Takeaways

- Ensemble methods improve model robustness and generalization  
- LightGBM and SGD are suitable for high-dimensional and large datasets  
- PR curves provide better insights than ROC when dealing with imbalanced data  

## Practical Implementation Tips

- Use ensemble techniques when single models overfit or underperform  
- Tune learning rates and iterations when using SGD  
- Always consider dataset balance when choosing evaluation metrics  
