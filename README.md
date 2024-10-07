```python
import numpy as np
file = np.load(dataset_path)

x = file['attmats']  # (N, T, D) node features
y = file['labels']  # (N, C)  node labels
adjs = file['adjs']  # (T, N, N) graph snapshots
```

From `Spatio-Temporal Attentive RNN for Node Classification in Temporal Attributed Graphs`
