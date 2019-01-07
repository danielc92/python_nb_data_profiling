# python_nb_data_profiling
This repository contains a `jupyter notebook` which is capable of profiling data and visualizing it using `python`.

# Setup
This project is using `python3`.

To grab this repository:
```sh
git clone https://github.com/danielc92/python_nb_data_profiling.git
```

Install the following modules before getting started:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

**note**: you should have general understanding of how to import data using pandas to use this notebook.

# Installation
```sh
pip install pandas numpy seaborn matplotlib
```

# Usage
1. First import your data using `pandas`, this can be in the form of a `.csv`, `.json`, `.sql`, `.txt` or any supported `pandas` format.
2. Setup your export path in `1.4.0.2` section.
3. Setup your report settings in `1.4.0.3` section.
4. Setup your visualization settings in `1.4.0.4` section. note: visualization can be turned off completely, it is optional.
5. Continue runnng the remaining cells, the notebook will now profile your dataset and visualize it if you have enabled the option.
6. The notebook will export the profile results to both `.json` and `.csv`, and export your visualization to `.png`.


# Contributors
- Daniel Corcoran

# Sources
1. [seaborn colour palettes](https://seaborn.pydata.org/tutorial/color_palettes.html)
2. [pandas website](https://pandas.pydata.org/)
3. [seaborn website](https://seaborn.pydata.org/)