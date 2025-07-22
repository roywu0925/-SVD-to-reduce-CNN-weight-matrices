# 🧠 SVD-CNN Compression: Reduce Inference Latency on Edge Devices

🎯 **Goal**: Reduce CNN inference latency and model size using SVD-based compression  
🛠️ **Method**: Apply Singular Value Decomposition to prune low-rank filters in ResNet-18  
📈 **Result**: −38% parameters, −24% latency, accuracy drop < 0.4% on CIFAR-10

You can:
- Inspect each convolutional layer’s rank and singular value spectrum
- Choose energy threshold (e.g., 80%) to retain
- Measure latency and accuracy tradeoffs
