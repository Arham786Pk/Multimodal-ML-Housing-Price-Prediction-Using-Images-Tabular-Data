🏠 CNN + Tabular Data Fusion Model
🔹 Key Features:

Image Branch: Pretrained ResNet50 (feature extraction)

Tabular Branch: Structured data (bedrooms, location, etc.)

Fusion: Concatenated features → XGBoost Regressor

Achieved 15% lower MAE vs tabular-only baseline

📉 Evaluation Metrics:

MAE: $18,500 | RMSE: $27,300

Ablation studies on modality importance
