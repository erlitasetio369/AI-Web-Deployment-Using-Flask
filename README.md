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

# Modelling

Model dibuat dengan model EfficientNetB3. Berikut adalah summary model:

![image](https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask/assets/145989415/7afa8474-4804-4eb9-b370-7b78f38a07d5)

Train data dilakukan dengan ```10 epoch```. Akurasi yang didapatkan adalah ```0.34``` dan loss ```1.08```. Berikut adalah hasil plot dari accuracy, val accuracy, loss dan val loss.

Graph Loss dan Accuracy Model:

![image](https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask/assets/145989415/439a6f57-7579-4a0c-84bb-c0539ee834f6)
Setelah dilakukan train data, maka model disimpan dalam format ```h5.```

Evaluation Matrix Model:

![image](https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask/assets/145989415/d4f967e0-c387-49c1-89e6-62093c0d95ae)

# Predict Data

![image](https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask/assets/145989415/e12548a4-3fa1-418b-b491-9eee62fc2ac0)

# AI Web Deployment

1. User memilih model apa yang ingin digunakan. User juga bisa mengupload gambar dengan cara memilih langsung pada beberapa model yang telah ditampilkan.
2. Selanjutnya, user mengupload gambar yang ingin diuji.
3. Setelah itu, user melakukan execute untuk pengujian gambar.
![image](https://github.com/erlitasetio369/AI-Web-Deployment-Using-Flask/assets/145989415/339a980c-c0e6-4652-8d5e-9a0a869582d3)








