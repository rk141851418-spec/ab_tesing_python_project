# 🌐 Website Conversion A/B Testing Project

## 📌 Overview

Improving website conversion rates is critical for businesses that rely on user sign-ups, purchases, or engagement.

This project analyzes user interaction data from an A/B testing experiment to determine whether a newly designed webpage performs better than the existing version.

## The dataset includes:

User ID and group assignment (Control vs Treatment)
Page viewed (Old vs New)
Conversion outcome (0 = No, 1 = Yes)
Timestamp of user activity

The data requires cleaning, validation, and preprocessing before performing statistical analysis to ensure accurate experiment results.

## 🎯 Objective

Use Python, statistics, and hypothesis testing to analyze conversion behavior and determine whether the new webpage leads to a statistically significant improvement in conversion rates, helping businesses make data-driven product decisions.

## ❓ Problem Statement

A company introduced a new webpage design to improve user conversions but is unsure if it performs better than the existing page.

### This project answers:

Do users convert more on the new page?
Is the difference statistically significant?
Should the company replace the old webpage?

The goal is to support a data-driven business decision using A/B testing and statistical analysis.

## 📂 Project Structure

ab_testing_project/
│
├── ab_test_dataset.xlsx              # Raw dataset (user activity & conversion data)
├── notebook.ipynb                    # Jupyter Notebook (data analysis & A/B testing)
│
├── ab_testing_web_page_dashboard     # Dashboard file (visual insights)
├── ab_testing_report.pdf             # Final analysis report


## 📊 Conversion & Statistical Analysis

We analyzed the relationship between page type and conversion status to understand whether users who viewed the new page behaved differently from those who viewed the old page. Visualizations were used to compare conversion distribution across both page versions and to examine user activity patterns over time using a Kernel Density Estimate (KDE) plot.

A QQ plot showed that the data does not follow a normal distribution. Therefore, instead of using a Z-test, a T-test was chosen because it is more suitable when the population standard deviation is unknown and the data represents a sample.

The hypothesis testing results showed that the p-value (0.384) is greater than the 5% significance level, meaning we fail to reject the null hypothesis.

## 💡 Final Insight

There is no statistically significant difference in conversion rates between the old and new webpages. Based on the available data, the new page does not provide enough improvement to justify replacing the existing page.

## 👤 Author

Rakesh Kumar
Data Analyst

📬 Contact
Email: rk141851418@gmail.com
