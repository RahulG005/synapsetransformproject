# synapsetransformproject
Transforming data using synapse notebook, data lake

We take CSV files from the raw folder in Azure Data Lake Storage. Using a Synapse Notebook, we clean and filter this data. After transforming it, we save the processed data back into Azure Data Lake Storage, this time in the transformed folder.

![data flow](https://github.com/user-attachments/assets/e2d9a460-66e1-4d3c-8d91-21a1afe46c28)


Raw data in Azure data lake storage linked with synapse 

![Raw data](https://github.com/user-attachments/assets/7a4c6a52-751e-44b1-8ad5-79b1734446e8)


Stored the transformed data in Azure Data Lake Storage. It's organized into folders based on partitioning, and each file is saved in Parquet format. This approach makes querying faster and more efficient, enhancing overall performance and scalability.

![transformed data](https://github.com/user-attachments/assets/3d1c9f72-9ef4-4a5c-8edb-fab820c0c4a2)
![partitioned month data files](https://github.com/user-attachments/assets/6c679370-b82c-4a66-b9fd-6a30dfcbc23c)
![parquet format partitioned year month](https://github.com/user-attachments/assets/5c3a55f6-8b2d-4c82-b57c-bf51d8115eb9)



