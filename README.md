# Feature Matching Benchmark

**Authors:** Zakaria Zaouak, Salma Azzimani, Lina Toumi

## Overview
This project benchmarks **local feature extractors** and **matchers** on a pair of images, providing insights into matching quality, efficiency, and robustness under common image transformations.  

We evaluate:  
- **Extractors:** SuperPoint, DISK, SIFT  
- **Matcher:** LightGlue  

Additionally, we test the robustness of **SuperPoint + LightGlue** under variations such as **rotation**, **brightness changes**, and **blur**.

## Metrics Collected
- Number of keypoints detected per image  
- Number of matches between image pairs  
- Execution time for extraction and matching  
- Matching robustness under controlled transformations

## Visualizations
- Keypoints plotted on images  
- Matches visualized between image pairs  
- Comparison charts showing performance across extractors and variations

## Usage
- The project is fully **Google Colab-ready**.  
- Open the notebook in Colab and run all cells; no installation needed.  
- Image variations are generated automatically within the notebook.  

## Notes
- Image variations are tested **only for SuperPoint + LightGlue**.  
- Original image comparison includes **all three extractors**.  

