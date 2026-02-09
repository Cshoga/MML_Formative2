# PCA library
## installation
Clone repository:
git clone https://github.com/Cshoga/MML_Formative2.git
cd MM_Formative2

Install dependencies:
pip install .

pip install MM_Format2

Usage:
Open Google colab and:

import pandas as pd

data_url = "https://data360.worldbank.org/en/dataset/GI_AII"
df = pd.read_csv(data_url)

print(df.head())
