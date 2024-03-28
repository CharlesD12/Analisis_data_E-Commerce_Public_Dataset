# ✨Charles Dometian Dashboard ✨
## Setup environment
```
conda create --name main-ds python=3.9
conda activate  main-ds
pip install pandas matplotlib numpy seaborn streamlit babel
```
## Run streamlit app
```
streamlit run dashboard.py
```
Link streamlit : https://submissiondicoding1.streamlit.app/

Jika requirement tidak bisa digunakan pada saat mengupload ke streamlit cloud, terdapat beberapa cara alternatif, diantaranya adalah :
1. Merename requirement menjadi **requirements.txt**
2. Pada requirement jangan menggunakan nama requirement namun menggunakan **pepreqs** supaya requirement yang dibutuhkan terisi otomatis.
3. Jika kedua cara tersebut juga tidak membuahhkan hasil, gunakan perangkat device lain kemudian install versi python yang kompatibel dengan versi streamlit cloud atau anda bisa mendowngrade versi python di device anda jika tidak mau menggunakan device lain (umumnya yang kompatibel mulai dari versi python 3.9 sampai python 3.11)
