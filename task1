import matplotlib.pyplot as plt

# Sample population data (in millions) from World Bank Population 2022 rankings 1
countries = [
    "India", "China", "USA", "Indonesia", "Pakistan", "Nigeria",
    "Brazil", "Bangladesh", "Russia", "Mexico"
]
pop_millions = [
    1417.173, 1412.175, 333.288, 275.501, 235.825, 218.541,
    215.313, 171.186, 143.556, 127.504
]

# Create bar chart
plt.figure(figsize=(12, 6))
bars = plt.bar(countries, pop_millions, color='teal', edgecolor='black')
plt.title('Population by Country (2022, in Millions)')
plt.xlabel('Country')
plt.ylabel('Population (million)')
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()