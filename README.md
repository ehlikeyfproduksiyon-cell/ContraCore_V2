# ContraCore V2 — Sürüm Dağıtımı

Bu repo **yalnızca sürüm dağıtımı** içindir. Kaynak kod burada yer almaz.

- `updates/version.json` — otomatik güncelleme manifesti (uygulama bunu okur).
- Releases — her sürümün `ContraCore-Setup-<version>.exe` kurulum dosyası.

Uygulama açılışta `updates/version.json`'daki sürümü kendi sürümüyle karşılaştırır;
yeni sürüm varsa Setup dosyasını indirir, SHA256 doğrular ve sessiz kurar.
