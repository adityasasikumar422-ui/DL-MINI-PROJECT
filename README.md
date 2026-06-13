PlantLeafNet – Advanced Plant Disease Detection using Transfer
Learning & Optimization
Dear Mentees,
You are now tasked with building a robust and production-ready deep learning system for
plant disease identification. This assignment emphasizes efficient model design,
systematic experimentation, strong evaluation, and practical deployment. Leverage your

existing knowledge of CNNs, transfer learning, and PyTorch/TensorFlow to deliver a high-
quality solution within the given timeframe.

Assignment Objectives
• Develop a high-accuracy plant disease classification model with proper fine-tuning
and optimization strategies.
• Conduct thorough experimentation and ablation studies.
• Ensure strong model interpretability and deployment readiness.
• Deliver actionable insights for real-world agricultural use.

Dataset Information
Source: PlantVillage Dataset
Download Link: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset
Guidelines
Section 1: Data Understanding & Preparation
• Perform detailed exploratory analysis including class distribution, image statistics,
and quality assessment.
• Implement advanced data augmentation strategies (consider Albumentations or
custom transforms).
• Design an efficient data pipeline (tf.data or PyTorch DataLoader) with proper
preprocessing and augmentation.
• Decide on and justify your train/validation/test split strategy.
Section 2: Model Development & Training

• Select and compare at least two pre-trained backbones (e.g., EfficientNetB0,
MobileNetV2, ConvNeXtTiny, or ResNet50).
• Design a custom classification head with appropriate regularization techniques
(Dropout, Label Smoothing, etc.).

• Implement staged training: initial head training followed by selective layer fine-
tuning with differential learning rates.

• Experiment with optimizers, schedulers, and loss functions. Use callbacks or
training loops effectively to prevent overfitting.
Section 3: Model Evaluation & Analysis
• Evaluate using comprehensive metrics (Accuracy, Macro/Micro F1, Per-class
Precision/Recall).
• Generate detailed visualizations: learning curves, confusion matrix, per-class
performance analysis.
• Conduct error analysis and discuss architectural or data-related limitations.
Section 4: Optimization, Deployment & Insights
• Optimize the model for inference (quantization, pruning, or TensorRT/OpenVINO if
using PyTorch).
• Build an interactive web demo using Gradio / Streamlit / Flask with features like
confidence thresholding and result explanation.
• Compare your best model against baseline approaches in terms of accuracy,
speed, and model size.
• Provide deep insights and realistic recommendations for deployment in agricultural
settings.
