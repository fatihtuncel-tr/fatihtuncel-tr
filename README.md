<div align="center">

  <!-- Animated Custom SVG Hero Banner -->
  <img src="./assets/hero-banner.svg" alt="Fatih Tunçel — Computer & Software Engineering | AI & Deep Learning Researcher" width="100%" />

  <br />

  <!-- Status & Profile Badges -->
  <p>
    <a href="https://github.com/fatihtuncel-tr">
      <img src="https://img.shields.io/badge/Focus-Deep_Learning_%26_Medical_AI-0284C7?style=for-the-badge&logo=pytorch&logoColor=white" alt="Deep Learning & Medical AI" />
    </a>
    <a href="https://github.com/fatihtuncel-tr/swarm-1000-code-perfectizer">
      <img src="https://img.shields.io/badge/Systems-Multi--Agent_Swarm_AI-7E22CE?style=for-the-badge&logo=openai&logoColor=white" alt="Multi-Agent Swarm AI" />
    </a>
    <a href="https://github.com/fatihtuncel-tr/design-project">
      <img src="https://img.shields.io/badge/Research-Uncertainty_%26_Fairness-4F46E5?style=for-the-badge&logo=scipy&logoColor=white" alt="Uncertainty Calibration & Fairness" />
    </a>
    <a href="mailto:fatih1975eses@gmail.com">
      <img src="https://img.shields.io/badge/Contact-Email_Me-0F172A?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" />
    </a>
  </p>

</div>

---

## 👨‍💻 About Me // Hakkımda

<table>
<tr>
<td width="50%" valign="top">

### 🇬🇧 English

Hello! I'm **Fatih Tunçel**, a **Computer & Software Engineering** specialist and **Artificial Intelligence & Deep Learning Researcher**.

My work bridges rigorous **deep learning research** with high-performance **software engineering**, focusing on trustworthy clinical AI and autonomous multi-agent architectures:

- 🩺 **Biomedical AI & Signal Processing:** Designing 1D Convolutional & Residual architectures (`xResNet1d-101`, `SimpleCNN1D`) on large-scale clinical datasets (**PTB-XL**) for reduced-lead ECG classification.
- 🎯 **Trustworthy AI (Uncertainty & Fairness):** Quantifying predictive confidence via **Expected Calibration Error (ECE)**, **Brier Score**, and **Monte Carlo (MC) Dropout**, while evaluating demographic fairness across age groups (`ΔECE`).
- ⚡ **Autonomous Multi-Agent Systems:** Building large-scale collaborative agent swarms (**SWARM-1000**) for automated cross-code auditing, self-healing debugging, and real-time neural mesh visualization.

</td>
<td width="50%" valign="top">

### 🇹🇷 Türkçe

Merhaba! Ben **Fatih Tunçel**, **Bilgisayar ve Yazılım Mühendisliği** alanında çalışan bir **Yapay Zeka ve Derin Öğrenme Araştırmacısıyım**.

Çalışmalarım; güvenilir klinik yapay zeka modelleri ve otonom çoklu ajan (multi-agent) mimarileri ekseninde **derin öğrenme araştırmaları** ile **yüksek performanslı yazılım mühendisliğini** birleştirmektedir:

- 🩺 **Biyomedikal Yapay Zeka & Sinyal İşleme:** Büyük ölçekli klinik veri setleri (**PTB-XL**) üzerinde derivasyon sayısı azaltılmış EKG sınıflandırması için 1B Evrişimli ve Artık ağ mimarileri (`xResNet1d-101`, `SimpleCNN1D`) geliştirilmesi.
- 🎯 **Güvenilir Yapay Zeka (Belirsizlik & Adalet):** **Beklenen Kalibrasyon Hatası (ECE)**, **Brier Skoru** ve **MC Dropout** ile model belirsizliğinin ölçülmesi; yaş grupları arası algoritmik adaletin (`ΔECE`) istatistiksel olarak doğrulanması.
- ⚡ **Otonom Çoklu Ajan Sistemleri:** Çapraz kod denetimi, otonom hata ayıklama ve gerçek zamanlı sinir ağı görselleştirmesi için 1.000 ajanlı işbirlikçi yapay zeka sistemlerinin (**SWARM-1000**) tasarlanması.

</td>
</tr>
</table>

---

## 📊 Research & Engineering Dashboard // Araştırma ve Mühendislik Vitrini

<div align="center">
  <img src="./assets/research-metrics.svg" alt="Research & System Benchmarks Dashboard" width="100%" />
</div>

---

## 🚀 Featured Projects // Öne Çıkan Projeler

<div align="center">
  <a href="https://github.com/fatihtuncel-tr/design-project">
    <img src="./assets/project-ecg.svg" width="49%" alt="design-project: ECG Uncertainty Calibration & Age-Group Fairness" />
  </a>
  <a href="https://github.com/fatihtuncel-tr/swarm-1000-code-perfectizer">
    <img src="./assets/project-swarm.svg" width="49%" alt="swarm-1000-code-perfectizer: 1,000 AI-Agent Code Auditor" />
  </a>
</div>

<br />

<table>
<tr>
<td width="50%" valign="top">

### 1. [🩺 Reduced-Lead ECG Classification: Uncertainty Calibration & Fairness (`design-project`)](https://github.com/fatihtuncel-tr/design-project)

