# 🔍 Feature Matcher Pro

Feature Matcher Pro is an interactive **Streamlit application** for benchmarking and visualizing **local feature extraction and matching** methods on image pairs.  
It compares **learning-based approaches** (SuperPoint, DISK + LightGlue) with the **classical SIFT** baseline, while providing **accurate inference timing** and clear visual results.

---

## ✨ Features

- 🧠 Learning-based & classical feature extractors  
  - SuperPoint + LightGlue  
  - DISK + LightGlue  
  - SIFT (OpenCV)

- ⏱️ Accurate inference timing  
  - Model loading excluded  
  - CUDA synchronization for precise GPU timing  

- 🧩 Custom match visualization  
  - Concatenated images  
  - Colored match lines  
  - Keypoints drawn on top  

- 🖥️ CPU & GPU support  
  - Automatic device detection  
  - GPU warm-up for fair benchmarking  

- 🛡️ Memory-safe execution  
  - Image resizing  
  - Explicit garbage collection  
  - CUDA cache cleanup  
  - Graceful out-of-memory handling  

---

## 🧪 Supported Methods

| Method        | Type           | Description |
|---------------|----------------|-------------|
| SuperPoint    | Learning-based | Fast and robust for general scenes |
| DISK          | Learning-based | Strong under viewpoint changes |
| SIFT          | Classical CV   | Reliable baseline |

---

## 📊 Metrics Displayed

- **Pure Inference Time (seconds)**
- **Number of keypoints** detected in each image
- **Total matches found**
- **Match ratio (%)**

---

## 🖼️ Visualization

- Matches drawn using OpenCV
- Adjustable match color
- Thin, anti-aliased match lines
- All matches displayed by default

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/feature-matcher-pro.git
cd feature-matcher-pro
