KÖKBAĞ OS — GEÇİCİ WEB SÜRÜMÜ
EFE CIDIK INDUSTRIAL | KÖKBAĞ Edition

YAYINLAMA (GitHub Pages):
1. ZIP'i bilgisayarına indir ve klasöre çıkar.
2. GitHub'da yeni bir repository oluştur (ör. kokbag-os).
3. Klasörün içindeki index.html, manifest.webmanifest, sw.js ve icon.svg dosyalarını repository'nin ana dizinine yükle.
4. Repository > Settings > Pages bölümüne gir.
5. Build and deployment altında Deploy from a branch seç.
6. Branch: main, folder: /(root) seçip Save'e bas.
7. Birkaç dakika sonra GitHub Pages adresin oluşur.

ÖNEMLİ:
- Bu sürüm backend veya bulut veritabanı kullanmaz.
- Kayıtlar cihazdaki tarayıcının localStorage alanında tutulur.
- Farklı cihazlarda ortak veri / otomatik senkronizasyon yoktur.
- Ayarlar bölümünden JSON yedeği indirip başka cihaza elle aktarabilirsin.
- Tarayıcı verilerini temizlemek kayıtları silebilir; düzenli yedek al.
- Bu sürüm geçici MVP'dir; ticari/üretim kullanımı öncesi sunucu, kullanıcı girişi, yetkilendirme, veritabanı ve yedekleme altyapısı eklenmelidir.
