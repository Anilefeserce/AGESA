# PRD: Tam Seffaf Dashboard ve AgeSA Gelecek Simulatoru

Hazirlayan: Anil  
Odak: UX/UI ve musteri deneyimi  
Hedef persona: Persona 1 - Kontrollu Hedefci  
Kapsam: 18-25 yas kullanicilar icin Akbank/Tosla icinde AgeSA odakli seffaf dashboard ve gelecek simulatoru deneyimi  
Ek kaynak: AgeSA Sinerji Agi Proje Raporu PDF'i

## 0. Calisma Takip Listesi

Durum: PRD ve ilk HTML mockup ciktisi tamamlandi. Tamamlanan maddeler `[x]` ile isaretlenir ve ustu cizilir; acik maddeler `[ ]` olarak kalir.

- [x] ~~Persona 1 - Kontrollu Hedefci gorseli incelendi.~~
- [x] ~~18-25 yas deneyim fazlari gorseli analiz edildi.~~
- [x] ~~AgeSA Sinerji Agi PDF'i incelendi.~~
- [x] ~~PRD ana iskeleti olusturuldu.~~
- [x] ~~PDF'teki Sinerji Agi parcalari PRD'ye eklendi.~~
- [x] ~~"Ekosistem Getirisi" dili PDF'e uygun sekilde "Ekosistemden Gelen" olarak guncellendi.~~
- [x] ~~Simulator dili kesin getiri yerine "Olasi Birikim Senaryosu" olarak guncellendi.~~
- [x] ~~Piyasa degiskenleri ve yuzdeliklerin Sabanci/AgeSA tarafindan belirlenecegi notu eklendi.~~
- [x] ~~Akbank Mobil gorsel dili ana tasarim yonu olarak belirlendi.~~
- [x] ~~Tam Seffaf Dashboard icin ilk wireframe ve gereksinimler yazildi.~~
- [x] ~~AgeSA Gelecek Simulatoru icin ilk wireframe ve gereksinimler yazildi.~~
- [x] ~~Fon Dagilimi ve Satis Sonrasi Etkilesim ekrani icin ilk wireframe ve gereksinimler yazildi.~~
- [x] ~~Basari metrikleri, riskler ve kapsam disi maddeler yazildi.~~
- [x] ~~Akbank Mobil gorsel diline gore 2-3 ekranlik daha detayli mockup taslaklari hazirlanacak.~~
- [x] ~~Dashboard ekraninda bilgi hiyerarsisi daha ayrintili hale getirilecek.~~
- [x] ~~Simulator ekraninda "sikmayan detay" katmani ve mikro metinler netlestirilecek.~~
- [x] ~~Satis sonrasi ekraninda Otopilot, Yuvarla ve Biriktir, Sinerji Geri Odemesi kirilimlari detaylandirilacak.~~
- [x] ~~"2 onayla baslat" akisi icin kapsam karari netlestirilecek.~~
- [x] ~~Sabanci/AgeSA yuzdelik ve varsayim detaylari icin placeholder/dipnot karari netlestirilecek.~~
- [x] ~~Son PRD kontrolu yapilip sunuma hazir ozet cikarilacak.~~
- [x] ~~Akbank Mobil gorsel dilinde 3 ekranlik HTML mockup/prototip dosyasi olusturuldu.~~
- [x] ~~HTML mockup icinde Dashboard, Simulator ve Satis Sonrasi Kontrol ekranlari hazirlandi.~~
- [x] ~~Mockup dosyasi temel icerik ve dosya kontrolunden gecirildi.~~
- [x] ~~Simulator artir/azalt, sure ve risk secimiyle calisir hale getirildi.~~
- [x] ~~Varsayimlar, kahve metaforu ve ekosistem detayi acilir/kapanir detay katmanlari olarak eklendi.~~
- [x] ~~"2 onayla baslat", Otopilot duzenleme, destek ve fon rehberi icin prototip geri bildirimleri eklendi.~~
- [x] ~~Etkilesimli HTML prototip tekrar temel dosya kontrolunden gecirildi.~~
- [x] ~~HTML prototip icindeki script blogu ayri JS olarak cikarilip `node --check` ile dogrulandi.~~
- [x] ~~Mikro ajanlarla sunum ozeti, Figma/Canva handoff ve QA incelemesi tamamlandi.~~
- [x] ~~Sunum ozeti dosyasi teslim paketine eklendi.~~
- [x] ~~Figma/Canva handoff dosyasi teslim paketine eklendi.~~
- [x] ~~QA bulgulari dogrultusunda yas girdisi, 2 onay akisi, basari karti, link temizligi ve erisilebilirlik iyilestirmeleri tamamlandi.~~
- [x] ~~Teslim paketi indeks dosyasi olusturuldu.~~
- [x] ~~Mikro ajanlarla kullanici test plani, juri soru-cevap ve final QA raporu hazirlandi.~~
- [x] ~~Tarayicida acilabilir 10 slaytlik sunum deck'i olusturuldu.~~
- [x] ~~Final QA riskleri dogrultusunda mutlak yasal mesajlar yumusatildi ve kaynak dosya adlari guncellendi.~~

## 1. Problem Tanimi

18-25 yas grubu finansal urunlere ilgi duyuyor ancak finansal okuryazarlik, guven ve sabir bariyerleri yuksek. Persona gorselindeki Kontrollu Hedefci; planli, hedef odakli, arastiran, karsilastiran ve zaman kaybina tahammulu olmayan bir kullanici. Ikinci gorseldeki yolculuk analizi de bu kitlenin hizli, sade, tamamen dijital, guven veren ve performansi net gosteren bir deneyim bekledigini gosteriyor.

