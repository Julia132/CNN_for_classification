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
