# flask-web-AI

**Instalasi**
python version >= 3.11
Clone repositori ini
```git clone https://github.com/erlitasetio369/flask-web-AI.git```
Masuk ke direktori repositori
Buat sebuah venv
```python -m venv ./rpsvenv```
Aktifkan venv
- Command Prompt
```./rpesvenv/Scripts/activate.bat```
- Powershell
```./rpesvenv/Scripts/activate.ps```

Setelah itu install semua requirements
```pip install -r requirements```
Lalu jalankan flask
```python app.py```

Web dapat diakses dengan url ```localhost:5000```


**Dataset**
Project ini menggunakan dataset rock paper scissor dengan jumlah data sebanyak 2520 file. Load image menggunakan image_dataset_from_directory dari pustaka tensorflow dengan pembagian train validation 80% dan test validation 20% dengan seed 123. Dataset menggunakan label categorical sehingga label dalam bentuk one hot encoding. Image size menggunakan (224, 244) dan batch size menggunkan 128
