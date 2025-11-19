Amazon Reviews 2023 Data Model

This repository presents a data model and exploration workflow built on the large-scale Amazon Reviews 2023 dataset (500K sample) from the McAuley Lab.
It includes:

A full ER diagram.

Data-modeling scripts and notebook for ingestion and analysis.

DBT models and Jupyter notebook to explore the review data.

📋 Contents
Folder/File	Description
/dbt/models	DBT models transforming the raw dataset into structured tables.
Amazon_Review_2023.ipynb	Jupyter notebook showing analysis and usage of the dataset.
ER_Diagram.jpg	Visual representation of the data model.
README.md	This file.
📌 Dataset Overview

The dataset is sampled (~500,000 reviews) from Amazon’s product review corpus for 2023, offering insights into:

User review ratings and behaviour.

Product categories and metadata.

Temporal trends in reviews.

Text-based review sentiment & topic analysis.

🛠 Usage & Workflow

Clone this repository:

git clone https://github.com/ozukun/Amazon-reviews-2023.git
cd Amazon-reviews-2023


Review the notebook (Amazon_Review_2023.ipynb) to see how the dataset is explored.

Deploy the DBT models in /dbt/models to create structured tables.

Use the ER diagram (ER_Diagram.jpg) to understand the relationships and schema design.

✨ Key Highlights

Dimensional-style modeling for review analytics (e.g., Reviews fact, Users dimension, Products dimension).

Sample size of 500K reviews to allow rapid experimentation while preserving scale.

Notebook includes EDA, visualization, and initial interpretations.

DBT models provide a foundation for transformation and extensibility.

🔍 Potential Extensions

Scale up to full dataset beyond 500K sample.

Add sentiment analysis or NLP pipelines on review text.

Build dashboards for review trends over time, by product category, user segments.

Integrate additional Amazon metadata (e.g., product attributes, seller info).

Deploy to a cloud warehouse (Snowflake/BigQuery) for large-scale analytics.

📚 License & Contribution

Feel free to open issues for suggestions or improvements. Pull requests are welcome.
This project is licensed under the MIT License (or your preferred license).

👍 Acknowledgements

Dataset collected and curated by the McAuley Lab. Many thanks for enabling large-scale review research and analysis.
