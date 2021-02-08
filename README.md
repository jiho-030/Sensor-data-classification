# AI data Hackathon 🔧_ 시계열정맨팀
---
[2020 기계 시설물 분야 AI 학습용 데이터 활용 경진대회](https://www.aidatahackathon.com/) 

## ✔Topic

- 기계 시설물 분야 AI 학습용 데이터 활용 기계 시설물의 고장 여부 예측 모델 개발 
---

## ✔Our Code Structure

```
Sensor-data-classification
├── README.md
├── data
│   ├── kimm.csv
│   ├── vibration_interp.csv
│   ├── curR.csv
│   ├── curT.csv
│   └── curS.csv
├── feature_classification (trial)
│   ├── pre-processing
│   │     ├── feature_extract.py
│   │     ├── feature_extract_cur.py
│   │     └── preprocessing.py
│   ├── model
│   │     ├── fcn.py
│   │     ├── knn.py
│   │     └── svm.py
│   ├── train.py
│   └── test.py
├── time_series_classification (final)
│   ├── pre-processing
│   │     └── data_augmentation_shift.ipynb
│   ├── classifiers
│   │     ├── fcn.py
│   │     ├── fcn4cur.py
│   │     ├── resnet.py
│   │     └── lstm_fcn.py
│   ├── utils
│   │     ├── utils.py
│   │     ├── utils4cur.py
│   │     └── pip-requirements.txt
│   ├── main.py
│   └── main4cur.py
└── Submission.ipynb
   
```
---
## ✔Our Score

||best valid accuracy(kimm)|best valid accuracy(vibration)|best valid accuracy(current)|final test score|
|---|---|---|---|--|
|our model|0.8943%|0.9521%|0.7535%|100점/150점|

---
## ✔Reference

- https://github.com/hfawaz/dl-4-tsc
- https://github.com/jeandeducla/ML-Time-Series
---
## Contributors

- [👩](https://github.com/jiho-030) Jiho Lee
- [👩](https://github.com/kole2706) Eunji Ko
- [👩](https://github.com/lilly9117) Hyebin Choi
---
