
# Skip-Gram + PCA + KMeans NLP Mini-Project

## 📌 Overview
This project implements a complete NLP pipeline from scratch:

1. **Training a Skip-Gram model** using PyTorch  
2. **Extracting word embeddings**  
3. **Applying PCA (ACP)** to reduce embeddings to 2D  
4. **Clustering words using K-Means** (with cosine distance via L2 normalization)  
5. **Visualizing semantic clusters**

Everything is fully implemented inside the final notebook:

➡️ `Skip-Gram + PCA + KMeans.ipynb`  
(Training + PCA + KMeans + Visualization)

---

## 🚀 Features

### ✔ Skip-Gram (Word2Vec-like)
- Custom dataset generation  
- PyTorch neural network  
- Negative sampling–ready architecture  
- Multiple epochs training

### ✔ PCA (ACP)
- Dimensionality reduction  
- Projection of embeddings into 2D space  
- Easy interpretation of semantic spaces

### ✔ KMeans Clustering
- Uses cosine distance (via normalization)  
- Groups words by semantic similarity  
- Visualization with PCA plots

---

## 📁 Project Structure

```
📦 your-project/
 ┣ 📜 Skip-Gram + PCA + KMeans.ipynb
 ┣ 📜 README.md  ← (this file)
 ┗ 📂 data/ (optional)
```

---

## 🛠 Installation

```bash
pip install torch scikit-learn matplotlib numpy
```

---

## ▶️ Run the Notebook

Open Jupyter:

```bash
jupyter notebook
```

Then run:

```
Skip-Gram + PCA + KMeans.ipynb
```

---

## 📊 Output Examples

- Word embeddings  
- PCA 2D visualization  
- KMeans clustered graph  
- Interpretation of clusters

---

## 🧠 Cluster Interpretation Example

| Cluster | Related Words |
|--------|---------------|
| 0 | maroc, marrakech, rabat |
| 1 | intelligence, apprentissage, données |
| 2 | ville, capitale, centre |
| 3 | fonctionnels (le, la, de, un…) |

## 👤 Author
**Abdellah Lambaraa**  
Full-Stack Developer

---

## 📧 Contact
Feel free to reach out for improvements or contributions!
