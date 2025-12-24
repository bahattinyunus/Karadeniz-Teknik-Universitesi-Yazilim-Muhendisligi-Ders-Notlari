# 🏗️ SOLID VE MİMARİ PRENSİPLER
### [ TASARIMIN KALBİ // SİSTEM MİMARİSİ ]

Yazılım geliştirme sadece kod yazmak değil, sürdürülebilir bir sistem inşa etmektir. Müfredatın en kritik konusu olan SOLID prensiplerini profesyonel bir bakış açısıyla öğrenin.

---

## 🏛️ SOLID PRENSİPLERİ

### 1. S - Single Responsibility (Tek Sorumluluk)
Bir sınıfın veya metodun sadece **bir** işi olmalıdır. Karmaşık sınıfları parçalayın.
*   *Örnek:* Bir `Rapor` sınıfı hem raporu hesaplamamalı hem de mail atmamalıdır. Mail atma işi başka bir sınıfa aittir.

### 2. O - Open/Closed (Açıklık/Kapalılık)
Kodunuz genişletilmeye **açık**, ancak değiştirilmeye **kapalı** olmalıdır.
*   *Örnek:* Yeni bir ödeme yöntemi eklemek için mevcut `OdemeSistemi` sınıfını değiştirmek yerine, bir arayüzden türetilmiş yeni bir sınıf ekleyin.

### 3. L - Liskov Substitution (Liskov'un Yerine Geçme)
Alt sınıflar, türetildikleri üst sınıfların yerine geçebilmeli ve aynı davranışı sergilemelidir.
*   *Örnek:* Kare bir dikdörtgendir mantığı matematikte doğru olsa da yazılımda `setHeight` ve `setWidth` metodları beklentiyi bozarsa Liskov ihlal edilir.

### 4. I - Interface Segregation (Arayüz Ayrımı)
Kullanıcıları kullanmadıkları metodlara zorlayan devasa arayüzler yerine, daha küçük ve spesifik arayüzler oluşturun.

### 5. D - Dependency Inversion (Bağımlılıkların Tersine Çevrilmesi)
Yüksek seviyeli modüller, düşük seviyeli modüllere bağımlı olmamalıdır; her ikisi de soyutlamalara (interface/abstract) bağımlı olmalıdır.

---

## 🏗️ MODERN MİMARİ YAKLAŞIMLARI
*   **N-Tier (Katmanlı Mimari):** UI, Business ve Data katmanlarının birbirinden bağımsızlığı.
*   **Clean Architecture:** Merkeze iş mantığını (domain) alan, dış dünyadan (DB, Framework) bağımsız yapı.

---

<p align="center">
  <b>MİMARİSİ OLMAYAN YAZILIM, TEMELİ OLMAYAN BİNADIR.</b>
</p>
