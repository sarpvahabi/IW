# IW Steeltec -- Microsoft Planner Basic Eğitim Örnekleri

Bu dokümanda IW Steeltec için Microsoft Planner Basic eğitiminde
kullanılabilecek iki farklı planlama yaklaşımı yer almaktadır.

------------------------------------------------------------------------

# Örnek 1 -- Süreç / Departman Bazlı Kovalar

Bu modelde **kovalar işin süreçlerini veya departmanlarını temsil
eder**. Görevler ilgili kovada oluşturulur ve genellikle başka bir
kovaya taşınmadan kendi kovasında tamamlanır.

## Kovalar

1.  Proje & Planlama
2.  Satın Alma & Malzeme
3.  Kesim & Hazırlık
4.  Kaynak & Montaj
5.  Yüzey İşlem & Boya
6.  Kalite Kontrol
7.  Sevkiyat
8.  Tamamlandı

## Örnek Görevler

  ---------------------------------------------------------------------------
  \#             Kova           Görev           Öncelik        Süre
  -------------- -------------- --------------- -------------- --------------
  1              Proje &        Müşteri teknik  Önemli         1 gün
                 Planlama       çizimlerini                    
                                incele                         

  2              Proje &        Üretim          Önemli         2 gün
                 Planlama       resimlerini                    
                                hazırla                        

  3              Proje &        Malzeme         Orta           1 gün
                 Planlama       listesini (BOM)                
                                oluştur                        

  4              Satın Alma &   Sac ve profil   Önemli         1 gün
                 Malzeme        siparişlerini                  
                                oluştur                        

  5              Satın Alma &   Gelen           Orta           1 gün
                 Malzeme        malzemelerin                   
                                kontrolünü yap                 

  6              Kesim &        CNC kesim       Orta           1 gün
                 Hazırlık       programını                     
                                hazırla                        

  7              Kesim &        Ana taşıyıcı    Önemli         2 gün
                 Hazırlık       profilleri kes                 

  8              Kesim &        Delik ve pah    Orta           1 gün
                 Hazırlık       işlemlerini                    
                                tamamla                        

  9              Kaynak &       Parçaların ön   Önemli         1 gün
                 Montaj         montajını yap                  

  10             Kaynak &       Kaynak          Acil           3 gün
                 Montaj         işlemlerini                    
                                tamamla                        

  11             Kalite Kontrol Kaynak kalite   Önemli         1 gün
                                kontrolünü                     
                                gerçekleştir                   

  12             Yüzey İşlem &  Kumlama         Orta           1 gün
                 Boya           işlemini                       
                                tamamla                        

  13             Yüzey İşlem &  Astar ve son    Orta           2 gün
                 Boya           kat boya uygula                

  14             Kalite Kontrol Final ürün      Önemli         1 gün
                                kontrolünü                     
                                gerçekleştir                   

  15             Sevkiyat       Paketleme ve    Önemli         1 gün
                                sevkiyatı                      
                                gerçekleştir                   
  ---------------------------------------------------------------------------

## Etiket Önerileri

-   Mühendislik
-   Satın Alma
-   Üretim
-   Kalite
-   Sevkiyat
-   Kritik

## Eğitimde Detaylandırılabilecek Görev

### Kaynak işlemlerini tamamla

-   **Kova:** Kaynak & Montaj
-   **Öncelik:** Acil
-   **Tahmini süre:** 3 gün
-   **Atanan:** Örnek bir üretim sorumlusu
-   **Etiket:** Üretim / Kritik

**Kontrol listesi:**

-   Teknik resmi kontrol et
-   Kaynak prosedürünü kontrol et
-   Parçaların ön montajını kontrol et
-   Kaynak işlemlerini gerçekleştir
-   Görsel kaynak kontrolünü yap
-   Kalite kontrol birimine bildir

Bu görev üzerinden Planner'da **kişi atama, başlangıç ve bitiş tarihi,
öncelik, etiket, kontrol listesi, açıklama, dosya ekleme, yorum ve
görevi tamamlama** özellikleri gösterilebilir.

### Ek eğitim senaryosu

"Gelen malzemelerin kontrolünü yap" görevi sırasında uygunsuz bir profil
tespit edildiği varsayılabilir.

