Smart Agriculture Edge AI - LGM Aggressor Detection
Lightweight image classification model for detecting Legume Pod Borer (LGM) pest in crops, optimized for edge deployment.
# Install dependencies
pip install tensorflow numpy pillow matplotlib

# Train model
python smart.py

# Convert to TensorFlow Lite
python convert_to_tflite.py

# Test inference
python smart.py
```

## Project Structure
```
├── smart.py          # Model training script
└── README.md
Model Details

Architecture: MobileNetV2 (transfer learning)
Input Size: 224x224x3
Classes: Healthy, Infected
Optimization: INT8 quantization
Target: Raspberry Pi / Edge devices
