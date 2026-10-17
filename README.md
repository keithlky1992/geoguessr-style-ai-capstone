# GeoGuessr-style AI Capstone

## Research Question
Can a pretrained image embedding model combined with a simple classifier accurately predict the country of a street-view image from a balanced 8-country subset of OpenStreetView-5M, and how does its performance compare to a majority-class baseline in terms of Top-1 accuracy, Top-3 accuracy, and median great-circle distance error?

（淺白版）我們能不能用「已經訓練好的影像特徵模型 + 簡單分類器」，從一張街景照片準確猜出它屬於哪一個國家（從我們選的 8 個國家裡選）？它的表現比起「永遠猜最多圖片的那個國家」這個最簡單方法，在「猜對率」和「距離誤差」上好多少？

## Selected Countries (8)
- Japan
- France
- Brazil
- Australia
- India
- South Africa
- United States
- Thailand

## Dataset Size
- 400 images per country
- Total ≈ 3,200 images

## Data Split
- Train: 70%
- Validation: 15%
- Test: 15%

## Project Status
- Step 1–11 completed
- Next: Set up local environment and start exploring metadata


## Data Source
- Dataset: OpenStreetView-5M (OSV-5M)
- Source: https://huggingface.co/datasets/osv5m/osv5m
- Paper: CVPR 2024
- License: CC-BY-SA-4.0
- Note: We will only use a small balanced subset of 8 countries (≈3,200 images). Full attribution will be provided.

## Next Steps (Week 1)
1. Explore metadata of OpenStreetView-5M
2. Filter images belonging to the 8 selected countries
3. Sample approximately 400 images per country
4. Save metadata into SQL database
5. Perform basic EDA
