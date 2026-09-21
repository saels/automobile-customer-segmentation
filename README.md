# 🚗 Automobile Customer Segmentation

## 💼 Business use case

Automotive brands collect preference surveys to understand what customers value, but raw survey responses are difficult to turn into actionable strategy. Segmentation can reduce hundreds of individual response patterns into a smaller set of customer profiles that product, research, and marketing teams can work with.

## 🎯 Principal objective

Explore 12 binary survey attributes across 793 respondents, study relationships among the variables, choose a cluster count with the elbow method, fit K-Means, check feature means by segment, and use PCA to visualize the resulting customer segments.

## 🔎 Summary of takeaways

The saved workflow selects **two clusters**. Because the input variables are binary indicators on the same scale, raw-feature K-Means is a reasonable exploratory baseline, and the notebook complements it with hierarchical views and PCA visualization.

The next step is to turn those clusters into evidence-based customer profiles. I would add silhouette score, stability checks across seeds and samples, and cluster-size reporting before assigning business labels. I would also compare K-Means with clustering methods better suited to binary similarity.

## 🧭 Explore the code

The [notebook](https://github.com/saels/automobile-customer-segmentation/blob/b6ea4eff145a94f0a3efa8d24a22da9388f2e37f/Automobile_customer_segmentation.ipynb) combines covariance and correlation analysis, hierarchical clustering, elbow selection, K-Means, and PCA. Check the code to see how multiple unsupervised views are used to build and inspect the segmentation rather than relying on one chart alone.
