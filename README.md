# Dual-Pathway-AlzheimerDetect-AI-Model
A Custom Dual-Pathway Deep Learning Architecture (DenseNet + EfficientNet) for 4-Class Alzheimer's MRI Detection. Achieved 97.34% accuracy with 1.00 Precision on severe cases.

# Dual-Pathway Alzheimer's MRI Classifier

A Custom Dual-Pathway Deep Learning Architecture (DenseNet + EfficientNet) for 4-Class Alzheimer's MRI Detection. Achieved 97.34% accuracy with 1.00 Precision on severe cases.

### Real-World AI Inference
![Real-World Inference Grid](images/The%206-Brain%20Inference%20Grid.jpg)

---

## 📊 Architecture Performance & Results

Standard single-pathway models struggle to process complex brain tissue textures without losing data. By engineering a Dual-Pathway ensemble, the AI processes both deep structural features (DenseNet) and broad tissue patterns (EfficientNet) simultaneously, resulting in a massive performance leap.

![Phase 1 vs Phase 2 Performance](images/Comparative%20Clinical%20Analytics.png)

---

## 🏥 Clinical Evaluation Metrics

The final Phase 2 model was evaluated on unseen, real-world validation data. The model achieved a flawless precision score on severe cases and successfully routed around standard false-positive bottlenecks.

![Final Confusion Matrix](images/final_confusionMatrix.png)

---

## 💻 Live Single-Patient Diagnosis

The finalized `.keras` brain is optimized for lightweight, real-time inference. Below is a live demonstration of the model predicting an unseen MRI scan on a standard CPU with zero computational bottleneck.

![Live Diagnosis Demo](images/demo.png)
