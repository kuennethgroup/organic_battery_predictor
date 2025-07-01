    
# Organic Battery Predictor 🔋

This repository is based on our published work, bringing AI to the forefront of battery material discovery! ✨

---

### Our Publications

* **Journal Publication:** Our research, "[AI-Driven Discovery of High Performance Polymer Electrodes for Next-Generation Batteries](https://doi.org/10.1002/pol.20250198)," is published in the Journal of Polymer Science. 📖
* **Preprint Version:** You can also check out the preprint on arXiv: [arXiv:2502.13899](https://doi.org/10.48550/arXiv.2502.13899). 🧪

---

### Project Files

This project includes the following key files to help you explore and utilize our models:

1.  `multi_task_learning.ipynb`: 🧠 This notebook handles loading the organic battery dataset, performing data scaling and splitting, and training models across 5 folds for robust results.
2.  `meta_learner.ipynb`: 📊 Here, we load the 5 multi-task models (one for each fold) and then train on the validation dataset (with testing on the training set) to refine predictions.
3.  `inverse_design.ipynb`: 💡 Use this notebook to specify reference candidate(s), modify SMILES strings, and predict new properties using the power of our pre-trained models for inverse design!
