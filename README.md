<div align="center">

<!-- Typing animation -->
<a href="https://github.com/yoshizawariku">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Riku+Yoshizawa+%F0%9F%91%8B;IoT+%C3%97+AI+%C3%97+Physical+AI+Engineer;Wearable+%7C+Robotics+%7C+Embedded+Systems;University+of+Tsukuba+M1+%F0%9F%8E%93" alt="Typing SVG" />
</a>

<br/>

<!-- Social badges -->
[![GitHub](https://img.shields.io/badge/GitHub-yoshizawariku-181717?style=flat-square&logo=github)](https://github.com/yoshizawariku)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Riku_Yoshizawa-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riku-yoshizawa-927664334)
[![TOEIC](https://img.shields.io/badge/TOEIC-905-blue?style=flat-square&logo=duolingo&logoColor=white)](https://github.com/yoshizawariku)
[![University of Tsukuba](https://img.shields.io/badge/University_of_Tsukuba-Cybernics_Lab-purple?style=flat-square)](https://github.com/yoshizawariku)
[![SII 2026](https://img.shields.io/badge/SII%2FSICE_2026-Cancun%2C_Mexico_%F0%9F%8C%8A-green?style=flat-square)](https://github.com/yoshizawariku)

</div>

---

## 👨‍💻 About Me

```python
class RikuYoshizawa:
    university  = "University of Tsukuba, Graduate School"
    program     = "Intelligent & Mechanical Interaction Systems (M1)"
    lab         = "Cybernics Laboratory"
    research    = ["Wearable IoT", "Knee Joint Load Estimation", "Physical AI", "Sim-to-Real"]
    languages   = ["Python", "C#", "C++", "Java"]
    interests   = ["IoT × AI fusion", "Robotics", "Digital Twin", "XR"]
    status      = "🎯 Open to new opportunities"
    publication = "SII/SICE 2026 @ Cancun, Mexico 🌊"
```

> **"見えないインフラが価値を支える"**  
> — ハードウェアからAIまで、フルスタックで社会課題を解決する

---

## 🔬 Research Highlights

<table>
<tr>
<td width="50%">

### 🦿 Knee Joint Load Estimation
**IMU Sensor × 1D-CNN / LSTM**

- 9軸IMUセンサ（加速度・角速度・地磁気）から膝関節の**3次元接触力をリアルタイム推定**
- 従来研究の1次元 → **3次元方向**へ拡張
- OpenSim による筋骨格解析との照合で高精度検証
- ラベリングツール自作で作業効率 **×6 改善**
- 🏥 筑波大学病院との共同研究・実証試験予定

</td>
<td width="50%">

### 🤖 Sim-to-Real Platform (NVIDIA Omniverse)
**Isaac Sim × Isaac Lab**

- 人とロボットの協働のためのシミュレーション環境構築
- ウェアラブルデバイス身体データのシミュレーション転送サーバー構築
- ロボットアームの強化学習（RL）検証
- 製造・物流向けデジタルツインへの応用

</td>
</tr>
</table>

---

## 📄 Publications

| Year | Venue                              | Paper                                                                                                                                               |
| ---- | ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2026 | **SII/SICE 2026** @ Cancun, Mexico | [Three-Dimensional Knee Joint Contact Force Estimation Using Wearable IMU Sensors and Deep Learning](https://ieeexplore.ieee.org/document/11404679) |

---

## 💻 Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

### AI / ML / Data
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Embedded / IoT
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)

### XR / Simulation
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![NVIDIA Omniverse](https://img.shields.io/badge/NVIDIA_Omniverse-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### Infrastructure / DevOps
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## Featured Projects

<table>
<tr>
<td width="50%">

### 🏋️ [SquatScope](https://github.com/yoshizawariku/SquatScope)

IMU + EMG センサ（M5StickC Plus2）から BLE で 1000 Hz データを受信・リアルタイム可視化する Python アプリ

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
[![Stars](https://img.shields.io/github/stars/yoshizawariku/SquatScope?style=flat-square&color=yellow)](https://github.com/yoshizawariku/SquatScope/stargazers)

</td>
<td width="50%">

### 🎨 [Marp4VSCode-CSS-CustomPrompt](https://github.com/yoshizawariku/Marp4VSCode-CSS-CustomPrompt)

Marp for VS Code 用カスタム CSS テーマ + AI 支援スライド作成ガイド。GitHub Pages CDN で即利用可能

![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![Marp](https://img.shields.io/badge/Marp-0288D1?style=flat-square&logo=markdown&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)
[![Stars](https://img.shields.io/github/stars/yoshizawariku/Marp4VSCode-CSS-CustomPrompt?style=flat-square&color=yellow)](https://github.com/yoshizawariku/Marp4VSCode-CSS-CustomPrompt/stargazers)

</td>
</tr>
</table>

---

## 🏆 Key Achievements

| 🎯 Achievement        | 📝 Detail                                       |
| -------------------- | ---------------------------------------------- |
| **国際学会発表**     | SII/SICE 2026 @ Cancun, Mexico                 |
| **6× 効率化**        | 時系列データラベリングツール自作（1h → 10min） |
| **産学連携**         | 筑波大学病院との共同研究・実証試験             |
| **ラボインフラ刷新** | GitLab サーバー導入・ネットワーク設計          |
| **Local LLM Server** | OpenCrow ベースの研究効率化サーバー構築中      |
| **サークル代表 2年** | 留学生 9名を招致・日英 Bot 開発・参加率改善    |

---

## 🌐 Domain Expertise

```mermaid
graph LR
    subgraph HW ["🔧 Hardware"]
        A["📡 ESP32 / IMU Sensor"]
        B["⚙️ Embedded C++"]
        C["🦾 Wearable Design"]
        D["🌐 Network Infra"]
    end

    PAI(["⚡ Physical AI"])

    subgraph SW ["💻 Software"]
        E["🧠 PyTorch / CNN / LSTM"]
        F["🦴 OpenSim / Biomechanics"]
        G["🏭 NVIDIA Omniverse"]
        H["🥽 XR / Unity / AR-VR"]
    end

    A <-.-> E
    B <-.-> F
    C <-.-> G
    D <-.-> H
    HW <--> PAI
    PAI <--> SW

    style PAI fill:#58A6FF,color:#0d1117,stroke:#58A6FF,font-weight:bold
    style HW fill:#161b22,stroke:#30363d,color:#c9d1d9
    style SW fill:#161b22,stroke:#30363d,color:#c9d1d9
```

---

<div align="center">

### 💬 Let's Connect!

*Research intern / Full-time opportunities welcome*

[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/yoshizawariku)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riku-yoshizawa-927664334)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=yoshizawariku&color=58A6FF&style=flat-square)

</div>
