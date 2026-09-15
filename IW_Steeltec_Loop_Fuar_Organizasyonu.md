# IW Steeltec -- Fuar Organizasyonu \| Microsoft Loop Uygulaması

**Senaryo:** IW Steeltec, **Metal Expo 2026** fuarına katılıyor. Tüm
hazırlıkları Microsoft Loop üzerinden yöneteceğiz.

Bu uygulamada Loop'u sıfırdan kurarak hangi noktada hangi Loop elementi
kullanılacağını ve `/` komutlarıyla nasıl ekleneceğini adım adım
göreceğiz.

------------------------------------------------------------------------

# 1. Workspace Oluştur

Loop ana ekranından **New workspace / Yeni çalışma alanı** seçin.

Workspace adı:

`IW Steeltec – Metal Expo 2026`

## Oluşturulacak Sayfalar

1.  🏠 Fuar Ana Sayfası
2.  ✅ Fuar Hazırlıkları
3.  🏗️ Stand Planlaması
4.  📦 Fuar Malzemeleri
5.  📝 Toplantı Notları
6.  💡 Fuar Fikirleri
7.  👥 Fuar Lead Takibi
8.  📊 Fuar Sonrası Değerlendirme

------------------------------------------------------------------------

# 2. 🏠 Fuar Ana Sayfası

**New page** oluşturun ve adını `🏠 Fuar Ana Sayfası` yapın.

## Fuar Bilgileri Başlığı

`/` yazın → **Heading 2** seçin → `Fuar Bilgileri` yazın.

**Element:** Heading

## Fuar Bilgileri Tablosu

`/table` yazın → **Table** seçin.

  Bilgi             Detay
  ----------------- --------------------------
  Fuar              Metal Expo 2026
  Tarih             21--24 Ekim 2026
  Lokasyon          İstanbul
  Stand             Hall 3 -- B24
  Stand Alanı       48 m²
  Proje Sorumlusu   Ayşe Yılmaz
  Hedef Lead        100
  Durum             🟡 Hazırlık devam ediyor

**Element:** Table

------------------------------------------------------------------------

# 3. 🎯 Fuar Hedeflerini Ekle

`/heading` → **Heading 2** → `🎯 Fuar Hedefleri`

Ardından `/bulleted list` yazın ve şunları ekleyin:

-   100 nitelikli lead toplamak
-   En az 20 potansiyel müşteriyle görüşmek
-   5 distribütör adayı belirlemek
-   Yeni ürün grubunu tanıtmak
-   Mevcut müşterilerle görüşmek

**Element:** Bulleted List

> Bunlar bilgi/hedef listesidir; atanmış görev değildir.

------------------------------------------------------------------------

# 4. ✅ Fuar Hazırlıkları Sayfası

Yeni Page: `✅ Fuar Hazırlıkları`

`/heading` → **Heading 2** → `Fuar Öncesi Yapılacaklar`

## Task List

`/task` → **Task list**

-   Stand tasarımını onayla → @Mehmet → 25 Eylül
-   Broşürleri baskıya gönder → @Elif → 5 Ekim
-   Otel rezervasyonlarını tamamla → @Zeynep → 20 Eylül
-   Numune ürünleri belirle
-   Müşterilere fuar davetiyesi gönder
-   Promosyon ürünlerini sipariş et

**Element:** Task List

**Mantık:** Task → Assignee → Due date

------------------------------------------------------------------------

# 5. 📦 Fuar Malzemeleri Sayfası

Yeni Page: `📦 Fuar Malzemeleri`

`/heading` → **Heading 2** → `Fuara Götürülecekler`

`/checklist` → **Checklist**

-   [ ] Laptop
-   [ ] HDMI kablosu
-   [ ] Uzatma kablosu
-   [ ] 500 adet katalog
-   [ ] 1.000 adet kartvizit
-   [ ] 3 adet roll-up
-   [ ] 500 adet kalem
-   [ ] 250 adet defter
-   [ ] Numune ürünler
-   [ ] Personel yaka kartları

**Element:** Checklist

### Checklist ve Task List farkı

`Laptop fuara götürüldü mü?` → **Checklist**

