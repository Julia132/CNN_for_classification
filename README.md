# CNN_for_classification
development of architecture convolutional neural network  for pattern classification task

## Code example

```python
plt.figure(figsize=(8, 8))
recall = metrics.recall_score(testY, predictions, average=None)
specificity = recall[0]
precision, recall, thresholds = metrics.precision_recall_curve(testY, predictions)
plt.plot(recall, precision)
plt.ylabel("Precision")
plt.xlabel("Recall")
plt.title("Curve dependent Precision и Recall of threshold")
plt.legend(loc='best')
plt.show()
```
## Image example for classification
#### without neomlasms 
![МОЗГИИИ](https://sun9-50.userapi.com/c858032/v858032820/177c5d/HNmZzznCrMA.jpg)
#### with neomlasms 
![МОЗГИИИ](https://sun9-51.userapi.com/c858032/v858032820/177c64/CERX85xTGlg.jpg)

## Trainin loss and Accuracy in process of training
![ГРАФИК](https://sun9-41.userapi.com/c858032/v858032820/177c75/xvKCem7O-ug.jpg)