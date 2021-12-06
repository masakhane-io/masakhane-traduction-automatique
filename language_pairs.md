# Paires de langues actuelles

- Nombre total de paires de langues uniques : 40
- Nombre total de benchmarks : 47

Les données d'entraînement pour les modèles présentés ci-dessous proviennent de [JW300](http://opus.nlpl.eu/JW300.php), sauf indication contraire (entre parenthèses). Pour plus de détails sur la source des données, le prétraitement, les configurations d'entraînement, etc., consultez les notebooks fournis dans les dossiers associés à chaque paire de langues.
Le score BLEU de test est calculé sur les [jeux de test](https://github.com/masakhane-io/masakhane-mt/tree/master/jw300_utils/test) de JW300 avec [SacreBLEU](https://github.com/mjpost/sacrebleu) (`tokenize=None` pour maintenir la tokenisation originale de JW300).

| Source | Cible | Meilleur Test BLEU | Lien | [Disponible sur Masakhane-web](http://translate.masakhane.io/) |
---------|--------|-----------|------| ------|
| Anglais | Afrikaans (Autshumato) | 19.56 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-af/autshumato-baseline) |  :x: |
| Anglais | Afrikaans (JW300) | 45.48 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-af/jw300-baseline) | :x: |
| Anglais | Amharique | 2.03 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-am/jw300-amharic-baseline) | :x: |
| Anglais | Arabe (TED, custom) | 9.28 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ar/jw300-tedtalk-baseline) | :x: |
| Anglais | Cinyanja | 30 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-nya/jw-300-baseline) | :x: |
| Anglais | Dendi | 22.30 | [lien](https://github.com/Jamiil92/masakhane/tree/master/en-ddn/live.bible.is-baseline) | :x: |
| Anglais | Efik | 33.48 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-efi/jw300-baseline) | :x: |
| Anglais | Ẹ̀dó | 12.49 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-bin/jw300-baseline) | :x: |
| Anglais | Ẹ̀sán | 6.25 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ish/jw300-baseline) | :x: |
| Anglais | Fon | 31.07 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-fon/jw300-baseline) | :x: |
| Anglais | Hausa | 41.11 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ha/opus_en_ha_baseline) | :x: |
| Anglais | Igbo | 34.85 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ig/jw300-baseline) | :heavy_check_mark: |
| Anglais | Isoko | 38.91 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-iso/jw300-baseline) | :x: |
| Anglais | Kamba | 27.90 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-kam/tuned-jw300-baseline) | :x: |
| Anglais | Kimbundu | 32.76 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-kmb/jw300-baseline) | :x: |
| Anglais | Kikuyu | 37.85  | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-ki/tuned-jw300-baseline) | :x: |  
| Anglais | Lingala | 48.64 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ln/jw300-baseline) | :heavy_check_mark: |
| Anglais | Luo | 34.33 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-luo/fine-tuned-jw300-baseline) | :x: |
| Anglais | Pidgin Nigérian |  24.29   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-pcm/jw300-baseline) | :x: |
| Anglais | Sotho du Nord (Autshumato) | 19.56  | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-nso/autshumato-baseline) | :x: |
| Anglais | Sotho du Nord (JW300) | 15.40 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-nso/jw300-baseline) | :x: |
| Anglais | Sesotho  | 41.23 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-st) | :x: |
| Anglais | Setswana |  19.66   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-tn/autshumato-baseline) | :heavy_check_mark: |
| Anglais | Shona | 30.84  | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-sn/jw300-shona-baseline) | :heavy_check_mark: |
| Anglais | Ndebele du Sud |  4.01 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-nr/ari-jw300-baseline) | :x: |
| Anglais | Ndebele du Sud | 26.61  | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-nr/jw300-baseline) | :x: |
| Anglais | KiSwahili (JW300) | 51.70  | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-sw/fine-tuned-jw300-baseline) | :heavy_check_mark: |
| Anglais | KiSwahili (SAWA) | 3.60 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-sw/sawa-baseline) | :x: |
| Anglais | KiSwahili (SAWA+JW300) | 17.61 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-sw/sawa%2Bjw300_baseline) | :x: |
| Anglais | Tigrigna (JW300) | 4.02 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ti/jw300-tigrigna-baseline) | :x: |
| Anglais | Tigrigna (JW300+Tatoeba+more) | 14.88  | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ti/tigmix-baseline) | :x: |
| Anglais | Tiv | 44.70 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-tiv/jw300-baseline) | :x: |
| Anglais | Tshiluba | 42.52 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-lua/jw300-baseline) | :heavy_check_mark: |
| Anglais | Tshivenda | 49.57 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-ve/jw300-baseline) | :x: |
| Anglais | Twi | 34.57 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-twi/jw300-baseline) | :x: |
| Anglais | Urhobo |  28.82   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-urh/jw300-baseline) | :x: |
| Anglais | isiXhosa (Autshumato) | 13.32 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-xh/autshumato-baseline) | :x: |
| Anglais | isiXhosa (JW300) | 6.00 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-xh/jw300-baseline) | :x: |
| Anglais | Xitsonga (JW300) |  4.44   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ts) | :x: |
| Anglais | Xitsonga (Autshumato) | 13.54 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-ts/autshumato-baseline) | :x: |
| Anglais | Yoruba |  38.62   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-yo/jw300-baseline-improve) | :x: |
| Anglais | isiZulu (Autshumato) |  1.96   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/en-zu/autshumato-baseline) | :x: |
| Anglais | isiZulu (JW300)|  4.87 | [lien](https://github.com/masakhane-io/masakhane-mt/tree/master/benchmarks/en-zu/jw300-baseline) | :x: |
| Efik | Anglais | 33.68 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/efi-en/jw300-baseline) | :x: |
| Hausa | Anglais | 25.27 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/ha-en/opus_ha_en_baseline) | :x: |
| Yoruba  | Anglais |  39.44   | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/yo-en/jw300-baseline) | :heavy_check_mark: |
| Français | Lingala | 39.81 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/fr-ln/Français-lingala-baseline) | :x: |
| Français | Swahili Congo | 33.73 | [lien](https://github.com/masakhane-io/masakhane/tree/master/benchmarks/fr-swc/Français-swahili_drc_baseline) | :x: |