# ERÜ Cumhuriyeti

Zeynep Betül ve Fatih için iki kişilik, birinci şahıs bakışlı bir hikâye oyunu.

## Nasıl oynanır?

1. Oda sahibi (Fatih) oyunu açar, **Oda kur** der ve hangi karakterle oynayacağını seçer.
2. Ekranda çıkan oda kodunu (ör. `ERU-1234`) arkadaşına gönderir.
3. Arkadaşı aynı bağlantıyı açar, **Odaya katıl** der ve kodu yazar.
4. İkisi de lobide “Hazır” görününce oda sahibi **Oyunu başlat** der.

Kayıt oda sahibinin cihazında tutulur. Kaldığınız yerden devam etmek için oda sahibi
ana menüde aynı odaya **Devam et** der, arkadaşı yine aynı kodla katılır.

## Kontroller

- Bilgisayar: `W A S D` yürü, `Shift` koş, fare bak, `E` incele / basılı tut: birlikte it,
  sol tık vur, `F` fener, `T` mesaj yaz, `Esc` duraklat.
- Telefon / tablet: sol taraf yürü, sağ taraf bak; ekrandaki düğmeler.

## Teknik not

Tek dosyadır (`index.html`). İki oyuncu birbirine PeerJS ile doğrudan bağlanır; ayrı bir
sunucu gerekmez. Bazı mobil veri ağlarında doğrudan bağlantı kurulamayabilir; o zaman
ikiniz de Wi‑Fi’ye bağlanın.
