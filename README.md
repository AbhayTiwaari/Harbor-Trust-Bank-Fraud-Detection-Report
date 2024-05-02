# Harbor-Trust-Bank-Fraud-Detection-Report

## Business Problem: Improving Financial Security with Fraud Detection**

## Background:
Harbor Trust Bank faces a challenge with small, *unnoticed transactions leading to potential losses and customer trust issues.*

## Objective:
Implement a Benford's Law to catch these small fraudulent transactions without prior knowledge.

## Approach:
1. *Extract Numbers from Amounts*: Use Excel formulas to extract the first digit from each amount. You can use the LEFT function to extract the leftmost digit.

2. *Generate Numbers 1 to 9*: Create a column with numbers 1 to 9 in Excel.

3. *Count the Frequency*: Use the COUNTIF function to count how many times each number from 1 to 9 appears in your extracted digits column.

4. *Sum of Frequencies*: Calculate the sum of the frequencies you obtained in step 3.

5. *Calculate Real Frequency*: Divide each count of the first digit by the sum obtained in step 4 to get the real frequency.

6. *Apply Benford's Law Formula*: In another column, apply the formula for Benford's Law, which is Log10(1 + 1/digit), where 'digit' represents the number 1 to 9.

## Insights
see insights in Report(Dashboard)