`Laptopları Ahmet 20 Ekim'e kadar fuar alanına götürsün.` → **Task
List**

**Kural:** Basit kontrol = Checklist. Sorumlusu ve tarihi olan iş = Task
List.

------------------------------------------------------------------------

# 6. 🏗️ Stand Planlaması Sayfası

Yeni Page: `🏗️ Stand Planlaması`

`/heading` → **Heading 2** → `Stand İhtiyaçları`

`/table` → **Table**

  Alan        İhtiyaç               Sorumlu         Durum
  ----------- --------------------- --------------- -------------
  Karşılama   Resepsiyon bankosu    Pazarlama       🟢 Hazır
  Görüşme     2 masa + 8 sandalye   Organizasyon    🟡 Bekliyor
  Ürün        3 sergileme alanı     Teknik          🟡 Bekliyor
  Dijital     65" TV                IT              🔴 Alınacak
  Depo        4 m² kapalı alan      Stand firması   🟢 Hazır
  İkram       Kahve + su            Organizasyon    🟡 Bekliyor

**Element:** Table

------------------------------------------------------------------------

# 7. 🗳️ Ekipten Fikir ve Oy Topla

`/heading` → **Heading 2** → `Stand İçin Karar Verilecek Konular`

`/voting` → **Voting table**

  Fikir                                Örnek Oy
  ------------------------------------ ----------
  65" TV kiralayalım                   👍👍👍
  LED ekran kullanalım                 👍
  Fiziksel ürün numuneleri getirelim   👍👍
  QR katalog kullanalım                👍👍👍👍

**Element:** Voting Table

**Canlı uygulama:** Katılımcılardan Loop'a girerek seçeneklere oy
vermelerini isteyin.

------------------------------------------------------------------------

# 8. 💡 Fuar Fikirleri Sayfası

Yeni Page: `💡 Fuar Fikirleri`

`/heading` → **Heading 2** → `Fuarda Neler Yapabiliriz?`

`/bulleted list` → **Bulleted List**

-   Üretim videosunu standdaki TV'de gösterelim
-   QR kod ile dijital katalog verelim
-   Mini ürün numuneleri sergileyelim

**Canlı uygulama:** Her katılımcı listeye bir fuar fikri eklesin.

**Element:** Bulleted List

------------------------------------------------------------------------

# 9. 📝 Toplantı Notları Sayfası

Yeni Page: `📝 Toplantı Notları`

`/heading` → **Heading 1** → `22 Eylül – Fuar Hazırlık Toplantısı`

## Katılımcılar

Normal metne `Katılımcılar:` yazın.

Ardından `@` yazarak kişileri seçin:

-   @Mehmet
-   @Elif
-   @Ahmet

**Element:** @Mention

------------------------------------------------------------------------

# 10. Toplantı Gündemi

`/numbered list` → **Numbered List**

1.  Stand tasarımı
2.  Sergilenecek ürünler
3.  Promosyon malzemeleri
4.  Otel ve ulaşım
5.  Müşteri davetleri

**Element:** Numbered List

------------------------------------------------------------------------

# 11. Toplantı Notları

`/heading` → **Heading 2** → `Toplantı Notları`

Normal metin olarak:

> Stand tasarımının genel olarak uygun olduğuna karar verildi. Teknik
> ekip sergilenecek ürünlerin ağırlıklarını stand firmasına iletecek.
> Katalogların güncellenmiş versiyonunun baskıya gönderilmesi gerekiyor.

**Element:** Text / Paragraph

------------------------------------------------------------------------

# 12. Toplantı Aksiyonlarını Göreve Dönüştür

`/heading` → **Heading 2** → `Aksiyonlar`

`/task` → **Task List**

-   Stand tasarımını onayla → @Mehmet → 25 Eylül
-   Ürün ağırlıklarını stand firmasına gönder → @Ahmet → 23 Eylül
-   Katalogları baskıya gönder → @Elif → 28 Eylül

**Element:** Task List

> Toplantı notunda bir işi yalnızca yazmak yerine, gerçekten takip
> edilecek aksiyonları Task haline getirin.

------------------------------------------------------------------------

# 13. 👥 Fuar Lead Takibi

