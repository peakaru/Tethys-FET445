# Tethys — Gaia DR3 Yıldız Spektral Sınıflandırması

Veri Madenciliği (FET445) dönem projesi.

**Araştırma sorusu:** Bir yıldızın spektral sınıfı (O, B, A, F, G, K, M), spektroskopi yapılmadan yalnızca Gaia'nın parlaklık, renk ve hareket ölçümlerinden ne kadar doğru tahmin edilebilir?

- **Rota:** Sınıflandırma (7 sınıf)
- **Yöntemler:** çoğunluk sınıfı temel modeli, k-NN, lojistik regresyon, karar ağacı
- **Hedef değişken:** `SpType-ELS`

## Veri seti

[Gaia 626k stars from DR3 (Data release 3) V2](https://www.kaggle.com/datasets/realkiller69/gaia-stars-dataset-from-dr3-data-release-3) — RealKiller69, Kaggle. Lisans: Open Database License (ODbL).
Kaynak katalog: ESA Gaia Data Release 3.

Veri boyutu nedeniyle depoya eklenmemiştir. Edinmek için:

1. Kaggle sayfasından veri setini indirin (ya da Kaggle API ile:
   `kaggle datasets download -d realkiller69/gaia-stars-dataset-from-dr3-data-release-3`).
2. Arşivi açıp CSV dosyasını `data/` klasörüne koyun.

## Depo yapısı

| Klasör | İçerik |
|---|---|
| `data/` | Ham veri (git'e eklenmez) |
| `notebooks/` | Numaralı Jupyter notebook'lar (`..._FET445_1.ipynb`, …) |
| `src/` | Yardımcı Python dosyaları |
| `report/` | Proje önerisi ve proje raporu (PDF) |
| `presentation/` | Sunum videosu (.mp4, 100 MB altında) |

## Sonuçların yeniden üretilmesi

Proje ilerledikçe eklenecek: Python sürümü, `requirements.txt` ve notebook'ların çalıştırılma sırası.

## Bağlantılar

- Sunum videosu (YouTube): _eklenecek_
