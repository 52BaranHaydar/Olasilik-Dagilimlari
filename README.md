# 📊 Olasılık Dağılımları (Probability Distributions)

[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)](https://scipy.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

Veri bilimi, makine öğrenmesi, istatistik ve yapay zeka alanlarında temel teşkil eden **Olasılık Dağılımları** için kapsamlı, teorik ve uygulamalı Türkçe eğitim ve uygulama deposu.

Her dağılım için:
- 📖 **Sezgisel ve teorik açıklamalar**,
- 📐 **Matematiksel formüller (PMF / PDF, CDF, Momentler)**,
- 🧪 **NumPy ve SciPy ile simülasyonlar**,
- 📊 **Matplotlib ve Seaborn ile zengin görselleştirmeler**,
- 💼 **Gerçek hayat senaryoları ve vaka analizleri**,
- 📑 **Ders notları ve PDF slaytları** yer almaktadır.

---

## 🗺️ Dağılımlar Yol Haritası (Roadmap)

### 🎲 1. Ayrık (Discrete) Olasılık Dağılımları
- [x] **[Bernoulli Dağılımı (Bernoulli Distribution)](bernoulli_distribution.ipynb)**
  - Tek denemeli iki sonuçlu olaylar, PMF/CDF, Varyans analizi, Büyük Sayılar Yasası (LLN) simülasyonu, CTR ve Kalite Kontrol örnekleri.
- [x] **[Binom Dağılımı (Binomial Distribution)](binom_distribution.ipynb)**
  - $n$ bağımsız Bernoulli denemesi, kombinasyon formülleri, PMF/CDF basamak eğrileri, Merkezi Limit Teoremi (Normal dağılıma yakınsama), A/B testi ve hata analizleri.
- [x] **[Poisson Dağılımı (Poisson Distribution)](poission_distribution.ipynb)**
  - Sabit zaman/alan aralıklarındaki nadir olaylar, $\lambda$ parametresi, Eşitlik İlkesi ($E[X]=\text{Var}(X)=\lambda$), Çağrı Merkezi ve Otopark modelleri, Binom'dan Poisson'a yakınsama.
- [ ] **Geometrik Dağılım (Geometric Distribution)**
- [ ] **Hipergeometrik Dağılım (Hypergeometric Distribution)**
- [ ] **Negatif Binom Dağılımı (Negative Binomial Distribution)**
- [ ] **Ayrık Düzgün Dağılım (Discrete Uniform Distribution)**

### 📈 2. Sürekli (Continuous) Olasılık Dağılımları
- [ ] **Normal (Gauss) Dağılımı (Normal Distribution)**
- [ ] **Standart Normal Dağılım & Z-Skoru**
- [ ] **Üstel Dağılım (Exponential Distribution)**
- [ ] **Sürekli Düzgün Dağılım (Uniform Distribution)**
- [ ] **Gamma Dağılımı (Gamma Distribution)**
- [ ] **Beta Dağılımı (Beta Distribution)**
- [ ] **Ki-Kare Dağılımı (Chi-Square Distribution)**
- [ ] **Student-t Dağılımı (Student's t-Distribution)**
- [ ] **F Dağılımı (F-Distribution)**

---

## 📁 PDF Ders Notları ve Dokümanlar ([PDF/](PDF/))

Depoda yer alan teorik ders notları ve görsel konu özetleri:

1. 📄 **[1 - Probability.pdf](PDF/1+-+Probability.pdf):** Temel olasılık kavramları, örnek uzay, olaylar ve olasılık aksiyomları.
2. 📄 **[2 - Probability Distribution Functions.pdf](PDF/2+-+Probability_Distribution_Functions.pdf):** Olasılık fonksiyonları, PMF, PDF, CDF ve moment hesaplama temelleri.
3. 📄 **[3 - Bernouilli and Binom.pdf](PDF/3+-+Bernouilli_and_Binom.pdf):** Bernoulli denemeleri ve Binom dağılımı teorik anlatımı.
4. 📄 **[4 - Poisson.pdf](PDF/4+-+Poisson.pdf):** Poisson süreci, oran parametresi ($\lambda$) ve uygulama alanları.
5. 📄 **[5 - Normal Dağılım.pdf](PDF/5+-+Normal_Dağılım.pdf):** Gauss / Normal dağılım, çan eğrisi özellikleri ve standartlaştırma.
6. 📄 **[6 - Uniform Distribution.pdf](PDF/6+-+Uniform_Distribution.pdf):** Düzgün (Uniform) dağılım özellikleri.
7. 📄 **[7 - Log Normal Distribution.pdf](PDF/7+-+Log_Normal_Distribution.pdf):** Log-Normal dağılım ve pozitif çarpık veri modelleme.

---

## 🚀 Hızlı Başlangıç & Kurulum

### 1. Depoyu Klonlayın
```bash
git clone https://github.com/52BaranHaydar/Olasilik-Dagilimlari.git
cd Olasilik-Dagilimlari
```

### 2. Sanal Ortam (Virtual Environment) Oluşturun ve Aktif Edin
```bash
# macOS / Linux
python3 -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate
```

### 3. Gerekli Paketleri Yükleyin
```bash
pip install -r requirements.txt
```

### 4. Jupyter Notebook'u Başlatın
```bash
jupyter notebook
# veya
jupyter lab
```

---

## 📦 Kullanılan Kütüphaneler

- **[NumPy](https://numpy.org/):** Vektörize matematiksel işlemler ve rastgele veri üretimi.
- **[SciPy (stats)](https://scipy.org/):** İstatistiksel dağılım nesneleri, olasılık fonksiyonları (PMF, PDF, CDF, PPF) ve moment hesaplamaları.
- **[Pandas](https://pandas.pydata.org/):** Veri işleme, özet tablolar ve analiz.
- **[Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/):** Yüksek çözünürlüklü ve estetik grafik görselleştirmeleri.

---

## 🤝 Katkıda Bulunma

Katkılarınızı memnuniyetle kabul ediyoruz!
1. Bu depoyu Fork'layın.
2. Yeni bir özellik dalı oluşturun (`git checkout -b feature/YeniDagilim`).
3. Değişikliklerinizi commit'leyin (`git commit -m 'feat: Poisson dagilimi eklendi'`).
4. Dalınıza push yapın (`git push origin feature/YeniDagilim`).
5. Bir Pull Request açın.

---

## 📄 Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.
