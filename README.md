# Becayişler: toplu ilan talep verileri

[Becayişler](https://becayisler.com/), Türkiye’de kamu personeli için bağımsız ve ücretsiz bir karşılıklı yer değiştirme ilan platformudur. Bu depo, aktif ilanların kişisel bilgi içermeyen toplu sayımlarını ve sayım yöntemini paylaşır.

## Kaynak

- [Güncel becayiş talep verileri ve yöntem](https://becayisler.com/becayis-verileri)
- [Güncel CSV dosyası](https://becayisler.com/becayis-verileri/veriler.csv)
- [Becayiş ilanlarını inceleyin](https://becayisler.com/becayis-ilanlari)

## 7 Ekim 2026 veri örneği

Veri alım zamanı (UTC): 2026-10-07T18:14:57.621Z. Aktif ilan grubu: 134.

[CSV dosyasını indirin](becayisler-talep-verileri-2026-10-07.csv). Boyutlar: mevcut il, kurum ve meslek. Dosya UTF-8/BOM biçimindedir; Python’da `encoding="utf-8-sig"` ile açılabilir.

Sütunlar: `veri_alim_zamani_utc`, `boyut`, `kategori`, `aktif_ilan_sayisi`, `kaynak`.

## Sayım yöntemi ve sınırlar

Bir kişinin birden fazla hedef il veya ilçe seçimi tek ilan grubu olarak sayılır. İl, kurum ve meslek sayımları ilan sahibinin beyanına dayanır. Boş kategori alanları o boyutun sayımına dahil edilmez; boyutların toplamı aktif ilan toplamından farklı olabilir.

Veri yalnızca Becayişler’deki aktif ilanları kapsar. Türkiye genelindeki tüm talepleri, resmi kurum istatistiklerini veya tamamlanmış tayinleri temsil etmez. İlan eşleşmesi resmi atama onayı değildir. Canlı kaynakta birkaç dakikalık önbellek gecikmesi olabilir. Bu depodaki CSV tarihlenmiş bir örnektir ve kendiliğinden güncellenmez.

Dosyada kişi adı, e-posta, telefon, ilan metni veya ilan kimliği bulunmaz. Kaynak belirtirken veri alım zamanını, platform kapsamını ve [yöntem sayfasını](https://becayisler.com/becayis-verileri) birlikte kullanın.

Veri kapsamı ve düzeltme talepleri: [Becayişler iletişim](https://becayisler.com/iletisim).
