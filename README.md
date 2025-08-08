

# RGB CAMERAS

## 📌 Proje Amacı

Bu proje, **RGB-D kameraların** (renk + derinlik bilgisi) çalışma prensiplerini, kullanım alanlarını ve teknik uygulamalarını incelemeyi amaçlamaktadır. 
Çalışmada hem mevcut teknolojiler hem de gelecekteki yenilikler değerlendirilmiş, ayrıca Intel RealSense tabanlı iki algoritma uygulanarak pratik testler yapılmıştır.

---

## 📖 İçerik

* **RGB-D Kamera Teknolojisi**

  * Renk (RGB) ve derinlik (D) bilgisinin eş zamanlı yakalanması
  * Structured Light, Time-of-Flight (ToF), Stereo Vision teknikleri
* **Pazar ve Cihazlar**

  * Microsoft Kinect, Intel RealSense, Orbbec Astra vb.
* **Uygulama Alanları**

  * Mobil robotik (SLAM)
  * 3D rekonstrüksiyon
  * Sağlık teknolojileri (protez tasarımı, cerrahi planlama)
  * Biyometri (yüz tanıma sistemleri)
* **Güncel Trendler**

  * AI entegrasyonu
  * HDR derinlik görüntüleme
  * Daha yüksek hassasiyetli sensörler

---

## 🔬 Ana Bulgular

* RGB-D kameralar, 2010’da Kinect’in çıkışıyla geniş kitlelere ulaşmıştır.
* Her derinlik algılama teknolojisinin avantajları ve dezavantajları vardır.
* Donanım + algoritma gelişmeleri, gerçek zamanlı 3D tarama ve nesne takibini mümkün kılmıştır.
* Teknik kısıtlamalar arasında düşük ışıkta gürültü, ortam ışığına hassasiyet ve sınırlı menzil bulunur.

---

## 🚀 Gelecek Fırsatlar

* Mobil cihazlara entegre derinlik sensörleri
* Metaverse ve uzamsal hesaplama
* Kuantum nokta tabanlı sensörler
* AI ile daha akıllı derinlik algılama

---

## 💻 Uygulama ve Algoritmalar

### **Algoritma 1**

* **Amaç:** RGB ve derinlik verisini yakalama, merkez nokta mesafesini hesaplama
* **Donanım:** Intel RealSense kamera
* **Çıktı:** Renkli görüntü + renk haritalı derinlik görüntüsü

### **Algoritma 2**

* **Amaç:** Belirli renkteki nesneleri algılama ve takip etme
* **İşlem:** HSV renk uzayında maskeleme, kontur tespiti, dikdörtgen ve çizgi ekleme

---

## 📦 Kurulum ve Kullanım

1. Intel RealSense SDK’yı yükleyin.
2. Gerekli bağımlılıkları kurun (OpenCV, NumPy vb.).
3. İlgili algoritma dosyasını çalıştırın.
4. Kamera verilerini gerçek zamanlı izleyin.

---

## 📚 Kaynaklar

* Intel RealSense Documentation
* Microsoft Kinect Fusion
* Orbbec Astra Teknik Dokümanları

---

