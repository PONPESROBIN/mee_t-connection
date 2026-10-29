# PhoneLink

Kirim teks dan file antara HP dan PC langsung lewat Wi-Fi (WebRTC, peer-to-peer).
Tanpa server, tanpa akun, tanpa build. Satu file: `index.html`.

## Deploy di Vercel
1. Upload folder ini ke repositori GitHub.
2. Di vercel.com pilih **Add New > Project**, lalu impor repositori tersebut.
3. Framework Preset: **Other**. Kosongkan Build Command dan Output Directory.
4. Klik **Deploy**.

## Cara pakai
1. Buka link Vercel di HP dan PC (satu Wi-Fi).
2. Perangkat pertama: **Get a code**, lalu lihat kode 5 angka.
3. Perangkat kedua: **Enter a code**, ketik kode itu, lalu **Connect**.

Kode dipasangkan lewat server publik gratis PeerJS. Teks dan file tetap dikirim langsung antar perangkat.
