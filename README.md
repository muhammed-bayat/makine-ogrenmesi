# [Kaggle](https://www.kaggle.com/datasnaek/chess)


# Satranç Kazanan Tahmini

## Problemin Türü
Amaç: Oynanan hamleler incelenerek kazananı belirlemek. 

Etiketlerimiz belli ve kategorik olduğu için Sınıflandırma Problemi.

Açılış kodları --> https://www.365chess.com/eco.php

## Veriseti
* **id**: Oyun numarası, nümerik
* **rated**: Değerlendime, kategorik
* **created_at**: Başlangıç zamanı, nümerik
* **last_move_at**: Bitiş zamanı, nümerik
* **turns**: Hamle sayısı, nümerik
* **victory_status**: Kazanan nasıl kazandı, kategorik
* **winner**: Kazanan renk, kategorik
* **increment_code**: Oyunun zaman türü, nümerik
* **white_id**: Beyaz taşlarda ki oyuncunun numarası, nümerik
* **black_id**: Siyah taşlarda ki oyuncunun numarası, nümerik
* **white_rating**: Beyaz taşlarda ki oyuncunun puanı, nümerik
* **black_rating**: Siyah taşlarda ki oyuncunun puanı, nümerik
* **moves**: Hamleler, nümerik
* **opening_eco**: Açılışın kodu, kategorik
* **opening_name**: Açılışın ismi, kategorik
* **opening_ply**: Açılış fazı kaç hamlede tamamlandı, nümerik

## Karışıklık Matrisi

**TP:** Kazanacak kişiye kazandı demek.

**TN:** Kaybedecek kişiye kaybetti demek.

**FP:** Kaybedecek kişiye kazandı demek.

**FN:** Kazanacak kişiye kaybetti demek.

**Kullanılacak Metrik:** Accuracy
