# 👗 Fashion Item Recommendation System

A **CNN-based image similarity recommendation system** for women's fashion items, built using **VGG16** features extraction.

---

## 🔹 Project Overview

This project aims to **recommend fashion items visually similar** to a user-provided image. It leverages deep learning features extracted from a **pre-trained VGG16 model** and cosine similarity to find the top matching fashion items.

- **Dataset:** Kaggle Women's Fashion dataset (preprocessed)
- **Total Images:** 97 high-quality fashion item images
- **Input:** Image of a fashion item
- **Output:** Top-N visually similar fashion item recommendations

---

## 🛠️ Key Features & Techniques

- **Deep Learning Feature Extraction:**  
  Used **VGG16 (pre-trained on ImageNet)** to extract features from images without the top classification layers.

- **Similarity Calculation:**  
  Cosine similarity between feature vectors to rank similarity.

- **Interactive Recommendations:**  
  Displays input image alongside top recommended fashion items visually.

- **Python Libraries Used:**  
  `TensorFlow`, `Keras`, `NumPy`, `Matplotlib`, `PIL`, `SciPy`

---

## 📊 Sample Recommendation

**Input Image:**  
Anarkali suit with lavender color and intricate white patterns

**Top 4 Recommendations:**  
| Recommendation 1 | Recommendation 2 | Recommendation 3 | Recommendation 4 |
|-----------------|-----------------|-----------------|-----------------|
| ![Rec1](link_to_image1) | ![Rec2](link_to_image2) | ![Rec3](link_to_image3) | ![Rec4](link_to_image4) |



---

## 💻 Implementation Steps

1. **Data Preprocessing:**  
   Extract images from ZIP, resize to 224x224 for VGG16 input, and normalize.

2. **Feature Extraction:**  
   Use **VGG16 without top layers** to get flattened, normalized feature vectors.

3. **Recommendation Engine:**  
   - Compute cosine similarity between input image feature and all dataset features.
   - Rank images based on similarity scores.
   - Return top-N recommendations.

4. **Visualization:**  
   Display input image alongside recommended fashion items using Matplotlib.

---

## ⚡ Skills & Technologies

- **Deep Learning:** CNN feature extraction (VGG16), image embeddings  
- **Computer Vision:** Image preprocessing, similarity search  
- **Python Libraries:** TensorFlow, Keras, NumPy, SciPy, PIL, Matplotlib  
- **Data Handling:** Preprocessed Kaggle dataset, ZIP extraction, OS & file management  

---

## 🔗 Project Link

- GitHub Repository: [Fashion Item Recommendation](https://github.com/yourusername/fashion-recommendation)

---

## 📝 Takeaways

- Hands-on **feature extraction and similarity-based recommendations** in deep learning.  
- Practical experience with **VGG16, cosine similarity, and image preprocessing**.  
- Built a **recruiter-friendly, visual recommendation demo** showcasing deep learning applied to fashion.  

---

*Created with ❤️ by Vanashree G. Hegde*
