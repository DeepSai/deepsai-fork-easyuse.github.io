---
layout: page
title:  "Data Visualization"
date:   2019-07-01
categories: data-visual
---

## seaborn heatmap
```python
%matplotlib inline

import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

data = np.random.rand(4,4)
sns.heatmap(data);
print(data)

# output
[[0.66551277 0.53291346 0.58329178 0.03840753]
 [0.28192606 0.35637815 0.66603227 0.63488134]
 [0.98989239 0.63482035 0.76583562 0.45823605]
 [0.40120982 0.7955449  0.74902682 0.28705992]]
```
![](data-visual/data-visual-heatmap.png)

### test
![](/assets/images/data-visual-heatmap01.jpg)
