# QA Raporu - Anil

Proje: AgeSA Sinerji Agi  
Kapsam: PRD, HTML prototip, sunum, Figma/Canva handoff ve teslim paketi son kalite kontrolu

## 1. Ozet

Mikro ajan QA incelemesi sonrasinda kritik bulgular ana pakete islendi. HTML prototipte yas girdisi, iki onay akisi, basari karti, link temizligi, dashboard toplam tutarliligi ve erisilebilirlik iyilestirmeleri tamamlandi. Sunum ve teslim mesajlarinda yasal olarak fazla mutlak olabilecek ifadeler yumusatildi.

## 2. Kapatilan P1 Bulgular

### Yas girdisi eksigi

Bulgu: PRD simulator kapsaminda yas girdisi varken HTML prototipte yas alani yoktu.  
Durum: Kapatildi.  
Yapilan: Simulator ekranina 18-25 araliginda calisan yas stepper'i eklendi.

### 2 onayla baslat akisi eksigi

Bulgu: PRD, 2 onay ve aktif basari durumunu tarif ediyordu; HTML sadece toast gosteriyordu.  
Durum: Kapatildi.  
Yapilan: Iki checkbox, disabled CTA davranisi ve "AgeSA Sinerji Agi aktif" basari karti eklendi.

### Olu linkler

Bulgu: HTML'de placeholder anchor linkleri vardi.  
Durum: Kapatildi.  
Yapilan: Placeholder linkler prototip geri bildirimi veren butonlara cevrildi.

### Fazla mutlak "param kilitlenmiyor" mesaji

Bulgu: Teslim paketi ve deck mesajinda yasal olarak fazla mutlak yorumlanabilecek ifade vardi.  
Durum: Kapatildi.  
Yapilan: Mesaj "Paramin kosullarini seffaf goruyorum..." seklinde yumusatildi. Sunumda "kosullar seffaf, kontrol hissi artiyor" dili kullanilmali.

## 3. Kapatilan P2 Bulgular

### Dashboard toplam tutarliligi

Bulgu: JS hesaplamasi dashboard toplamini uc ana kalemin toplamindan farkli gosterebilirdi.  
Durum: Kapatildi.  
Yapilan: Dashboard toplam tutari `Benim Yatirdigim + Devlet Katkisi + Ekosistemden Gelen` uzerinden hesaplanacak sekilde duzeltildi.

### Grafik erisilebilirligi

Bulgu: Grafiklerde ekran okuyucu ozeti zayifti.  
Durum: Kapatildi.  
Yapilan: Barlara aria etiketleri ve grafik icin sr-only ozet eklendi. Tab butonlarina `role="tab"` ve `aria-selected` eklendi.

### Mobil yukseklik riski

Bulgu: Telefon mockup yuksekligi sabitti.  
Durum: Kapatildi.  
Yapilan: Telefon yuksekligi `clamp()` ve viewport tabanli hesapla daha responsive hale getirildi.

### `node --check` notu

Bulgu: HTML dosyasina dogrudan `node --check` uygulanamaz.  
Durum: Kapatildi.  
Yapilan: PRD ve teslim notu, script blogunun ayri JS olarak cikarilip `node --check` ile dogrulandigini soyleyecek sekilde netlestirildi.

### Oran/varsayim sorgusu riski

Bulgu: Handoff'ta placeholder oranlar juri tarafindan gercek sanilabilir.  
Durum: Kapatildi.  
Yapilan: Handoff'a oranlarin gercek teklif/taahhut olmadigi ve nihai oranlarin Sabanci/AgeSA tarafindan belirlenecegi notu eklendi.

### Kaynak dosya adi tutarsizligi

Bulgu: Teslim paketindeki kaynak dosya adlari klasordeki gercek Turkce dosya adlariyla birebir ayni degildi.  
Durum: Kapatildi.  
Yapilan: Teslim paketinde kaynak adlari klasordeki dosya adlariyla aynilandi.

## 4. Kapatilan P3 Bulgular

### Mikro metin tutarsizligi

Bulgu: PRD `Varsayimlari gor` derken HTML `Varsayimlar` diyordu.  
Durum: Kapatildi.  
Yapilan: HTML butonu `Varsayimlari gor` olarak guncellendi.

### Acik checklist kontrolu

Bulgu: PRD checklist tamamen kapaliydi.  
Durum: Sorun yok.  
Yapilan: Final kontrolde acik checkbox kalmadigi dogrulandi.

## 5. Son Kontrol Sonuclari

- PRD checklist tamamlandi.
- HTML prototipte olu placeholder link kalmadi.
- HTML script blogu ayri JS olarak cikarilip `node --check` ile dogrulandi.
- Teslim paketi guncellendi.
- Sunum deck, kullanici test plani, juri soru-cevap ve Figma/Canva handoff dosyalari hazirlandi.

## 6. Sunumda Dikkat Edilecek Noktalar

- "Param kilitlenmiyor" gibi mutlak ifade kullanma; "kosullar seffaf, kontrol hissi artiyor" de.
- Oranlari gercek teklif gibi sunma; "konsept placeholder, nihai oran Sabanci/AgeSA belirler" de.
- Anlatimi uc ana ekran uzerinden kur: Dashboard, Simulator, Satis Sonrasi Kontrol.
- Akbank Mobil gorsel dilinin birebir kopya degil, konsept uyarlama oldugunu belirt.
- Tosla'yi ana ekran degil, alternatif genc kanal/varyant olarak konumla.