Yeni Page: `👥 Fuar Lead Takibi`

`/heading` → **Heading 2** → `Potansiyel Müşteriler`

`/table` → **Table**

  --------------------------------------------------------------------------
  Firma          İlgili Kişi    İlgilendiği    Potansiyel     Sonraki
                                Ürün                          Aksiyon
  -------------- -------------- -------------- -------------- --------------
  ABC Metal      Ali Kaya       Çelik platform 🔥 Yüksek      Teklif gönder

  Delta Makine   John Smith     Özel imalat    🟡 Orta        Toplantı yap

  XYZ Endüstri   Mehmet Demir   Kaynaklı       🔥 Yüksek      Fabrika
                                imalat                        ziyareti

  Beta           Sarah Lee      Tedarik        🟢 Düşük       Katalog gönder
  Engineering                                                 
  --------------------------------------------------------------------------

Ardından `/task` → **Task List**

-   ABC Metal'e teklif gönder → @Satış → 27 Ekim
-   XYZ Endüstri ile fabrika ziyareti planla → @Mehmet → 30 Ekim

**Mantık:** Bilgi = Table. Yapılması gereken aksiyon = Task List.

------------------------------------------------------------------------

# 14. 📊 Fuar Sonrası Değerlendirme

Yeni Page: `📊 Fuar Sonrası Değerlendirme`

`/heading` → **Heading 2** → `Fuar Sonuçları`

`/table` → **Table**

  KPI                    Hedef   Gerçekleşen
  -------------------- ------- -------------
  Toplam ziyaretçi         200           245
  Nitelikli lead           100           118
  Teklif talebi             20            27
  Distribütör adayı          5             7
  Planlanan toplantı        10            14

Ardından:

`/heading` → **Heading 2** → `Neler İyi Gitti?`

`/bulleted list`

-   Stand lokasyonu iyiydi
-   Teknik ekibin bulunması faydalı oldu
-   QR katalog ilgi gördü
-   Ürün videoları dikkat çekti

Son olarak:

`/heading` → **Heading 2** → `Bir Sonraki Fuarda Neyi Değiştirelim?`

Bu alanı boş bırakın ve katılımcılardan birlikte doldurmalarını isteyin.

------------------------------------------------------------------------

# Loop Elementleri ve `/` Komutları -- Özet

  İhtiyaç                     Loop Elementi      Nasıl Eklenir?
  --------------------------- ------------------ --------------------------
  Bölüm başlığı               Heading            `/heading`
  Normal açıklama             Text / Paragraph   Normal yazın
  Bilgileri düzenleme         Table              `/table`
  Fikir/hedef listeleme       Bulleted List      `/bulleted list`
  Sıralı gündem               Numbered List      `/numbered list`
  Basit kontrol               Checklist          `/checklist`
  Sorumlusu olan iş           Task List          `/task`
  Ekipten oy toplama          Voting Table       `/voting`
  Kişiyi içeriğe dahil etme   Mention            `@`
  Başka sayfaya bağlantı      Page Link          `@` veya bağlantı ekleme
  Emoji                       Emoji              `:` veya emoji seçici

> **Not:** Loop'un dili veya sürümüne göre menüde görünen adlarda küçük
> farklılıklar olabilir. `/` yazdıktan sonra açılan menüden karşılık
> gelen elementi seçin.

------------------------------------------------------------------------

# Eğitimde Verilecek Temel Mesaj

-   **Workspace:** Tüm fuar projesini tek çalışma alanında toplar.
-   **Page:** Konuları birbirinden ayırır.
-   **Table:** Bilgiyi düzenler.
-   **Checklist:** Basit kontrolleri takip eder.
-   **Task List:** Sorumlusu ve tarihi olan işleri takip eder.
-   **Voting Table:** Ekipçe karar vermeyi sağlar.
-   **@Mention:** Kişileri çalışmaya dahil eder.
-   **Bulleted List:** Fikir ve bilgi toplamak için kullanılır.

Planner ile birlikte kullanıldığında **Planner görev ve iş akışı
yönetimini**, Loop ise **ortak proje çalışma alanını, toplantı
notlarını, fikirleri, tabloları ve kararları** destekler.
