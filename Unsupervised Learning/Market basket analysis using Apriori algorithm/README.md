# 🛒 Market Basket Analysis using Apriori Algorithm

This project uses the Apriori algorithm to identify associations between items purchased together in a transaction dataset.

---

## 📌 What Was Done

- Transformed transaction data into a format suitable for association rule mining.
- Applied the **Apriori algorithm** using the `apyori` library to generate frequent itemsets based on a defined support threshold.
- Extracted **association rules** from the frequent itemsets using:
  - **Support**: How frequently the itemset appears in the dataset.
  - **Confidence**: The probability that the consequent is purchased when the antecedent is.
  - **Lift**: The strength of association compared to random chance.
- Parsed and structured the output into a DataFrame with columns for:
  - Left-hand item (Item1)
  - Right-hand item (Item2)
  - Support
  - Confidence
  - Lift

---

## 📊 Top 3 Association Rules

| Item1          | Item2    | Support | Confidence | Lift     |
|----------------|----------|---------|------------|----------|
| fromage blanc  | honey    | 0.003333| 0.245098   | 5.178128 |
| light cream    | chicken  | 0.004533| 0.290598   | 4.843305 |
| pasta          | escalope | 0.005867| 0.372881   | 4.700185 |
