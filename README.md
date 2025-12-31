📘 Algorithms: Theory, Formula & Examples
📌 Overview

This repository is dedicated to understanding core algorithms and machine learning techniques through:

📐 Mathematical formulas

📖 Conceptual theory

🧪 Simple examples

🧠 Intuition behind each algorithm

It is designed for students, freshers, and interview preparation.

🧠 What is an Algorithm?

An algorithm is a finite set of well-defined steps used to solve a specific problem or perform a computation efficiently.

Characteristics of a Good Algorithm:

Finite

Well-defined

Input & output specified

Efficient in time and space

🔹 1. Linear Regression
📖 Theory

Linear Regression is a supervised learning algorithm used to model the relationship between:

Independent variable (X)

Dependent variable (Y)

It assumes a linear relationship between input and output.

📐 Formula

Hypothesis function:

𝑦
=
𝑚
𝑥
+
𝑐
y=mx+c

For multiple features:

𝑦
=
𝑤
1
𝑥
1
+
𝑤
2
𝑥
2
+
.
.
.
+
𝑤
𝑛
𝑥
𝑛
+
𝑏
y=w
1
	​

x
1
	​

+w
2
	​

x
2
	​

+...+w
n
	​

x
n
	​

+b
📉 Cost Function (Mean Squared Error)
𝐽
(
𝑤
,
𝑏
)
=
1
𝑛
∑
(
𝑦
𝑝
𝑟
𝑒
𝑑
−
𝑦
𝑎
𝑐
𝑡
𝑢
𝑎
𝑙
)
2
J(w,b)=
n
1
	​

∑(y
pred
	​

−y
actual
	​

)
2
🧪 Example

If:

House size = 1000 sq.ft

Price = ₹50 lakhs

Linear regression helps predict the price of a house based on size.

🔹 2. Logistic Regression
📖 Theory

Logistic Regression is used for binary classification problems such as:

Yes / No

Spam / Not Spam

Pass / Fail

It outputs a probability between 0 and 1.

📐 Formula (Sigmoid Function)
𝜎
(
𝑧
)
=
1
1
+
𝑒
−
𝑧
σ(z)=
1+e
−z
1
	​


Where:

𝑧
=
𝑤
𝑥
+
𝑏
z=wx+b
📊 Decision Boundary

If probability ≥ 0.5 → Class 1

If probability < 0.5 → Class 0

🧪 Example

Predict whether a student passes (1) or fails (0) based on study hours.

🔹 3. K-Means Clustering
📖 Theory

K-Means is an unsupervised learning algorithm used to group data into K clusters based on similarity.

📐 Distance Formula (Euclidean Distance)
𝑑
=
(
𝑥
2
−
𝑥
1
)
2
+
(
𝑦
2
−
𝑦
1
)
2
d=
(x
2
	​

−x
1
	​

)
2
+(y
2
	​

−y
1
	​

)
2
	​

⚙️ Algorithm Steps

Choose number of clusters (K)

Initialize centroids randomly

Assign points to nearest centroid

Update centroid positions

Repeat until convergence

🧪 Example

Customer segmentation based on:

Age

Income

Spending score

🔹 4. Principal Component Analysis (PCA)
📖 Theory

PCA is a dimensionality reduction algorithm that converts high-dimensional data into fewer dimensions while preserving variance.

📐 Formula (Covariance Matrix)
𝐶
𝑜
𝑣
(
𝑋
)
=
1
𝑛
−
1
(
𝑋
−
𝜇
)
𝑇
(
𝑋
−
𝜇
)
Cov(X)=
n−1
1
	​

(X−μ)
T
(X−μ)

Eigenvalues determine importance of components.

🧪 Example

Reducing:

50 features → 2 principal components
for visualization and faster computation.

🔹 5. Evaluation Metrics
📐 Accuracy
𝐴
𝑐
𝑐
𝑢
𝑟
𝑎
𝑐
𝑦
=
𝑇
𝑃
+
𝑇
𝑁
𝑇
𝑃
+
𝑇
𝑁
+
𝐹
𝑃
+
𝐹
𝑁
Accuracy=
TP+TN+FP+FN
TP+TN
	​

📐 Precision
𝑃
𝑟
𝑒
𝑐
𝑖
𝑠
𝑖
𝑜
𝑛
=
𝑇
𝑃
𝑇
𝑃
+
𝐹
𝑃
Precision=
TP+FP
TP
	​

📐 Recall
𝑅
𝑒
𝑐
𝑎
𝑙
𝑙
=
𝑇
𝑃
𝑇
𝑃
+
𝐹
𝑁
Recall=
TP+FN
TP
	​

🧪 Example

Used in:

Medical diagnosis

Fraud detection

Spam classification

⏱️ Time & Space Complexity

Time Complexity: Measures execution time

Space Complexity: Measures memory usage

Example:

Linear Search → O(n)

Binary Search → O(log n)

🛠 Technologies Used

Python 🐍

NumPy

Pandas

Matplotlib

Scikit-learn
