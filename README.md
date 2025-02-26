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

   1.Scrapes Images – Downloads images from the specified website. 
   2.Filters Ads – Removes small-sized images (potential ads).
   3.Extracts Features – Uses ResNet-50 to generate embeddings.
   4.Builds FAISS Index – Stores embeddings for fast retrieval.
   5.Searches Similar Images – Compares a query image against the indexed images.

 ## Future Enhancements
   1.Implement deep learning-based ad filtering using CNNs.
   2.Add support for multi-threaded scraping for faster downloads.
   3.Improve feature extraction using CLIP or EfficientNet.
