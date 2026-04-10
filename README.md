# Data Mining Project: Melbourne Housing & IMDB Dataset

## Tổng quan
Dự án này thực hiện phân tích, tiền xử lý và trực quan hóa dữ liệu trên ba loại dữ liệu:
- **Dữ liệu tabular**: Melbourne Housing (giá nhà, đặc trưng bất động sản)
- **Dữ liệu hình ảnh**: Bộ ảnh rau củ (Vegetable Image Dataset)
- **Dữ liệu văn bản**: IMDB Movie Reviews

Các notebook cung cấp các bước EDA, tiền xử lý, mã hóa, chuẩn hóa, phát hiện ngoại lai, phân tích văn bản và hình ảnh.

## Cấu trúc thư mục
```
notebooks/
  01_EDA_image.ipynb              # Khám phá dữ liệu ảnh
  02_preprocessing_image.ipynb     # Tiền xử lý dữ liệu ảnh
  03_EDA_tabular.ipynb             # Khám phá dữ liệu tabular
  04_preprocessing_tabular.ipynb   # Tiền xử lý dữ liệu tabular
  05_text_preprocessing.ipynb      # Tiền xử lý dữ liệu văn bản
```

## Hướng dẫn cài đặt & chạy
1. **Cài đặt Python >= 3.8**
2. **Cài đặt các thư viện cần thiết:**
   ```bash
   pip install -r requirements.txt
   ```
3. **(Khuyến nghị) Cài đặt thêm model tiếng Anh cho spaCy:**
   ```bash
   python -m spacy download en_core_web_sm
   ```
4. **Chạy các notebook:**
   - Mở thư mục `notebooks/` và chạy từng notebook theo thứ tự để xem các bước phân tích và tiền xử lý.

## Tài nguyên dữ liệu
- **Melbourne Housing Dataset:**
  - [Kaggle Link](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)
- **Vegetable Image Dataset:**
  - [Kaggle Link](https://www.kaggle.com/datasets/kritikseth/vegetable-image-dataset)
- **IMDB Movie Reviews:**
  - [Kaggle Link](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Liên hệ
- Nếu có thắc mắc hoặc góp ý, vui lòng liên hệ nhóm thực hiện qua email hoặc github.
