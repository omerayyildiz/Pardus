# Pardus AutoSetup 
## **Pardus Otomatik Kurulum Aracı**
![Pardus Resim](/images/photo1.jpg)

[![GitHub license](https://img.shields.io/github/license/omerayyildiz/Pardus-AutoSetup)](https://github.com/omerayyildiz/Pardus-AutoSetup/blob/master/LICENSE) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/omerayyildiz/Pardus-AutoSetup)
![GitHub repo size](https://img.shields.io/github/repo-size/omerayyildiz/Pardus-AutoSetup)

## **Pardus AutoSetup Nedir?**

Live ya da normal kurulum sonrası açılan Pardus'a otomatik olarak belirlediğim uygulamaları indiren ve ayarlarımı yapan bir BASH Scripttir.

## **Nasıl Çalışır?**

 Ana dizinde bulunan kurulum başlatıcılarından, kullandığınız Pardus dağıtımına göre çalıştırınız.

 XFCE Kurulum:
 ```bash
 bash setupXFCE.sh
 ```
 Gnome Kurulum:
```bash
bash setupGnome.sh
```
## **Kullanmadan Önce Yapmanız Gerekenler**

- Ön kurulumda bulunan alanları doğru doldurmanız ve gerekli tüm paketlerin sayısını ve adlarını ilgili alanlara girmeniz yeterli olacaktır.

## **Hata Anında Ne Yapmalıyım?**
 
 Uygulama içi hata vermemek adına sürekli apt onarılıyor ve güncelleniyor. Fakat bazı iptal etme durumlarında apt arızalanabiliyor.

 Eğer,
 ```
E: /var/lib/dpkg/lock kilidi alınamadı - open (11: Özkaynak geçici olarak kullanılamaz durumda)

E: Yönetim dizini (/var/lib/dpkg/)kilitlenemiyor, başka bir işlem tarafından kullanılıyor olmasın?
```
hatasını alırsanız repair klasöründe bulunan apt-lock-error-solve.sh dosyasını çalıştırın.

Bağımlılık hatası aldığınızda ise apt-repair.sh'ı çalıştırabilirsiniz.

## **ÖNEMLİ NOT**
Klasör adları Pardus'ta Türkçe olduğundan dolayı İngilizce kurulum halinde hata ile karşılaşmamak adına **"~/İndirilenler"** adlı klasör yollarını **"~/Downloads"** olarak değiştirmeyi unutmayınız.

## **Örnek Kurulumlar**

[version 3.0](https://www.youtube.com/watch?v=4H4pc_ZkUGM)

[version 2.0](https://www.youtube.com/watch?v=cSXQsUMQ4z8)

[version 1.0](https://www.youtube.com/watch?v=QkfiUk5FyQc)

Ömer Ayyıldız
