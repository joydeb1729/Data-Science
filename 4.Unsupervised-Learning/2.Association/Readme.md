## Association Rule Learning

### What is Association Rule Learning?
Association rule learning is an unsupervised learning technique that discovers relationships between variables in large datasets. It is widely used for market basket analysis and recommendation systems.

### Common Association Rule Learning Algorithms

#### 1. Apriori Algorithm
- Identifies frequent itemsets in transactional datasets.
- Uses a bottom-up approach to generate association rules.
- Employs the support-confidence framework to filter strong rules.

#### 2. Eclat Algorithm
- A depth-first search algorithm that finds frequent itemsets efficiently.
- Uses intersection-based computations for better performance in dense datasets.

#### 3. FP-Growth (Frequent Pattern Growth)
- Builds a compact data structure called an FP-tree to store itemsets.
- Avoids candidate generation, making it faster than Apriori for large datasets.

### Applications of Association Rule Learning
- Market basket analysis for product recommendations
- Web usage mining for user behavior analysis
- Medical diagnosis and bioinformatics
- Fraud detection in financial transactions

---
This folder contains implementations of association rule learning algorithms along with explanations and practical applications.

