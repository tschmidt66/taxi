# taxi
import seaborn as sns
import pandas as pd
import matplotlib.pyplot as plt

# Laden des zuvor gespeicherten Datensatzes
data = pd.read_csv('taxi_dataset.csv')

# Anzeige des Boxplots für die Spalte 'total'
plt.figure(figsize=(8, 6))
sns.boxplot(data['total'])
plt.title('Boxplot der Spalte "total"')
plt.show()
