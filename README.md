# Laporan Tugas Machine Learning
## Nama : Fathan Naufal R
## NIM : 211351054
## Kelas : Informatika Pagi B

## Domain Proyek
  Memprediksi kanker payudara secara dini dapat membantu mengidentifikasi kasus kanker sebelum gejala muncul atau sebelum kanker mencapai tahap lanjut. Deteksi dini meningkatkan peluang kesembuhan dan mengurangi resiko penyebaran kanker pada organ lain, memprediksi mulai dari tekstur,area,kecekungan,radius, DLL. untuk mengidentifikasikan jenis kanker Ganas atau Jinak.

## Business Understanding
  Kanker merupakan penyakit yang sulit untuk di obati, karenanya perusahaan dan lembaga terlibat mengembangkan strategi bisnis yang lebih efektif, menciptakan produk dan layanan yang lebih baik, dan memberikan dukungan yang lebih baik bagi pasien dan individu yang terkena dampak kanker payudara. Juga mempermudah pembuatan obat jika sudah diketahui diagnosanya terlebih dahulu, maka dari itu dibuat lah prediksi jenis kanker payudara ini.

### Problem Statements
- Mahalnya biaya jika harus mengidetifikasikan jenis kanker, apakah kanker tersebut kanker ganas atau kanker jinak

### Goals
- Mencari cara untuk memprediksikan jenis kanker melalui diagnosa yang kita ketahui

### Solution Statement
- Dapat mengidentifikasikan jenis kanker yang dialami para pengidap dengan melihat diagnosanya (Dengan membandingkan dengan dataset)
- Membuat penelitian tentang kanker payudara untuk mengidentifikasikan jenisnya (dengan algoritma SVM)

## Data Understanding
(Breast Cancer Dataset [https://www.kaggle.com/datasets/imtkaggleteam/breast-cancer])

Pertama-tama kita akan mengimport library yang di butuhkan
``` python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import StandardScaler
from sklearn.model_selection import train_test_split
from sklearn import svm
from sklearn.metrics import accuracy_score
from sklearn.preprocessing import OrdinalEncoder
'''