PDF'teki AgeSA Sinerji Agi kurgusu, bu problemi Sabanci ekosistemi uzerinden somutlastiriyor: Tosla/Akbank girisi, CarrefourSA yuvarlama, Enerjisa/Akbank geri odeme, Teknosa hos geldin faydasi, Sabanci Universitesi icerikleri ve AgeSA Otopilot. Bu PRD'nin amaci, kullanicinin "Param nereye gidiyor?", "Devlet katkisi bana ne kazandiriyor?", "Ekosistem getirisi ne kadar?", "Param kilitlenir mi?", "Hedefime ne kadar yaklastim?" sorularini tek bakista cevaplayan bir dashboard ve simulator akisi tanimlamaktir.

## 2. Persona ve Gorsel Bulgularina Baglanti

Birinci gorselden ana persona ozellikleri:

- Yas: 20-24
- Yasam yeri: Buyuksehir
- Gelir durumu: Orta - Orta ustu
- Hedefler: Iyi kariyer, maddi guvence, aileye gurur verme
- Calisma tarzi: Planli calisir, program yapar, zamanini verimli kullanir
- Motivasyonlar: Kariyer basarisi, iyi gelecek, maddi guvence, ailesine kendini kanitlama
- Zorluklar: Kararsizlikta stres, cok secenekten kafa karisikligi, zaman kaybina tahammulsuzluk, basarisizlik ve geride kalma korkusu
- Davranis: Arastirir, karsilastirir, analiz eder; tavsiye dinler ama son karari kendisi verir
- Ihtiyac: Net bilgi, guven veren icerik, somut fayda, zaman kaybi yasamamak

Ikinci gorselden yolculuk bulgulari:

- Farkindalik: Kolay anlasilir, hizli, mobil odakli ve guvenilir icerik bekliyor.
- Satis ani: Hizli, sade, tamamen dijital surec; fiyat-performans dengesi; minimum form; anlik geri bildirim bekliyor.
- Satis sonrasi: Birikim, getiri ve fon dagilimini kolay takip etmek; grafikler, bildirimler, otomatik yonlendirmeler ve kisisellestirilmis icgoruler bekliyor.
- Aci noktasi: "Param kilitlenir" algisi, duzenli birikim disiplininin zayif olmasi, satis sonrasi hizmetlere ulasma zorlugu ve sistemin yeterince kisisel hissettirmemesi.

Tasarim bu nedenle dekoratif degil, is odakli olmalidir: hizli taranabilir, karsilastirmali, rakamlari saklamayan, guven hissi veren ve kullaniciyi uzun vadeli hedefe motive eden bir deneyim.

## 3. PDF Proje Raporundan Netlesen Kararlar

PDF, fikri "AgeSA Sinerji Agi" olarak konumlandiriyor. BES, bu hedef kitleye sadece "emeklilik" diliyle degil, "erken finansal bagimsizlik ve kontrol edilebilir yatirim portfoyu" diliyle sunulmali.

Netlesen urun parcalari:

- Sabanci Universitesi Finansal Kapsul: 1 dakikalik kariyer ve finans icerikleriyle farkindalik ve guven olusturma.
- Tosla & Akbank Gelecek Simulatoru: "Bugun icmedigin 1 kahve parasi, 10 yil sonra neye donusur?" sorusunu interaktif gosterme.
- Tek Tikla BES: Akbank/Tosla KYC verileriyle uzun form yerine 2 onay tikiyle aktivasyon.
- Teknosa Hos Geldin Paketi: Uzun vadeli urune kisa vadeli somut odul ekleme.
- CarrefourSA Yuvarla ve Biriktir: Alisveris kusuratini otomatik BES'e aktarma.
- Enerjisa & Akbank Sinerji Geri Odemesi: Otomatik fatura odemelerinden belirli oranda BES fonuna katki.
- AgeSA Otopilot: Risk profiline gore fon secimi/yonetimi icin robo-danisman.
- Tam Seffaf Dashboard: "Benim Yatirdigim", "Devletin Verdigi" ve "Ekosistemden Gelen" ayrimini net grafiklerle gosterme.

## 4. Urun Hedefleri

1. Kullaniciya birikiminin toplam durumunu 5 saniye icinde anlatmak.
2. "Benim yatirdigim", "Devlet katkisi" ve "Ekosistemden Gelen" kalemlerini ayri ve net gostermek.
3. Fon dagilimi, getiri ve hedef ilerlemesini basit grafiklerle takip ettirmek.
4. Satis aninda karar verme stresini azaltmak icin karsilastirma ve seffaf aciklama sunmak.
5. Akbank/Tosla icinde AgeSA Gelecek Simulatoru ile kullanicinin kucuk tutarlarla deneme motivasyonunu desteklemek.
6. Satis sonrasi etkilesimde kullaniciya otomatik, hedef odakli ve kisisel oneriler sunmak.
7. Gunluk harcamalari otomatik birikime baglayarak disiplin bariyerini azaltmak.
8. Tek Tikla BES ile basvuruyu 1 dakikanin altinda tamamlanabilir hale getirmek.

## 5. Basari Metrikleri

- Dashboard ilk bakis anlama orani: Kullanici testlerinde en az %80 kullanici uc ana kalemi dogru aciklayabilmeli.
- Simulator tamamlama orani: Simulatoru baslatan kullanicilarin en az %60'i sonuc ekranina ulasmali.
- Satis akisi terk orani: Uzun form ve belirsizlik kaynakli terklerde azalma hedeflenmeli.
- Tek Tikla BES aktivasyon suresi: Akbank/Tosla musterilerinde hedef sure 1 dakikanin altinda olmali.
- Fon dagilimi goruntuleme orani: Satis sonrasi kullanicilarin en az %50'si ayda bir fon dagilimi ekranina girmeli.
- Guven algisi: Kullanici testinde "bilgiler seffaf" ifadesi icin 5 uzerinden minimum 4 skor.

