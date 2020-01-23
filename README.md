Matplotlib style sheet for astronomy and Astrophysics plots

Find where the style sheets for your matplotlib install

```python
import matplotlib as mpl
mpl.matplotlib_fname()
```

and put the astro.mplstyle file into it.

use as:
```python
import matplotlib.pyplot as plt
plt.style.use('astro')

```
see the matplotlib docs on manually creating the style sheets.

