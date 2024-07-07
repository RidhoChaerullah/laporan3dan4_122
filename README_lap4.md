# Laporan Praktikum 4: EKSTRAKSI FITUR
## Ridho Chaerullah 202231122
### Pendahuluan
Tekstur pada citra adalah salah satu fitur penting dalam pengolahan citra yang dapat digunakan untuk segmentasi, klasifikasi, dan identifikasi objek. Gray Level Co-occurrence Matrix (GLCM) adalah salah satu metode statistik yang digunakan untuk mengekstrak fitur tekstur dari citra. GLCM menggambarkan bagaimana kombinasi pasangan piksel dengan nilai intensitas tertentu muncul dalam suatu citra.

### Tujuan
Penelitian ini bertujuan untuk menganalisis tekstur pada citra menggunakan pendekatan GLCM dan menghitung beberapa parameter statistik seperti kontras, dissimilarity, homogeneity, energy, dan correlation.

### Teori GLCM
GLCM adalah matriks yang menunjukkan frekuensi kemunculan pasangan piksel dengan intensitas tertentu pada jarak dan arah tertentu. Berikut adalah parameter-parameter yang dihitung dari GLCM:

- Kontras (Contrast): Mengukur seberapa banyak intensitas antara piksel dan tetangganya bervariasi. Kontras yang tinggi menunjukkan variasi intensitas yang besar.
- Dissimilarity: Serupa dengan kontras, tetapi lebih sensitif terhadap perubahan intensitas.
- Homogeneity: Mengukur keseragaman distribusi intensitas piksel. Nilai homogeneity yang tinggi menunjukkan bahwa intensitas piksel cenderung seragam.
- Energy: Mengukur kekompakan atau kesejajaran pasangan piksel. Energi yang tinggi menunjukkan adanya pola yang teratur.
- Correlation: Mengukur sejauh mana piksel dengan intensitas yang berbeda berkorelasi satu sama lain.
### Hasil Analisis
Analisis dilakukan pada tiga komponen citra: Hue, Saturation, dan Value. Hasil perhitungan parameter untuk masing-masing komponen adalah sebagai berikut:

#### HUE
1. Kontras: 8061.42
2. Dissimilarity: 81.20
3. Homogeneity: 0.00455
4. Energy: 0.03155
5. Correlation: -0.2585
#### SATURATION
1. Kontras: 12344.26
2. Dissimilarity: 94.44
3. Homogeneity: 0.00747
4. Energy: 0.05349
5. Correlation: -0.3813
#### VALUE
1. Kontras: 82.34
2. Dissimilarity: 5.47
3. Homogeneity: 0.2753
4. Energy: 0.02468
5. Correlation: 0.9603
### Kesimpulan
Analisis tekstur menggunakan GLCM dapat memberikan informasi penting mengenai karakteristik tekstur dari citra. Parameter-parameter yang dihitung memberikan gambaran tentang variasi intensitas, keseragaman, dan pola pada citra. Informasi ini dapat digunakan untuk berbagai aplikasi dalam bidang pengolahan citra seperti segmentasi dan klasifikasi objek.