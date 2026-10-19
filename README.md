# Görsel Lab

Kavramları etkileşimli görsellerle öğrenmek için küçük deneyler. İlk deney: OR ve AND nöronlarıyla XOR.

## Yerelde açma

`site/index.html` dosyasını tarayıcıda açın. Sunucuyla önizlemek için:

```sh
python3 -m http.server 8766 --bind 127.0.0.1 --directory site
```

## GitHub Pages

Settings → Pages → Build and deployment → Source: **GitHub Actions**.
`main` dalına her push, yalnızca `site/` klasörünü yayımlar.

## Yeni deney ekleme

1. Deneyin bağımsız HTML dosyasını `site/` içine ekleyin.
2. `site/index.html` içinden göreli bağlantı verin.
3. `main` dalına gönderin.

`sources/xor-network.html`, XOR görselinin düzenlenebilir kaynak parçasıdır.
XOR örneği elle seçilmiş ağırlıklar ve basamak aktivasyonu kullanır; model eğitimi yapmaz.
