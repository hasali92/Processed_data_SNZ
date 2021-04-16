# Processed_data_SNZ
Following the QuTech guidelines this public repository contains the processed data in all figures of the SNZ paper (accepted in PRL).

---

For figures 1, 2, 3, S1, S3, S6 the following Python 3.7+ scrip can be used to load the data:

```python
from pathlib import Path
from pprint import pprint
import numpy as np
# specify the filename of the corresponding figure on the line below
file_path = Path().resolve() / "Fig_1.npz"

fig_data = np.load(file_path)
pprint(list(fig_data.keys()))
```
