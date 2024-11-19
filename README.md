# Tổng quan
<p align="center">
  <b>Sơ đồ nối chân</b><br>
  <img src="3.png" alt="Mô tả hình ảnh 1" width="600"/>
</p>

</p>

# Kết quả 
# Cài đặt môi trường chạy venv 
<p align="center">
  <b>Sơ đồ nối chân</b><br>
  <img src="1.png" alt="Mô tả hình ảnh 1" width="600"/>
</p>
<p align="center">
  <b>Sơ đồ nối chân</b><br>
  <img src="2.png" alt="Mô tả hình ảnh 1" width="600"/>
</p>
# Preprocesscing với dữ liệu mới 
```python src/align_dataset_mtcnn.py  Dataset/FaceData/raw Dataset/FaceData/processed --image_size 160 --margin 32  --random_order --gpu_memory_fraction 0.25```

# Tiến hành train
```python src/classifier.py TRAIN Dataset/FaceData/processed Models/20180402-114759.pb Models/facemodel.pkl --batch_size 1000```
