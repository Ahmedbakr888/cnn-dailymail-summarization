# 🧠 CNN/DailyMail Summarization

This project demonstrates **text summarization** on the CNN/DailyMail news dataset. It applies both **abstractive** and **extractive** approaches to generate summaries for news articles.

---

## ✂️ Approaches Used

- **Abstractive Summarization**: BART-large-CNN (Hugging Face Transformers)  
- **Extractive Summarization**: TextRank (Sumy)

---

## 📌 Project Overview

Text summarization is an NLP task that condenses text while preserving meaning. In this project, we:

- Load and preprocess the CNN/DailyMail dataset  
- Generate summaries using BART (abstractive)  
- Generate summaries using TextRank (extractive)  
- Compare summaries to reference summaries using ROUGE metrics  
- Visualize ROUGE scores

---

## 🛠️ Technologies Used

- Python 3  
- Hugging Face Transformers  
- Datasets  
- Evaluate & ROUGE  
- Sumy (TextRank)  
- Pandas & Matplotlib  
- Jupyter Notebook  

---

## 📂 Dataset

**CNN/DailyMail v3.0.0**  

The dataset contains:

- News articles  
- Reference summaries (highlights)  

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/cnn-dailymail-summarization.git
cd cnn-dailymail-summarization
pip install -r requirements.txt
```
##▶️ How to Run

1. Open the notebook:  
   `notebooks/summarization_pipeline.ipynb`  
2. Run all cells sequentially. The notebook will:  
   - Load dataset  
   - Generate abstractive summaries (BART)  
   - Generate extractive summaries (TextRank)  
   - Evaluate ROUGE metrics  
   - Save results to CSV  

---

## 🔎 Example

**Article (excerpt):**  
> The Palestinian Authority officially became the 123rd member of the International Criminal Court on Wednesday...

**Abstractive Summary (BART):**  
> Membership gives the ICC jurisdiction over alleged crimes committed in Palestinian territories...

**Extractive Summary (TextRank):**  
> (CNN)The Palestinian Authority officially became the 123rd member of the International Criminal Court on Wednesday, a step that gives the court jurisdiction over alleged crimes in Palestinian territories...

---

## 🚀 Future Improvements

- Fine-tune BART on a custom dataset for improved performance  
- Evaluate on larger test set  
- Compare other summarization models (T5, Pegasus)  
- Deploy as a web app (Streamlit or Gradio)  

---

## 👨‍💻 Author

**Ahmed Bakr**  
Python | NLP | Data Science Enthusiast
