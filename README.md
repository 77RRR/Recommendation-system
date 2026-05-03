🛍️ Hybrid Product Recommendation System (Text + Image)

A smart recommendation system that suggests products based on **text queries** and **uploaded images** using **NLP + Computer Vision** techniques.

🚀 Features

🔍 Text-Based Search

   Uses transformer-based embeddings to find similar products from user queries.

   Image-Based Recommendation
  * Upload an image and get visually similar product suggestions.

 ⚡ Fast Similarity Matching

  Uses cosine similarity for efficient recommendations.

🌐 Web Interface

  Built with Flask for easy interaction

🧠 Tech Stack

Backend: Flask (Python)
NLP Model: Sentence Transformers (`paraphrase-MiniLM-L6-v2`)
Computer Vision: ResNet50 (pretrained on ImageNet)

Libraries:

  * NumPy, Pandas
  * Scikit-learn
  * TensorFlow / Keras
  * Pillow (PIL)

---

📁 Project Structure

```
├── app.py
├── data/
│   ├── products.csv
│   ├── styles.csv
├── static/
│   └── images/
├── templates/
│   ├── index.html
│   ├── results.html
├── README.md
└── requirements.txt
```
⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/hybrid-recommendation-system.git
cd hybrid-recommendation-system
```

 2. Create virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

 ▶️ Running the Application

```bash
python app.py
```

Then open:

```
http://127.0.0.1:5000/
```



🧪 How It Works
🔤 Text Recommendation

1. User enters a query
2. Query is converted into embeddings using SentenceTransformer
3. Compared with product titles
4. Top similar products are returned


🖼️ Image Recommendation

1. User uploads an image
2. Image is processed using ResNet50
3. Feature embeddings are extracted
4. Compared with dataset images
5. Most similar products are returned



📊 Evaluation Metrics

The system includes evaluation using:

* Precision
* Recall
* F1 Score


## 👨‍💻 Author

**Ranjeeth Kumar Patra**

---

## ⭐ Show Your Support


