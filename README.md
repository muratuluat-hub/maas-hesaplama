# Net Ücret ve Brüt Ücret Maaş Hesaplama

Türkiye bordro mevzuatına göre netten brüte ve brütten nete maaş hesaplama yapan tek sayfalık web uygulaması.

## Özellikler

- Aylık ücret net veya brüt olarak girilebilir.
- 12 aylık kümülatif gelir vergisi hesaplanır.
- SGK işçi, işsizlik işçi, SGK işveren ve işsizlik işveren payları hesaplanır.
- SGK taban/tavan parametreleri dikkate alınır.
- Aylık ve yıllık muhasebe kayıtları gösterilir.
- 2027 ve sonraki yıllar için vergi/SGK parametreleri arayüzden değiştirilebilir.

## GitHub Pages ile Yayınlama

1. Bu klasörü GitHub'da yeni bir public repository'ye gönderin.
2. GitHub'da repository sayfasından `Settings > Pages` bölümüne girin.
3. `Build and deployment` altında source olarak `Deploy from a branch` seçin.
4. Branch olarak `main`, klasör olarak `/root` seçin.
5. Kaydettikten sonra uygulama birkaç dakika içinde yayınlanır.

## Yerelde Çalıştırma

```bash
python3 -m http.server 4173
```

Sonra tarayıcıda açın:

```text
http://localhost:4173
```

## Not

Bu uygulama bordro hesaplama ön izlemesi içindir. Resmi bordro, teşvik ve sektör özelindeki uygulamalar için mali müşavir veya bordro uzmanı kontrolü önerilir.