## 6. Rakip ve Benchmark Gozlemleri

Kaynaklar herkese acik uygulama magazasi, resmi sayfa ve yayinlanan ekran/aciklama metinlerinden olusur.

Tosla benzeri genc odakli finans uygulamalarindan alinacak dersler:

- Ana bakiye ve temel aksiyonlar ilk ekranda net gorunmeli.
- Para gonderme, kampanya, kart/cuzdan gibi islemler kisa yollarla erisilebilir olmalidir.
- Dil genc, direkt ve sade olmali; finansal terimler kisa aciklamalarla desteklenmelidir.

Midas benzeri yatirim uygulamalarindan alinacak dersler:

- Portfoy toplam degeri, gunluk/haftalik/toplam getiri gibi veriler tek bakista gorunmeli.
- Kullanici varliklarini kolay siralayabilmeli ve detaydan aksiyona hizli gecebilmelidir.
- Dusuk maliyet, hizli islem ve kolay takip algisi karar surecinde guven yaratir.

Akbank Mobil baglami icin alinacak dersler:

- Deneyim mevcut bankacilik uygulamasi icine gomulecegi icin guvenli, hizli ve mevcut Akbank/Tosla tasarim diline uyumlu olmalidir.
- Kisisellestirilmis akilli ipuclari, hatirlaticilar ve hedef bazli yonlendirmeler AgeSA deneyimine tasinmalidir.
- Akbank Mobil'in "Senin Icin", bildirim/mesaj, asistan, hizli islem ve BES/fon yonetimi baglami bu deneyim icin dogal giris noktalaridir.
- "Mobilin Akbanklisi" gibi oyunlastirilmis seviye/gorev yapilari, AgeSA Sinerji Agi icinde sikmayan ama kontrollu motivasyon katmani olarak kullanilabilir.

Referanslar:

- Tosla App Store: https://apps.apple.com/tr/app/tosla/id1463160775
- Tosla Google Play: https://play.google.com/store/apps/details?id=com.akode.tosla
- Midas Google Play: https://play.google.com/store/apps/details?id=com.getmidas.app
- Midas App Store: https://apps.apple.com/tr/app/midas-borsa-hisse-al%C4%B1m-sat%C4%B1m/id1554268946
- Akbank Mobil: https://www.akbank.com/dijital-bankacilik/akbank-mobil
- Akbank Mobil Google Play: https://play.google.com/store/apps/details?hl=tr&id=com.akbank.android.apps.akbank_direkt
- Mobilin Akbanklisi: https://www.akbank.com/dijital-bankacilik/akbank-mobil/mobilin-akbanklisi

## 7. Hedef Kullanici Senaryolari

Senaryo 1: Ilk kez ilgilenen kullanici  
Kullanici Tosla veya Akbank icinde "1 kahve parasi gelecekte ne olur?" kartini gorur. Simulatoru acar, aylik yatirabilecegi tutari girer, devlet katkisi ve tahmini ekosistem katkisini aninda gorur.

Senaryo 2: Kararsiz kullanici  
Kullanici BES veya benzeri uzun vadeli urune girme konusunda kararsizdir. Dashboard/Simulator ona "benim yatirdigim", "devlet katkisi", "ekosistemden gelen" ve "fon getirisi" ayrimini acikca gosterdigi icin urunu daha somut algilar.

Senaryo 3: Satis sonrasi takip eden kullanici  
Kullanici birikimini actiktan sonra dashboard'a girer. Fon dagilimini, hedefe kalan sureyi, toplam getiriyi ve degisiklik onerilerini gorur. Gerekirse tek tikla destek veya fon degisiklik rehberine ulasir.

Senaryo 4: Otomatik birikim kullanan kullanici  
Kullanici CarrefourSA alisverisinde 142 TL odediginde tutar 150 TL'ye yuvarlanir ve 8 TL AgeSA BES hesabina aktarilir. Dashboard'da bu katkiyi "Ekosistemden Gelen" altinda gorur.

Senaryo 5: Fon seciminde kararsiz kullanici  
Kullanici hangi fonu sececegini bilemez. AgeSA Otopilot'ta "Garantici", "Dengeli" veya "Agresif" risk profilini secer; sistem fon dagilimini sade bir ozetle onerir.

## 8. Bilgi Mimarisi

Ana giris noktasi:

- Akbank Mobil ana sayfasinda "Senin Icin" veya varlik/birikim alanindan "AgeSA Sinerji Agi" girisi
- Akbank Mobil hizli islemler icinde "Gelecek Simulatoru" kisa yolu
- Tosla varyanti icin ayni akisin daha hafif ve kampanya odakli uyarlamasi

Ana ekranlar:

1. Tam Seffaf Dashboard
2. AgeSA Gelecek Simulatoru
3. Fon Dagilimi ve Satis Sonrasi Aksiyonlar

Alt moduller:

- Katki ayrisimi
- Getiri ozeti
- Hedef ilerleme
- Fon dagilimi
- Risk/tercih ayari
- Kisisel oneriler
- Sabanci Universitesi Finansal Kapsul
- Tek Tikla BES aktivasyonu
- Yuvarla ve Biriktir
- Sinerji Geri Odemesi
- AgeSA Otopilot
- Destek ve SSS

