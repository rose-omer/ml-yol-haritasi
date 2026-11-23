# Makine Öğrenmesi, Yapay Zekâ ve Görüntü İşleme — İleri Düzey Yol Haritası

Hedef: 3 yıllık deneyimin üstüne uzmanlık kurmak ve öğrenilen her konuyu Medium'da yayımlamak.
Medium: <https://medium.com/@omersofware>

## Nasıl kullanılır

- Her aşama konuyu temelden kurar, ama kaynaklar lisansüstü düzeydedir.
- Sıra önerilir, zorunlu değildir. Bildiğin aşamada yalnız "Okunacak makaleler" ve "Uygulama projeleri" kısmını yap.
- Bir aşama şu üç çıktı ile biter: sıfırdan yazılmış kod, ölçüm sonucu, en az 4 Medium yazısı.
- Bir konuyu bitirince kutuyu işaretle. Yazının bağlantısını başlığın yanına ekle.

## Aşamalar

| # | Aşama | Süre | Durum |
|---|-------|------|-------|
| 1 | Matematik ve teori | gerektikçe; toplam ~2 hafta | ☐ |
| 2 | Klasik ML derinlemesine | 5 hafta | ☐ |
| 3 | Derin öğrenme çekirdeği | 8 hafta | ☐ |
| 4 | Görüntü işleme ve geometrik görü | 8 hafta | ☐ |
| 5 | Modern bilgisayarlı görü | 10 hafta | ☐ |
| 6 | Üretken modeller ve 3B görü | 8 hafta | ☐ |
| 7 | Transformer, LLM ve görü-dil modelleri | 8 hafta | ☐ |
| 8 | Üretim, hız ve ML sistemleri | 8 hafta | ☐ |
| 9 | Araştırma becerisi ve teknik yazarlık | sürekli | ☐ |

Toplam: haftada 10-12 saat ile yaklaşık 13-14 ay.

**Başlangıç: Aşama 3.** Aşama 1 blok olarak çalışılmaz; bir formülde takılınca ilgili konuya dönülür.

Kısa yol (görüntü işleme önce): 3 → 4 → 5 → 8, sonra 6 → 7; Aşama 2 paralel yürür.

## Aşama içinde nasıl ilerlenir

Aşamalar sırayla yürür; her aşama farklı konu anlatır. Bir aşamanın kaynakları ise aynı konuyu farklı biçimde anlatır: tablo bir menüdür, hepsi okunmaz.

1. Ana kaynağı bitir (her aşamada "Ana kaynak" satırı).
2. "Okunacak makaleler"den 3-4 tanesini seç.
3. Bir uygulama projesini yap.
4. Yazıları yaz.
5. Sonraki aşamaya geç; kalan kaynaklara dönme.

- Başvuru kaynağı baştan sona okunmaz; yalnız takılınan konuda açılır.
- Zorunlu sıra: 3 → 5 ve 3 → 6 → 7. Aşama 4 ve 8 araya girebilir.

## Bağlantı etiketleri

Kaynak tablolarında her kaynağın bağlantıları etiketlidir:

| Etiket | Nereye gider |
|--------|--------------|
| Site | Kaynağın ana sayfası |
| PDF | Kitabın ya da notun doğrudan PDF dosyası |
| Web kitap | Kitabın tarayıcıda okunan sürümü (çeviri için en rahatı) |
| Video listesi | Ders videolarının oynatma listesi |
| Notlar | Ders notları ya da slaytlar |
| Ödevler | Ödev ve çözüm sayfası |
| Kod | GitHub deposu |

"Ücretsiz" sütunu: Evet / Yalnız web (PDF yok) / Kısmen / Hayır.

## Haftalık düzen

| Gün | İş | Süre |
|-----|----|------|
| Pzt-Sal | Ders ya da kitap bölümü; elle not | 2 × 1,5 saat |
| Çar | Bir makale; üç geçişli okuma | 1,5 saat |
| Per-Cum | Kod: makaleyi ya da yöntemi sıfırdan yaz | 2 × 2 saat |
| Cmt | Ölçüm, şekil, yazı taslağı | 2 saat |
| Paz | Yazıyı yayımla, README'yi güncelle | 1 saat |

## Uzmanlık ölçütü

Bir konuyu "bildim" saymak için dördü de gerekir:

- Kütüphane kullanmadan sıfırdan yazarsın.
- Özgün makaleyi okudun ve bir sonucunu yeniden ürettin.
- Yöntemin nerede bozulduğunu ölçümle gösterirsin.
- Konuyu bir yazıda, formül ve şekille, başkasına anlatırsın.



## Aşama 1 — Matematik ve teori
**Hedef:** Lineer cebir, olasılık ve optimizasyonu öğrenme kuramına bağlamak.

**Ana kaynak:** Mathematics for Machine Learning (bölüm seçerek). **Başvuru:** The Matrix Cookbook, CS229 Lecture Notes.

**Çalışma biçimi: gerektikçe.** Mühendislik temeli (vektör, matris, özdeğer, türev, temel olasılık) varsa bu aşamayı baştan sona yapma.

- Atla: temel lineer cebir ve analiz; Strang dizisinin tamamı; 3Blue1Brown.
- Atlama: matris türevi, SVD'nin kullanımı (PCA, düşük rütbe, LoRA), Bayes çıkarımı ve en büyük olabilirlik, bilgi kuramı (entropi, çapraz entropi, KL), optimizasyon (SGD, kayıp yüzeyi).
- Tek başvuru kitabı: Mathematics for Machine Learning; bölüm seçerek oku.
- Sınama: bir doğrusal katmanın gradyanını kâğıtta çıkar; çapraz entropiyi en büyük olabilirlikten türet. İkisi rahat çıkıyorsa aşama tamam.

