# datacamp

1.

```py
xs = points[:, 0]
ys = points[:, 1]

plt.scatter(xs, ys)

In [4]: plt.show()
```

2.

```py
# Import KMeans

from sklearn.cluster import KMeans

# Create a KMeans instance with 3 clusters: model

model = KMeans(n_clusters=3)

# Fit model to points

model.fit(points)

# Determine the cluster labels of new_points: labels

labels = model.predict(new_points)

# Print cluster labels of new_points

print(labels)
```
