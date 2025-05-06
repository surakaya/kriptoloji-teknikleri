# Kriptoloji Steganografi Ödevi

Bu proje, kriptoloji dersi kapsamında verilen **steganografi teknikleriyle ses ve video verilerine gizli mesaj gömme ve çıkarma uygulamalarını** içermektedir.

## Kullanılan Teknikler:

1. **LSB (Least Significant Bit)**
2. **JPEG (DCT) Algoritması**
3. **BPCS (Bit Plane Complexity Segmentation)**
4. **Maskeleme ve Filtreleme**
5. **Sezgisel Steganaliz Yöntemleri**

Her teknik için ayrı Python dosyaları hazırlanmış ve gizli mesaj (160 karaktere kadar) ses ya da görsel veriye gömülmüştür.

## Kullanım

Her klasör içinde:
- Gömme işlemi (örneğin: `lsb_gomme.py`)
- Mesaj çıkarma işlemi (örneğin: `lsb_cikar.py`)
- Örnek veri dosyası (örneğin: `.wav` ya da `.jpg`)
bulunmaktadır.

## Gereksinimler

- Python 3.x
- `numpy`, `opencv-python`, `scipy`, `matplotlib`, `wave` vb. kütüphaneler.

## Not

Bu proje eğitim amaçlıdır. Yüklediğiniz medya dosyaları `.wav` ve `.jpg` formatındadır. Her algoritma ayrı klasörde sunulmuştur.

---

Hazırlayan: `Zeynep Şura Kaya`  
Ders: Kriptoloji  
