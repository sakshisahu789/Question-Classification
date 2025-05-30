# Question-Classificati
# Quantum-Enhanced Transformers for GATE CSE Question Classification

This project explores the effectiveness of **quantum-enhanced transformer models** in improving the performance of question classification, using **GATE CSE** questions across 8 core topics. We benchmark classical transformer models and introduce quantum encoding techniques to push the boundaries of accuracy and efficiency.

---

## Dataset

The dataset was **manually curated** and consists of a total of **2400 questions** from the **GATE CSE** domain, distributed evenly across the following 8 categories:

- Computer Networks  
- Operating System  
- Programming & Algorithms  
- Mathematics  
- General Aptitude  
- Theory of Computation  
- Computer Organization & Architecture  
- Digital Logic  

Each topic contains exactly **300 questions**.

 **[Dataset on Kaggle → (Link to be added)]**

If you use this dataset in your research or project, please cite:
Sahu, S. (2025): GATE CSE Question Classification Dataset. Retrieved from [Kaggle URL].

---

## Classical Transformer Benchmarking

We benchmarked five popular transformer models:

- `BERT`
- `DistilBERT`
- `RoBERTa`
- `XLNet`
- `ALBERT`

### Experimental Setup

- **Cross-Validation:** 5-Fold
- **Epochs:** 5
- **Metrics Evaluated:** Accuracy, Precision, Recall, F1 Score
- **Hyperparameter Tuning** was applied to optimize each model.

 The model with the **highest classification accuracy** was selected as the baseline for quantum enhancement.

---

## Quantum Enhancement

To enhance the best-performing transformer model, we introduced **quantum computing techniques** using the following pipeline:

1. **BERT Embeddings** were extracted from the input text.
2. **Dimensionality Reduction** was applied using **PCA**.
3. **Quantum Embedding Techniques**:
   - **Direct Amplitude Encoding**
   - **Segmented Amplitude Encoding**

These quantum embeddings were passed to a **quantum-inspired classifier** to evaluate performance improvements over the classical approach.

## Tech Stack

- Python
- PyTorch / TensorFlow
- HuggingFace Transformers
- Pennylane / Qiskit
- scikit-learn
- NumPy / Pandas / Matplotlib


---

## Future Work

- Experiment with other quantum embedding techniques (e.g., angle encoding, QSVT)
- Extend dataset to include other competitive exams
- Deploy as a web service for real-time GATE question classification

---

## Contact & Contributions

Contact & Contributions
For questions, feedback, or contributions, reach out at:
Email: sakshisahu0920@gmail.com
GitHub: https://github.com/sakshisahu789

---

## 📎 License

This project is licensed under the CC0: Public Domain License.


