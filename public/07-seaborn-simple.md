# Seaborn



```r
library(reticulate)
use_condaenv("r-python", required = TRUE)
```



```python
from __future__ import print_function, division

import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

x = np.linspace(0, 10, 1000)
plt.style.use('ggplot')
plt.plot(x, np.sin(x), x, np.cos(x));
plt.show()
```

<img src="07-seaborn-simple_files/figure-html/unnamed-chunk-2-1.png" width="90%" style="display: block; margin: auto;" />




```python
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

x = np.linspace(0, 10, 1000)
sns.set()
plt.plot(x, np.sin(x), x, np.cos(x));
plt.show()
```

<img src="07-seaborn-simple_files/figure-html/unnamed-chunk-3-1.png" width="90%" style="display: block; margin: auto;" />

