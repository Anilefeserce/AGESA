# Figma/Canva Handoff: AgeSA Sinerji Agi - Anil

Hazirlayan rol: Mikro Ajan 2  
Kullanici: Anil  
Proje: AgeSA/Akbank Mobil - Tam Seffaf Dashboard ve Gelecek Simulatoru  
Kaynak dosyalar: `PRD_Anil_Arayuz_Dashboard_Arastirma.md`, `akbank_agesa_mockup.html`  
Dil notu: Bu dokuman ASCII karakterlerle yazilmistir.

## 1. Tasarim Amaci

Bu handoff dokumani, AgeSA Sinerji Agi deneyiminin Figma veya Canva uzerinde hizli ve tutarli sekilde yeniden kurulmasi icin hazirlandi. Deneyim Akbank Mobil icinde konumlanan, genc kullaniciya hizli karar aldiran ama finansal guven hissini koruyan bir mobil arayuz olarak ele alinmalidir.

Ana hedef, Anil gibi Kontrollu Hedefci personaya su sorularin cevabini 5 saniye icinde vermektir:

- Param hangi parcalardan olusuyor?
- Benim yatirdigim, devlet katkisi ve ekosistemden gelen tutarlar ne kadar?
- Olasi birikim senaryom ne?
- Fonlarim ve Otopilot kontrolumde mi?
- BES baslatmak veya katkini artirmak icin sonraki net aksiyon ne?

## 2. Frame Listesi

Tum mobil frame'ler 390 x 844 px baz alinabilir. Figma'da iPhone 14/15 veya benzeri mobil preset kullanilabilir. Canva'da "Mobile Phone Mockup" ya da 390 x 844 custom size tercih edilebilir.

### Frame 01 - Dashboard / AgeSA Sinerji Agi

Frame adi: `01_Dashboard_AgeSA_Sinerji_Agi`

Amac: Toplam birikimi ve katkilarin kaynagini tek bakista gostermek.

Bolumler:

- Status bar: 09:41, sinyal/batarya ikonlari.
- App bar: Geri ikonu, "AgeSA Sinerji Agi", "Akbank Mobil", yardim ikonu.
- Hero panel: "Tam Seffaf Dashboard", toplam birikim, hedef ilerleme, piyasa kosulu uyarisi.
- Uc katki karti: "Benim Yatirdigim", "Devlet Katkisi", "Ekosistemden Gelen".
- Ekosistem kirilimi: CarrefourSA, Enerjisa, Teknosa.
- Fon getirisi grafigi: 1A / 3A / 1Y / Tum segmented control.
- Hizli aksiyonlar: Simulator, Otopilot, Yuvarla, Destek.
- Alt CTA: "Katkimi artir".

### Frame 02 - Simulator / Gelecek Simulatoru

Frame adi: `02_Gelecek_Simulatoru`

Amac: Kullaniciya aylik katki, sure ve risk tercihiyle olasi birikim senaryosunu anlik gostermek.

Bolumler:

- App bar: Geri ikonu, "Gelecek Simulatoru", "Olasi birikim senaryosu", yardim ikonu.
- Hero panel: "1 kahve parasi gelecekte ne olur?"
- Aylik katki stepper: eksi, tutar, arti.
- Sure secimi: 5 yil, 10 yil, 15 yil.
- Risk tercihi: Garantici, Dengeli, Agresif.
- Sonuc paneli: Benim yatirdigim, olasi devlet katkisi, olasi ekosistem katkisi, olasi fon getirisi, olasi toplam birikim.
- Varsayimlar acilir alani.
- Alt CTA: "2 onayla baslat".

### Frame 03 - Satis Sonrasi Kontrol / Otopilot

Frame adi: `03_Birikim_Kontrolu_Otopilot`

Amac: Kullaniciya fon dagilimi, performans ve ekosistem katkilarini kontrol edebildigini hissettirmek.

Bolumler:

- App bar: Geri ikonu, "Birikim Kontrolu", "Otopilot ve fon takibi", yardim ikonu.
- Otopilot hero paneli: "AgeSA Otopilot", profil "Dengeli", durum "Aktif".
- Fon dagilimi: Fon A %40, Fon B %35, Fon C %25.
- Performans paneli: 1A / 3A / 1Y / Tum, bu ay +%2.1.
- Icgooru paneli: "Fon dagilimin hedefinle uyumlu ilerliyor."
- Ekosistem katkilarin: Yuvarla ve Biriktir, Sinerji Geri Odemesi, Teknosa faydasi.
- Ikincil aksiyonlar: "Otopilotu duzenle", "Destek al".
- Alt CTA: "Fon degisikligini kesfet".

