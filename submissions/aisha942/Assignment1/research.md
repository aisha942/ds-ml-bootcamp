Research Assignment: Introduction to Machine Learning
1. Definition of Machine Learning

Machine Learning (ML) is a branch of artificial intelligence that enables computers to learn patterns from data and improve their performance without being explicitly programmed for every task. Instead of writing fixed rules, developers provide examples, and the algorithm learns relationships that allow it to make predictions or decisions.

A real-life example is email spam filtering. When an email service labels messages as “spam” or “not spam,” it uses machine learning models trained on millions of past emails. The system learns patterns such as suspicious keywords, sender behavior, and formatting styles. Over time, as more emails are labeled by users, the model improves its ability to classify future messages correctly.

This example shows a core idea of ML: learning from experience (data) to improve accuracy over time.

2. ##Supervised vs Unsupervised Learning

Machine learning algorithms are commonly grouped into supervised and unsupervised learning based on the type of data they use.

Supervised Learning

Supervised learning uses labeled data. Each training example includes an input and a correct output. The goal is to learn a mapping from inputs to outputs.

Example: House price prediction
A dataset contains house size, location, and number of rooms (inputs), along with the actual selling price (output). A supervised model learns to predict prices for new houses.

##Unsupervised Learning

Unsupervised learning uses unlabeled data. The algorithm tries to discover hidden patterns or structures without predefined answers.

Example: Customer segmentation
A retail company groups customers based on purchasing behavior. The algorithm clusters customers into categories like “budget shoppers” or “premium buyers,” even though no labels were provided.

Comparison Table
| Feature   | Supervised Learning            | Unsupervised Learning    |
| --------- | ------------------------------ | ------------------------ |
| Data type | Labeled                        | Unlabeled                |
| Goal      | Predict known outcomes         | Discover hidden patterns |
| Example   | Email spam detection           | Customer clustering      |
| Output    | Predictions or classifications | Groups or structures     |

3. Overfitting: Causes and Prevention

Overfitting occurs when a model learns the training data too closely, including noise and random fluctuations. Instead of learning general patterns, it memorizes the dataset. As a result, the model performs well on training data but poorly on new, unseen data.

Causes of Overfitting

Too complex a model for the dataset size

Insufficient training data

Excessive training without regularization

Noisy or irrelevant features

Prevention Methods

Regularization: Adds penalties to overly complex models

Cross-validation: Tests performance on multiple subsets of data

Simpler models: Reduces risk of memorization

More data: Improves generalization

Feature selection: Removes irrelevant variables

Preventing overfitting is essential because ML systems must generalize to real-world data.

4. Training Data vs Test Data

A dataset is typically divided into:

Training set: Used to train the model

Test set: Used to evaluate performance on unseen data

A common split is 80% training and 20% testing, though ratios vary.

Why this split is necessary

If we test the model on the same data it was trained on, we cannot measure real performance. The model might simply memorize the data. The test set simulates real-world situations where the model encounters new information.

This separation ensures:

Fair evaluation

Detection of overfitting

Reliable performance estimates

5. Case Study: Machine Learning in Healthcare

One widely cited application of ML in healthcare is the use of deep learning for medical image analysis.

A study by Esteva et al. (2017) demonstrated that a deep neural network could classify skin cancer from images with accuracy comparable to dermatologists. The researchers trained the model on over 100,000 clinical images of skin lesions. The system learned to distinguish malignant from benign cases.

Findings

The model achieved dermatologist-level performance

Automated systems can assist early diagnosis

ML tools can improve accessibility in areas lacking specialists

This study shows that ML can enhance decision-making in healthcare by supporting professionals rather than replacing them.



