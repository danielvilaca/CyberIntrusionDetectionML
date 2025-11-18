# <h1 align="center">Cybersecurity Intrusion Detection using Machine Learning</h1>
<h2 align="center">Academic PoC using Decision Trees, Random Forest, K-Means and Apriori Algorithms</h2> 

<br>

> Kaggle Dataset: https://www.kaggle.com/code/i0nlyaziz/cybersecurity-intrusion-detection

<br>

The `CyberIntrusionDetectionML` repository, is an Academic PoC, that aims to build and evaluate `Machine-Learning` Models that can automatically determine whether a network event represents a cyber attack or normal behavior.
The entire project revolves around a `binary classification target` variable:
> `attack_detected = 0` → No attack (Normal traffic)
>
> `attack_detected = 1` → Attack detected (Malicious traffic)

Using this `binary label`, the repository trains and tests several `ML algorithms` such as `Decision Trees`, `Random Forests`, `K-Means clustering`, and `Apriori rule mining` to learn patterns that distinguish safe traffic from harmful activity.