## 9. Ekran 1: Tam Seffaf Dashboard

Amac: Kullaniciya birikimini, devlet katkisini ve ekosistemden gelen buyumeyi tek bakista seffaf bicimde gostermek.

Ust alan:

- Baslik: "Gelecegim"
- Alt metin: "Birikimin ve katkilarin tek ekranda."
- Toplam deger: "Toplam birikim"
- Hedef ilerleme cubugu: "Hedefine %X yaklastin"

Ana kartlar:

- Benim Yatirdigim: Kullanicinin cebinden cikan toplam tutar
- Devlet Katkisi: Kazanilan veya hak edilen devlet katkisi
- Ekosistemden Gelen: CarrefourSA yuvarlama, Enerjisa/Akbank geri odeme, Teknosa faydasi ve diger ekosistem katkilarinin toplami

Karar: Mockup'ta ana kart etiketi PDF'teki gibi "Ekosistemden Gelen" olmalidir. Bu alan fon getirisi degil, Sabanci ekosisteminden gelen ek katkilarin toplamidir. Fon getirisi ayri performans grafiginde gosterilmelidir.

Gorsel kural:

- Uc ana kalem ayni hiyerarside gorunmeli.
- Toplam birikim bu uc kalemin toplam mantigini kullaniciya anlatmali.
- Renkler tek basina anlam tasimamali; ikon, etiket ve aciklama birlikte kullanilmali.

Kritik mikro metinler:

- "Bu tutar senin yatirdigin ana paradir."
- "Devlet katkisi kosullara gore hak edilir."
- "Ekosistemden Gelen CarrefourSA, Enerjisa, Teknosa ve benzeri katkilarin toplamidir."
- "Olasi birikim piyasa kosullarina gore degisebilir."
- "Paran kilitli degil; islem kosullarini buradan gorebilirsin."

Wireframe:

```text
[Gelecegim]                         [Yardim]
Toplam Birikim
24.850 TL
[Hedef ilerleme cubugu: %42]

[Benim Yatirdigim] [Devlet Katkisi] [Ekosistemden Gelen]
  18.000 TL          4.500 TL          2.350 TL

[Ekosistemden Gelen]
CarrefourSA +8 TL | Enerjisa +24 TL | Teknosa avantaji

[Fon Getirisi Grafigi: 1A / 3A / 1Y / Tum]

[Fon Dagilimi]
Fon A %40 | Fon B %35 | Fon C %25

[Oneri]
Hedefine daha hizli yaklasmak icin aylik katkini 250 TL artirabilirsin.
```

## 10. Ekran 2: AgeSA Gelecek Simulatoru

Amac: Kullanicinin kucuk tutarlarla baslayip gelecekteki potansiyelini anlamasini saglamak.

Giris:

- Akbank Mobil ana sayfa/Senin Icin karti: "1 kahve parasi gelecekte ne olur?"
- Akbank Mobil icinde alternatif hizli islem etiketi: "Gelecegini 30 saniyede simule et"
- Tosla varyanti icin ayni mesaj daha genc ve kampanya odakli kullanilabilir.
- CTA: "Hesapla"

Form alanlari minimum olmalidir:

- Yas
- Aylik yatirim tutari
- Hedef sure
- Risk tercihi: Garantici / Dengeli / Agresif

Anlik sonuc alanlari:

- Benim yatiracagim toplam
- Olasi devlet katkisi
- Olasi ekosistem katkisi
- Olasi fon getirisi
- Olasi toplam birikim

Persona baglantisi:

- Cok secenek kafa karisikligi yarattigi icin varsayilan degerler onceden secili gelmelidir.
- Kullanici analiz etmeyi sevdigi icin "detayi goster" secenegi bulunmalidir.
- Zaman kaybina tahammulu olmadigi icin sonuc ayni ekranda, anlik guncellenmelidir.
- "Tek Tikla BES" icin sonuc ekranindan 2 onayli baslatma akisi verilmelidir.
- Simulator kesin getiri vaadi vermemelidir; sonuc "olasi birikim senaryosu" olarak sunulmalidir.
- Piyasa degiskenleri, yuzdelikler ve hesaplama varsayimlari Sabanci/AgeSA tarafindan belirlenecek konsept detaylari olarak birakilmalidir.

Wireframe:

```text
[AgeSA Gelecek Simulatoru]
1 kahve parasi gelecekte ne olur?

Yas: [22]
Aylik katki: [1.000 TL]  [-] [+]
Hedef sure: [10 yil]
Risk tercihi: [Garantici] [Dengeli] [Agresif]

Olasi Birikim Senaryosu
Benim yatirdigim:       120.000 TL
Olasi devlet katkisi:    36.000 TL
Olasi ekosistem katkisi: 12.000 TL
Olasi fon getirisi:      36.000 TL
Olasi toplam birikim:   204.000 TL

Piyasa kosullarina gore degisebilir.

[Detayi goster] [2 onayla baslat]
```

## 11. Ekran 3: Fon Dagilimi ve Satis Sonrasi Etkilesim

Amac: Kullaniciya satis sonrasinda kontrol hissi vermek ve "param kilitlenir" algisini azaltmak.

Ana bilesenler:

- Fon dagilimi halka grafigi veya yatay bar
- Getiri performansi cizgi grafigi
- "Ne degisti?" kisa icgoru modulu
- AgeSA Otopilot risk profili ve durum karti
- Yuvarla ve Biriktir katki ozeti
- Sinerji Geri Odemesi katki ozeti
- Fon degisikligi rehberi
- Destek ve canli yardim girisi

