# 🏢 Aksaray Konutları - Apartman Yönetim Paneli

Bu proje, site ve apartman yönetim süreçlerini dijitalleştirmek amacıyla geliştirilmiş, mobil uyumlu ve kullanıcı dostu bir web arayüzüdür. 

**Not:** Bu sürüm GitHub Pages üzerinde çalışabilmesi için **Serverless (Sunucusuz)** modda tasarlanmıştır. Veritabanı olarak tarayıcının `LocalStorage` özelliğini kullanır. Sayfayı yenileseniz bile verileriniz kaybolmaz (tarayıcı önbelleği temizlenene kadar).

🔗 **Canlı Demo:** [Buraya GitHub Pages Linkinizi Yapıştırın](https://kullaniciadi.github.io/repo-adi)

---

## 🚀 Özellikler

* **📱 Mobil Uyumlu Tasarım:** Telefon, tablet ve masaüstünde sorunsuz çalışan responsive arayüz (Tailwind CSS).
* **👥 Rol Bazlı Yetkilendirme:** Yönetici, Personel ve Site Sakini için özelleştirilmiş paneller.
* **📢 Duyuru Sistemi:** Acil durum ve genel bilgilendirme duyuruları (Acil durumlarda yanıp sönen uyarı barı).
* **🛠️ Şikayet & Talep Yönetimi:** * Sakinler fotoğraflı (simülasyon) arıza kaydı oluşturabilir.
    * Yönetim durum güncellemesi yapabilir (İnceleniyor, Çözüldü vb.).
* **💬 Mesajlaşma:** Personel ve Yönetici arasında dahili mesajlaşma sistemi.
* **📊 İstatistikler:** Blok bazlı ısı haritası ve şikayet durum grafikleri (Chart.js).
* **🔔 Bildirim Sistemi:** Yeni mesaj veya güncelleme olduğunda anlık bildirimler.

---

## 🔐 Giriş Bilgileri (Demo Hesapları)

Sistemi test etmek için aşağıdaki varsayılan hesapları kullanabilirsiniz.
**Tüm hesaplar için ortak şifre:** `123456`

| Rol | Kullanıcı Adı | Şifre | Yetkiler |
| :--- | :--- | :--- | :--- |
| **Yönetici** | `admin` | `123456` | Tüm yetkiler, kullanıcı ekleme, istatistikler. |
| **Personel** | `personel` | `123456` | Duyuru ekleme, mesajlaşma, şikayet görüntüleme. |
| **Sakin** | `sakin` | `123456` | Şikayet oluşturma, duyuru okuma. |

> **Not:** Giriş ekranında farklı bir şifre girerseniz sistem hata verecektir.

---

## 🛠️ Teknolojiler

Bu proje, herhangi bir Backend kurulumu gerektirmeden, sadece tarayıcı üzerinde çalışacak şekilde modern web teknolojileri ile geliştirilmiştir.

* **HTML5 & CSS3**
* **JavaScript (ES6+)**
* **Tailwind CSS** (CDN üzerinden)
* **Chart.js** (Grafikler için)
* **FontAwesome** (İkonlar için)
* **LocalStorage API** (Veri kalıcılığı için)

---

## 📥 Kurulum ve Çalıştırma

Bu projeyi kendi bilgisayarınızda çalıştırmak için herhangi bir sunucu kurmanıza (Node.js, PHP, MySQL vb.) gerek yoktur.

1.  Projeyi indirin veya klonlayın:
    ```bash
    git clone [https://github.com/kullaniciadi/proje-adi.git](https://github.com/kullaniciadi/proje-adi.git)
    ```
2.  Klasörün içindeki `index.html` dosyasına çift tıklayın.
3.  Proje varsayılan tarayıcınızda açılacaktır.


---

## ⚠️ Önemli Bilgilendirme

Bu proje bir **Demo/Prototip** çalışmasıdır. 
* Fotoğraf yükleme işlemleri simülasyondur (rastgele internet görselleri atanır).
* Veriler sadece sizin kullandığınız tarayıcıda saklanır. Başka bir cihazdan girdiğinizde verileri göremezsiniz.
* Tarayıcı geçmişini temizlerseniz veriler sıfırlanır ve varsayılan ayarlara döner.

---

**Geliştirici:** [Talayhan Tuğra TOKUR]
