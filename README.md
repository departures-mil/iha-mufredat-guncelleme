# İHA Müfredat Sistemi — eski güncelleme kanalı (köprü)

3.4.0'dan beri güncellemeler **yalnız GitHub Releases** üzerinden gelir: `departures-mil/iha-mufredat-kaynak` (latest.json + yama,
NSIS kurulum). Bu depo yalnız ≤3.3 kurulumların (kabuk 2/3) okuduğu eski kanaldır.

- `latest.json` + `paketler/iha_3_4.b64`: köprü paketi (3.4.0 arayüzü). Eski programda açılınca "Yeni kurulum gerekli" der ve
  kurulumu GitHub sürümünden indirip SHA-256 ile doğrulayarak kurar. Kayıtlar korunur.
- Üretim: kaynak deposunda `node araclar/eski-kanal.js --yayinla ../iha-mufredat-guncelleme`. Yeni sürümlerde tekrar gerekmez.

Kayıtlar ve yedekler bu depoda **bulunmaz**.