Kisisel oneriler:

- "Risk tercihin dengeli. Son 3 ayda fon dagilimin hedefinle uyumlu."
- "Aylik katkini 250 TL artirirsan hedefe olasi olarak X ay erken ulasirsin."
- "Devlet katkisi avantajini daha iyi kullanmak icin yillik limitini kontrol et."
- "CarrefourSA yuvarlama ile bu ay ek 84 TL biriktirdin."

Wireframe:

```text
[Fonlarim ve Performans]

[Dagilim Grafigi]
Fon A %40
Fon B %35
Fon C %25

[Getiri Performansi]
1A +%2.1 | 3A +%6.4 | 1Y +%18.2

[AgeSA Otopilot]
Profil: Dengeli | Durum: Aktif

[Ekosistem Katkilari]
CarrefourSA yuvarlama: +84 TL
Enerjisa geri odeme: +32 TL

[Kisisel Icogru]
Hedefine uygun ilerliyorsun. Katkini artirirsan sure kisalabilir.

[Fon degisikligini kesfet] [Destek al]
```

## 12. Akbank Mobil Mockup Taslaklari

Bu bolum Figma/Canva'da cizilecek ekranlar icin daha detayli ama sikmayan taslak tarifidir. Ekranlar Akbank Mobil'in sade bankacilik yuzeyi, guclu kirmizi aksiyonlari ve "Senin Icin" mantigina yakin kurgulanir.

### 12.1 Ekran A - AgeSA Sinerji Agi Dashboard

Amac: Kullanici uygulamaya girdiginde birikiminin nereden geldigini 5 saniye icinde anlasin.

Ust kisim:

- Ust bar: Geri oku, "AgeSA Sinerji Agi" basligi, yardim/asistan ikonu.
- Kisisel karsilama: "Anil, gelecegin kontrolunde."
- Ana rakam: "Toplam birikim" ve buyuk tutar.
- Kisa durum: "Hedefine %42 yaklastin."
- Mini uyari: "Olasi birikim ve fon performansi piyasa kosullarina gore degisebilir."

Orta kisim:

- 3 ana katki karti yan yana veya mobilde alt alta:
  - Benim Yatirdigim
  - Devlet Katkisi
  - Ekosistemden Gelen
- Her kartta tutar, tek satir aciklama ve detay oku bulunur.
- "Ekosistemden Gelen" kartina dokununca CarrefourSA, Enerjisa, Teknosa kirilimi acilir.

Alt kisim:

- Hedef ilerleme cubugu.
- Fon getirisi grafigi: 1A, 3A, 1Y, Tum sekmeleri.
- Hizli aksiyonlar: Simulator, Otopilot, Yuvarla, Destek.
- Sabit CTA: "Katkimi artir" veya "Simulatoru ac".

Mockup notu:

```text
[<] AgeSA Sinerji Agi                         [?]

Anil, gelecegin kontrolunde.
Toplam birikim
24.850 TL
[Hedef ilerleme: %42]
Olasi birikim piyasa kosullarina gore degisebilir.

[Benim Yatirdigim] 18.000 TL
[Devlet Katkisi]    4.500 TL
[Ekosistemden Gelen]2.350 TL

[Ekosistem Kirilimi]
CarrefourSA +84 TL | Enerjisa +32 TL | Teknosa avantaji

[Fon getirisi grafigi]  1A | 3A | 1Y | Tum

[Simulator] [Otopilot] [Yuvarla] [Destek]
[Katkimi artir]
```

### 12.2 Ekran B - AgeSA Gelecek Simulatoru

Amac: Kullanici uzun form hissi yasamadan, "bir kahve parasi" metaforuyla olasi birikimini gorebilsin.

Ust kisim:

- Baslik: "Gelecek Simulatoru"
- Ana soru: "1 kahve parasi gelecekte ne olur?"
- Alt metin: "Degerleri degistir, olasi birikimini aninda gor."

Girdi alani:

- Aylik katki stepper: eksi/arti butonlari ve tutar.
- Sure secimi: 5 yil, 10 yil, 15 yil.
- Risk tercihi: Garantici, Dengeli, Agresif.
- Girdiler varsayilan dolu gelir; kullanici bos form doldurmaz.

Sonuc alani:

- Baslik: "Olasi Birikim Senaryosu"
- Benim yatirdigim
- Olasi devlet katkisi
- Olasi ekosistem katkisi
- Olasi fon getirisi
- Olasi toplam birikim
- "Varsayimlari gor" linki

Sikmayan detay:

- Ekranda yasal metin blok halinde verilmez.
- "Varsayimlari gor" acilinca yuzdelerin Sabanci/AgeSA tarafindan belirlenecegi ve piyasa kosullarina gore degisecegi yazilir.
- CTA metni net olur: "2 onayla baslat".

Mockup notu:

```text
[<] Gelecek Simulatoru                         [?]

1 kahve parasi gelecekte ne olur?
Degerleri degistir, olasi birikimini aninda gor.

Aylik katki
[-] 1.000 TL [+]

Sure
[5 yil] [10 yil] [15 yil]

Risk tercihi
[Garantici] [Dengeli] [Agresif]

Olasi Birikim Senaryosu
Benim yatirdigim        120.000 TL
Olasi devlet katkisi     36.000 TL
Olasi ekosistem katkisi  12.000 TL
Olasi fon getirisi       36.000 TL
Olasi toplam            204.000 TL

[Varsayimlari gor]
[2 onayla baslat]
```

### 12.3 Ekran C - Satis Sonrasi Kontrol ve Otopilot