> **EN:** Comprehensive deep learning pipeline on the **PTB-XL** clinical ECG dataset investigating how lead reduction (`12 → 6 → 2 → 1` leads) impacts diagnostic performance, predictive uncertainty calibration, and age-group fairness.
>
> **TR:** **PTB-XL** klinik EKG veri seti üzerinde derivasyon azaltımının (`12 → 6 → 2 → 1` derivasyon) tanı başarımı, belirsizlik kalibrasyonu ve yaş grubu adaleti üzerindeki etkisini inceleyen uçtan uca derin öğrenme araştırması.

- **Verified Benchmark:** `0.9256` Macro AUROC (`95% CI: [0.9185, 0.9326]`) with `xResNet1d-101` on Fold 10 test set, matching the Strodthoff et al. (`0.928`) literature standard within `-0.0024`.
- **Zero-Leakage Signal Pipeline:** Strict patient-disjoint splitting (`15,023` train / `1,942` val / `1,904` test patients), `0.5 Hz` zero-phase Butterworth filtering (`sosfiltfilt`), and `.npz` caching yielding a **`121.6x`** data loading speedup.
- **Calibration & Fairness Metrics:** Class-wise binary ECE (`M=15`), multi-label Brier score, patient-level bootstrap confidence intervals, and age-stratified disparity metrics (`ΔECE(75+ - <40)`).

</td>
<td width="50%" valign="top">

### 2. [⚡ SWARM-1000: AI Code Perfectizer & Autonomous Debugger (`swarm-1000-code-perfectizer`)](https://github.com/fatihtuncel-tr/swarm-1000-code-perfectizer)

> **EN:** Multi-agent autonomous code inspection, error debugging, and refactoring platform powered by a coordinated swarm architecture with an interactive HTML5 neural mesh visualization interface.
>
> **TR:** Koordineli çoklu ajan mimarisi ve etkileşimli HTML5 sinir ağı görselleştirme arayüzü ile güçlendirilmiş; çapraz kod denetimi, otonom hata ayıklama ve yeniden yapılandırma (refactoring) platformu.

- **Swarm Intelligence Engine:** Orchestrates specialized agent roles across syntax auditing, security vulnerability scanning, complexity reduction, and automated patch synthesis (`real_super_ai.py`, `agent_swarm.js`).
- **Interactive Neural Mesh UI:** Real-time canvas network (`network_canvas.js`) visualizing agent communication topologies, consensus formation, and live diagnostic streams.
- **Full-Stack Architecture:** Lightweight Python backend (`app.py`) paired with a responsive, zero-dependency modern JavaScript frontend (`main.js`, `academy.js`).

</td>
</tr>
</table>

---

## 🛠️ Tech Stack & Arsenal // Teknoloji Yığını ve Araçlar

<div align="center">

  <!-- Skill Icons Visual Bar -->
  <p>
    <img src="https://skillicons.dev/icons?i=python,pytorch,scikitlearn,js,html,css,git,github,linux,vscode&perline=10" alt="Core Tech Stack Icons" />
  </p>

</div>

| Category / Kategori | Technologies & Frameworks / Teknolojiler ve Kütüphaneler |
| :--- | :--- |
| **🧠 Deep Learning & AI**<br>*(Derin Öğrenme & YZ)* | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TorchMetrics](https://img.shields.io/badge/TorchMetrics-7E22CE?style=flat-square&logo=pytorch&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Multi-Agent LLMs](https://img.shields.io/badge/Multi--Agent_Swarm_AI-4F46E5?style=flat-square&logo=openai&logoColor=white) ![MC Dropout](https://img.shields.io/badge/Uncertainty_Calibration_(ECE_%2F_MC_Dropout)-0284C7?style=flat-square) |
| **📊 Scientific & Biomedical DSP**<br>*(Bilimsel Hesaplama & Sinyal İşleme)* | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy_(Butterworth_DSP)-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![WFDB](https://img.shields.io/badge/WFDB_(PhysioNet_%2F_PTB--XL)-059669?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn_%26_Matplotlib-3776AB?style=flat-square&logo=python&logoColor=white) |
| **💻 Languages & Web Systems**<br>*(Programlama Dilleri & Web)* | ![Python](https://img.shields.io/badge/Python_3.9+-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript_(ES6+)-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5 Canvas](https://img.shields.io/badge/HTML5_Canvas-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![REST APIs](https://img.shields.io/badge/RESTful_APIs-0F172A?style=flat-square) |
| **⚙️ Engineering & Workflow**<br>*(Mühendislik & Araçlar)* | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Reproducible Research](https://img.shields.io/badge/Reproducible_ML-10B981?style=flat-square) ![Bootstrap CI](https://img.shields.io/badge/Statistical_Validation-6366F1?style=flat-square) |

---

## 📫 Connect & Collaboration // İletişim ve İşbirliği

- 🌐 **GitHub Portfolio:** [github.com/fatihtuncel-tr](https://github.com/fatihtuncel-tr)
- 📧 **Email / E-posta:** [fatih1975eses@gmail.com](mailto:fatih1975eses@gmail.com)
- 🔬 **Research Interests / Araştırma Alanları:** Deep Learning, Biomedical Signal Processing (ECG), Uncertainty Quantification, Algorithmic Fairness, Multi-Agent AI Systems.

<div align="center">
  <br />
  <img src="https://img.shields.io/badge/Crafted_with_Precision-Fatih_Tun%C3%A7el-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8" alt="Fatih Tunçel" />
</div>
