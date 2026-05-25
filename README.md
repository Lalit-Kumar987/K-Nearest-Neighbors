Instead of relying solely on existing libraries, I implemented the core KNN algorithm manually, covering:

🔹 Custom distance calculation between data points
🔹 Sorting and selecting the K nearest neighbors
🔹 Majority voting for classification
🔹 Integration with real-world data (Social Network Ads dataset)
🔹 Feature scaling using StandardScaler for optimal performance

The model predicts whether a user will purchase a product based on their age and estimated salary — a classic binary classification problem.

Building this from the ground up gave me a much deeper understanding of how KNN works under the hood, beyond just calling sklearn.neighbors.KNeighborsClassifier.
