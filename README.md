# Categorize transactions using machine learning

### The project aims to categorize bank transactions based on transaction text using machine learning
The following models were trained:
- Random Forest
- Neural Network (with Tensorflow)
- Logistic Regression
- Naive Bayes

## Dataset 
Dataset was constructed and labeled manually based on my own transactions from the past year. 
An example of data records:
| Transaction text  | Category Id |
| ------------- | ------------- |
| Lidl )))) | 2 |
| Deposit Rent | 1 |
| McDonalds Banegaards )))) | 3 |
| Burger Shack | 3 |

## Transaction categories/labels
Possible categories have been manually selected. A transaction can be categorized as one of the following categories:
| Category Id  | Category Name |
| ------------- | ------------- |
| 0 | Automobile and Transport |
| 1 | Housing and Real-Estate |
| 2 | Groceries |
| 3 | Recreation and Leisure |
| 4 | Health and Well Being |
| 5 | Hobby and Knowledge |
| 6 | Clothes and Equipment |
| 7 | Cash and Credit |
| 8 | Financial Services |
| 9 | Other |

## Results
| Model | Accuracy |
| ------------- | ------------- |
| Random Forest | 0.937 |
| Neural Network | 0.929 |
| Logistic Regression | 0.921 |
| Naive Bayes | 0.905 |

## Conclusion
Random Forest seems to be good enough to classify transactions
