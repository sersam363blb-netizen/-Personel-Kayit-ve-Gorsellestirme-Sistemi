# Personel Kayıt ve Görselleştirme Sistemi

C# ve SQL kullanılarak geliştirilmiş masaüstü uygulaması.  
Kullanıcılar personel ekleyip çıkarabilir, güncelleyebilir ve grafiklerle personel durumlarını analiz edebilir.

---

## 🚀 Özellikler
- SQL veritabanına bağlı personel kayıt sistemi  
- Personel ekleme, silme, güncelleme ve listeleme  
- İstatistiksel veriler: toplam personel sayısı, medeni durum, şehir dağılımı, ortalama maaş  
- Grafiklerle görselleştirme (Chart kontrolü)  
- Basit giriş ekranı ile kullanıcı doğrulama  
- Windows Forms arayüzü

---

## 🧩 Kullanılan Teknolojiler
- **C# (.NET Framework 4.7.2)**  
- **Windows Forms**  
- **SQL Server (MSSQL)**  
- **ADO.NET** (veri bağlantısı için)

---

## 🗄️ Veritabanı Bilgisi
Veriler **SQL Server** üzerinde `Tbl_Personel` adlı tabloya kaydedilir.  
Uygulama personel ekleme, silme ve güncelleme işlemlerini doğrudan SQL üzerinden yapar.  

Tablo örneği:
| Sütun Adı | Veri Tipi | Açıklama |
|------------|------------|-----------|
| Perid | int | Otomatik artan ID |
| PerAd | varchar(50) | Personel adı |
| PerSoyad | varchar(50) | Personel soyadı |
| PerSehir | varchar(50) | Personel şehir bilgisi |
| PerMaas | int | Maaş bilgisi |
| PerDurum | bit | Medeni durum |
| PerMeslek | varchar(50) | Meslek |

---

## 📊 Ekran Görüntüleri

### 🔐 Giriş Ekranı
![Giriş Ekranı](Ekran%20Görüntüsü%20(559).png)

### 🧾 Personel Yönetimi
![Personel Yönetimi](Ekran%20Görüntüsü%20(560).png)

### 📈 İstatistik ve Grafik Görünümü
![Grafikler ve İstatistik](Ekran%20Görüntüsü%20(561).png)
![Grafikler ve İstatistik](Ekran%20Görüntüsü%20(562).png)


---


