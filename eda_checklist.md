# Exploratory Data Analysis Checklist

This checklist is used before any modeling to ensure the dataset
is properly understood and evaluated.

---

## 1. Problem Understanding
- [ ] Target column clearly identified
- [ ] Problem type confirmed (classification or regression)
- [ ] Metric that matters defined
- [ ] Real-world objective understood

---

## 2. Data Overview
- [ ] Dataset shape reviewed
- [ ] Column data types verified
- [ ] Obvious ID or non-predictive columns identified

---

## 3. Target Analysis
- [ ] Target distribution analyzed
- [ ] Class imbalance checked (if classification)
- [ ] Outliers or extreme values noted (if regression)

---

## 4. Feature Analysis
- [ ] Numeric feature distributions reviewed
- [ ] Categorical feature cardinality reviewed
- [ ] Potential redundant features identified

---

## 5. Missing Values
- [ ] Missing value percentages computed
- [ ] Columns with excessive missingness flagged
- [ ] Initial imputation or removal strategy decided

---

## 6. Correlation & Relationships
- [ ] Feature–feature correlations reviewed
- [ ] Feature–target relationships explored
- [ ] Highly correlated features flagged

---

## 7. Leakage Checks
- [ ] No features derived from the target
- [ ] No post-outcome or future information included
- [ ] IDs, timestamps, or proxies reviewed for leakage risk

---

## 8. Key Insights
- [ ] At least 3 key insights documented
- [ ] Potential modeling challenges identified
- [ ] Next steps clearly defined

