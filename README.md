 # 📑 2026 Monthly Tech Paper Deep Dive
### 🇰🇷 2026 매월 CS 논문 & 기술 아티클 심층 분석
### 🇦🇺 Monthly Research Paper Review: From CS Classics to SOTA AI

> **"Read less, but read deeply. Code less, but code efficiently."**
>
> **🇰🇷 소개:** 컴퓨터공학 전공자로서 **CS 기초(Basics)**, **데이터 엔지니어링(Data Eng)**, **최신 AI 연구(Research)** 분야의 핵심 논문 12편을 선정하여 읽고 분석합니다. 단순 요약을 넘어 **비판적 사고(Critique)**와 **구현 가능성(Implementation)**을 탐구합니다.
>
> **🇦🇺 Intro:** A repository dedicated to analyzing 12 essential papers in **CS, Data Engineering, and AI**. This journey focuses on understanding core architectures and cultivating **research-level critical thinking**.

<br>

## 🏃‍♂️ Research Progress
![Progress](https://img.shields.io/badge/Progress-0%2F12-lightgrey?style=for-the-badge&logo=bookstack&logoColor=white)
![Last Commit](https://img.shields.io/badge/Last%20Update-2025.12.31-228B22?style=for-the-badge&logo=github&logoColor=white)

## 🛠️ Domains & Keywords
<img src="https://img.shields.io/badge/CS_Classics-000000?style=flat-square&logo=acm&logoColor=white"> <img src="https://img.shields.io/badge/Data_Engineering-E34F26?style=flat-square&logo=apachespark&logoColor=white"> <img src="https://img.shields.io/badge/Data_Analytics-4479A1?style=flat-square&logo=googlebigquery&logoColor=white"> <img src="https://img.shields.io/badge/AI_Research-FF6F00?style=flat-square&logo=pytorch&logoColor=white">

<br>

---

## 🗓️ 2026 Curriculum Roadmap

### 1️⃣ Quarter 1: The Philosophy of Engineering (CS Classics)
*기술의 유행을 타지 않는 엔지니어의 '태도'와 '본질'을 탐구합니다.*

| Month | Track | Title (Original Source) | Key Takeaway & Insight | Status |
| :---: | :---: | :--- | :--- | :---: |
| **Jan** | <img src="https://img.shields.io/badge/Classic-Black?style=flat-square"> | **[Computing Machinery and Intelligence](https://redirect.cs.umbc.edu/courses/471/papers/turing.pdf)**<br>*(Alan Turing, 1950)* | **AI의 기원.** "기계가 생각할 수 있는가?"에 대한 튜링의 공학적/철학적 고찰. | ⬜ |
| **Feb** | <img src="https://img.shields.io/badge/Classic-Black?style=flat-square"> | **[No Silver Bullet](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf)**<br>*(Fred Brooks, 1986)* | **SW 공학의 바이블.** 복잡성(Complexity)을 다루는 엔지니어의 자세. | ⬜ |
| **Mar** | <img src="https://img.shields.io/badge/Classic-Black?style=flat-square"> | **[Reflections on Trusting Trust](https://www.cs.cmu.edu/~rdriley/487/papers/Thompson_1984_ReflectionsonTrustingTrust.pdf)**<br>*(Ken Thompson, 1984)* | **보안의 근본.** 컴파일러와 시스템 신뢰성에 대한 충격적인 통찰. | ⬜ |

<br>

### 2️⃣ Quarter 2: Infrastructure & Pipeline (Data Engineering)
*대용량 데이터가 저장(Storage), 이동(Flow), 처리(Compute)되는 아키텍처를 이해합니다.*

| Month | Track | Title (Original Source) | Key Takeaway & Insight | Status |
| :---: | :---: | :--- | :--- | :---: |
| **Apr** | <img src="https://img.shields.io/badge/Data_Eng-Red?style=flat-square"> | **[The Google File System (GFS)](https://static.googleusercontent.com/media/research.google.com/ko//archive/gfs-sosp2003.pdf)**<br>*(Google, 2003)* | **Big Data의 시조.** 수천 대의 노드를 묶는 분산 파일 시스템(HDFS)의 원리. | ⬜ |
| **May** | <img src="https://img.shields.io/badge/Data_Eng-Red?style=flat-square"> | **[Kafka: a Distributed Messaging System](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/09/Kafka.pdf)**<br>*(LinkedIn, 2011)* | **파이프라인의 심장.** Log 기반의 Pub/Sub 모델과 스트리밍 아키텍처. | ⬜ |
| **Jun** | <img src="https://img.shields.io/badge/Data_Eng-Red?style=flat-square"> | **[Spark: Resilient Distributed Datasets](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final138.pdf)**<br>*(UC Berkeley, 2012)* | **In-Memory Computing.** 하둡을 넘어선 속도, RDD의 개념과 Lineage. | ⬜ |

<br>

### 3️⃣ Quarter 3: Analytics & Efficiency (Data Analytics)
*데이터를 효율적으로 조회하고, 통계적으로 검증하는 분석 방법론을 익힙니다.*

| Month | Track | Title (Original Source) | Key Takeaway & Insight | Status |
| :---: | :---: | :--- | :--- | :---: |
| **Jul** | <img src="https://img.shields.io/badge/Analytics-Blue?style=flat-square"> | **[Dremel: Interactive Analysis](https://static.googleusercontent.com/media/research.google.com/ko//pubs/archive/36632.pdf)**<br>*(Google, 2010)* | **BigQuery의 엔진.** Columnar Storage가 쿼리 속도를 혁신한 원리. | ⬜ |
| **Aug** | <img src="https://img.shields.io/badge/Analytics-Blue?style=flat-square"> | **[The Snowflake Elastic Data Warehouse](https://dl.acm.org/doi/pdf/10.1145/2882903.2903741)**<br>*(Snowflake, 2016)* | **Modern Data Stack.** 컴퓨팅과 저장소를 분리한 클라우드 네이티브 아키텍처. | ⬜ |
| **Sep** | <img src="https://img.shields.io/badge/Analytics-Blue?style=flat-square"> | **[Controlled experiments on the web](https://robotics.stanford.edu/~ronnyk/2002ControlledExperimentsOnTheWeb.pdf)**<br>*(Microsoft, 2002)* | **A/B Testing.** 상관관계를 넘어 인과관계를 밝히는 실험 설계 방법론. | ⬜ |

<br>

### 4️⃣ Quarter 4: Graduate Prep & SOTA (AI Research)
*최신 AI 트렌드(System Efficiency, Data-Centric)를 연구자 관점에서 비평합니다.*

| Month | Track | Title (Original Source) | Key Takeaway & Insight | Status |
| :---: | :---: | :--- | :--- | :---: |
| **Oct** | <img src="https://img.shields.io/badge/Research-Orange?style=flat-square"> | **[LoRA: Low-Rank Adaptation of LLMs](https://arxiv.org/pdf/2106.09685.pdf)**<br>*(Microsoft, 2021)* | **Model Optimization.** 거대 모델을 효율적으로 튜닝하는 경량화 기술. | ⬜ |
| **Nov** | <img src="https://img.shields.io/badge/Research-Orange?style=flat-square"> | **[FlashAttention: Fast and Memory-Efficient](https://arxiv.org/pdf/2205.14135.pdf)**<br>*(Stanford, 2022)* | **System & Hardware.** GPU 메모리 계층(IO)을 고려한 속도 최적화. | ⬜ |
| **Dec** | <img src="https://img.shields.io/badge/Research-Orange?style=flat-square"> | **[Chain-of-Thought Prompting](https://arxiv.org/pdf/2201.11903.pdf)**<br>*(Google Brain, 2022)* | **Data-Centric AI.** 추론 과정(CoT)을 통해 모델의 지능을 끌어올리는 법. | ⬜ |

<br>



---
Copyright © 2026. All rights Reserved.
