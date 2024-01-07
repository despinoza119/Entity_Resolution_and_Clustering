![python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![terminal](https://img.shields.io/badge/windows%20terminal-4D4D4D?style=for-the-badge&logo=windows%20terminal&logoColor=white)
![git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)

## Record Linkage

<p align="center">
	<img src="https://blog.carlow.edu/wp-content/uploads/sites/26/2022/04/how-artificial-intelligence-is-shaping-data-analytics-1024x683.jpg" alt="400" width="600"/>
</p>

### Project Overview
This project, developed for Data Driven Business class at Barcelona Technology School, focuses on finding the common products between two retailers to help the marketing team to create more personalized product offering campaigns and product indexes.

### Context
Let's consider that you, as a data scientist, are working for **Retailer A**, a large-scale department store chain. Retailer A has recently entered into a strategic partnership with **Retailer B**, an online e-commerce platform specializing in products. As part of this partnership, Retailer B has shared its product descriptions dataset with Retailer A for the purpose of cross-promotion, product indexing and targeted marketing.

Your task is to perform **entity resolution**, also known as record linkage, on these datasets. The goal is to identify which products in Retailer B's dataset are also products of Retailer A. This will allow the marketing department to create more personalized product offering campaigns and product indexes.

### Data Source

### Repo Structure
- **entity_resolution_clustering.ipynb**: Contains the code with the application of entity resolution and clustering.
- **exploration_data_analysis.ipynb**: Contains the analysis for choosing the best columns to compare.
- **retailerA.csv**: Database from retailer A.
- **retailerB.csv**: Database from retailer B.

### Key Features
- Data processing: We choose the column that doesn't need cleaning but we have to be aware of the structure of the information, in this case numbers are important to compare them between variables.
- Model Vectorizing: For vectorizing the word values we used TfidfVectorizer.
- Model Clustering: We used HDBSCAN because if we see this project as a pipeline we need the model to define the number of clusters.
- Automation: All models are in functions.

### Installation and Usage
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the jupyter notebook.

### License
MIT
