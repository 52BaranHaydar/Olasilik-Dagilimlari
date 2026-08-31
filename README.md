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
- 💼 **Gerçek hayat senaryoları ve vaka analizleri** yer almaktadır.

---

## 🗺️ Dağılımlar Yol Haritası (Roadmap)

### 🎲 1. Ayrık (Discrete) Olasılık Dağılımları
- [x] **[Bernoulli Dağılımı (Bernoulli Distribution)](bernoulli_distribution.ipynb)**
  - Tek denemeli iki sonuçlu olaylar, PMF/CDF, Varyans analizi, Büyük Sayılar Yasası (LLN) simülasyonu, CTR ve Kalite Kontrol örnekleri.
- [ ] **Binom Dağılımı (Binomial Distribution)**
- [ ] **Poisson Dağılımı (Poisson Distribution)**
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