### Konular
- Matris ayrışımları: SVD, özayrışım, düşük rütbe yaklaşımı
- Sayısal lineer cebir: kayan nokta, koşul sayısı, en küçük kareler
- Olasılık ve Bayes çıkarımı: posterior, marjinalleştirme, yaklaşık çıkarım
- İstatistiksel öğrenme teorisi: genelleme sınırı, VC boyutu, Rademacher karmaşıklığı
- Bias-variance ve double descent
- Konveks optimizasyon: dualite, KKT koşulları, Lipschitz ve güçlü konveklik
- SGD dinamiği: gürültü, öğrenme oranı, yakınsama hızı
- Bilgi kuramı: entropi, KL sapması, karşılıklı bilgi

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| MIT 18.065: Matrix Methods in Data Analysis (Strang) | ders | [Site](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) · [Video listesi](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/video_galleries/video-lectures/) · [Notlar](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/pages/readings/) · [Ödevler](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/pages/assignments/) | Evet | SVD ve PCA'yı veri analizi bağlamında işler |
| Mathematics for Machine Learning (Deisenroth ve ark.) | kitap | [Site](https://mml-book.com) · [PDF](https://mml-book.com/book/mml-book.pdf) | Evet | ML için matematik temeli; yazarlar ücretsiz PDF sunar |
| EE364A: Convex Optimization I (Boyd) | ders | [Site](https://web.stanford.edu/class/ee364a/index.html) · [Notlar](https://www.stanford.edu/~boyd/cvxbook/bv_cvxslides.pdf) | Kısmen | Konveks optimizasyonun resmî Stanford ders sayfası |
| Convex Optimization (Boyd, Vandenberghe) | kitap | [Site](https://web.stanford.edu/~boyd/cvxbook/) · [PDF](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf) | Evet | Konveks optimizasyonun standart referansı; PDF ücretsiz |
| Introduction to Applied Linear Algebra (Boyd, Vandenberghe) | kitap | [Site](https://web.stanford.edu/~boyd/vmls/) · [PDF](https://web.stanford.edu/~boyd/vmls/vmls.pdf) | Evet | En küçük kareler ve lineer modeller için sade anlatım |
| The Matrix Cookbook (Petersen, Pedersen) | referans | [Site](https://www2.compute.dtu.dk/pubdb/pubs/3274-full.html) · [PDF](https://www2.compute.dtu.dk/pubdb/edoc/imm3274.pdf) | Evet | Matris türevleri ve özdeşlikleri için başvuru kaynağı |
| Information Theory, Inference, and Learning Algorithms (MacKay) | kitap | [Site](https://www.cambridge.org/0521642981) | Kısmen | Bilgi kuramı ve Bayes çıkarımı; yazar ücretsiz PDF'i kendi sitesinde (inference.org.uk) verir, bağlantı doğrulanamadı |
| Probabilistic Machine Learning: An Introduction (Murphy) | kitap | [Site](https://probml.github.io/pml-book/book1.html) · [PDF](https://github.com/probml/pml-book/releases/latest/download/book1.pdf) | Evet | Olasılıksal ML için kapsamlı, ücretsiz taslak PDF |
| CS229 Lecture Notes (Ng, Ma) | ders | [Site](https://cs229.stanford.edu/) · [PDF](https://cs229.stanford.edu/main_notes.pdf) | Evet | Kuramsal ML notları; kurs sayfası Stanford girişi ister |
| Understanding Machine Learning (Shalev-Shwartz, Ben-David) | kitap | [Site](https://www.cambridge.org/core/books/understanding-machine-learning/preface/78FF9A254F682A1E33037CE2D82B4270) · [PDF](https://cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf) | Evet | PAC öğrenme ve genelleme sınırları |
| Essence of linear algebra (3Blue1Brown) | video | [Site](https://www.3blue1brown.com/) · [Video listesi](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | Evet | Lineer cebir sezgisi; yalnız ön hazırlık için |

### Okunacak makaleler
- [Reconciling Modern Machine Learning Practice and the Bias-Variance Trade-off (2019)](https://arxiv.org/abs/1812.11118) — double descent'in ilk ayrıntılı kuramsal açıklaması.
- [Deep Double Descent: Where Bigger Models and More Data Hurt (2019)](https://arxiv.org/abs/1912.02292) — derin ağlarda model ve veri boyutuna göre test hatası deneyleri.
- [Understanding Deep Learning Requires Rethinking Generalization (2016)](https://arxiv.org/abs/1611.03530) — klasik genelleme açıklamalarının yetersiz kaldığını gösterir.
- [Optimization Methods for Large-Scale Machine Learning (2016)](https://arxiv.org/abs/1606.04838) — stokastik gradyan yöntemlerinin kapsamlı incelemesi.
- [Stochastic Gradient Descent as Approximate Bayesian Inference (2017)](https://arxiv.org/abs/1704.04289) — SGD'yi yaklaşık Bayes çıkarımı olarak yorumlar.

### Uygulama projeleri
- SVD'yi güç yinelemesiyle sıfırdan yaz; görüntü sıkıştırma yap. Çıktı: rütbe-k hatası grafiği ve sıkıştırma oranı tablosu. `np.linalg.svd` sonucuyla karşılaştır.
- Rastgele özellikli regresyonla double descent deneyi kur. Çıktı: üç veri boyutu için model kapasitesi-test hatası eğrisi; interpolasyon eşiğini işaretle.
- Lojistik regresyonu sıfırdan yaz; öğrenme oranı ve mini-batch boyutunu tara. Çıktı: yakınsama eğrileri ve öğrenme oranı-kayıp kararlılık raporu.

### Medium yazı başlıkları
- Matris Rütbesi Neden Veriyi Sıkıştırır: SVD'den Düşük Rütbe Yaklaşımına
- PCA'da Özdeğerler Neden Varyansı Gösterir
- Koşul Sayısı En Küçük Kareler Çözümünü Neden Bozar
- Posterior Dağılımı Modelin Hangi Belirsizliğini Taşır
- Bias-Variance Eğrisi Neden Tek Bir U Değildir: Double Descent
- Genelleme Sınırları Derin Ağların Başarısını Neden Açıklayamaz
- Konveks Problemde Yerel Minimum Neden Global Minimumdur
- SGD Gürültüsü Neden Bir Düzenleyici Gibi Davranır

## Aşama 2 — Klasik ML derinlemesine
**Hedef:** Tabular veride klasik modellerin kuramını, değerlendirmesini ve kalibrasyonunu uygulamaya bağlamak.

**Ana kaynak:** CS229 Lecture Notes (bağlantısı Aşama 1 tablosunda). **Başvuru:** Probabilistic Machine Learning (Murphy), The Elements of Statistical Learning.

**Tekrar planı (3 hafta):** 1) doğrusal modeller, düzenlileştirme, bias-variance; 2) ağaçlar ve gradient boosting, XGBoost makalesi; 3) değerlendirme, kalibrasyon, veri sızıntısı ve bir proje. Çekirdek yöntemleri, Gauss süreçleri ve grafik modeller sonraya kalır.

### Konular
- Çekirdek yöntemleri: RKHS, çekirdek seçimi, destek vektör makineleri
- Gauss süreçleri: posterior çıkarım ve belirsizlik tahmini
- Olasılıksal grafik modeller: Bayes ağları, faktör grafikleri, değişken eliminasyonu
- Karar ağaçları ve topluluk yöntemleri: bagging ve boosting
- Gradient boosting: ikinci dereceden Taylor açılımı, düzenlileştirme, histogram tabanlı bölme
- Değerlendirme ve kalibrasyon: ECE, reliability diyagramı, sıcaklık ölçeklemesi
- Veri sızıntısı: hedef sızıntısı, zaman sızıntısı, doğru veri bölme
- Tabular veride derin öğrenme karşılaştırması ve nedensellik girişi

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| Deep Learning: Foundations and Concepts (Bishop, Bishop) | kitap | [Site](https://link.springer.com/book/10.1007/978-3-031-45468-4) · [Web kitap](https://www.bishopbook.com/) | Yalnız web | Derin öğrenmenin kuramsal temeli; basılı kitap ücretli, çevrimiçi okuma ücretsiz |
| Pattern Recognition and Machine Learning (Bishop) | kitap | [Site](https://www.microsoft.com/en-us/research/people/cmbishop/) · [PDF](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) | Evet | Olasılıksal modelleme ve çıkarımın klasik referansı |
| The Elements of Statistical Learning (Hastie, Tibshirani, Friedman) | kitap | [Site](https://hastie.su.domains/ElemStatLearn/) | Evet | Ağaç, boosting ve çekirdek yöntemlerinin istatistiksel çerçevesi; PDF bağlantısı sitede |
| Gaussian Processes for Machine Learning (Rasmussen, Williams) | kitap | [Site](https://gaussianprocess.org/gpml/) · [PDF](https://gaussianprocess.org/gpml/chapters/RW.pdf) | Evet | GP çıkarımı ve çekirdek seçimi için standart kaynak |
| XGBoost deposu (dmlc) | repo | [Site](https://xgboost.ai) · [Kod](https://github.com/dmlc/xgboost) | Evet | Eksik değer ve histogram bölme kodunu doğrudan incele |
| LightGBM deposu | repo | [Site](https://lightgbm.readthedocs.io) · [Kod](https://github.com/lightgbm-org/LightGBM) | Evet | GOSS ve EFB uygulamalarını C++ kodunda izle |
| CatBoost deposu | repo | [Site](https://github.com/catboost/catboost) | Evet | Sıralı hedef istatistiklerinin ve kategorik kodlamanın uygulaması |
| Tabular benchmark (Grinsztajn ve ark.) | repo | [Site](https://github.com/LeoGrin/tabular-benchmark) | Evet | Tabular veride ağaç ve derin modellerin deneysel karşılaştırması |
| Causal Inference: What If (Hernán, Robins) | kitap | [Site](https://miguelhernan.org/whatifbook) · [PDF](https://miguelhernan.org/s/hernanrobins_WhatIf_19aug26.pdf) | Evet | Gözlemsel veride nedensel çıkarım |
| Introduction to Causal Inference (Brady Neal) | ders | [Site](https://www.bradyneal.com/causal-inference-course) · [PDF](https://www.bradyneal.com/Introduction_to_Causal_Inference-Dec17_2020-Neal.pdf) · [Video listesi](https://www.youtube.com/playlist?list=PLoazKTcS0Rzb6bb9L508cyJ1z-U9iWkA0) | Evet | Potansiyel sonuçlar ve nedensel grafikler için ücretsiz ders |

### Okunacak makaleler
- [XGBoost: A Scalable Tree Boosting System (2016)](https://arxiv.org/abs/1603.02754) — seyrek veri yönetimi ve ağırlıklı kuantil eskizi.
- [LightGBM: A Highly Efficient Gradient Boosting Decision Tree (2017)](https://proceedings.neurips.cc/paper/2017/file/6449f44a102fde848669bdd9eb6b76fa-Paper.pdf) — GOSS ve EFB ile eğitim hızlanması.
- [CatBoost: Unbiased Boosting with Categorical Features (2018)](https://arxiv.org/abs/1706.09516) — hedef sızıntısını önleyen sıralı boosting.
- [Revisiting Deep Learning Models for Tabular Data (2021)](https://arxiv.org/abs/2106.11959) — tabular derin modellerin eşit protokolle karşılaştırması.
- [Why Do Tree-Based Models Still Outperform Deep Learning on Tabular Data? (2022)](https://arxiv.org/abs/2207.08815) — ağaçların tabular veride üstünlüğünün nedenleri.
- [On Calibration of Modern Neural Networks (2017)](https://arxiv.org/abs/1706.04599) — modern ağların aşırı güvenli olduğunu ve sıcaklık ölçeklemesini gösterir.
- [Leakage and the Reproducibility Crisis in ML-based Science (2022)](https://arxiv.org/abs/2207.07048) — veri sızıntısının bilimsel tekrarlanabilirliğe etkisi.

### Uygulama projeleri
- Regresyon karar ağaçları ve ikinci dereceden kayıpla gradient boosting'i sıfırdan yaz. Çıktı: sklearn `GradientBoostingRegressor` ile tahmin farkı tablosu ve öğrenme eğrisi.
- Hedef ve zaman sızıntısı içeren bir tabular veri setinde iki boru hattı kur: sızıntılı ve temiz. Çıktı: doğrulama ve test skor farkı raporu.
- İkili sınıflandırıcıda ECE, reliability diyagramı ve sıcaklık ölçeklemesi uygula. Çıktı: kalibrasyon öncesi ve sonrası ECE ve Brier skoru tablosu; isotonic regresyonla karşılaştırma.

### Medium yazı başlıkları
- Gradient Boosting Hatayı Neden Gradyan Olarak Öğrenir
- XGBoost Kaybı Neden İkinci Dereceden Taylor Açılımıyla Çözer
- LightGBM Neden Tüm Örnekleri Değil Büyük Gradyanlı Olanları Tarar
- CatBoost Hedef Sızıntısını Sıralı Boosting ile Nasıl Önler
- Tabular Veride Ağaçlar Neden Hâlâ Sinir Ağlarını Geride Bırakır
- Model Doğru Olasılık Veriyor mu: Reliability Diyagramı ve ECE
- Veri Sızıntısı Neden Tekrar Üretilemeyen Sonuçlar Doğurur
- Gauss Süreçleri Tahminle Birlikte Belirsizliği de Neden Verir


## Aşama 3 — Derin öğrenme çekirdeği

**Hedef:** Derin öğrenme eğitimini sıfırdan kurmak, ölçmek ve ölçekte yeniden üretilebilir hâle getirmek.

**Ana kaynak:** Neural Networks: Zero to Hero (kod yazarak). **Başvuru:** Understanding Deep Learning.

### Konular
- Otomatik türev: hesap grafı, ileri ve geri mod, zincir kuralı, sayısal gradyan denetimi.
- İlklendirme: Xavier ve Kaiming, varyans korunumu, çıkış katmanının ilklendirilmesi.
- Normalizasyon: BatchNorm, LayerNorm, RMSNorm; eğitim ve çıkarım arasındaki fark.
- Optimizasyon: SGD ve momentum, Adam, AdamW, bias düzeltmesi.
- Öğrenme oranı: warmup, kosinüs ve one-cycle çizelgeleri, öğrenme oranı aralık testi.
- Düzenlileştirme ve veri artırma: weight decay, dropout, stokastik derinlik, mixup, CutMix.
- Kayıp yüzeyi ve genelleme: keskinlik, double descent, grokking, lottery ticket.
- Eğitim reçetesi ve hata ayıklama: tek batch'e ezberletme, gradyan ve aktivasyon istatistikleri.
- PyTorch iç yapısı: autograd motoru, dispatch, bellek biçimi, torch.compile.
- AMP, DDP ve deney takibi: kayıp ölçekleme, çok GPU eşitleme, tohum ve yapılandırma kaydı.

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| Neural Networks: Zero to Hero | ders | [Site](https://karpathy.ai/zero-to-hero.html) · [Video listesi](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) · [Kod](https://github.com/karpathy/nn-zero-to-hero) | Evet | Geri yayılımı ve GPT'yi sıfırdan kodlar. |
| micrograd | repo | [Site](https://github.com/karpathy/micrograd) · [Kod](https://github.com/karpathy/micrograd) | Evet | Skaler autograd motoru; ilk okunacak kod. |
| A Recipe for Training Neural Networks | blog | [Site](http://karpathy.github.io/2019/04/25/recipe/) | Evet | Hata ayıklama sırası ve eğitim kontrol listesi. |
| Understanding Deep Learning | kitap | [Site](https://udlbook.github.io/udlbook/) | Evet | Modern mimarileri ve eğitim pratiğini kapsayan güncel metin; PDF bağlantısı sitede. |
| Deep Learning | kitap | [Site](https://www.deeplearningbook.org/) · [Web kitap](https://www.deeplearningbook.org/) | Yalnız web | Teorik temel; genelleme ve optimizasyon çerçevesi. |
| Dive into Deep Learning | kitap | [Site](https://d2l.ai/) · [PDF](https://d2l.ai/d2l-en.pdf) | Evet | Kodlu ve etkileşimli; PyTorch sürümü mevcut. |
| CMU 10-414/714 Deep Learning Systems | ders | [Site](https://dlsyscourse.org/) · [Notlar](https://dlsyscourse.org/lectures) · [Ödevler](https://dlsyscourse.org/assignments) | Evet | Otomatik türev motorunu sıfırdan kurdurur. |
| CMU 11-785 Introduction to Deep Learning | ders | [Site](https://deeplearning.cs.cmu.edu/F25/index.html) | Kısmen | Eğitim pratiği ve mimari; kayıt durumu doğrulanamadı. |
| MIT 6.7960 Deep Learning | ders | [Site](https://deeplearning6-7960.github.io/) · [Video listesi](https://ocw.mit.edu/courses/6-7960-deep-learning-fall-2024/video_galleries/lecture-videos/) · [Ödevler](https://ocw.mit.edu/courses/6-7960-deep-learning-fall-2024/lists/homework/) | Evet | Eski 6.S898; teori ve uygulamayı birlikte verir. |
| NYU DS-GA 1008 Deep Learning | ders | [Site](https://atcold.github.io/NYU-DLSP21/) · [Video listesi](https://atcold.github.io/NYU-DLSP21/) · [Kod](https://github.com/Atcold/NYU-DLSP21) | Evet | LeCun ve Canziani; 2021 dönemi, enerji tabanlı bakış. |
| Deep Learning Tuning Playbook | repo | [Site](https://github.com/google-research/tuning_playbook) | Evet | Sistematik hiperparametre ayarı için adım adım reçete. |
| PyTorch internals | blog | [Site](http://blog.ezyang.com/2019/05/pytorch-internals/) | Evet | Tensör düzeni, dispatch ve autograd iç yapısı. |
| Getting Started with DDP | ders | [Site](https://docs.pytorch.org/tutorials/intermediate/ddp_tutorial.html) | Evet | Çok GPU eğitiminin resmî başlangıç noktası. |
| Introduction to torch.compile | ders | [Site](https://docs.pytorch.org/tutorials/intermediate/torch_compile_tutorial.html) | Evet | Derleme akışı ve grafik kırılmaları için resmî giriş. |

### Okunacak makaleler
- [Batch Normalization (2015)](https://arxiv.org/abs/1502.03167) — normalizasyonun temel referansı; iç kovaryans kayması iddiası tartışmalı.
- [Layer Normalization (2016)](https://arxiv.org/abs/1607.06450) — batch'ten bağımsız normalizasyon; transformer'ın temeli.
- [Root Mean Square Layer Normalization (2019)](https://arxiv.org/abs/1910.07467) — ortalama çıkarmayı atar; daha az hesap.
- [Adam: A Method for Stochastic Optimization (2015)](https://arxiv.org/abs/1412.6980) — birinci ve ikinci moment tahmini ve bias düzeltmesi.
- [Decoupled Weight Decay Regularization (2019)](https://arxiv.org/abs/1711.05101) — AdamW; ağırlık sönümü gradyan güncellemesinden ayrılır.
- [Deep Residual Learning for Image Recognition (2015)](https://arxiv.org/abs/1512.03385) — ResNet; kalıntı bağlantılarla derin ağ eğitimi.
- [The Lottery Ticket Hypothesis (2019)](https://arxiv.org/abs/1803.03635) — seyrek, baştan eğitilebilir alt ağların varlığı.
- [Deep Double Descent (2019)](https://arxiv.org/abs/1912.02292) — model ve veri büyüdükçe test hatasının iki kez düşmesi.
- [Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets (2022)](https://arxiv.org/abs/2201.02177) — eğitim kaybı sıfırken geç genelleme.
- [Sharpness-Aware Minimization for Efficiently Improving Generalization (2020)](https://arxiv.org/abs/2010.01412) — düz minimumları hedefleyen eğitim amaç fonksiyonu.

### Uygulama projeleri
- **Sıfırdan autograd ve MLP:** Tensör destekli otomatik türev motoru ve üç katmanlı MLP yaz. Çıktı: `torch.autograd.gradcheck` testi geçen tek dosya; BatchNorm ve LayerNorm katmanları için ileri ve geri geçiş kıyası.
- **Normalizasyon ve optimizasyon kıyası:** Küçük bir transformer'da BatchNorm, LayerNorm ve RMSNorm; Adam ve AdamW; warmup ve kosinüs çizelgesi. Çıktı: en az üç tohumla ortalama ve standart sapma tablosu, eğitim kaybı eğrileri.
- **Yeniden üretilebilir çok GPU eğitim hattı:** AMP ve DDP ile eğitim döngüsü; torch.compile ile hızlanma ölçümü. Çıktı: tek komutla çalışan betik; tek GPU ve çok GPU kayıp eğrilerinin tolerans içinde eşleşmesi; throughput ve tepe bellek raporu; yapılandırma, tohum ve git commit kaydı.

### Medium yazı başlıkları
- Geri yayılımı sıfırdan yazmak: skaler autograd motorunda zincir kuralı
- BatchNorm küçük batch'te neden bozulur?
- LayerNorm ile RMSNorm: ortalama çıkarmak gerçekten gerekli mi?
- Adam'da ikinci moment ve bias düzeltmesi, adım adım
- AdamW: ağırlık sönümü neden gradyan güncellemesinden ayrılmalı?
- Warmup olmadan transformer eğitimi neden dağılır?
- Gradyan normunu izlemek: eğitim sorunlarını erken yakalamak
- Double descent: model büyüdükçe test hatası neden yeniden düşer?
- Grokking: eğitim kaybı sıfırken model neden hâlâ öğrenir?
- Mixed precision'da kayıp ölçekleme: float16 gradyanları neden sıfıra düşer?


## Aşama 4 — Görüntü işleme ve geometrik görü

**Hedef:** Kamera geometrisini, öznitelik eşlemeyi ve 3B yeniden yapılandırmayı kendi kamera verisinde uygulayabilmek.

**Ana kaynak:** First Principles of Computer Vision. **Başvuru:** Computer Vision: Algorithms and Applications (Szeliski).

### Konular
- Görüntü oluşumu ve delikli kamera modeli
- Renk uzayları ve ISP hatları
- Filtreleme, konvolüsyon ve frekans alanı
- Öznitelikler: SIFT, ORB, SuperPoint, LightGlue
- Kamera kalibrasyonu ve lens bozulması
- Epipolar geometri ve temel matris
- Homografi ve düzlem tabanlı eşleme
- Stereo eşleme ve derinlik
- Optik akış: RAFT
- SfM ve SLAM: COLMAP, ORB-SLAM3
- Kalibrasyonsuz 3B: DUSt3R, MASt3R, VGGT
- OpenCV ile verimli uygulama: bellek, vektörleştirme, GPU

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| Computer Vision: Algorithms and Applications, 2. baskı | kitap | [Site](https://szeliski.org/Book/) · [PDF](https://szeliski.org/Book/download.php) | Evet | Kapsamlı referans; PDF kısa bir formdan sonra iner, yalnız kişisel kullanım |
| Multiple View Geometry in Computer Vision | kitap | [Site](https://www.cambridge.org/core/books/multiple-view-geometry-in-computer-vision/0B6F289C78B2B23F596CAA76D3D43F7A) | Hayır | Epipolar ve çok görüntü geometrisinin standart kaynağı; basılı |
| First Principles of Computer Vision | video | [Site](https://fpcv.cs.columbia.edu/) · [Video listesi](https://www.youtube.com/channel/UCf0WB91t8Ky6AuYcQV0CcLw/featured) | Evet | Sezgisel ders serisi; kamera ve görüntü oluşumu |
| Foundations of Computer Vision | kitap | [Site](https://visionbook.mit.edu/) · [Web kitap](https://visionbook.mit.edu/) · [Kod](https://github.com/Foundations-of-Computer-Vision/visionbook) | Yalnız web | Çevrim içi ücretsiz; modern öğrenme yaklaşımlarını da kapsar |
| Cyrill Stachniss, YouTube kanalı | video | [Site](https://www.youtube.com/@cyrillstachniss) | Evet | Fotogrametri ve SLAM anlatımları; oynatma listesini tek tek seç |
| 16-385 Computer Vision, CMU | ders | [Site](https://www.cs.cmu.edu/~16385/) · [Notlar](https://www.cs.cmu.edu/~16385/) · [Ödevler](https://www.cs.cmu.edu/~16385/) | Evet | Klasik geometri; sayfa 2020 bahar dönemine ait |
| Computer Vision, Tübingen (Geiger) | ders | [Site](https://uni-tuebingen.de/pt/203146) · [Video listesi](https://www.youtube.com/playlist?list=PL05umP7R6ij35L2MHGzis8AEHz7mg381_) · [Notlar](https://drive.google.com/file/d/1J4jA3wAteiChtSAdGgd_2PaWklabBsek/view?usp=sharing) · [Ödevler](https://drive.google.com/drive/folders/17YkOlItn9PycNb5bT_O4nVlavlX0_VKQ?usp=sharing) | Evet | 3B görü ve SfM; son sunum 2025 yazı, 2026'da verilmiyor |
| Digital Image Processing, 4. baskı (Gonzalez, Woods) | kitap | [Site](http://www.imageprocessingplace.com) | Kısmen | Filtreleme ve frekans alanı; destek sitesinde hata listesi ve görüntü veritabanı var |
| OpenCV | repo | [Site](https://opencv.org) · [Kod](https://github.com/opencv/opencv) | Evet | Resmî kütüphane; Apache-2.0; kod ve örnekler |
| COLMAP | repo | [Site](https://colmap.github.io/) · [Kod](https://github.com/colmap/colmap) | Evet | SfM ve çok görüntülü yoğun yeniden yapılandırma aracı |

### Okunacak makaleler
- [SuperPoint: Self-Supervised Interest Point Detection and Description (2017)](https://arxiv.org/abs/1712.07629) — Öğrenilmiş öznitelik noktası ve tanımlayıcısının ilk ayrıntılı hâli.
- [LightGlue: Local Feature Matching at Light Speed (2023)](https://arxiv.org/abs/2306.13643) — Uyarlamalı derinlikli hızlı öznitelik eşleyici.
- [RAFT: Recurrent All-Pairs Field Transforms for Optical Flow (2020)](https://arxiv.org/abs/2003.12039) — Tüm çiftler korelasyon hacmiyle yinelemeli optik akış.
- [ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual-Inertial and Multi-Map SLAM (2020)](https://arxiv.org/abs/2007.11898) — Görsel, görsel-ataletsel ve çok haritalı SLAM referansı.
- [DUSt3R: Geometric 3D Vision Made Easy (2023)](https://arxiv.org/abs/2312.14132) — Kalibrasyonsuz nokta haritası regresyonu.
- [Grounding Image Matching in 3D with MASt3R (2024)](https://arxiv.org/abs/2406.09756) — DUSt3R'a eşleme başlığı ekler.
- [VGGT: Visual Geometry Grounded Transformer (2025)](https://arxiv.org/abs/2503.11651) — Tek ileri geçişte poz, derinlik ve nokta tahmini.

### Uygulama projeleri
- Kendi kamera çiftinde stereo derinlik: çıktı, ölçülen FPS ve kalibrasyon sonrası reprojeksiyon hatası (piksel).
- Öznitelik eşleme karşılaştırması: SIFT, ORB, SuperPoint+LightGlue; çıktı, eşleşme doğruluğu ve kare başına milisaniye tablosu.
- 200 karelik video ile COLMAP ve ORB-SLAM3 çalıştırma; çıktı, poz hatası ve toplam işlem süresi.

### Medium yazı başlıkları
- Kamera Modeli: Piksel Koordinatından Dünya Noktasına Giden Matematik
- Lens Bozulması Neden Kalibrasyonda Ayrı Bir Adım?
- Epipolar Geometri ile İki Kamera Arasında Eşleşme Aramayı Daraltmak
- Homografi Ne Zaman Yeterli, Ne Zaman Yanıltıcı?
- SIFT'ten LightGlue'ya: Öznitelik Eşlemenin Evrimi
- ORB ile Gerçek Zamanlı Öznitelik Çıkarımı: CPU Bütçesinde Kararlar
- Optik Akış: RAFT'ın Korelasyon Hacmi Nasıl Çalışır?
- Stereo Derinlik Haritasında Kayıp Bölgeler ve Sol-Sağ Tutarlılık
- DUSt3R ve MASt3R: Kalibrasyonsuz 3B Yeniden Yapılandırma
- Videoda Kare Seçimi: Yeniden Projeksiyon Hatası Nasıl Ölçülür?

---

## Aşama 5 — Modern bilgisayarlı görü

**Hedef:** Güncel omurga, tespit, bölütleme, takip ve öz-denetimli modelleri seçip kendi veri setinde karşılaştırabilmek.

**Ana kaynak:** CS231n, Stanford. **Başvuru:** Okunacak makaleler, Lil'Log.

### Konular
- Omurgalar: ResNet, ConvNeXt, ViT, Swin
- Tespit: YOLO ailesi, DETR, RT-DETR, D-FINE, RF-DETR
- Bölütleme: Mask2Former, SAM, SAM 2, SAM 3
- Çoklu nesne takibi: SORT, DeepSORT, ByteTrack, BoT-SORT, OC-SORT
- Öz-denetimli öğrenme: SimCLR, MAE, DINOv2, DINOv3
- Açık sözlük tespiti: CLIP, SigLIP, Grounding DINO, OWLv2, YOLO-World
- Video anlama: VideoMAE, V-JEPA 2
- Poz tahmini: ViTPose, RTMPose
- ReID ve OCR
- Anomali tespiti: PatchCore, anomalib
- Tek gözle derinlik: Depth Anything V2, Depth Anything 3
- Veri etiketleme ve aktif öğrenme

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| CS231n, Stanford (2026 bahar) | ders | [Site](https://cs231n.stanford.edu/) · [Notlar](https://cs231n.github.io/) | Evet | Derin öğrenme tabanlı görü; güncel dönem |
| Community Computer Vision Course, Hugging Face | ders | [Site](https://huggingface.co/learn/computer-vision-course) · [Kod](https://github.com/huggingface/computer-vision-course) | Yalnız web | Uygulamalı Python kodu; ücret bilgisi sayfada yok |
| timm | repo | [Site](https://huggingface.co/docs/timm) · [Kod](https://github.com/huggingface/pytorch-image-models) | Evet | Omurga modelleri; Apache-2.0 kod; bazı ağırlıklar CC-BY-NC |
| Ultralytics YOLO | repo | [Site](https://docs.ultralytics.com/) · [Kod](https://github.com/ultralytics/ultralytics) | Evet | YOLO26 ve YOLO11 belgeleri; eğitim ve dışa aktarma |
| supervision, Roboflow | repo | [Site](https://supervision.roboflow.com) · [Kod](https://github.com/roboflow/supervision) | Evet | Takip, işaretleme ve değerlendirme yardımcıları; MIT lisanslı |
| MMDetection | repo | [Site](https://mmdetection.readthedocs.io/en/latest/) · [Kod](https://github.com/open-mmlab/mmdetection) | Evet | Tespit çerçevesi; v3.3.0 (2024) sürümü; depo etkin |
| Lil'Log, Lilian Weng | blog | [Site](https://lilianweng.github.io/) | Evet | Derin öğrenme konularında derin ve kısa özetler |
| Hugging Face Daily Papers | blog | [Site](https://huggingface.co/papers) | Evet | Yeni makaleleri topluluk oylarıyla takip etmek için |
| anomalib | repo | [Site](https://anomalib.readthedocs.io/en/latest/) · [Kod](https://github.com/open-edge-platform/anomalib) | Evet | Anomali tespiti; PatchCore dahil; Apache-2.0 |
| PaddleOCR | repo | [Site](https://www.paddleocr.com) · [Kod](https://github.com/PaddlePaddle/PaddleOCR) | Evet | Çok dilli OCR; Apache-2.0; Türkçe model durumu kontrol edilmeli |
| Torchreid | repo | [Site](https://kaiyangzhou.github.io/deep-person-reid/) · [Kod](https://github.com/KaiyangZhou/deep-person-reid) | Evet | ReID referansı; son güncelleme 2022; bakım belirsiz |
| Computer Vision, Tübingen (Geiger) | ders | [Site](https://uni-tuebingen.de/pt/203146) · [Video listesi](https://www.youtube.com/playlist?list=PL05umP7R6ij35L2MHGzis8AEHz7mg381_) · [Notlar](https://drive.google.com/file/d/1J4jA3wAteiChtSAdGgd_2PaWklabBsek/view?usp=sharing) · [Ödevler](https://drive.google.com/drive/folders/17YkOlItn9PycNb5bT_O4nVlavlX0_VKQ?usp=sharing) | Evet | 11. ders öz-denetimli öğrenmeyi işler; 2026'da verilmiyor |

### Okunacak makaleler
#### Omurga
- [Deep Residual Learning for Image Recognition (2015)](https://arxiv.org/abs/1512.03385) — Artık bağlantılar; her modelin referans noktası.
- [A ConvNet for the 2020s (2022)](https://arxiv.org/abs/2201.03545) — ViT dönemine karşı modernize edilmiş saf CNN.
- [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale (2020)](https://arxiv.org/abs/2010.11929) — Görüntüyü yama dizisi olarak modelleme.

#### Tespit
- [End-to-End Object Detection with Transformers (2020)](https://arxiv.org/abs/2005.12872) — DETR; NMS gerektirmeyen uçtan uca tespit.
- [DETRs Beat YOLOs on Real-time Object Detection (2023)](https://arxiv.org/abs/2304.08069) — RT-DETR; gerçek zamanlı DETR.
- [D-FINE: Redefine Regression Task in DETRs as Fine-grained Distribution Refinement (2024)](https://arxiv.org/abs/2410.13842) — Kutu regresyonunu dağılım iyileştirme olarak tanımlar.
- [RF-DETR: Neural Architecture Search for Real-Time Detection Transformers (2025)](https://arxiv.org/abs/2511.09554) — Hedef veri setine göre doğruluk-gecikme eğrisi arar.

#### Bölütleme
- [Segment Anything (2023)](https://arxiv.org/abs/2304.02643) — İstem tabanlı genel bölütleme modeli.
- [SAM 3: Segment Anything with Concepts (2025)](https://arxiv.org/abs/2511.16719) — Kısa metin ve örnek görsel istemiyle kavram bölütleme ve takip.

#### Takip
- [Observation-Centric SORT (2022)](https://arxiv.org/abs/2203.14360) — Kalman kestirim hatasını gözlemle düzeltir.
- [ByteTrack: Multi-Object Tracking by Associating Every Detection Box (2021)](https://arxiv.org/abs/2110.06864) — Düşük skorlu kutuları da ilişkilendirir.

#### Derinlik ve 3B
- [Depth Anything V2 (2024)](https://arxiv.org/abs/2406.09414) — Sentetik veriyle eğitilmiş tek gözle derinlik modeli.
- [Depth Anything 3: Recovering the Visual Space from Any Views (2025)](https://arxiv.org/abs/2511.10647) — Herhangi bir görünümden derinlik ve poz tahmini.

#### Öz-denetimli öğrenme
- [DINOv2: Learning Robust Visual Features without Supervision (2023)](https://arxiv.org/abs/2304.07193) — Genel amaçlı, yoğun öznitelikler.
- [DINOv3 (2025)](https://arxiv.org/abs/2508.10104) — 7B model; Gram anchoring ile uzun eğitimde yoğun öznitelik kalitesi.

#### Açık sözlük tespiti
- [Learning Transferable Visual Models From Natural Language Supervision (2021)](https://arxiv.org/abs/2103.00020) — CLIP; metin-görüntü hizalamanın temeli.
- [Grounding DINO: Marrying DINO with Grounded Pre-Training for Open-Set Object Detection (2023)](https://arxiv.org/abs/2303.05499) — Metin istemiyle açık kümeli tespit.

#### Video
- [V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning (2025)](https://arxiv.org/abs/2506.09985) — Video öznitelikleri; tahmin ve planlama için.

### Uygulama projeleri
- Tespit karşılaştırması: YOLO26, RT-DETR ve D-FINE aynı video setinde; çıktı, mAP@0.5:0.95 ve GPU üzerinde FPS tablosu.
- Çoklu nesne takibi: ByteTrack ve OC-SORT kendi kamera kayıtlarında; çıktı, IDF1 ve kimlik değişim sayısı.
- Anomali tespiti: anomalib ile PatchCore; çıktı, AUROC ve piksel düzeyi F1, eğitim kare sayısına göre.

### Medium yazı başlıkları
- ResNet'ten ViT'e: Omurga Seçiminin Gerçek Maliyeti
- ConvNeXt Neden ViT Karşısında Hâlâ Güçlü?
- DETR Olmadan NMS: Uçtan Uca Tespit Ne Kazandırır?
- D-FINE ile Kutu Regresyonunu Dağılım Olarak Düşünmek
- SAM'dan SAM 3'e: Metinle Kavram Bölütleme
- ByteTrack: Düşük Skorlu Tespitleri Atmamak
- OC-SORT ile Kalman Filtresinin Kör Noktaları
- DINOv2'den DINOv3'e: Yoğun Öznitelik Kalitesi
- Grounding DINO ile Sözlüksüz Tespit: Sınırlar Nerede?
- V-JEPA 2 ile Video Anlama: Maskelenmiş Tahminin Gücü


## Aşama 6 — Üretken modeller ve 3B görü

**Hedef:** Difüzyon, akış eşleştirme ve 3B gösterimleri türeterek kodlayabilmek.

**Ana kaynak:** MIT 6.S184: Introduction to Flow Matching and Diffusion Models. **Başvuru:** What are Diffusion Models? (Lilian Weng), Hugging Face Diffusers.

### Konular
- VAE, GAN (kısa) ve normalizing flow
- DDPM: ileri ve ters süreç, gürültü tahmini kaybı
- DDIM ve hızlı örnekleme
- Skor tabanlı SDE ve Langevin dinamiği
- Classifier-free guidance
- Latent difüzyon ve otoenkoder sıkıştırması
- Flow matching ve rectified flow
- Difüzyon transformer (DiT): yama tokenları, koşullandırma
- Tutarlılık modelleri ve damıtma
- Kontrol: ControlNet, LoRA
- Video üretimi: zamansal dikkat, video difüzyonu
- NeRF, 3D Gaussian Splatting ve ileri beslemeli 3B yeniden kurma

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| MIT 6.S184: Introduction to Flow Matching and Diffusion Models (2026) | ders | [Site](https://diffusion.csail.mit.edu/2026/) · [Notlar](https://diffusion.csail.mit.edu/2026/docs/lecture_notes.pdf) | Evet | Akış eşleştirmenin ilkeli türetimi; 2026 sürümü |
| Stanford CS236: Deep Generative Models | ders | [Site](https://deepgenerativemodels.github.io/) · [Notlar](https://deepgenerativemodels.github.io/notes/index.html) | Evet | VAE, akış ve difüzyon için olasılıksal temel |
| Berkeley CS294-158: Deep Unsupervised Learning (2020) | ders | [Site](https://sites.google.com/view/berkeley-cs294-158-sp20/home) | Evet | Otoregresif ve difüzyon modelleri; arşiv ders |
| What are Diffusion Models? (Lilian Weng) | blog | [Site](https://lilianweng.github.io/posts/2021-07-11-diffusion-models) | Evet | Difüzyonun matematiksel akışını adım adım anlatır |
| Generative Modeling by Estimating Gradients (Yang Song) | blog | [Site](https://yang-song.net/blog/2021/score/) | Evet | Skor tabanlı üretimin kaynağı |
| Hugging Face Diffusion Course | ders | [Site](https://huggingface.co/learn/diffusion-course) · [Kod](https://github.com/huggingface/diffusion-models-class) | Evet | Diffusers ile uygulamalı difüzyon; ücretsiz notebook'lar |
| Perspectives on diffusion (Sander Dieleman) | blog | [Site](https://sander.ai/2023/07/20/perspectives.html) | Evet | Difüzyon yaklaşımlarının kavramsal haritası |
| Understanding Diffusion Models: A Unified Perspective (Calvin Luo) | ders | [Site](https://arxiv.org/abs/2208.11970) | Evet | ELBO ve skor görüşlerini tek çatıda bağlar |
| MIT 6.S978: Deep Generative Models (Kaiming He) | ders | [Site](https://mit-6s978.github.io/) · [Notlar](https://mit-6s978.github.io/schedule.html) | Evet | VAE, GAN ve difüzyonu görüntü odaklı işler |
| nerfstudio | repo | [Site](https://docs.nerf.studio/) · [Kod](https://github.com/nerfstudio-project/nerfstudio) | Evet | NeRF eğitimi ve testi için modüler araç seti |
| gsplat | repo | [Site](https://github.com/nerfstudio-project/gsplat) | Evet | CUDA hızlandırmalı Gaussian rasterizasyon kütüphanesi |
| 3D Gaussian Splatting (resmî sayfa) | repo | [Site](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) · [Kod](https://github.com/graphdeco-inria/gaussian-splatting) | Evet | Özgün 3DGS yöntemi ve kodu |
| Hugging Face Diffusers | repo | [Site](https://huggingface.co/docs/diffusers) · [Kod](https://github.com/huggingface/diffusers) | Evet | Difüzyon boru hatları, ince ayar ve nicemleme |

### Okunacak makaleler
- [Auto-Encoding Variational Bayes (2013)](https://arxiv.org/abs/1312.6114) — Yeniden parametreleme hilesinin kaynağı.
- [Scaling Rectified Flow Transformers (2024)](https://arxiv.org/abs/2403.03206) — SD3; akış ve MMDiT'nin güncel referansı.
- [Denoising Diffusion Probabilistic Models (2020)](https://arxiv.org/abs/2006.11239) — DDPM kaybının ve örneklemenin temeli.
- [Denoising Diffusion Implicit Models (2020)](https://arxiv.org/abs/2010.02502) — Deterministik ve hızlı örnekleme.
- [Score-Based Generative Modeling through SDEs (2020)](https://arxiv.org/abs/2011.13456) — Difüzyonu SDE çerçevesine oturtur.
- [High-Resolution Image Synthesis with Latent Diffusion Models (2021)](https://arxiv.org/abs/2112.10752) — Stable Diffusion'ın mimari temeli.
- [Classifier-Free Diffusion Guidance (2022)](https://arxiv.org/abs/2207.12598) — Koşullu üretimde ölçek parametresinin kaynağı.
- [Flow Matching for Generative Modeling (2022)](https://arxiv.org/abs/2210.02747) — Vektör alanı regresyonu ile eğitim.
- [Flow Straight and Fast: Rectified Flow (2022)](https://arxiv.org/abs/2209.03003) — Düz yollarla az adımlı örnekleme.
- [Scalable Diffusion Models with Transformers (2022)](https://arxiv.org/abs/2212.09748) — DiT; difüzyonda transformer omurgası.
- [Adding Conditional Control to Text-to-Image Diffusion Models (2023)](https://arxiv.org/abs/2302.05543) — ControlNet; kontrolün kopyalanarak eklenmesi.
- [3D Gaussian Splatting for Real-Time Radiance Field Rendering (2023)](https://arxiv.org/abs/2308.04079) — Gerçek zamanlı 3B sahne gösterimi.

### Uygulama projeleri
- Sıfırdan DDPM ve DDIM (PyTorch, U-Net ile): MNIST üzerinde eğitim; çıktı: örnek ızgarası ve adım sayısına göre FID tablosu.
- Sıfırdan flow matching ve rectified flow eğitimi (küçük VAE gizli uzayında): çıktı: 1 adım ve 20 adım örnekleme karşılaştırması.
- Sıfırdan 2B Gaussian rasterizasyonu (PyTorch): tek bir sahneyi eğitme; çıktı: sahne için PSNR ve eğitim kaybı grafiği.

### Medium yazı başlıkları
- Difüzyonda İleri Süreç: Gürültü Takvimi Neyi Değiştirir?
- DDPM'den DDIM'e: Örnekleme Adımını Eğitimden Ayırmak
- Skor Fonksiyonu Nedir ve Neden Gürültü Tahmini Ona Eşittir?
- Classifier-Free Guidance: Ölçek Parametresi Kaliteyi Nasıl Değiştirir?
- Latent Difüzyon: Piksel Uzayından Sıkıştırılmış Uzaya Geçiş
- Flow Matching ile Düz Yollar: Eğitim Hedefi Nasıl Kurulur?
- Rectified Flow ile Az Adımlı Örnekleme: Bedeli Nedir?
- Diffusion Transformer'da Yama Tokenları ve Koşullandırma
- ControlNet ve LoRA: Kontrolü Çekirdeği Dondurarak Eklemek
- 3D Gaussian Splatting: Sahneyi Gauss'lardan Kurup Rasterize Etmek

## Aşama 7 — Transformer, LLM ve görü-dil modelleri

**Hedef:** LLM ve görü-dil modellerini sıfırdan kodlayıp verimli çıkarım ve değerlendirme yapabilmek.

**Ana kaynak:** CS336: Language Modeling from Scratch. **Başvuru:** Neural Networks: Zero to Hero, Hugging Face LLM Course.

### Konular
- Dikkat ve transformer: sıfırdan kodlama
- BPE tokenizasyonu
- RoPE ve bağlam uzatma
- Ön eğitim, ölçekleme yasaları, SFT ve tercih optimizasyonu
- LoRA ve QLoRA
- Nicemleme: GGUF, GPTQ, AWQ
- KV önbellek, FlashAttention, PagedAttention
- vLLM ile çıkarım sunumu
- RAG ve değerlendirme
- Ajanlar ve araç kullanımı
- Görü-dil modelleri: CLIP, SigLIP, LLaVA, Qwen-VL ailesi
- VLM ile video anlama ve mekanistik yorumlanabilirlik girişi

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| CS336: Language Modeling from Scratch (Spring 2025) | ders | [Site](https://cs336.stanford.edu/spring2025) | Evet | Veri, ölçekleme, sistem ve hizalamayı sıfırdan kapsar |
| CS224N: NLP with Deep Learning (Winter 2026) | ders | [Site](https://web.stanford.edu/class/cs224n/) | Kısmen | Transformer temelleri ve NLP görevlerinin çerçevesi |
| CS25: Transformers United V6 | ders | [Site](https://web.stanford.edu/class/cs25/) | Evet | Transformer araştırmasının güncel konuk konuşmaları |
| Neural Networks: Zero to Hero | video | [Site](https://karpathy.ai/zero-to-hero.html) · [Video listesi](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) · [Kod](https://github.com/karpathy/nn-zero-to-hero) | Evet | GPT'yi koddan sıfırdan kurma ve tokenizer |
| nanochat | repo | [Site](https://github.com/karpathy/nanochat) | Evet | Küçük ChatGPT benzeri modeli uçtan uca eğitme |
| LLMs-from-scratch | repo | [Site](https://github.com/rasbt/LLMs-from-scratch) · [Video listesi](https://www.youtube.com/playlist?list=PLTKMiZHVd_2IIEsoJrWACkIxLRdfMlw11) | Evet | Kitabın resmî kodu; GPT modelini adım adım yazma |
| The Annotated Transformer | blog | [Site](https://nlp.seas.harvard.edu/annotated-transformer/) · [Kod](https://github.com/harvardnlp/annotated-transformer) | Evet | Orijinal makalenin satır satır PyTorch uygulaması |
| Hugging Face LLM Course | ders | [Site](https://huggingface.co/learn/llm-course) | Evet | Tokenizer, ince ayar ve akıl yürüten modeller |
| Hugging Face Agents Course | ders | [Site](https://huggingface.co/learn/agents-course) | Evet | Ajan çerçeveleri ve araç kullanımı uygulamalı |
| Advanced LLM Agents MOOC (Spring 2025) | ders | [Site](https://llmagents-learning.org/sp25) · [Video listesi](https://rdi.berkeley.edu/adv-llm-agents/sp25) | Evet | Ajan değerlendirmesi ve araştırma odaklı konular |
| AI Engineering (Chip Huyen) | kitap | [Site](https://www.oreilly.com/library/view/ai-engineering/9781098166298/) | Hayır | Temel modelle uygulama, değerlendirme ve RAG pratikleri |
| Building effective agents (Anthropic) | blog | [Site](https://www.anthropic.com/engineering/building-effective-agents) | Evet | Ajan iş akışlarında basit tutma ilkeleri; 2024 |
| How To Become a Mechanistic Interpretability Researcher (Neel Nanda) | blog | [Site](https://www.alignmentforum.org/posts/jP9KDyMkchuv6tHwm/how-to-become-a-mechanistic-interpretability-researcher) | Evet | Mekanistik yorumlanabilirliğe aşamalı giriş yolu |
| Umar Jamil YouTube | video | [Site](https://www.youtube.com/@umarjamilai) | Evet | Transformer ve LLaMA bileşenlerini sıfırdan kodlayan videolar |

### Okunacak makaleler
- [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) — Transformer'ın özgün mimarisi.
- [Neural Machine Translation of Rare Words with Subword Units (2015)](https://arxiv.org/abs/1508.07909) — BPE tokenizasyonunun kaynağı.
- [RoFormer: Enhanced Transformer with Rotary Position Embedding (2021)](https://arxiv.org/abs/2104.09864) — RoPE konum kodlaması.
- [FlashAttention (2022)](https://arxiv.org/abs/2205.14135) — GPU bellek hiyerarşisine göre dikkat hesabı.
- [Efficient Memory Management for LLM Serving with PagedAttention (2023)](https://arxiv.org/abs/2309.06180) — vLLM'in KV önbellek yönetimi.
- [QLoRA: Efficient Finetuning of Quantized LLMs (2023)](https://arxiv.org/abs/2305.14314) — 4-bit taban modelde adaptör eğitimi.
- [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (2020)](https://arxiv.org/abs/2005.11401) — RAG'in özgün çerçevesi.
- [ReAct: Synergizing Reasoning and Acting in Language Models (2022)](https://arxiv.org/abs/2210.03629) — Düşünce ve eylem döngüsünün temeli.
- [Learning Transferable Visual Models From Natural Language Supervision (2021)](https://arxiv.org/abs/2103.00020) — CLIP; görü-dil hizalamasının referansı.
- [Sigmoid Loss for Language Image Pre-Training (2023)](https://arxiv.org/abs/2303.15343) — SigLIP; softmax yerine sigmoid kaybı.
- [Visual Instruction Tuning (2023)](https://arxiv.org/abs/2304.08485) — LLaVA; görsel token'ın dil modeline bağlanması.
- [Qwen2.5-VL Technical Report (2025)](https://arxiv.org/abs/2502.13923) — Güncel açık VLM ve video anlama.

### Uygulama projeleri
- Sıfırdan GPT (PyTorch): dikkat, RoPE ve KV önbellekli üretim; küçük metin kümesinde eğitim; çıktı: kod, doğrulama perplexity'si ve üretim örnekleri.
- Sıfırdan BPE tokenizer ve QLoRA ile küçük LLM ince ayarı: çıktı: taban ve ince ayarlı model için değerlendirme tablosu.
- Yerel belgeler üzerinde RAG ve araç çağıran ajan: çıktı: 100 soruluk değerlendirme setinde doğruluk ve hata sınıflandırması.

### Medium yazı başlıkları
- Dikkat Mekanizmasını Sıfırdan Yazmak: Maske ve Ölçekleme
- BPE Tokenizer: Birleştirme Kuralları Nasıl Öğrenilir?
- RoPE ile Konum Bilgisini Döndürmek: Uzun Bağlamda Ne Olur?
- LoRA ve QLoRA: 4-bit Taban Modelde Adaptör Eğitimi
- KV Önbelleği ve vLLM: Sayfalı Bellek Yönetimi
- RAG Hattında Geri Getirme Hatası Nasıl Ölçülür?
- ReAct: Düşünce-Eylem Döngüsünün Hata Ayıklaması
- CLIP'ten SigLIP'e: Kontrastif Kayıpta Softmax'ı Bırakmak
- LLaVA'da Görsel Token'ı Dil Modeline Bağlamak
- Mekanistik Yorumlanabilirlikte Dikkat Başlığı Devreleri


## Aşama 8 — Üretim, hız ve ML sistemleri
**Hedef:** Eğitilmiş bir modeli gerçek zamanlı video hattında düşük gecikme ve düşük maliyetle çalıştırmak.

**Ana kaynak:** MIT 6.5940 TinyML and Efficient AI Computing. **Başvuru:** araç dokümanları (TensorRT, ONNX Runtime, Triton, DeepStream).
### Konular
- Nicemleme: PTQ, QAT, INT8 ve FP8 doğruluk kaybı.
- Budama ve damıtma: yapısal budama, öğretmen-öğrenci kaybı.
- ONNX ve ONNX Runtime: dışa aktarma, operatör desteği.
- TensorRT ve OpenVINO: motor derleme, kalibrasyon, katman füzyonu.
- torch.compile ve ExecuTorch: derleme ve uç cihaz çalışma zamanı.
- GPU profil çıkarma: Nsight Systems ve Nsight Compute ile darboğaz bulma.
- CUDA temelleri: bellek hiyerarşisi, akış, çekirdek başlatma.
- Toplu çıkarım ve dinamik batch: gecikme ile verim dengesi.
- Model sunumu: Triton, LitServe, BentoML, Ray Serve.
- Video hattı: GStreamer, FFmpeg, DeepStream, donanım kod çözme, RTSP.
- Kenar cihazlar: Jetson güç modları, bellek ve sıcaklık sınırları.
- MLOps ve izleme: DVC, MLflow, CI, model kaydı, veri kayması, veri merkezli YZ, ML sistem tasarımı.

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| MIT 6.5940 TinyML and Efficient AI Computing | ders | [Site](https://hanlab.mit.edu/course) · [Video listesi](https://www.youtube.com/playlist?list=PL80kAHvQbh-qGtNc54A6KW4i4bkTPjiRF) | Evet | Nicemleme ve budamanın kapsamlı anlatımı; Fall 2026 sürümü. |
| CMU 10-414 Deep Learning Systems | ders | [Site](https://dlsyscourse.org) · [Notlar](https://dlsyscourse.org/lectures/) · [Ödevler](https://dlsyscourse.org/assignments/) | Evet | Derin öğrenme çatısının iç yapısı; Fall 2026 sürümü. |
| Full Stack Deep Learning | ders | [Site](https://fullstackdeeplearning.com) · [Video listesi](https://youtube.com/playlist?list=PL1T8fO7ArWleMMI8KPJ_5D5XSlovTW_Ur) | Evet | Üretim ML uçtan uca; en son sürüm 2022. |
| Stanford CS329S | ders | [Site](https://stanford-cs329s.github.io) · [Notlar](https://stanford-cs329s.github.io/syllabus.html) | Evet | ML sistem tasarımı; bulunan en son sürüm 2022. |
| MLOps Zoomcamp | repo | [Site](https://datatalks.club/blog/mlops-zoomcamp.html) · [Video listesi](https://www.youtube.com/playlist?list=PL3MmuxUbc_hIUISrluw_A7wDSmfOhErJK) · [Kod](https://github.com/DataTalksClub/mlops-zoomcamp) | Evet | Uygulamalı MLOps hattı. |
| MIT Introduction to Data-Centric AI | ders | [Site](https://dcai.csail.mit.edu) · [Notlar](https://dcai.csail.mit.edu/2024) · [Video listesi](https://www.youtube.com/playlist?list=PL_1TbuIu65A8NTNuLutFoD87vbMl8GL8K) | Evet | Veri merkezli YZ; IAP 2024 sürümü. |
| Machine Learning Systems (Harvard) | kitap | [Site](https://mlsysbook.ai) · [Web kitap](https://mlsysbook.ai/vol1/) | Yalnız web | Üretim ML sistemleri; ücretsiz çevrim içi okuma. |
| Designing Machine Learning Systems | kitap | [Site](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/) | Hayır | Tasarım kararları; yayın yılı 2022. |
| TensorRT dokümanı | doküman | [Site](https://docs.nvidia.com/deeplearning/tensorrt/latest/index.html) | Yalnız web | NVIDIA çıkarım optimizasyonu; sürüm 11.5.0. |
| Triton Inference Server | doküman | [Site](https://docs.nvidia.com/deeplearning/triton-inference-server/user-guide/docs/index.html) | Yalnız web | Model sunumu ve dinamik batch ayarları. |
| DeepStream SDK Geliştirici Kılavuzu | doküman | [Site](https://docs.nvidia.com/metropolis/deepstream/dev-guide/index.html) | Yalnız web | Video analitiği hattı; sürüm 9.2. |
| ONNX Runtime | doküman | [Site](https://onnxruntime.ai/docs/) | Yalnız web | Çapraz platform çıkarım ve sağlayıcı seçimi. |
| PyTorch Performance Tuning Guide | doküman | [Site](https://docs.pytorch.org/tutorials/recipes/recipes/tuning_guide.html) | Yalnız web | Eğitim ve çıkarım hız ayarları. |
| CUDA C++ Programming Guide | doküman | [Site](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html) · [PDF](https://docs.nvidia.com/cuda/cuda-programming-guide/pdf/cuda-programming-guide.pdf) | Evet | CUDA temelleri; sürüm 13.5. |

### Okunacak makaleler
- [Deep Compression (2015)](https://arxiv.org/abs/1510.00149) — budama, nicemleme ve Huffman birlikte.
- [Learning both Weights and Connections for Efficient Neural Networks (2015)](https://arxiv.org/abs/1506.02626) — budamanın erken kaynağı.
- [Distilling the Knowledge in a Neural Network (2015)](https://arxiv.org/abs/1503.02531) — damıtmanın temel makalesi.
- [Quantizing deep convolutional networks for efficient inference: A whitepaper (2018)](https://arxiv.org/abs/1806.08342) — INT8 nicemleme pratiği.
- [Quantization and Training of Neural Networks for Efficient Integer-Arithmetic-Only Inference (2017)](https://arxiv.org/abs/1712.05877) — tam tamsayı çıkarım ve QAT.
- [Mixed Precision Training (2017)](https://arxiv.org/abs/1710.03740) — FP16 eğitim ve kayan nokta kaybı.
- [The Lottery Ticket Hypothesis (2018)](https://arxiv.org/abs/1803.03635) — seyrek alt ağların eğitilebilirliği.
- [EfficientNet (2019)](https://arxiv.org/abs/1905.11946) — model ölçekleme ve verim dengesi.
- [MobileNetV4 (2024)](https://arxiv.org/abs/2404.10518) — mobil ve kenar mimarileri.
- [Hidden Technical Debt in Machine Learning Systems (2015)](https://papers.nips.cc/paper_files/paper/2015/hash/86df7dcfd896fcaf2674f757a2463eba-Abstract.html) — üretim ML borcunun kaynakları.

### Uygulama projeleri
- YOLO modelini TensorRT ile FP16 ve INT8 olarak derle; gecikme (ms), bellek (MB) ve mAP kaybını ölç.
- Dört RTSP akışını DeepStream hattında işle; toplam FPS, GPU kullanımı (%) ve uçtan uca gecikmeyi (ms) raporla.
- Modeli Triton'da dinamik batch ile sun; p95 gecikme (ms) ve saniyedeki istek sayısını batch boyutuna göre çiz.

### Medium yazı başlıkları
- Nicemleme ile Modeli Küçültmek: PTQ ile QAT Arasındaki Doğruluk Farkı
- Budama mı, Damıtma mı? Gecikme Bütçesine Göre Seçim
- ONNX'ten TensorRT Motoruna: Dönüşümde Kırılan Operatörler
- Nsight ile GPU Darboğazını Bulmak: Çıkarım Profili Okumak
- Dinamik Batch ile Gecikme ve Verim Dengesi
- RTSP Akışında Kare Kaybını GStreamer ile Ölçmek
- Donanım Kod Çözme ile CPU Yükünü Düşürmek
- Jetson'da Güç Modu Altında Model Seçimi
- Veri Kayması Tespiti: Üretimde Hangi Metrik Alarm Vermeli?
- DVC ve MLflow ile Tekrar Üretilebilir Eğitim Hattı

## Aşama 9 — Araştırma becerisi ve teknik yazarlık
**Hedef:** Makale okumayı, deney tasarımını ve yazılı anlatımı üretim seviyesinde yapmak.

**Ana kaynak:** Keshav "How to Read a Paper" ve Schulman "An Opinionated Guide to ML Research". Bu aşama öbürleriyle birlikte, sürekli yürür.
### Konular
- Makale okuma: Keshav'ın üç geçişli yöntemi.
- Makale yeniden üretme: kod, veri ve hata ayıklama günlüğü.
- Deney tasarımı ve ablation: tek değişken kuralı, tekrar ve istatistik.
- Konferanslar: CVPR, ICCV, ECCV, NeurIPS, ICLR, ICML takvimi.
- Takip yolları: arXiv, HF Papers, alphaXiv, OpenReview. Papers with Code, Hugging Face Papers sayfasına yönlendiriyor.
- Açık kaynağa katkı ve Kaggle çözüm arşivleri.
- Teknik yazı: Distill tarzı görsel anlatım.
- Şekil üretimi: manim, matplotlib, excalidraw.
- Medium'da okur büyütme: dizi, yayın, SEO, çift dil.
- Araştırma yönü: Hamming, Schulman ve Karpathy yazıları.

### Kaynaklar
| Kaynak | Tür | Bağlantılar | Ücretsiz | Neden |
|---|---|---|---|---|
| Keshav "How to Read a Paper" (2007) | doküman | [Site](https://dl.acm.org/doi/10.1145/1273445.1273458) · [PDF](https://www.cs.princeton.edu/courses/archive/fall18/cos561/papers/HowToRead05.pdf) | Evet | Üç geçişli makale okuma yöntemi. |
| Karpathy "A Survival Guide to a PhD" | blog | [Site](https://karpathy.github.io/2016/09/07/phd/) | Yalnız web | PhD'de öncelik ve verimlilik. |
| Hamming "You and Your Research" | doküman | [Site](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html) | Yalnız web | Büyük problem seçme ve düşünme alışkanlığı. |
| Schulman "An Opinionated Guide to ML Research" | blog | [Site](https://joschu.net/blog/opinionated-guide-ml-research.html) | Yalnız web | Hedef odaklı araştırma ve günlük tutma. |
| Rachel Thomas: blog yazma tavsiyesi (2017) | blog | [Site](https://rachel.fast.ai/posts/2017-07-28-you-should-blog/) | Yalnız web | Yazmanın zamandan nasıl kazandırdığı. |
| Distill | blog | [Site](https://distill.pub) | Yalnız web | Görsel anlatım örnekleri; 2021'den beri yeni yazı yok. |
| Ahead of AI | blog | [Site](https://magazine.sebastianraschka.com) | Yalnız web | Sebastian Raschka; araştırma ve model analizleri. |
| The Batch | blog | [Site](https://www.deeplearning.ai/the-batch/) | Yalnız web | Haftalık sektör özeti; DeepLearning.AI. |
| Import AI | blog | [Site](https://jack-clark.net) | Yalnız web | Jack Clark; araştırma ve politika bülteni. |
| Yannic Kilcher | video | [Site](https://www.youtube.com/@YannicKilcher) | Evet | Makale okuma videoları; uzun anlatım. |
| Hugging Face Daily Papers | doküman | [Site](https://huggingface.co/papers) | Yalnız web | Papers with Code yerine güncel makale takibi. |
| alphaXiv | doküman | [Site](https://www.alphaxiv.org) | Yalnız web | arXiv makalelerine kısa özet ve tartışma. |
| Manim Community | repo | [Site](https://www.manim.community) | Evet | Matematiksel animasyon üretimi. |
| Gwern.net | blog | [Site](https://gwern.net) | Yalnız web | Uzun deneme yazımı ve araştırma notları. |

### Okunacak makaleler
- [How to Read a Paper (2007)](https://www.cs.princeton.edu/courses/archive/fall18/cos561/papers/HowToRead05.pdf) — üç geçişli okuma sırası.
- [You and Your Research (1986)](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html) — önemli problemleri seçmek.
- [A Survival Guide to a PhD (2016)](https://karpathy.github.io/2016/09/07/phd/) — PhD'de verimli çalışma.
- [An Opinionated Guide to ML Research (2020)](https://joschu.net/blog/opinionated-guide-ml-research.html) — hedef odaklı araştırma planı.
- [Why you should blog (2017)](https://rachel.fast.ai/posts/2017-07-28-you-should-blog/) — yazının araştırma pratiğine katkısı.

### Uygulama projeleri
- Üç yakın tarihli CVPR makalesini Keshav yöntemiyle oku; her makale için 1 sayfalık özet ve yeniden üretme planı yaz.
- Bir makalenin ana sonucunu yeniden üret; hedef değerin yüzde kaçına ulaştığını ve ablation tablosunu raporla.
- Bir üretim projesinden bir teknik yazı yaz; Medium'da yayınla ve okunma, kaydetme ve yorum sayılarını takip et.

### Medium yazı başlıkları
- Makaleyi Üç Geçişte Okumak: Keshav Yönteminin Uygulaması
- Bir Makaleyi Sıfırdan Yeniden Üretmek: Hata Ayıklama Günlüğü
- Ablation Tasarımında Tek Değişken Kuralı
- Açık Kaynak Koda Makale Sonucunu Eklemek: Adım Adım Süreç
- Manim ile Algoritma Animasyonu: Bir Kavramı Üç Dakikada Anlatmak
- Kaggle Çözümünü Makaleye Dönüştürmek
- Medium'da Dizi Planlamak: Her Yazının Tek Sorusu
- Türkçe ve İngilizce Yayın: Aynı Deneyin İki Okuru
- Araştırma Günlüğü Tutmak: Schulman'ın Önerisi Üzerine
- Okur Büyütmek İçin Başlık ve Arama Terimi Seçimi


## Medium yayın planı

### Yazı dizileri

| Dizi | Kaynak aşama | İçerik |
|------|--------------|--------|
| Sıfırdan | 1, 2, 3, 7 | Bir yöntemi yalnız NumPy ya da saf PyTorch ile yazma |
| Makale Okuyorum | 5, 6, 7 | Tek makale: sorun, fikir, formül, sonuç, zayıf yan |
| Görü Mühendisliği | 4, 5 | Kamera, geometri, tespit, takip; ölçümle |
| Hız Defteri | 8 | Bir modeli hızlandırma; önce-sonra gecikme ve FPS |
| Saha Notları | 8, 9 | Üretimde çıkan hata, kök neden, çözüm |

### Yazı şablonu

1. Sorun: bir cümle; okur neden okusun.
2. Sezgi: bir şekil ya da küçük örnek.
3. Matematik: yalnız gereken formül; her simge tanımlı.
4. Kod: çalışır en kısa hâl; depo bağlantısı.
5. Ölçüm: tablo ya da grafik; donanım ve sürüm yazılı.
6. Sınırlar: yöntemin bozulduğu durum.
7. Kaynaklar: makale ve ders bağlantıları.

### Yayın kuralları

- Haftada bir yazı; uzunluk 6-10 dakika okuma.
- Her yazının kodu GitHub'da ayrı klasörde durur; yazı depoya, depo yazıya bağlanır.
- Başlık özgül olur: yöntem adı + okurun kazancı. Örnek: "ByteTrack'i Sıfırdan Yazmak: Düşük Skorlu Kutular Neden Atılmaz".
- Dizi yazıları birbirine bağlanır: baş kısımda önceki, son kısımda sonraki yazı.
- Türkçe yaz; en çok okunan yazıyı sonra İngilizceye çevir ve bir yayına (ör. Towards AI, Level Up Coding) gönder.
- Her şekli kendin üret; başkasının şeklini kullanırsan kaynağını yaz.
- Her 10 yazıda bir özet yazısı çıkar: dizinin haritası ve bağlantıları.

### İlerleme takibi

| Tarih | Aşama | Konu | Kod | Yazı |
|-------|-------|------|-----|------|
| | | | | |


