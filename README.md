# Ders 2: Sekiller Dunyasi

Dosyalar:
- `baslangic.html`  -> BURADAN BASLA. Sadece kup hazir, gerisini sen ekleyeceksin.
- `index.html`      -> Tam kod. Takilirsan buna bak (once kendin dene!).
- `three.min.js`    -> Three.js kutuphanesi. Dokunma. Hepsi AYNI klasorde kalmali.

Calistirmak: html dosyasina cift tikla, tarayicida acilir.
Degisiklikten sonra: Ctrl+S (kaydet), F5 (yenile).

## Yeni fikir: konum (position)
- `x` -> saga (+) / sola (-)
- `y` -> yukari (+) / asagi (-)
- `z` -> sana dogru (+) / uzaga (-)

Her nesne icin ayni 3 adim:
1. Sekli sec ve nesne yap: `new THREE.Mesh(new THREE.SphereGeometry(...), malzeme)`
2. `nesne.position.x = ...` ile yerini sec
3. `sahne.add(nesne)` ile sahneye koy

## Gorevler (baslangic.html icinde)
1. Kure ekle
2. Silindir ekle
3. Halka ekle
4. Bonus: Zemin ekle

## Bozma Oyunu
- `kure.position.y = 2` yap, ne oldu?
- `SphereGeometry(1.2, 32, 32)` -> `SphereGeometry(1.2, 6, 6)`
- `CylinderGeometry(1, 1, 2.5, 32)` -> `CylinderGeometry(0.2, 1, 2.5, 32)`
- `zemin.position.y = -2` -> `zemin.position.y = 0`

## Odev: Kardan Adam (ya da Robot, Kule, Roket)
Sekilleri ust uste koyarak kendi nesneni yap.
Ipucu: Ust uste koymak icin `position.y` degerini degistir.

## Sayfa bos kalirsa
F12 -> Console -> kirmizi yaziyi oku.
