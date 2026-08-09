# 📊 Superstore Dataset — Deep Analysis Notebooks

This repository contains three separate, deep-dive Jupyter notebooks based on the Superstore.csv dataset (9,994 orders — US retail sales data). Each notebook **focuses on only one library** so you can deeply learn Pandas, NumPy, and Matplotlib individually. All notebooks are **fully executed** with embedded outputs and charts.

---

## 📁 Files

| Notebook | Focus | Cells |
|---|---|---|
| `Superstore_Deep_Analysis.ipynb` | 🐼 **Pandas** — data cleaning, exploration & business analysis | 89 |
| `Superstore_NumPy_Analysis.ipynb` | 🔢 **NumPy** — array-based numerical computing & stats | 83 |
| `Superstore_Matplotlib_Analysis.ipynb` | 📈 **Matplotlib** — professional data visualization | 61 |

---

## 🐼 1. `Superstore_Deep_Analysis.ipynb` (Pandas)

**Only Pandas** is used to load, clean, explore, and analyze the dataset (with minor Matplotlib support for basic visualization).

**Topics covered:**
- Data load & inspection — `read_csv`, `info`, `describe`, `dtypes`, `memory_usage`
- Cleaning — `isnull`, `duplicated`, `astype`, `to_datetime`, `fillna`, rename/drop
- Filtering & indexing — `loc/iloc`, `query`, boolean masking
- Sorting — `sort_values`, `nlargest/nsmallest`
- GroupBy & aggregation — `groupby`, `agg`, `transform`, `filter`
- Reshaping — `pivot_table`, `crosstab`, `melt`, `stack/unstack`
- Transform — `apply`, `map`, `str`/`dt` accessors
- Binning — `cut`, `qcut`
- Stats — `corr`, `rank`, `cumsum/cummax`
- Time series — `resample`, `rolling`
- Combine — `merge`, `concat`, `idxmax/idxmin`
- Export — `to_csv`
- Visualization — pandas `.plot()` (bar, line, pie)

---

## 🔢 2. `Superstore_NumPy_Analysis.ipynb` (NumPy)

The CSV is parsed using Python's built-in csv module (due to quoted fields), but **all computations use pure NumPy arrays** — zero Pandas involved.

**Topics covered:**
- Array basics — `np.array`, dtype, shape/ndim/size, `reshape/ravel/transpose`
- Indexing — slicing, boolean masking, fancy indexing, `np.where`
- Sorting — `np.unique`, `np.sort/argsort`
- Statistics — `mean/median/std/var`, `argmin/argmax`, `percentile`, `ptp`
- Group-aggregation without pandas — boolean masks + `np.bincount`
- Cumulative — `cumsum`, `cumprod`, `diff`
- Correlation — `np.corrcoef`, `np.cov`
- Broadcasting — profit margin %, discount simulation, `clip/round/abs/log/sqrt`
- Distribution — `np.histogram`, `np.bincount`
- Regression — `np.polyfit`, `np.linalg.lstsq` (trend line)
- Combining arrays — `concatenate/vstack/hstack/split`
- Random — `np.random` bootstrap resampling (95% confidence interval)
- NaN handling — `isnan`, `nanmean/nanstd/nansum`
- Date/time arrays — `datetime64`, `timedelta64`
- Structured (record) arrays
- Save/Load — `np.save`, `np.savetxt`, `np.load`

---

## 📈 3. `Superstore_Matplotlib_Analysis.ipynb` (Matplotlib)

Data preparation is done using NumPy and the csv module, but **every chart and customization is built purely with Matplotlib.**

**Topics covered:**
- Figure/Axes anatomy — `plt.figure`, `plt.subplots`
- Line plots — multi-line, styles, markers
- Bar charts — vertical, horizontal, grouped, stacked
- Histograms — normal, cumulative, overlapping
- Scatter plots — basic + bubble chart (color/size mapping)
- Pie charts
- Box & violin plots
- Layouts — `subplot2grid`, `GridSpec`
- Twin axes — `twinx()`
- Annotations — `annotate`, `text`, arrows
- Colormaps & `colorbar`
- Heatmaps — `imshow`
- Contour plots — `contour/contourf`
- Stem & step plots
- Error bars & `fill_between`
- Date axis formatting — `matplotlib.dates`
- Log scale axes
- 3D plotting — scatter + `bar3d`
- Styles & `rcParams` customization
- `savefig` (high-res export)
- Final combined executive dashboard

---

## 📌 Dataset Info

**Superstore.csv** — Order-level retail dataset from a US superstore (2014–2017). It contains 9,994 rows and 21 columns, including Order/Ship dates, Customer details, Product Category/Sub-Category, Sales, Quantity, Discount, and Profit.

## 👤 Author

**Azeem** — [@Azeem8541](https://github.com/Azeem8541)