Amac: Kullanici sisteme girdikten sonra "param kilitlendi" hissi yerine "param benim kontrolumde" hissi yasasin.

Ust kisim:

- Baslik: "Birikim Kontrolu"
- Durum karti: "Otopilot aktif - Dengeli profil"
- Kisa aciklama: "Kontrol sende, istedigin zaman degistirebilirsin."

Orta kisim:

- Fon dagilimi: Basit halka veya yatay bar.
- Fon performansi: 1A, 3A, 1Y, Tum sekmeleri.
- "Ne degisti?" kisa icgoru karti.

Ekosistem detaylari:

- Yuvarla ve Biriktir: Bu ay gelen toplam katki.
- Sinerji Geri Odemesi: Enerjisa/Akbank kaynakli katki.
- Teknosa faydasi: Aktif/pasif durum.
- Her satirda "Detay" linki var ama ilk ekrani kalabaliklastirmaz.

Aksiyonlar:

- Otopilot profilini degistir
- Fon degisikligini kesfet
- Yuvarla ve Biriktir'i yonet
- Destek al

Mockup notu:

```text
[<] Birikim Kontrolu                         [?]

Otopilot aktif
Profil: Dengeli
Kontrol sende, istedigin zaman degistirebilirsin.

[Fon Dagilimi]
Fon A %40 | Fon B %35 | Fon C %25

[Performans] 1A | 3A | 1Y | Tum
Bu ay +%2.1

[Ne degisti?]
Fon dagilimin hedefinle uyumlu ilerliyor.

[Ekosistem Katkilari]
Yuvarla ve Biriktir       +84 TL  [Detay]
Sinerji Geri Odemesi      +32 TL  [Detay]
Teknosa faydasi           Aktif   [Detay]

[Otopilotu duzenle] [Destek al]
```

## 13. UX Ilkeleri

- Ilk ekran 5 saniyede anlasilmali.
- Kullanici asla toplam tutarin hangi parcalardan olustugunu tahmin etmek zorunda kalmamali.
- Her finansal terim icin tek cumlelik sade aciklama verilmeli.
- Kritik karar anlarinda "Detayi goster" kullanilmali; detay varsayilan olarak kullaniciyi bogmamali.
- Her aksiyon sonrasi anlik geri bildirim verilmeli.
- Satinalma akisi tamamen dijital ve minimum formlu olmalidir.
- Uzun vadeli hedefler motivasyonel ama abartisiz bir dille sunulmalidir.
- Kisa vadeli odul, uzun vadeli BES hedefinin yerine gecmemeli; sadece karar bariyerini azaltan destekleyici bir fayda olmalidir.
- "Kontrol sende" hissi icin Otopilot her zaman aciklanabilir ve kapatilabilir olmalidir.

## 14. UI Tonu ve Gorsel Yon

Tasarim dili:

- Sade, guvenilir, hizli taranabilir
- Genc kullaniciya yakin ama ciddi finansal karar hissini koruyan
- Kartlar net ayrimli, ic ice kart yapisi olmadan
- 44px+ dokunma alanlari
- Grafiklerde okunabilir etiketler ve tooltip
- Akbank Mobil gorsel diline yakin: beyaz/acik gri yuzeyler, guclu kirmizi ana aksiyon, koyu metin, kontrollu vurgu renkleri

Tipografi:

- Rakamlar buyuk ve okunakli
- Aciklama metinleri kisa
- Finansal uyari metinleri kucuk ama gizlenmemis

Erisilebilirlik:

- Renk kontrasti minimum 4.5:1
- Renk tek anlam tasiyici olmamali
- Ekran okuyucu icin her grafik ozet metinle desteklenmeli
- Hareketli grafiklerde azaltilmis hareket tercihi desteklenmeli

### 14.1 Akbank Mobil Gorsel Dili ve Mockup Rehberi

Bu proje icin Figma/Canva mockup'lari Akbank Mobil gorsel diline yakin tasarlanmalidir. Ama amac Akbank ekranini birebir kopyalamak degil; Akbank'in guven, hizli islem ve kisisel finans yonetimi hissini AgeSA Sinerji Agi'na tasimaktir.

Ana his:

- Bankacilik guveni: Temiz, net, kurumsal ve hatasiz hisseden bir yuzey.
- Genc kullanici hizi: Kisa metinler, tek bakista rakamlar, tek ekranda karar.
- Kontrol duygusu: "Benim param", "Devlet katkisi", "Ekosistemden Gelen" ayrimi saklanmadan gosterilir.
- Sikmayan detay: Detaylar ilk ekrani doldurmaz; "Detayi goster", tooltip, mini aciklama ve alt sayfalarla verilir.

Renk ve yuzey:

- Arka plan: Acik gri veya kirik beyaz bankacilik yuzeyi.
- Ana aksiyon: Akbank kirmizisina yakin guclu kirmizi CTA.
- Ikinci aksiyonlar: Beyaz zemin uzerinde kirmizi kontur veya koyu metin.
- Bilgi katmanlari: Devlet katkisi, ekosistemden gelen ve fon getirisi icin ayrisan ama sakin vurgu renkleri.
- Uyari/varsayim metinleri: Gri metin, ikon ve kisa cumle; gizlenmis dipnot gibi hissetmemeli.

Yerlesim:

- Ust bar: Geri, ekran basligi, yardim/asistan ikonu.
- Ilk gorulen alan: Toplam birikim, hedef ilerleme, 3 ana katki kalemi.
- Ana CTA: Ekranin altina yakin sabit veya kolay erisilir konumda.
- Kartlar: Tek seviyeli, 8px radius civari, genis bosluklu ama bilgi yogunlugu dengeli.
- Hizli aksiyonlar: "Simulator", "Otopilot", "Yuvarla", "Destek" gibi 4 kisa yol.

