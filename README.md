# Similar Image Search Across Fashion Images

## Software and platform
For the project, we used Python and the additional numpy, matplotlib, keras, scipy, and skimage libraries. Each of our group members used Mac platforms.

## Map of Documentation
1. DATA folder: The DATA folder includes a "Data" file with a link to the description of the dataset on the Keras website. There is also a description of the dataset and class labels in our Data Appendix in this folder.
2. RESOURCES folder: Contains online resources to aid in the reproduction of this case study. 
3. SCRIPTS folder: Includes DS_PROJECT_3.ipynb, which holds all the source code for loading and preprocessing the data, building and training the CNN-based autoencoder, generating test image embeddings, and displaying similar test images.

## Instructions for reproducing results
To reproduce the results of this study, follow the steps outlined below:

1. Navigate to Google Colab and sign in with your Google account.
2. In the Colab interface, click on File in the top navigation bar, then select Open Notebook.
3. In the popup titled "Open Notebook," find the left-hand navigation bar and click on the GitHub tab.
4. In the search bar, enter the username RainaVardhan. In the Repository field, select laurenwisniewski/DS4002-Project-3.
5. Open the file located at SCRIPTS/DS_PROJECT_3.ipynb.
6. After the file opens, go to Runtime in the menu and select Run all to execute all the cells. This will run the entire analysis process, including data preprocessing, model building, and result generation.
7. The notebook contains sections for data exploration, preprocessing, model training, and evaluation. Review the outputs, plots, and performance metrics generated. You can also modify or rerun specific cells to test different models or parameters.
8.  Once the notebook finishes running, save the results (such as plots and metrics) by downloading them locally or saving them to your Google Drive.


## References
[1] D. Wei, “Demystifying Neural Networks: Similar Image Search with AutoEncoder,” Medium, Feb. 03, 2024. https://medium.com/@weidagang/demystifying-neural-networks-similar-image-search-with-autoencoder-d15eedbae436 (accessed Nov. 08, 2024).
[2] zalandoresearch, “GitHub - zalandoresearch/fashion-mnist: A MNIST-like fashion product database. Benchmark,” GitHub, 2017. https://github.com/zalandoresearch/fashion-mnist/tree/master (accessed Nov. 08, 2024).
[3] K. Team, “Keras documentation: Fashion MNIST dataset, an alternative to MNIST,” keras.io. https://keras.io/api/datasets/fashion_mnist/ 
[4] V. Reddy, “Exploring Image Similarity Approaches in Python,” ScrapeHero, Oct. 12, 2023. https://medium.com/scrapehero/exploring-image-similarity-approaches-in-python-b8ca0a3ed5a3
[5] GeeksforGeeks, “Keras Layers API,” GeeksforGeeks, May 13, 2024. https://www.geeksforgeeks.org/keras-layers-api/ (accessed Nov. 08, 2024).
