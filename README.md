# Tehlikeli Nesne Tespiti Yapay Sinir Ağı Projesi 🚨
![image](https://github.com/user-attachments/assets/69d024fb-00b4-43d5-a028-6b1330c3a51c)

Bu proje, tehlikeli nesnelerin tespiti için **Yapay Sinir Ağı (YSA)** ve **YOLOv11** modelini kullanarak geliştirilmiştir. Model, çeşitli tehlikeli nesneleri tanımak için eğitilmiş olup, gerçek zamanlı nesne tespiti yapabilmektedir. Proje, **Google Colab** ortamında çalıştırılmıştır ve YOLOv11 modelinin son versiyonu kullanılmıştır.

## 🔍 Proje Açıklaması

Bu proje, çeşitli tehlikeli nesneleri tespit etmek için derin öğrenme tabanlı bir yaklaşım kullanır. YOLOv11, yüksek doğrulukla nesneleri tanımlayabilen hızlı ve etkili bir modeldir. Proje, nesne tespiti için geniş bir veri kümesi üzerinde eğitilmiş ve farklı senaryolarda test edilmiştir.

### Özellikler
- 🚀 **Gerçek Zamanlı Nesne Tespiti**: Video akışları üzerinde tehlikeli nesnelerin hızlı tespiti.
- 🧠 **Yapay Sinir Ağı ile Eğitilmiş Model**: YOLOv11 modeli kullanılarak yüksek doğruluk elde edilmiştir.
- 🎯 **Yüksek Doğruluk**: Tehlikeli nesneleri doğru bir şekilde tespit eder.
- 📊 **Kolay Kullanım**: Google Colab üzerinden çalıştırılabilir ve eğitilebilir.

## 💻 Kullanılan Teknolojiler

- **Python 3.x** 🐍
- **YOLOv11** 🟢
- **Google Colab** ☁️
- **OpenCV** 👁️
- **TensorFlow / Keras** 🧠

## 📊 Veri Kümesi

Veri kümesi, tehlikeli nesneleri tanımak amacıyla Roboflow üzerindnen çeşitli etiketlemelerle oluşturulmuştur. Veri kümesinin içeriği şunlardır:

**Toplam Görsel Sayısı**: 8837
**Sınıflar**:
🔪 **Knife**: Kesici aletler
🗡️ **Weapon**: Silahlar
✅ **Normal**: Günlük nesneler
✂️ **Scissors**: Makaslar
🚨 **Suspicious**: Şüpheli nesneler (diğer potansiyel tehlikeli objeler)

Her görselin, nesnenin türü ve konumu hakkında bilgi içeren etiketlerle birlikte geldiği bu veri kümesi, modelin eğitimi için kullanılmıştır.

### Veri Dağılımı:
**Eğitim Seti**: %73
**Doğrulama Seti**: %19
**Test Seti**: %8

## 🚀 Kurulum Talimatları

Proje Google Colab ortamında çalışacak şekilde yapılandırılmıştır, bu yüzden özel bir kurulum gerekmemektedir. Colab'da projenizi başlatmak için aşağıdaki adımları takip edebilirsiniz.


### 📸 Ekran Görüntüleri
Aşağıda modelin tespit ettiği nesnelerin örnek ekran görüntülerini görebilirsiniz:

![output](https://github.com/user-attachments/assets/4b9f0806-8896-4e1e-8a7a-6e22922a9bc6)

## 🔧 Yapılabilecek İyileştirmeler

- ⏳ **Epoch Sayısı Artırılabilir**: Daha uzun eğitim süreçleri, modelin doğruluğunu artırabilir.  
- 🖼️ **Görsel Sayısı Artırılabilir**: Daha büyük bir veri kümesiyle modelin genelleme kabiliyeti iyileştirilebilir.  
- 🎭 **Sınıf Çeşitlendirilebilir**: Yeni sınıflar eklenerek modelin kapsamı genişletilebilir.  
- 🚀 **Daha Güçlü GPU Kullanılabilir**: Yüksek işlem gücü sağlayan GPU'lar, eğitim süresini kısaltarak daha karmaşık modellerin eğitilmesine olanak tanır.  

### 🤝 Katkı Sağlama
Projenize katkıda bulunmak isterseniz, lütfen bir pull request gönderin. Katkılarınız için teşekkür ederiz! 🎉
