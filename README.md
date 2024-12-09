# Basic-Search-Engine

This repository contains implementations of various data mining tasks such as frequent itemset mining, text search engine development, and optimization using TF-IDF.

## Table of Contents
- [Apriori Algorithm](#apriori-algorithm)
- [Term-Document Matrix](#term-document-matrix)
- [Basic Text Search Engine](#basic-text-search-engine)
- [Enhanced Search Engine with TF-IDF](#enhanced-search-engine-with-tf-idf)
  
## Apriori Algorithm
- Implemented the **Apriori Algorithm** to mine frequent itemsets without using external libraries.
- Extracted patterns from the dataset and identified the optimal minimum support to balance the number of frequent patterns.
- Explained the impact of these patterns on decision-making.

## Term-Document Matrix
- Collected a dataset containing over 500 textual samples from various sources.
- Extracted vocabulary and constructed a **term-document matrix** with frequency counts.
- Generated a report highlighting the top 100 terms along with their partial term-document matrix.

## Basic Text Search Engine
- Developed a simple text search engine that retrieves the top 10 search results based on a query.
- Ranking is performed using the total summation of term weights from the term-document matrix.
- Demonstrated the search engine's results with a sample query.

## Enhanced Search Engine with TF-IDF
- Enhanced the text search engine by calculating the term-document matrix using **TF-IDF** for better accuracy.
- Calculated a **term-term correlation matrix** to discover hidden relationships among terms.
- Updated the search engine to utilize TF-IDF weights and performed a comparative analysis of ranking positions with the previous version.
- Displayed the top 10 results for queries and analyzed rank displacement for the top 50 results.