### Frame 04 - Basvuru Onay Toast / Overlay

Frame adi: `04_Toast_AgeSA_Sinerji_Agi_Aktif`

Amac: "2 onayla baslat" aksiyonu sonrasi prototip seviyesinde geri bildirim vermek.

Metin:

`AgeSA Sinerji Agi aktif. Onay detaylari Akbank/AgeSA akisinda tamamlanir.`

### Frame 05 - Detay Acilir Durumlari

Frame adi: `05_Detay_Acilir_Durumlar`

Amac: Dashboard ve Simulator icindeki "sikmayan detay" prensibini gostermek.

Acilir alanlar:

- Ekosistem detay: "Bu alan fon getirisi degildir. CarrefourSA, Enerjisa, Teknosa ve benzeri Sabanci ekosistemi katkilarinin ayrismis gorunumudur."
- Kahve metaforu: "Kahve metaforu, kucuk ve duzenli katkilarin uzun vadede nasil gorunur hale geldigini anlatmak icin kullanilir."
- Varsayimlar: "Yuzdelikler, piyasa varsayimlari ve kampanya detaylari Sabanci/AgeSA tarafindan belirlenir. Bu prototipteki hesap sadece sunum icin olasi senaryo placeholderidir."

## 3. Tasarim Tokenlari

### Renkler

```text
ak-red        #D71920   Ana CTA, aktif vurgu, Akbank kirmizisi
ak-red-dark   #A80F17   CTA pressed/hover varyanti
ink           #17191F   Ana metin
muted         #68707A   Ikincil metin
soft          #F2F3F6   Uygulama arka plani
surface       #FFFFFF   Panel ve kart zemini
line          #DEDFE4   Cizgi ve border
blue          #2663D9   Devlet katkisi vurgusu
green         #11845B   Ekosistemden Gelen / aktif durum
amber         #B86B00   Varsayim/uyari notu
teal          #087C89   Icgooru vurgusu
```

### Tipografi

Figma oneri: Inter veya SF Pro. Canva oneri: Inter, Arial veya benzer sade sans-serif.

```text
Display Amount   28 px / 30 px, 800-900, letter spacing 0
Section Title    15 px / 18 px, 700-800
Body             13 px / 18 px, 400-600
Microcopy        11-12 px / 15-16 px, 400-700
CTA              15 px / 18 px, 800
```

### Bosluk ve Olcu

```text
Frame width           390 px
Phone screen height   844 px
Outer content padding 14 px
Panel padding         14 px
Card gap              8-10 px
Panel radius          8 px
Phone shell radius    28 px
Touch target          minimum 44 px
Bottom CTA height     48 px
App bar height        56 px
Status bar height     28 px
```

### Gorsel Stil

- Arka plan acik gri bankacilik yuzeyi gibi olmali.
- Kartlar tek seviyeli olmali; kart icinde kart hissi yaratilmamali.
- Ana aksiyon kirmizi ve dolu buton olmali.
- Ikincil aksiyonlar beyaz zemin, kirmizi border veya koyu metinle verilmeli.
- Grafiklerde renk tek anlam tasimamalidir; etiket ve sayi mutlaka yaninda olmalidir.
- Finansal uyari metinleri kucuk ama gorunur olmalidir.

## 4. Component Listesi

### 4.1 App Bar

Icerik:

- Sol: geri ikonu
- Orta: ekran basligi ve alt baslik
- Sag: yardim/asistan ikonu

Variantlar:

- Dashboard: "AgeSA Sinerji Agi" / "Akbank Mobil"
- Simulator: "Gelecek Simulatoru" / "Olasi birikim senaryosu"
- Kontrol: "Birikim Kontrolu" / "Otopilot ve fon takibi"

### 4.2 Hero Panel

Kullanim:

- Dashboard'da toplam birikim ve hedef ilerleme
- Simulator'da ana soru
- Kontrol ekraninda Otopilot profili

Ozellik:

- Ustte 4 px ak-red vurgu cizgisi
- Beyaz zemin
- 8 px radius
- 1 px line border