Tipografi ve hiyerarsi:

- En buyuk tipografi toplam birikim icin kullanilir.
- Kart basliklari kisa olur: "Benim Yatirdigim", "Devlet Katkisi", "Ekosistemden Gelen".
- Aciklamalar tek cumleyi gecmez.
- Uzun yasal/varsayim metinleri ekrani bogmaz; "Varsayimlari gor" ile acilir.

Grafik dili:

- Dashboard'da karma grafik yerine basit bar, cizgi veya halka grafik kullanilir.
- Renk tek basina anlam tasimaz; etiket ve tutar her zaman grafigin yaninda gorunur.
- Fon getirisi ile ekosistem katkisi ayni grafik icinde eritilmez.
- Zaman araligi secimi segmented control ile verilir: 1A, 3A, 1Y, Tum.

Akbank Mobil icindeki dogal deneyim baglantilari:

- Senin Icin: Kisisel icgoru ve "hedefine yaklastin" kartlari burada konumlanabilir.
- Hizli Islemler: Gelecek Simulatoru ve Tek Tikla BES girisi burada kisa yol olabilir.
- Bildirimler ve Mesajlar: Devlet katkisi, fon dagilimi, yuvarlama ve geri odeme bildirimleri buradan takip edilebilir.
- Akbank Asistan: "Fonumu nasil degistiririm?", "Param kilitlenir mi?" gibi sorulara kisa cevap verebilir.
- Mobilin Akbanklisi: Gorev/seviye mantigi, "bu ay 3 otomatik katki tamamlandi" gibi hafif motivasyon icin kullanilabilir.

Sikmayan detay prensibi:

- Ilk ekran cevap verir, ikinci ekran aciklar, ucuncu ekran aksiyon aldirir.
- Her ekranda tek ana karar vardir.
- Finansal metinler ders gibi degil, karar yardimi gibi yazilir.
- Oyunlastirma sadece motivasyon katmani olur; BES'in ciddi ve guvenilir yapisini golgelememelidir.

Mockup'a eklenmesi onerilen mikro anlar:

- Simulator sonucu hesaplanirken kisa sayi animasyonu.
- "Olasi birikim senaryosu" altinda tek satirlik piyasa degiskeni uyarisi.
- "Ekosistemden Gelen" kartina dokununca CarrefourSA, Enerjisa, Teknosa kirilimi.
- Otopilot profilinde "Kontrol sende, istedigin zaman degistirebilirsin" mikro metni.
- Basvuru sonunda "AgeSA Sinerji Agi aktif" onay ekrani.

## 15. Fonksiyonel Gereksinimler

- Kullanici toplam birikimini goruntuleyebilmelidir.
- Kullanici "Benim Yatirdigim", "Devlet Katkisi", "Ekosistemden Gelen" kalemlerini ayri gorebilmelidir.
- Kullanici fon getirisi ile ekosistem katkisini ayri gorebilmelidir.
- Kullanici fon dagilimini yuzdesel olarak gorebilmelidir.
- Kullanici getiri performansini zaman araligi bazinda gorebilmelidir.
- Kullanici simulator icinde yas, aylik tutar, hedef sure ve risk tercihi girebilmelidir.
- Simulator degerler degistikce sonucu anlik guncellemelidir.
- Kullanici sonuc ekranindan basvuru akisina gecebilmelidir.
- Kullanici satis sonrasi destek veya SSS alanina ulasabilmelidir.
- Sistem kisisellestirilmis oneriler sunabilmelidir.
- Kullanici Akbank/Tosla KYC verileri uygunsa 2 onay tikiyle BES aktivasyonunu baslatabilmelidir.
- Kullanici CarrefourSA yuvarlama katkilarini acip kapatabilmeli ve gecmis katkilarini gorebilmelidir.
- Kullanici Enerjisa/Akbank fatura geri odemesi katkilarini gorebilmelidir.
- Kullanici AgeSA Otopilot risk profilini secebilmelidir.

## 16. Fonksiyonel Olmayan Gereksinimler

- Dashboard acilis suresi 2 saniye altinda hedeflenmelidir.
- Simulator hesaplamasi kullanici girdisinden sonra anlik algilanacak hizda guncellenmelidir.
- Mobil oncelikli tasarlanmalidir.
- Akbank/Tosla guvenlik ve kimlik dogrulama standartlarina uyumlu olmalidir.
- Olasi birikim senaryolari icin hukuki uyari ve varsayim aciklamalari gorunur olmalidir.
- Ekosistem katkisi, devlet katkisi ve fon getirisi hesaplamalari veri kaynagi bazinda izlenebilir olmalidir.

## 17. Kapsam Disi

- Gercek fon al-sat motorunun teknik tasarimi
- Yasal metinlerin nihai icerigi
- Kesin getiri vaadi
- Tum AgeSA urun ailesinin detayli katalog deneyimi
- Masaustu web deneyimi

## 18. Riskler

- Olasi birikim senaryosu kullanicida kesin kazanc algisi yaratabilir.
- Devlet katkisi kosullari yeterince sade anlatilmazsa guven yerine kafa karisikligi yaratabilir.
- Fazla grafik ve detay personanin zaman kaybi hassasiyetini tetikleyebilir.
- Akbank/Tosla icindeki mevcut navigasyon yapisi AgeSA akisina yeterli alan acmayabilir.
- Ekosistem katkisi ile fon getirisi karisirse seffaflik hedefi zedelenir.
- Teknosa indirim ve Enerjisa geri odeme kosullari net yazilmazsa "sakli sart" algisi olusabilir.

