# GenAI

 Question 1 .Image Scraping, Filtering & Semantic Search

## Overview
This project implements an automated image scraping, filtering, and semantic search system using deep learning and FAISS (Facebook AI Similarity Search). It enables efficient image retrieval by extracting features from images and performing similarity searches.

## Tech Stack 
   Python
   Requests, BeautifulSoup - for web scraping
   Pillow (PIL) - for image processing
   PyTorch, Torchvision - for feature extraction using ResNet-50
   FAISS -for efficient similarity search
   NumPy - for handling image embeddings

 ## How its Work

   Scrapes Images – Downloads images from the specified website.
   Filters Ads – Removes small-sized images (potential ads).
   Extracts Features – Uses ResNet-50 to generate embeddings.
   Builds FAISS Index – Stores embeddings for fast retrieval.
   Searches Similar Images – Compares a query image against the indexed images.

 ## Future Enhancements
   Implement deep learning-based ad filtering using CNNs.
   Add support for multi-threaded scraping for faster downloads.
   Improve feature extraction using CLIP or EfficientNet.