### 4.3 Metric Card

Variantlar:

- Benim Yatirdigim: ak-red vurgu
- Devlet Katkisi: blue vurgu
- Ekosistemden Gelen: green vurgu

Icerik:

- Label
- Tutar
- Tek satir aciklama

### 4.4 Split Row

Kullanim:

- Ekosistem kirilimi
- Simulator sonuc satirlari
- Satis sonrasi katkilar

Yapi:

- Sol: baslik + aciklama
- Sag: tutar/durum

### 4.5 Segmented Control

Variantlar:

- Zaman araligi: 1A, 3A, 1Y, Tum
- Sure secimi: 5 yil, 10 yil, 15 yil
- Risk tercihi: Garantici, Dengeli, Agresif

Aktif durum:

- Beyaz veya acik kirmizi zemin
- ak-red border/metin

### 4.6 Stepper

Kullanim:

- Aylik katki ayari

Yapi:

- 44 x 44 eksi butonu
- Ortada tutar kutusu
- 44 x 44 arti butonu

### 4.7 CTA Buttons

Primary:

- Kirmizi zemin
- Beyaz metin
- 48 px yukseklik
- 8 px radius

Secondary:

- Beyaz zemin
- Kirmizi border
- Kirmizi metin
- 44 px yukseklik

### 4.8 Quick Action

Kullanim:

- Dashboard altinda Simulator, Otopilot, Yuvarla, Destek.

Yapi:

- 4 kolon grid
- Ikon ustte, label altta
- Minimum 62 px yukseklik

### 4.9 Toast

Kullanim:

- Onay, destek ve Otopilot profil degisimi geri bildirimi.

Yapi:

- Koyu zemin
- Beyaz metin
- Ekranin alt CTA ustunde
- 2.5 saniye gorunur

## 5. Prototip Davranislari

### Dashboard

- "Ekosistemden Gelen" veya "Detay" tiklaninca ekosistem kirilimi acilir/kapanir.
- Fon getirisi segmented control aktif sekme durumunu degistirir.
- "Simulator" hizli aksiyonu Frame 02'ye gider.
- "Otopilot" hizli aksiyonu Frame 03'e gider.
- "Katkimi artir" aksiyonu ileride katkini artirma akisina baglanacak placeholder olarak kalabilir.

### Simulator

- Eksi butonu aylik katkini 100 TL azaltir, minimum 100 TL.
- Arti butonu aylik katkini 100 TL artirir, maksimum 10.000 TL.
- Sure secimi sonucu anlik gunceller.
- Risk tercihi sonucu anlik gunceller.
- "Varsayimlar" tiklaninca varsayim notu acilir/kapanir.
- "2 onayla baslat" tiklaninca Frame 04 toast/overlay gorunur.

Hesaplama placeholder mantigi:

Onemli sunum notu: Asagidaki oranlar gercek teklif, taahhut veya finansal vaat degildir. Figma/Canva prototipinde hesaplama davranisini gostermek icin kullanilan konsept placeholder degerlerdir. Nihai oranlar, piyasa varsayimlari, kampanya kosullari ve yasal metinler Sabanci/AgeSA tarafindan belirlenmelidir.

```text
Benim yatirdigim = aylik katki x sure x 12
Olasi devlet katkisi = benim yatirdigim x 0.30
Olasi ekosistem katkisi = benim yatirdigim x 0.10
Olasi fon getirisi =
  Garantici: benim yatirdigim x 0.18
  Dengeli: benim yatirdigim x 0.30
  Agresif: benim yatirdigim x 0.42
Olasi toplam = tum kalemlerin toplami
```

Not: Bu oranlar sadece prototip placeholderidir. Nihai yuzdeler Sabanci/AgeSA tarafindan belirlenmelidir.

### Satis Sonrasi Kontrol

- "Otopilotu duzenle" tiklaninca profil sirayla Garantici, Dengeli, Agresif olarak degisebilir.
- Profil degisince toast gosterilir: `Otopilot profili Dengeli olarak guncellendi.`
- "Destek al" tiklaninca destek toast'i gosterilir.
- "Fon degisikligini kesfet" tiklaninca fon rehberi placeholder toast'i gosterilir.

## 6. Ekran Metinleri

### Dashboard Metinleri