Yeni görev:

**Uygunsuz profil için tedarikçiyle iletişime geç**

Bu senaryo, beklenmeyen bir durumdan yeni görev oluşturmayı göstermek
için kullanılabilir.

------------------------------------------------------------------------

# Örnek 2 -- Kanban / Kovalar Arasında Görev Taşıma

Bu modelde kovalar departmanları değil, **işin mevcut durumunu** temsil
eder.

Bir iş veya proje, ilerledikçe Planner üzerinde bir kovadan diğerine
sürüklenir.

## Kovalar

**Yeni İşler → Planlandı → Üretimde → Kalite Kontrolde → Sevkiyata Hazır
→ Tamamlandı**

## Örnek İşler

  -----------------------------------------------------------------------
  Görev / İş              Başlangıç Kovası        Örnek İlerleme
  ----------------------- ----------------------- -----------------------
  Çelik platform --       Yeni İşler              Planlandı → Üretimde →
  PRJ-026                                         Kalite Kontrolde →
                                                  Sevkiyata Hazır →
                                                  Tamamlandı

  Makine şasesi --        Yeni İşler              Planlandı → Üretimde →
  PRJ-027                                         Kalite Kontrolde →
                                                  Tamamlandı

  Çelik merdiven --       Planlandı               Üretimde → Kalite
  PRJ-028                                         Kontrolde → Sevkiyata
                                                  Hazır → Tamamlandı

  Boru taşıyıcı           Üretimde                Kalite Kontrolde →
  konstrüksiyon --                                Sevkiyata Hazır →
  PRJ-029                                         Tamamlandı

  Bakım platformu --      Kalite Kontrolde        Sevkiyata Hazır →
  PRJ-030                                         Tamamlandı
  -----------------------------------------------------------------------

## Canlı Eğitim Örneği

### Çelik platform -- PRJ-026

Eğitimin başında görev:

**Yeni İşler**

kovasında oluşturulur.

Planlama yapıldığında:

**Yeni İşler → Planlandı**

Üretim başladığında:

**Planlandı → Üretimde**

Üretim tamamlandığında:

**Üretimde → Kalite Kontrolde**

Kalite onayı sonrasında:

**Kalite Kontrolde → Sevkiyata Hazır**

Sevkiyat tamamlandığında:

**Sevkiyata Hazır → Tamamlandı**

Bu yöntem özellikle Planner'da **sürükle-bırak ile görev yönetimini ve
Kanban yaklaşımını** göstermek için uygundur.

## PRJ-026 İçin Örnek Kontrol Listesi

-   Teknik çizimler onaylandı
-   BOM hazırlandı
-   Malzemeler temin edildi
-   Kesim tamamlandı
-   Kaynak tamamlandı
-   Boya tamamlandı
-   Kalite kontrol yapıldı
-   Paketleme tamamlandı
-   Sevkiyat gerçekleştirildi

------------------------------------------------------------------------

# İki Yaklaşımın Farkı

  -----------------------------------------------------------------------
  Özellik                 Süreç / Departman       Kanban Modeli
                          Modeli                  
  ----------------------- ----------------------- -----------------------
  Kovalar neyi gösterir?  Departman veya üretim   İşin mevcut durumunu
                          aşamasını               

  Görev yapısı            Yapılacak faaliyet      Proje / iş emri / ürün

  Görev kova değiştirir   Genellikle hayır        Evet
  mi?                                             

  Sürükle-bırak kullanımı Daha az                 Yoğun

  Eğitimde kullanım       Planner görev           Kanban ve iş akışını
                          detaylarını göstermek   göstermek

  Örnek                   "Kaynak işlemlerini     "Çelik Platform --
                          tamamla"                PRJ-026"
  -----------------------------------------------------------------------

## Eğitim Önerisi

Planner Basic eğitiminde iki modelin de gösterilmesi faydalıdır.

Önce **Süreç / Departman Bazlı Model** ile görev oluşturma ve görev
detayları anlatılabilir.

Ardından **Kanban Modeli** ile aynı işin süreç içerisinde kovalar
arasında nasıl ilerletilebileceği gösterilebilir.
