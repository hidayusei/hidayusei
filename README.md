# 飛田 祐聖 / Yusei Hida

奈良先端科学技術大学院大学（NAIST）情報科学領域 修士1年 / 2028年卒業予定。<br>
データサイエンティスト・機械学習エンジニアを志望しています。

**C++によるアルゴリズム・進化計算の研究経験を基礎に、現在はPythonでスマートホームのセンサデータ解析と人間行動認識に取り組んでいます。研究に加え、Web技術やハードウェアを組み合わせたプロトタイプ開発も経験しています。**

- **Research:** Human Activity Recognition / Sensor Data / Zero-shot Learning
- **Core:** Python / C++ / Machine Learning / Data Analysis / Evolutionary Computation
- **Development:** センサ入力から認識、可視化、動作するデモまで一貫して実装

## Research

### スマートホームにおける人間行動認識

家庭内の連続センサログから、人間の行動の開始・終了位置を推定する**行動区間推定**を研究しています。

家庭ごとに異なる間取り、センサ配置、生活習慣を踏まえ、将来的には未知の家庭にも大量の正解ラベルなしで適用できる **Zero-shot宅内行動認識**につなげることを目指しています。CASAS Arubaなどのスマートホームセンサデータを対象に、Pythonで時系列処理、センサログ解析、機械学習モデルの評価を行っています。

主な経験: TF-IDF + Logistic Regression / Random Forest / pandas / NumPy / scikit-learn / matplotlib

### 進化計算による多角形詰込み（高専時代）

遺伝的アルゴリズムを用いた多角形詰込み問題を研究しました。C++でアルゴリズムを実装し、局所解や多様性維持の課題に対して、改良、パラメータ調整、実験、可視化、性能比較を繰り返しました。

## Research & Presentations

### Current Research

- **情報処理学会 関西支部大会（G-37）**<br>
  「Zero-shot宅内行動認識に向けた行動区間推定手法の検討」 — [発表プログラム](https://kansai.ipsj.or.jp/guide/pages/proceedings/kaisai_2026/sessions/session-g09.html)

### Previous Research

- **第41回ファジィシステムシンポジウム（FSS2025）**<br>
  「自律的に統廃合を繰り返す進化計算アルゴリズムにおける簡略個体の評価」 — [DOI](https://doi.org/10.14864/fss.41.0_730)
- **ICICIC2025**<br>
  “Development of an Evolutionary Algorithm with Autonomous Merge-and-Split and Applying to the Polygon Packing Problem” — [Program](https://www.aims.or.th/wp-content/uploads/2025/08/2025-08-26-ICICIC2025-Program.pdf)
- **日本設備管理学会 知能技術応用研究部会**<br>
  「自律的に統廃合を繰り返す進化計算アルゴリズムにおける統廃合規則の検証」 — [開催案内](https://www.sopej.gr.jp/wp-content/uploads/2025/02/⑤-SOPEJsigITA2024-2知能技術応用研究部会-大分高専情報0221.pdf)
- **第26回 日本知能情報ファジィ学会九州支部学術講演会**<br>
  「自律的に統廃合を繰り返す進化計算アルゴリズムの開発と任意の枠における多角形詰込み問題への応用」 — [Program](https://soft-kyushu.org/2024/conf/prog.html)

## Projects

### [M1GP QUEST](https://github.com/hidayusei/m1gp-quest) — Motion Recognition RPG

スマートフォンを魔法の杖のように振って操作する、加速度センサを利用したモーション認識RPGの個人制作プロトタイプです。DeviceMotion APIによる連続センサ入力から動作区間を抽出し、DTW / Random Forestで分類してゲーム内スキルを発動します。

`Python` `React` `TypeScript` `DeviceMotion API` `DTW` `Random Forest`

### [DeskMate](https://github.com/hidayusei/hackathon) — Event-camera Desk Companion

技育CAMPでチーム開発し、サポーターズ賞を受賞した集中支援アプリです。GenX320イベントカメラで机上の動きを捉え、Raspberry Pi上で特徴量抽出・状態推定・キャラクター表示までを行います。RGB画像を使わず、机上の状態を「集中・非集中・離席中」として可視化します。— [関連投稿](https://x.com/geek_pjt/status/2083831680738234667)

`Python` `NumPy` `PySide6` `Raspberry Pi` `GenX320` `Metavision SDK`

### [すきのたね](https://yoooch0614.github.io/geiot_prototype/website_company/)

NAISTの実践型プログラムGEIOTでチーム開発したプロダクトです。学外のビジネスコンテスト「ビジコンOSAKA」でも代表者として発表しました。

## Skills

| 分野 | 技術・経験 |
|---|---|
| Data Science / ML | Python, pandas, NumPy, scikit-learn, matplotlib, 時系列データ解析, センサデータ処理 |
| Algorithms | C++（約5年）, 遺伝的アルゴリズム, 進化計算, 最適化, 実験・可視化・性能比較 |
| Prototyping | TypeScript, React, JavaScript, Raspberry Pi, DeviceMotion API |
| Other Experience | Java, R, MATLAB, Unity, ROS2, YOLO |

## Activities & Experience

- エムスリー株式会社 データサイエンティストインターン参加（データ分析から発表までを経験）
- 技育CAMPでDeskMateをチーム開発、サポーターズ賞を受賞
- GEIOTで「すきのたね」をチーム開発、ビジコンOSAKAで代表発表
- [THE HACK 2026](https://thehack.nxtend.or.jp/) 参加
- 高専専攻科の約12名の異分野チームで災害対応自律ロボットを共同制作（ROS2 / YOLO / 自律走行）

## Certification

- 基本情報技術者試験 合格

## Background

- **2026年4月–現在:** 奈良先端科学技術大学院大学（NAIST） 情報科学領域
- **2024年4月–2026年3月:** 大分工業高等専門学校 専攻科 電気電子情報工学専攻
- **2019年4月–2024年3月:** 大分工業高等専門学校 本科

## Interests

Machine Learning / Data Science / Human Activity Recognition / Sensor Data / Optimization / Evolutionary Computation / Ubiquitous Computing
