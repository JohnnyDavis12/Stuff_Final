John Davis and Mike Rabayda

Attached is the final project for this semester's machine learning course. 

1. A Jupyter notebook (.ipynb) with full source code to run the model.
2. The corresponding research paper that looks at the model results and discusses it in length.

To pull training and testing data, simply use MLB's python API:

import pybaseball as pyb
from pybaseball import statcast
df_2022 = statcast(start_dt='Enter Start Date / 2018 ', end_dt='Enter End Date / 2023')
df_2023 = statcast(start_dt='Enter Start Date / 2024 ', end_dt='Enter End Date / 2024')
