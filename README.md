# Klasifikasi Gunting, Batu dan Kertas

Project klasifikasi guntuing, batu dan kertas ini menggunakan model pretrained EfficientNetB3 yang diambil menggunakan pustaka tensorflow. Dataset project ini menggunakan dataset rock, paper, scissor dengan jumlah data sebanyak 2520 file. 

**Cara menggunakan project ini :**

1. python version >= 3.11 Clone repositori ini
```git clone https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask.git``` 
2. Masuk ke direktori repositori
3. Membuat sebuah venv 
```python -m venv ./rpsvenv```
4. Mengaktifkan venv
  - Command Prompt
```./rpesvenv/Scripts/activate.bat```
  - Powershell
```./rpesvenv/Scripts/activate.ps```

5. Lakukan install library yang diperlukan dengan perintah berikut
```pip install -r requirements```
6. Lalu jalankan flask
```python app.py```

7. Web dapat diakses dengan url ```http://192.0.0.1:5000```

**Modelling**

Model dibuat dengan model EfficientNetB3. Berikut adalah summary model:
![image](https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask/assets/145989415/99f6225c-d638-475b-8f92-34eada0ed295)

