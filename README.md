# 🥗 Menu Detector - OpenCV ve Python ile Menü Tanıma  
Bu proje, OpenCV kullanarak **renk ve şekil tanıma** yoluyla menü öğelerini algılar. Web kamerasından alınan görüntüde bulunan renkli ve farklı şekillere sahip nesneleri tespit eder ve ilgili menü öğesini belirler.  

## 📌 Özellikler  
✔️ OpenCV ile **gerçek zamanlı görüntü işleme**  
✔️ Renk ve şekil algılama  
✔️ **Kamera üzerinden anlık analiz**  
✔️ Nesne tabanlı programlama (OOP) yapısı  

## 🚀 Kullanılan Teknolojiler  
- Python 🐍  
- OpenCV 🎥  
- NumPy 🔢  

## 📸 Nasıl Çalışır?  
1️⃣ Kamera ile görüntü alır.  
2️⃣ **Renk filtresi** uygular (Kırmızı, Mavi, Yeşil, Sarı).  
3️⃣ Algılanan **şekilleri belirler** (Daire, Dikdörtgen, Üçgen).  
4️⃣ Tespit edilen renge ve şekle göre **menü önerisi yapar**.  

Örneğin:  
- **Kırmızı Daire → Çorba**  
- **Mavi Üçgen → Omlet**  
- **Yeşil Dikdörtgen → Güveç**  

## 🛠️ Kurulum ve Çalıştırma  
1️⃣ **Gerekli kütüphaneleri yükleyin**  
```bash
pip install opencv-python numpy
