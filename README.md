# 🍬 Şekerli Hesap: AI-Powered Financial Navigation System

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](https://flutter.dev)
[![Gemini AI](https://img.shields.io/badge/Gemini%20AI-8E75B2.svg?style=for-the-badge&logo=google-gemini&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![Security](https://img.shields.io/badge/Security-Locked-success.svg?style=for-the-badge&logo=cloudera&logoColor=white)](#-siber-güvenlik-analizi)

**Şekerli Hesap**, özellikle şahıs şirketleri ve küçük işletmelerin finansal karmaşasını çözen, yapay zeka destekli bir "Algoritmik Muhasebe" ve kâr analiz motorudur.

---

## 📱 Uygulama Görünümleri

<div align="center">
  <table border="0">
    <tr>
      <td width="50%" align="center">
        <img src="main_screen.jpg" alt="Ana Sayfa" width="250px"/><br>
        <b>Finansal Özet & Takip</b>
      </td>
      <td width="50%" align="center">
        <img src="analysis.jpg" alt="AI Analiz" width="250px"/><br>
        <b>Gemini AI Stratejik Rapor</b>
      </td>
    </tr>
  </table>
</div>

---

## 🎯 Çözülen Temel Sorun
Küçük esnafların yaşadığı en büyük sorun olan **"Ciro vs. Net Kâr"** ayrımını netleştirir. Uygulama; KDV, stopaj, Bağkur, gelir vergisi ve operasyonel maliyetleri otomatik hesaplayarak kullanıcıya gerçek "Net Birim Kâr" ve **ROI (Yatırım Getirisi)** verilerini sunar.

## 🛠️ Teknik Mimari
* **Engine:** Flutter & Dart (Native performans).
* **State Management:** `ChangeNotifier` ve `ListenableBuilder` ile dinamik arayüz yönetimi.
* **AI Katmanı:** `Gemini Flash-Latest` modeli ile finansal veri analizi ve yönetici özeti.
* **Veri Görselleştirme:** `fl_chart` ile karmaşık finansal verilerin (PieChart/BarChart) görselleştirilmesi.
* **Hibrit Depolama:** Genel ayarlar için `shared_preferences`, kritik API anahtarları için `flutter_secure_storage` (Keystore/Keychain).

## 🔒 Siber Güvenlik Uzmanı Gözüyle Analiz
Proje geliştirilirken profesyonel siber güvenlik standartları göz önünde bulundurulmuştur:

* **Disk Üstünde Veri Güvenliği:** `shared_preferences` üzerindeki plain-text riskine karşı kritik ticari verilerin şifrelenmesi kurgulanmıştır.
* **Biyometrik Katman:** Ticari sırların korunması için `local_auth` (FaceID/Parmak İzi) entegrasyonu planlanmıştır.
* **Tersine Mühendislik Savunması:** Kodun decompile edilmesini zorlaştırmak adına **Obfuscation** (Kod Gizleme) teknikleri uygulanmıştır.
* **Input Sanitization:** JSON veri ithalatı sırasında "Schema Validation" uygulanarak injection riskleri minimize edilmiştir.

## 📊 Öne Çıkan Fonksiyonlar
- **Dinamik Gider Motoru:** Muhasebe ücretinden stopaja kadar tüm yasal kesintilerin anlık hesaplanması.
- **KPI Dashboard:** Brüt marj ve net kâr oranlarının profesyonel metriklerle sunulması.
- **AI Asistan:** Verilerinizi analiz ederek işletmenizin verimliliğini artıracak tavsiyeler veren entegre yapay zeka.

---

### 👨‍💻 Geliştirici
**Recep** *Software Development Student & Cybersecurity Aspirant*

---
*Bu proje, küçük işletmelerin dijital finansal dönüşümünü sağlamak amacıyla geliştirilmiştir.*
