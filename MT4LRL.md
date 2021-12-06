# Documents et Ressources sur la Traduction Automatique (TA) pour les Langues à Faibles Ressources 

Il existe une grande variété de techniques à employer lorsqu'on essaie de créer un nouveau modèle de traduction automatique pour une langue à faibles ressources ou d'améliorer une base de référence existante. L'applicabilité de ces techniques dépend généralement de la disponibilité de corpus parallèles et monolingues pour la langue cible ainsi que de la disponibilité de corpus parallèles pour des langues/domaines connexes.

## Scénarios courants

### Scénario 1 - Les données dont vous disposez sont très bruitées (par exemple, elles sont extraites du Web) et vous n'êtes pas sûr des paires de phrases qui sont " appropriées ".

Articles :

- [Low-Resource Corpus Filtering using Multilingual Sentence Embeddings](https://arxiv.org/pdf/1906.08885.pdf)
- [Findings of the WMT 2019 Shared Task on Parallel Corpus Filtering for Low-Resource Conditions](https://research.fb.com/Articles/findings-of-the-wmt-2019-shared-task-on-parallel-corpus-filtering-for-low-resource-conditions/)

Ressources / Exemples:
- [Implémentation - `fast_align` crée des alignements de mots qui peuvent être utilisés pour attribuer un score aux paires de phrases](https://github.com/clab/fast_align)
- [Implémentation - `zipporah` nettoyeur de corpus parallèles](https://github.com/hainan-xv/zipporah)
- [Implémentation - `bicleaner` nettoyeur de corpus parallèles](https://github.com/bitextor/bicleaner)
- [Implémentation - LASER Language-Agnostic SEntence Representations ou Représentations de Phrases Indépendantes de la Langue](https://github.com/facebookresearch/LASER)

### Scénario 2 - Vous ne disposez pas de données parallèles pour la paire de langues source-cible, vous n'avez que des données cibles monolingues.

Articles:

- [Phrase-Based & Neural Unsupervised Machine Translation](https://aclweb.org/anthology/D18-1549)
- [Word Translation Without Parallel Data](https://arxiv.org/abs/1710.04087)
- [Unsupervised Statistical Machine Translation](https://paperswithcode.com/paper/unsupervised-statistical-machine-translation)

Ressources / exemples :

- [Mise en œuvre - TA non supervisée (Facebook)](https://github.com/facebookresearch/UnsupervisedMT)

### Scénario 3 - Vous ne disposez que d'une petite quantité de données parallèles pour la paire de langues source-cible, mais vous avez beaucoup de données parallèles pour une paire de langues source-cible similaire.

Articles:

- [Rapid Adaptation of Neural Machine Translation to New Languages](https://arxiv.org/abs/1808.04189)
- [Neural Machine Translation with Pivot Languages](https://arxiv.org/abs/1611.04928)
- [Transfer Learning across Low-Resource, Related Languages for Neural Machine Translation](https://arxiv.org/abs/1708.09803)
- [Transfer Learning for Low-Resource Neural Machine Translation](https://arxiv.org/pdf/1604.02201v1.pdf)
- [Trivial Transfer Learning for Low-Resource Neural Machine Translation](https://arxiv.org/abs/1809.00357)
- [Pivot-based Transfer Learning for Neural Machine Translation between Non-English Languages](https://arxiv.org/abs/1909.09524)

Ressources / exemples :

- [Implémentation - méthodes d'adaptation rapide (Neubig)](https://github.com/neubig/rapid-adaptation)
- [Vidéo - méthodes d'adaptation rapide (Neubig)](https://vimeo.com/305207187)
- [Implémentation - apprentissage par transfert pour les langues à faibles ressources (Zoph)](https://github.com/isi-nlp/Zoph_RNN)

### Scénario 4 - Vous ne disposez que d'une petite quantité de données parallèles pour la paire de langues source-cible, mais vous avez beaucoup de données monolingues pour la langue cible et/ou la langue source.

Articles:

- [Improving Neural Machine Translation Models with Monolingual Data](https://arxiv.org/abs/1511.06709)
- [Iterative Back-Translation for Neural Machine Translation](https://www.semanticscholar.org/paper/Iterative-Back-Translation-for-Neural-Machine-Hoang-Koehn/0669f0a031cfaada55841e5962eb6796d4e94971)
- [Generalizing Back-Translation in Neural Machine Translation](https://www.semanticscholar.org/paper/Generalizing-Back-Translation-in-Neural-Machine-Gra%C3%A7a-Kim/9a127a2903fb3dff2a480e82dd18fcf331333caa)
- [Improving Back-Translation with Uncertainty-based Confidence Estimation](https://www.semanticscholar.org/paper/Improving-Back-Translation-with-Uncertainty-based-Wang-Liu/dae35736329852c83d32cefd66448dc73cd73368)
- [Neural Machine Translation of Low-Resource and Similar Languages with Backtranslation](https://www.semanticscholar.org/paper/Neural-Machine-Translation-of-Low-Resource-and-with-Przystupa-Abdul-Mageed/19d9226a98066ef32b4c727a9992dbfbec7dbffc)

Ressources/exemples:

- [Vidéo - À propos de la rétro-traduction (backtranslation) itérative et de la gestion des problématiques liées au "lieu"] (https://youtu.be/5A6MlGfZni0)

### Scénario 5 - Vous disposez d'une petite quantité de données parallèles pour la paire de langues source-cible, mais vous disposez également de beaucoup de données parallèles pour d'autres paires de langues.

Articles :

- [Massively Multilingual Neural Machine Translationin the Wild: Findings and Challenges](https://arxiv.org/pdf/1907.05019.pdf)
- [Multilingual Neural Machine Translation With Soft Decoupled Encoding](https://arxiv.org/abs/1902.03499)
- [Meta-Learning for Low-Resource Neural Machine Translation](https://arxiv.org/pdf/1808.08437.pdf)
- [Effective Cross-lingual Transfer of Neural Machine Translation Models without Shared Vocabularies](https://arxiv.org/abs/1905.05475)

Ressources / exemples:

- [Vidéo - Méta-apprentissage (Meta-learning) pour la TA à faibles ressources](https://vimeo.com/306147573)
- [Blog - Exploration de la TA Neuronale Massive et Multilingue](https://ai.googleblog.com/2019/10/exploring-massively-multilingual.html)
- [Blog - Traduction Zero-Shot avec le système de TA Neuronal Multilingue de Google](https://ai.googleblog.com/2016/11/zero-shot-translation-with-googles.html)

### Scénario 6 - Vous ne disposez d'aucune donnée pour la paire de langues source-cible, même pas de données monolingues, mais vous avez un linguiste ou un locuteur.

Articles :

- [Apertium: a free/open-source platform for rule-based machine translation](http://www.springerlink.com/content/h134p1j73377071k/). *Machine Translation* 24(1) pp. 1--18

Ressources / exemples:

- [apertium.org](http://www.apertium.org)

## Autres ressources diverses

Articles et ressources générales sur les langues africaines ou la TA pour les langues africaines:

- [Towards Neural Machine Translation for African Languages](https://arxiv.org/abs/1811.05467)
- [A Focus on Neural Machine Translation for African Languages](https://arxiv.org/abs/1906.05685)
- [Parallel Corpora for bi-lingual English-Ethiopian Languages Statistical Machine Translation](https://ethionlp.github.io/publication/2018-08-23-solomon_mt)

## Collecte des données, Création de corpus:

- [cocohub.cc, outils pour le crowdsourcing de corpus parallèles](https://cocohub.cc/)
- [Bitextor outil d'extraction de corpus parallèles à partir de sites web](https://bitextor.readthedocs.io/en/latest/)
- [CommonCrawl réparti par langue](http://data.statmt.org/ngrams/raw/). Si la langue n'est pas prise en charge par CLD2, construisez un modèle de langue (language model) puis demandez-leur d'exécuter un filtre de perplexité sur CommonCrawl.

## Rechercher des langues, des familles de langues, des populations, des ressources linguistiques en ligne connues, etc. via :

- [OLAC](http://www.language-archives.org/)
- [Glottolog](https://glottolog.org/)
- [Ethnologue](https://www.ethnologue.com/) (Gratuit jusqu'à un certain nombre de clics, mais de nombreuses universités proposent des abonnements au cas où vous seriez affilié à l'une d'entre elles)
