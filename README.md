# Oyun Kuru — Türkiye oyun parası ve e-pin fiyat arşivi

Türkiye'deki oyun parası, e-pin, hediye kartı ve oyun anahtarı satıcılarının
**günlük ölçülmüş fiyatları**. Veriyi [oyunkuru.com](https://oyunkuru.com/) üretir;
yöntem [oyunkuru.com/yontem](https://oyunkuru.com/yontem/) sayfasında yazılı.

## Dosyalar

| Yol | İçerik |
|---|---|
| `arsiv/YYYY/MM/YYYY-MM-DD.csv.gz` | O günün bütün paket satırları (gzip'li CSV) |
| `gosterge.json` | Son ölçümdeki Oyun Kuru Genel Fiyat Durumu |
| `gosterge_gecmis.csv` | Göstergenin gün gün değeri |

## CSV sütunları

`oyun, sayfa, birim, miktar, satici, fiyat_tl, birim_fiyat_tl, urun_adresi`

- `fiyat_tl`: paketin satıcı sayfasındaki TL fiyatı (stoksuz paket alınmaz)
- `birim_fiyat_tl`: 1 adet oyun parası başına TL
- `sayfa`: aynı ürünün oyunkuru.com'daki karşılaştırma sayfası

Günün güncel dosyası her zaman [oyunkuru.com/veri](https://oyunkuru.com/veri/) adresinde.

## Lisans

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.tr). Kullanırken
kaynak olarak **Oyun Kuru — oyunkuru.com** yazmanız yeterli.