## 19. Netlesen Kapsam Kararlari

1. Basvuru akisi mockup kapsaminda "2 onayla baslat" ve "AgeSA Sinerji Agi aktif" onay ekranina kadar cizilecek. Sozlesme ve detayli yasal onay metinleri Akbank/AgeSA standart akisina birakilacak.
2. Sabanci/AgeSA tarafindan belirlenecek yuzdelik, piyasa varsayimi ve kampanya detaylari mockup'ta placeholder ve dipnot diliyle gosterilecek. Ekran dili "detaylar Sabanci/AgeSA tarafindan belirlenir" netliginde kalacak.
3. Simulator kesin getiri vaadi vermeyecek; "Olasi Birikim Senaryosu" dili kullanilacak.
4. Ana gorsel dil Akbank Mobil olacak; Tosla sadece alternatif genc kanal/varyant olarak kalacak.

## 20. Sunuma Hazir Kisa Ozet

AgeSA Sinerji Agi, 20-24 yas arasi Kontrollu Hedefci personaya BES'i klasik emeklilik urunu gibi degil, kontrol edilebilir bir gelecek ve birikim deneyimi olarak sunar. Akbank Mobil icinde konumlanan Tam Seffaf Dashboard, kullaniciya parasinin uc ana kaynaktan nasil buyudugunu net gosterir: Benim Yatirdigim, Devlet Katkisi ve Ekosistemden Gelen.

Gelecek Simulatoru, "1 kahve parasi gelecekte ne olur?" sorusunu hizli ve sade bir akisa donusturur. Kullanici uzun form doldurmaz; aylik katki, sure ve risk tercihini degistirerek olasi birikim senaryosunu aninda gorur. Yuzdeler ve piyasa varsayimlari Sabanci/AgeSA tarafindan belirlenecek konsept detaylari olarak kalir.

Satis sonrasinda AgeSA Otopilot, Yuvarla ve Biriktir, Sinerji Geri Odemesi ve fon performansi tek ekranda takip edilir. Bu sayede "param kilitlendi" algisi, "param benim kontrolumde ve ekosistemle buyuyor" algisina donusur. Deneyim Akbank Mobil'in guvenli, hizli ve kisisellestirilmis bankacilik diliyle tasarlanir.

## 21. Teslim Ciktilari

- 2-3 ekranlik wireframe/mockup:
  - Tam Seffaf Dashboard
  - AgeSA Gelecek Simulatoru
  - Fon Dagilimi ve Satis Sonrasi Etkilesim
- HTML mockup/prototip:
  - `akbank_agesa_mockup.html`
  - Statik dosya olarak tarayicida acilabilir.
  - Akbank Mobil gorsel dili, kirmizi ana CTA, acik bankacilik yuzeyi ve sikmayan detay mantigiyla hazirlandi.
  - Simulator artir/azalt, sure ve risk secimiyle anlik olasi birikim senaryosu gunceller.
  - Varsayimlar ve ekosistem detayi tiklandiginda acilir; ilk ekran kalabaliklasmaz.
  - Otopilot ve onay butonlari prototip seviyesinde geri bildirim verir.
  - Yas girdisi, iki onay kutusu ve "AgeSA Sinerji Agi aktif" basari karti eklendi.
  - Placeholder linkler prototip geri bildirimi veren butonlara cevrildi.
  - Script blogu ayri JS olarak cikarilip `node --check` ile dogrulandi.
- Sunum ozeti:
  - `SUNUM_OZETI_Anil.md`
  - 3-4 dakikalik sunum akisi, problem, persona, cozum, ekranlar ve kapanis onerisi icerir.
- Figma/Canva handoff:
  - `FIGMA_CANVA_HANDOFF_Anil.md`
  - Frame listesi, tasarim tokenlari, component listesi, prototip davranislari, ekran metinleri, ikon onerileri ve kurulum adimlari icerir.
- Teslim paketi indeksi:
  - `TESLIM_PAKETI_Anil.md`
  - Tum dosyalari, sunum akis onerilerini ve son kontrol maddelerini tek yerde toplar.
- Sunum deck:
  - `SUNUM_DECK_Anil.html`
  - 10 slaytlik tarayicida acilabilir sunum dosyasi.
- Kullanici test plani:
  - `KULLANICI_TEST_PLANI_Anil.md`
  - Test hedefleri, gorevler, basari kriterleri, 5 saniye testi ve raporlama sablonu icerir.
- Juri soru-cevap:
  - `JURI_SORU_CEVAP_Anil.md`
  - 20 kritik juri sorusu ve net cevap onerileri icerir.
- QA raporu:
  - `QA_RAPORU_Anil.md`
  - Mikro ajan QA bulgulari, kapatilan aciklar ve sunum risk notlarini icerir.
- Benchmark ozeti:
  - Tosla: genc, hizli, cuzdan/aksiyon odakli deneyim
  - Midas: portfoy, getiri, kolay takip ve hizli aksiyon deneyimi
  - Akbank Mobil: guvenli bankacilik, mevcut ekosistem ve kisisellestirilmis ipucu baglami
- Kullanici testi icin temel gorevler:
  - "Toplam birikimin hangi parcalardan olustugunu anlat"
  - "Aylik 1.000 TL ile 10 yil sonunda ne olacagini simule et"
  - "Fon dagilimini bul ve performansi yorumla"
  - "CarrefourSA ve Enerjisa'dan gelen katkilarin nerede gorundugunu bul"
