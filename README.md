# 📧 Advanced Spam Detection System

## 📝 Descrizione del Progetto
Pipeline completa di Natural Language Processing (NLP) e Machine Learning per filtrare le email, distinguendo la posta legittima (Ham) dallo Spam o Phishing. 

## 🎯 Obiettivi e Risultati
* **Feature Engineering:** Vettorizzazione del testo tramite TF-IDF e l'uso di n-grams (bigrammi).
* **Confronto Modelli:** Valutazione di Multinomial Naive Bayes, Linear SVC e Random Forest.
* **Topic Modeling e NER:** (Sviluppi futuri/integrazioni) Estrazione di entità nominate tramite spaCy e modellazione degli argomenti con LDA.
* **Risultati:** Modelli ottimizzati per ridurre i Falsi Positivi (email legittime finite nello spam) massimizzando l'F1-Score.

## 🛠️ Tecnologie e Librerie
* Python
* Scikit-Learn (TF-IDF, Naive Bayes, SVC, Random Forest)
* NLTK / spaCy
