# CNN-Lab-Untersuchung-von-Hyperparametern-bei-der-Erkennung-handgeschriebener-Ziffern

## 🧠 Projektübersicht

Dieses Projekt untersucht systematisch den Einfluss verschiedener Hyperparameter auf die Leistung eines Convolutional Neural Networks (CNN) zur Klassifikation handgeschriebener Ziffern anhand des MNIST-Datensatzes.

Der Fokus liegt nicht nur auf dem Training eines Modells, sondern auf der **experimentellen Analyse**

Angefangen hat das als Gruppe, jedoch habe ich mich dazu entschieden, mir das weiterhin genauer anzuschauen und weitere
Erfahrungen/Erkenntnisse zu sammeln.

---

## 🎯 Ziel des Projekts

- Training eines CNN auf dem MNIST-Datensatz
- Systematische Variation wichtiger Hyperparameter:
  - Learning Rate
  - Optimizer (SGD, Momentum, Adam)
  - Dropout-Rate
  - Netzwerk-Architektur (Filteranzahl / Tiefe)
  - Learning Rate Schedules (z. B. Exponential Decay)
- Analyse von Overfitting und Generalisierung
- Vergleich verschiedener Trainingskonfigurationen

---

## Starten des Projektes

- py-m venv .venv
- .venv\Scripts\activate
 
Installieren folgender Pakete:
- pip install tensorflow
- pip install keras
- pip install matplotlib  
- pip install numpy   
- pip install scikit-learn  

---

## 📊 Evaluationsmethoden

Die Modelle werden anhand folgender Methoden bewertet:

- Accuracy und Loss-Kurven
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)
- Visualisierung von Gewichten
- Visualisierung von Aktivierungen einzelner Schichten

---

## 🧪 Verwendete Technologien

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn

---

👉 [Projektbericht öffnen, und dann auf "Download raw file"](./Dokumentation_CNN_Lab.pdf)
