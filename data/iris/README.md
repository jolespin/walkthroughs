# Iris
The iris dataset is a classic used for classification, statistical analysis, and machine learning.  

```python
import pandas as pd
from sklearn.datasets import load_iris

# Load iris data
iris = load_iris()
X_iris = pd.DataFrame(
    data=iris.data, 
    index=map(lambda i: f"Iris_{i}", range(150)), 
    columns=map(lambda j: j.split(" (")[0].strip().replace(" ","_"), iris.feature_names),
)
X_iris = X_iris.astype(int)
y_iris = pd.Series(iris.target, index=X_iris.index).map(lambda i: iris.target_names[i])
```