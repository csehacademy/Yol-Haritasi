# 🚀 Yol-Haritası
### CSEH Academy tarafından siber güvenlikle ilgili sorularınıza cevap olması amacıyla hazırlanmıştır.

---

- 💻 **Bilgisayar Özellikleri (Minimum Öneri)**
  * Minimum i5 veya Ryzen 5 işlemci
  * Minimum 8 GB RAM (en kritik bileşen)
  * Aynı anda 2 veya daha fazla sanal makine çalıştırabilmelisiniz
    * *Örn: saldırgan makine + kurban makine*
  * Mutlaka SSD (240 GB SSD, 1 TB HDD’den daha iyidir)

---

- ❓ **“XX yaşındayım, geç kaldım mı?”**
  * Hayır. Teknoloji alanında geç kalmak diye bir şey yok.
  * **Önemli olan:** Doğru yöntemle çalışmak, araştırmayı bilmek ve öğrenmeyi öğrenmek.
  * İlerleyen yaş, motivasyon ve disiplinle avantaj bile olabilir.

---

- 🎓 **Öğrenciyim, ne gibi haklarım var?**
  * Ortaöğretim ve üzerindeyseniz:
  * 👉 **GitHub Education Pack** ile birçok ürüne ücretsiz erişebilirsiniz (domain + hosting dahil).
  * 🔗 https://education.github.com/pack

---

- 🗺️ **Yol haritası nereden bulacağım?**
  * Hazır roadmap siteleri:
  * 🔗 https://roadmap.sh *(ilgili alanı seç ve maddeler halinde ilerle)*

---

