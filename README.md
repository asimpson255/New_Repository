# New_Repository

# Test

**Adam**

pip install seaborn

import seaborn as sns
import matplotlib.pyplot as plt

# Load example dataset
df = sns.load_dataset("tips")  # restaurant tips dataset
print(df.head())

sns.barplot(x="day", y="total_bill", data=df)
plt.show()
