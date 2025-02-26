# GenAI

 Question 1 .Image Scraping, Filtering & Semantic Search

## Overview
This project implements an automated image scraping, filtering, and semantic search system using deep learning and FAISS (Facebook AI Similarity Search). It enables efficient image retrieval by extracting features from images and performing similarity searches.

## Tech Stack 
   1. Python
   2. Requests, BeautifulSoup - for web scraping
   3. Pillow (PIL) - for image processing
   4. PyTorch, Torchvision - for feature extraction using ResNet-50
   5. FAISS -for efficient similarity search
   6. NumPy - for handling image embeddings

 ## How its Work

   This project scrapes images from a website, filters ads by removing small-sized images, and extracts features using ResNet-50 to generate embeddings. 
   These embeddings are then stored in a FAISS index for efficient retrieval, enabling a semantic search that compares a query image against indexed images to 
   find the most similar matches.

 ## Future Enhancements
   Future enhancements for this project include implementing deep learning-based ad filtering using CNNs for better accuracy, 
   adding multi-threaded scraping to speed up image downloads, and improving feature extraction by integrating advanced models like
   CLIP or EfficientNet for more precise semantic search.