```text
AgeSA Sinerji Agi
Akbank Mobil
Tam Seffaf Dashboard
24.850 TL
Anil, gelecegin kontrolunde. Hedefine %42 yaklastin.
Olasi birikim piyasa kosullarina gore degisebilir.
Benim Yatirdigim
18.000 TL
Senin ana katkilarin
Devlet Katkisi
4.500 TL
Kosullara gore hak edilir
Ekosistemden Gelen
2.350 TL
Sabanci ekosistemi katkisi
Ekosistem kirilimi
CarrefourSA Yuvarla
Bu ay otomatik birikim
Enerjisa geri odeme
Fatura odeme katkisi
Teknosa avantaji
Hos geldin faydasi
Fon getirisi
Fon getirisi ekosistem katkilarindan ayri gosterilir.
Katkimi artir
```

### Simulator Metinleri

```text
Gelecek Simulatoru
Olasi birikim senaryosu
30 saniyelik hesaplama
1 kahve parasi gelecekte ne olur?
Degerleri degistir, olasi birikimini aninda gor.
Sonuclar kesin getiri vaadi degildir.
Aylik katki
1.000 TL
Sure
5 yil
10 yil
15 yil
Risk tercihi
Garantici
Dengeli
Agresif
Olasi Birikim Senaryosu
Benim yatirdigim
Olasi devlet katkisi
Olasi ekosistem katkisi
Olasi fon getirisi
Olasi toplam birikim
Varsayimlar
2 onayla baslat
```

### Satis Sonrasi Kontrol Metinleri

```text
Birikim Kontrolu
Otopilot ve fon takibi
AgeSA Otopilot
Dengeli
Aktif
Kontrol sende, istedigin zaman degistirebilirsin.
Fon dagilimi
Fon A
Fon B
Fon C
Performans
Bu ay fon performansi
+%2.1
Ne degisti?
Fon dagilimin hedefinle uyumlu ilerliyor.
Ekosistem katkilarin
Yuvarla ve Biriktir
CarrefourSA alisverisleri
Sinerji Geri Odemesi
Enerjisa ve Akbank odemeleri
Teknosa faydasi
Hos geldin paketi
Otopilotu duzenle
Destek al
Fon degisikligini kesfet
```

## 7. Ikon Onerileri

Figma icin Lucide, Material Symbols veya SF Symbols kullanilabilir. Canva icin benzer sade line ikonlar secilmelidir.

```text
Geri                  chevron-left
Yardim/asistan        circle-help veya message-circle-question
Benim Yatirdigim      wallet veya piggy-bank
Devlet Katkisi        landmark veya badge-percent
Ekosistemden Gelen    network veya sparkles
Simulator             calculator
Otopilot              bot veya gauge
Yuvarla               rotate-cw veya coins
Destek                headset
Fon getirisi          line-chart
Fon dagilimi          pie-chart veya chart-no-axes-column
Risk tercihi          sliders-horizontal
Sure                  calendar-clock
Onay                  check-circle
Varsayim/uyari        info veya triangle-alert
```

Ikon kurallari:

- Ikonlar metnin yerine gecmemeli; finansal kavramlarda label her zaman gorunmeli.
- Ana CTA icinde ikon zorunlu degil.
- Yardim, geri, detay gibi tanidik aksiyonlarda ikon tek basina kullanilabilir.
- Dokunma alani minimum 44 x 44 px olmali.

## 8. Figma Kurulum Adimlari

1. Yeni Figma dosyasi ac.
2. Pages alaninda su sayfalari olustur:
   - `00_Cover`
   - `01_Frames`
   - `02_Components`
   - `03_Prototype`
   - `04_Notes`
3. `01_Frames` icinde 390 x 844 px mobil frame olustur.
4. Frame'leri su sekilde cogalt ve adlandir:
   - `01_Dashboard_AgeSA_Sinerji_Agi`
   - `02_Gelecek_Simulatoru`
   - `03_Birikim_Kontrolu_Otopilot`
   - `04_Toast_AgeSA_Sinerji_Agi_Aktif`
   - `05_Detay_Acilir_Durumlar`
5. Local styles alaninda renk tokenlarini tanimla.
6. Text styles alaninda Display Amount, Section Title, Body, Microcopy ve CTA stillerini tanimla.
7. `02_Components` icinde componentleri olustur:
   - App Bar
   - Hero Panel
   - Metric Card
   - Split Row
   - Segmented Control
   - Stepper
   - Primary Button
   - Secondary Button
   - Quick Action
   - Toast
