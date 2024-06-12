# Efficient Text Analysis and Query Processing with Apache Spark

# Project Overview
This project was part of the assessed coursework for the Big Data postgraduate course at the University of Glasgow during the 2022-2023 academic year.

# Coursework Specification

## Objective
The aim of this project is to gain hands-on experience in designing, implementing, and performance testing Big Data analysis tasks using Apache Spark. The task involves creating a complex Spark application, testing its performance with various data sizes on a local setup, and writing a report that outlines the design, the decisions made, and critiques where necessary. Evaluation criteria include the functionality of the code (accuracy of the output), the quality of the code (adherence to software engineering principles), and efficiency (speed and resource utilization), along with the quality of the submitted report.

## Task Description
The project requires the development of a batch-based text search and filtering pipeline using Apache Spark. The main objective is to process a large collection of text documents and user-defined queries. For each query, the pipeline should rank the text documents based on relevance and filter out excessively similar documents from the final ranking. The top 10 documents for each query should be provided as output. The text processing should involve removing stopwords (non-informative words such as 'the') and applying stemming (reducing words to their base or root form to address term mismatch issues). The documents should be ranked using the DPH ranking model. Additionally, the final ranking should be analyzed to eliminate redundancy by removing near-duplicate documents, retaining only the most relevant one (based on the DPH score) if any pairs of documents have a title similarity score (using a provided comparison function) of less than 0.5. The final output should include 10 documents per query, even after redundancy filtering.

# Results
Processing the full dataset (~5 GB) with a set of ten queries using four local executors took approximately 120 seconds.

# Note
The dataset used for this project is too large to be included in the submission, but it can be accessed from the provided link.
