Conjoint Analysis and Recommender System Design
Overview

This project involves two key components:

    Recommender Systems: Research and framework for building an automated recommendation system tailored for Barnes & Noble.
    Chestnut Ridge Laptop Conjoint Analysis: Analysis of customer preferences to identify the optimal laptop configuration for Chestnut Ridge, leveraging conjoint analysis.

Objectives
Recommender Systems

    Explore different types of recommender systems and recommend the most suitable approach for Barnes & Noble.
    Identify algorithms and data requirements for building an effective recommendation engine.
    Provide metrics to measure the success of the implemented system.

Conjoint Analysis

    Identify the most valued laptop attributes (e.g., RAM size, screen size, battery life) using customer preference data.
    Determine the optimal laptop configuration to maximize consumer ratings.
    Quantify the monetary value of specific laptop features.

Datasets

    ChestnutRidge_laptops.xlsx:
        Contains customer preference ratings for 15 unique laptop configurations.
        Attributes:
            RAM Size: 4GB, 8GB, 16GB
            Screen Size: 13 inches, 14 inches, 15 inches
            Battery Life: 6 hours, 8 hours, 10 hours
            Price: $800, $850, $900
            Hard Drive Type: SSD, SATA

Methodology
Recommender Systems

    Types of Recommender Systems:
        Content-Based Filtering: Recommends items similar to user interests based on item features.
        Collaborative Filtering: Uses preferences of similar users to recommend items.
        Recommendation: A hybrid system combining both methods is ideal for Barnes & Noble.

    Data Mining Algorithms:
        K-Nearest Neighbors (KNN): Identifies and recommends items preferred by similar users.
        Matrix Factorization (e.g., SVD): Discovers hidden patterns in user-item interactions.
        Random Forests: Predicts user preferences based on behavior and characteristics.

    Data Requirements:
        User Data: Demographics, reading history, ratings.
        Item Data: Metadata (e.g., title, genre, author).
        User-Item Interactions: Clicks, purchases, views.

    Success Metrics:
        Click-Through Rate (CTR)
        Conversion Rate
        User Engagement Metrics
        Diversity and Novelty of Recommendations

Conjoint Analysis

    Data Cleaning:
        Verified correct data types.
        No missing values found in the dataset.

    Baseline Configuration:
        RAM: 4GB
        Screen Size: 13 inches
        Battery Life: 6 hours
        Price: $800
        Hard Drive: SATA

    Analysis Steps:
        Calculated average partworths for all attributes.
        Identified the most influential attribute based on partworth ranges.
        Quantified the dollar value for specific attribute levels.

    Key Findings:
        Most Important Attribute: Price had the largest range in partworths, indicating the strongest impact on preferences.
        Optimal Laptop Configuration:
            RAM: 8GB
            Screen Size: 14 inches
            Battery Life: 10 hours
            Price: $850
            Hard Drive: SSD
        Monetary Values:
            16GB RAM: $20.67
            15-inch Screen: -$18.91
            SSD Hard Drive: $11.78
            10-hour Battery Life: -$11.14

Tools and Technologies

    Python: Used for analysis and modeling.
        Libraries: pandas, numpy, matplotlib, scipy, sklearn.
    Jupyter Notebook: For interactive coding and documentation.
    Microsoft Excel: For dataset review and preparation.

Deliverables

    Python Code:
        Assignment_4.ipynb: Jupyter Notebook with code for conjoint analysis.
    Documentation:
        Answer_of_Assignment_4_Arafat_Ahmed.docx: Detailed responses and insights.
    HTML Report:
        Assignment_4.html: Comprehensive report of analysis results.

Instructions for Use

    1. Clone the repository:git clone https://github.com/YourUsername/Conjoint-Recommender-Analysis.git
    2. Open the Jupyter Notebook:jupyter notebook Assignment_4.ipynb
    3. Follow the code to replicate or expand the analysis.

Acknowledgments
This project was completed as part of the MKT 568 coursework at WPI Business School. Special thanks to the course instructors for guidance and support.