8. Auto Layout kullan:
   - App screen vertical stack
   - Content padding 14 px
   - Panel gap 10 px
   - Kart gap 8 px
9. Prototype baglantilarini kur:
   - Dashboard `Simulator` -> Simulator frame
   - Dashboard `Otopilot` -> Kontrol frame
   - Simulator `2 onayla baslat` -> Toast frame veya overlay
   - Kontrol `Destek al` -> Toast overlay
10. Variant durumlarini ekle:
   - Segmented control active/inactive
   - Metric card red/blue/green
   - Toast visible/hidden
   - Detail open/closed
11. Dev Mode veya Inspect icin component adlarini temiz tut.
12. `04_Notes` sayfasina oranlarin placeholder oldugu ve nihai yasal metinlerin Akbank/AgeSA akisina birakildigi notunu ekle.

## 9. Canva Kurulum Adimlari

1. Canva'da yeni tasarim olustur.
2. Custom size gir:
   - Width: 390 px
   - Height: 844 px
3. Her ekran icin ayri sayfa olustur:
   - Dashboard
   - Gelecek Simulatoru
   - Birikim Kontrolu
   - Toast / Overlay
   - Detay Acilir Durumlar
4. Arka plan rengini `#F2F3F6` yap.
5. Panel ve kartlar icin beyaz dikdortgenler kullan:
   - Radius: 8 px civari
   - Border: `#DEDFE4`
6. Ana CTA icin kirmizi dikdortgen kullan:
   - Fill: `#D71920`
   - Text: beyaz, bold
7. Ikonlar icin Elements aramasinda su terimleri kullan:
   - back arrow
   - help circle
   - wallet
   - government building
   - network
   - calculator
   - bot
   - headset
   - line chart
8. Font olarak Inter varsa Inter, yoksa Arial veya Canva Sans kullan.
9. Grafikler icin basit bar/line elementleri kullan; karmasik finans grafigi hissi yaratma.
10. Her ekranin altina speaker note olarak prototip davranisini yaz.
11. Canva prototip/presentation linklerinde:
   - Dashboard'daki Simulator butonunu Simulator sayfasina bagla.
   - Dashboard'daki Otopilot butonunu Birikim Kontrolu sayfasina bagla.
   - "2 onayla baslat" butonunu Toast sayfasina bagla.
12. Export oncesi mobil gorunumde metin tasmasi ve buton yuksekliklerini kontrol et.

## 10. QA Kontrol Listesi

- Kontrol: Tum metinler ASCII karakterlerle mi?
- Kontrol: Ana CTA her ekranda net mi?
- Kontrol: Toplam birikim en yuksek hiyerarside mi?
- Kontrol: Benim Yatirdigim, Devlet Katkisi ve Ekosistemden Gelen ayni hiyerarside mi?
- Kontrol: Fon getirisi ile ekosistem katkisi karistirilmiyor mu?
- Kontrol: "Olasi birikim" dili kesin getiri vaadi gibi durmuyor mu?
- Kontrol: Varsayim metni gorunur ama ekrani bogmuyor mu?
- Kontrol: Dokunma alanlari minimum 44 px mi?
- Kontrol: Renk tek basina anlam tasimiyor mu?
- Kontrol: Dashboard 5 saniyede anlasiliyor mu?
- Kontrol: Simulator bos form hissi vermiyor mu?
- Kontrol: Otopilot ekrani "kontrol sende" hissini veriyor mu?

## 11. Tasarim Kararlari

- "Ekosistemden Gelen" ifadesi korunmalidir; "Ekosistem Getirisi" kullanilmamalidir.
- Simulator basligi ve sonuc alaninda "Olasi Birikim Senaryosu" dili kullanilmalidir.
- Kesin getiri, garanti kazanc veya sabit oran vaadi veren ifadeler kullanilmamalidir.
- Yuzdelikler ve kampanya detaylari Sabanci/AgeSA tarafindan belirlenecek placeholder olarak kalmalidir.
- Akbank Mobil hissi taklit degil, uyum hedefidir: temiz yuzey, guvenli bankacilik dili, kirmizi ana aksiyon.
- Tosla varyanti bu dokumanda ana frame degildir; gerekirse daha genc dil ve kampanya vurgusuyla ayrica turetilebilir.
