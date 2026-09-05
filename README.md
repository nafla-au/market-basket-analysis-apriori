# Market Basket Analysis using Apriori

## 📌 Overview

Market Basket Analysis using the **Apriori algorithm** to identify product associations and purchasing patterns from transaction data.

## 🎯 Objectives

* Identify frequently purchased product combinations
* Generate association rules using the Apriori algorithm
* Analyze **support, confidence, and lift**
* Identify product combinations that can support business decisions

## 🛠️ Tools

* Python
* Pandas
* NumPy
* Mlxtend
* Google Colab

## 🔍 Method

The analysis uses the following steps:

1. Data preprocessing
2. Create transaction basket
3. Generate frequent itemsets using **Apriori**
4. Generate association rules
5. Analyze support, confidence, and lift

## 📊 Key Results

Several strong product associations were identified.

Examples:

* **Red Hanging Heart T-Light Holder → White Hanging Heart T-Light Holder**

  * Confidence: **72.22%**
  * Lift: **4.06**

* **Sweetheart Ceramic Trinket Box → Strawberry Ceramic Trinket Box**

  * Confidence: **76.05%**
  * Lift: **10.14**

* **Toilet Metal Sign → Bathroom Metal Sign**

  * Confidence: **80.49%**
  * Lift: **19.83**

A **lift greater than 1** indicates that the products are purchased together more often than would be expected if they were independent.

## 💡 Business Insight

The identified associations can be used to support:

* Product bundling
* Cross-selling recommendations
* Store/product placement
* Promotional strategies