- 👨‍💻 **Programlama geçmişim var, hangi alana yönelmeliyim?**
  * En hızlı geri dönüş alınan alanlar: **Application Pentesting** ve **Security Researcher**
  * **Başlamak için:** OWASP dökümantasyonları ve Bug bounty platformları:
    * [HackerOne](https://www.hackerone.com/)
    * [Bugcrowd](https://www.bugcrowd.com/)
  * *Eğitim bölümleri de var – doğrudan pratik yapıp gelişebilirsin.*

---

- 🔐 **Hack saldırılarından nasıl korunurum?**
  * Güçlü şifre kullan (büyük/küçük harf + sayı + özel karakter, tercihen 12+ karakter).
  * Şifreleri farklı platformlarda tekrar kullanma ve password manager tercih et.
  * 2FA (Çift aşamalı doğrulama) mutlaka aktif et.
  * **Şifren sızmış mı kontrol et:** 🔗 https://haveibeenpwned.com/

---

- 🐧 **Linux’u nereden öğreneceğim?**
  * **Başlangıç için interaktif pratik:** 🔗 https://cmdchallenge.com
  * **Türkçe sıfırdan kaynak:** 🔗 [LuNiZz Linux ve Pentesting Başlangıç](https://github.com/LuNiZz/siber-guvenlik-sss/blob/master/Linux-ve-Pentesting-Baslangic.md)

---

- 🌐 **Web uygulama güvenliği için kaynak**
  * **Türkçe:** MDISEC (üst düzey içerik) 🔗 https://youtu.be/WtHnT73NaaQ
  * **Yabancı:** The Cyber Mentor playlist 🔗 https://www.youtube.com/watch?v=X4eRbHgRawI
  * **Lab ortamları:**
    * bWAPP → http://www.itsecgames.com
    * PortSwigger Academy → https://portswigger.net/

---

- 🛠️ **Güvenli Kod Geliştirme (Secure Coding) Nedir?**
  * Bir sistemi hacklemek kadar, o sistemi güvenli inşa etmeyi bilmek de önemlidir.
  * **Web Framework Güvenliği (Django / Python):**
    * `SECRET_KEY` ve hassas API kimliklerinin `.env` dosyalarıyla izole edilmesi, kod içinde bırakılmaması.
    * Django ORM kullanımı ve arka plandaki SQL Injection koruma yapısı.
    * Kullanıcı oturum (Session) güvenliği ve CSRF/XSS korumalarının sıkılaştırılması.
  * **Veri Tabanı Güvenliği:** MySQL/PostgreSQL veritabanlarında servis kullanıcısı yetkilerinin "En Az Yetki İlkesi" (Principle of Least Privilege) uyarınca kısıtlanması.

---

- 🎛️ **Donanım ve Gömülü Sistem Güvenliği (Hardware Hacking)**
  * Siber güvenlik sadece ekrandaki kodlardan ibaret değildir; fiziksel dünya ile temas ettiğiniz an donanım güvenliği başlar.
  * **Kablosuz Ağ ve Sinyal Analizi (Flipper Zero):** Radyo frekansları (RF), RFID, NFC, Kızılötesi (IR) ve Sub-GHz sinyallerinin yakalanması ve analizi.
  * **Man-in-the-Middle & Rogue AP (WiFi Pineapple):** Kablosuz ağlarda sahte erişim noktası oluşturma ve ağ trafiğini manipüle etme mantığı.
  * **IoT & BLE Saldırı Mekanizmaları (M5StickC Plus / ESP32):** Wi-Fi deauthentication (bağlantı koparma) ve Bluetooth Low Energy (BLE) spam altyapılarının incelenmesi.
  * **Firmware Analizi:** `Binwalk` aracı ile IoT cihazlarının gömülü yazılımlarını (firmware) dosya sistemine ayrıştırma ve tersine mühendislik pratikleri.

---

- 📦 **Modern Altyapı ve Konteyner Güvenliği (DevSecOps)**
  * Modern kurumsal dünyada uygulamalar artık ham sunucularda değil, konteyner mimarilerinde çalışmaktadır.
  * **Konteyner Teknolojileri (Docker):** Docker mimarisi, Dockerfile güvenliği, root dışı (non-root) kullanıcı çalıştırma prensipleri.
  * **Zafiyet Tarama (Image Scanning):** Üretilen Docker imajlarının `Trivy` veya `Grype` gibi araçlarla bağımlılık açıklarına karşı taranması.
  * **Pratik Altyapı:** Kendi yerel ağınızda Docker üzerinde **Pi-hole / AdGuard Home** kurarak DNS tabanlı ağ izleme pratikleri gerçekleştirmek.

---

- 🎓 **Hangi programlama dillerine ağırlık vermeliyim?**
  * Python
  * JavaScript
  * C / C++
  * Bash scripting
  * SQL temelleri
  * Kali Linux sanal makine kullanımı
  * Temel ağ bilgisi (CCNA seviyesi)

---

- 🐍 **Python için kaynak önerileri**
  * **Türkçe:** 🔗 https://python-istihza.yazbel.com/
  * **Türkçe (Sadi Evren Şeker):** 🔗 https://youtu.be/AaOv4BjN2UY
  * **Yabancı:** 🔗 https://youtu.be/rfscVS0vtbw

---

- 🇬🇧 **İngilizcem yok, ne yapacağım?**
  * Kısa cevap: Öğreneceksin 🙂 Siber güvenlikte teknik İngilizce şarttır.
  * **Öneriler:** Duolingo vb. uygulamalar, altyazılı dizi-film takibi ve Voscreen (🔗 https://www.voscreen.com/)

---

- 🌐 **Networking öğrenmek istiyorum**
  * **Hedef:** CCNA düzeyi temel ağ mimarisi bilgisi.
  * **Öneri playlist:** 🔗 https://www.youtube.com/playlist?list=PLDQaRcbiSnqF5U8ffMgZzS7fq1rHUI3Q8

---

- 🧪 **Pentesting çalışacağım ama kimseye zarar vermek istemiyorum**
  * Yasal ve güvenli lab ortamları:
    * https://tryhackme.com (Başlangıç–Orta)
    * https://www.hackthebox.com (Orta–İleri)
  * **Türkçe platform:** https://priviahub.com

---

- 🌍 **VPN’i nasıl kurarım?**
  * Kişisel VPN ve gizlilik konuları için uygulamalı eğitim rehberi:
  * 🔗 [CSEH Academy Uygulamalı Etik Hacker Olma Kursu](https://www.udemy.com/course/uygulamali-etik-hacker-olma-kursu/?referralCode=A2C91BDCEC549705CC1E)

---

- 🎖️ **Hangi sertifikaları almalıyım?**
  * **Popüler ve etkili:** OSCP, CISSP (Daha kurumsal / bilgi güvenliği odaklı)
  * *Not: Bunlar pahalı sınavlardır. Çoğu zaman sektörde çalışırken şirketiniz sponsor olur. Başlangıç aşaması için zorunlu değillerdir.*

---

- 🤖 **Yapay Zekâ ve Siber Güvenlik – Neden Önemli?**
  * Yapay zekâ (AI) günümüzde saldırıların otomasyonunda, zafiyet tespitinde, zararlı yazılım analizinde, SOC ve SIEM sistemlerinde ve tehdit istihbaratında aktif şekilde kullanılmaktadır.
  * Aynı zamanda saldırganlar da AI kullanıyor: Phishing e-mailleri otomatik üretme, parola deneme saldırılarını optimize etme, kötü amaçlı kod oluşturma ve deepfake ile sosyal mühendislik.
  * Bu yüzden siber güvenlik + yapay zekâ birleşimi, geleceğin en kritik alanlarından biridir.

---

- 🧠 **Hangi Yapay Zekâ Alanları Siber Güvenlikle Kesişir?**
  * Machine Learning for Security
  * Adversarial Machine Learning
  * Malware Classification
  * Network Anomaly Detection
  * Fraud Detection
  * Threat Intelligence Automation
  * LLM Security & Prompt Injection Analizi (Yapay zeka modellerine yönelik girdi manipülasyonu)
  * AI Red Teaming

---

- 🛡️ **AI destekli savunma neler yapabilir?**
  * Loglardan otomatik saldırı tespit etme
  * Anomali tabanlı IDS/IPS sistemleri geliştirme
  * Gelişmiş phishing tespiti
  * Zararlı yazılım ailelerini sınıflandırma
  * Otomatik raporlama, olay analizi ve yara izi (IOC) çıkarımı

---

- ⚠️ **AI destekli saldırılar**
  * Günümüzde saldırganların AI’yı kullanabildiği alanlar: Otomatik OSINT toplama, sosyal mühendislik mesajları üretme, phishing site/e-mail taslakları üretimi, exploit varyantları oluşturma ve LLM zafiyetlerini (prompt injection vb.) sömürme.
  * *Not: Tüm çalışmalar hukuka uygun lab ortamlarında ve eğitim amaçlı yapılmalıdır.*

---

- 🛠️ **AI + Siber Güvenlik için hangi teknolojiler öğrenilmeli?**
  * Python (Numpy / Pandas / Scikit-Learn / PyTorch veya TensorFlow)
  * Jupyter Notebook
  * Regex
  * Wireshark + PCAP analizi
  * YARA kuralları
  * ELK Stack (Elastic – Logstash – Kibana)

---

- ✅ **Son Tavsiye**
  * Açık kaynak projelere katkı ver, Pull Request gönder.
  * Kendi blogunu, reponu veya çalışma notlarını açıkça paylaş.
  * Topluluklarda aktif ol. “Siberci” olmanın yolu sürekli üretmekten ve paylaşmaktan geçer.

---

## 🤝 Katkıda Bulunun (Contribution)
Bu yol haritası **CSEH Academy** topluluğu tarafından canlı tutulan ve siber güvenlik trendlerine göre sürekli güncellenen açık kaynaklı bir projedir. 
* Rehbere eklenmesini istediğiniz güncel bir teknik veya faydalı kaynak varsa lütfen bir **Pull Request (PR)** açın!
* Faydalı bulduysanız sağ üst köşeden **Star (Yıldız)** vermeyi unutmayın! ⭐

---

## ✍️ Kaynakça ve Katkı
* **Orijinal İçerik:** LuNiZz
* **Düzenleme ve Eklemeler:** CSEH Academy
