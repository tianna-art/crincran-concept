# crincran — Concept

> **曲がってきた道を、強さに変える。**

日々の違和感・喜び・憧れ・挫折・試行錯誤を集め、時間をかけてつなぐことで、  
「自分を生かす条件」を育てていくブランド／アプリケーション **crincran** の事業コンセプトをまとめたリポジトリ。

## 🔗 Site

**https://tianna-art.github.io/crincran-concept/**

## About the name

crincran は、イギリスにある波状のレンガ壁 **Crinkle Crankle Wall** に由来する。  
まっすぐな壁は自立するために厚みを必要とするが、波状に曲がった壁は、その曲線自体が強度を生み出す。

> 曲がっているからこそ、強くなれる。

## Contents

| Path | 内容 |
|---|---|
| `index.html` | **Concept Graph** — コンセプト全体をノードとしてたどるインタラクティブなグラフ（canvas・力学レイアウト） |
| `concept.html` | **Concept Book** — 事業コンセプト総括ページ（Vogue的エディトリアル構成／全16章） |
| `docs/concept.md` | 元となった検討メモ（全40章のマークダウン原文） |

どちらも外部依存が Google Fonts のみの単一HTMLファイル。ビルド不要でそのまま開ける。

## Concept Graph

中心の `crincran` から5つの領域が伸び、そこから各概念のノードへ枝分かれする。

| 領域 | 内容 |
|---|---|
| **思想 / IDEA** | 波打つ壁・無理に前向きにしない・答えではなくEvidence・芯ではなく輪郭・点を線にする・向上心の扱い方 |
| **プロダクト / PRODUCT** | COLLECT（Spark / Friction / Longing / Experiment / Turning Point / People）・CONNECT・Personal Context Graph・Style Book・Small Experiment |
| **ユーザー / READER** | まっすぐ乗れなかった人・ターゲットの感情・Emotional / Functional Benefit・自分を生かす条件・憧れという入口 |
| **ブランド / BRAND** | 編集姿勢・Visual Direction・美しい形で返す・SNSの役割・ブランドコピー・約束しないもの |
| **事業 / BUSINESS** | 1,000人 × ¥500・課金理由5つ・キャリアを入口に・転職をゴールにしない・差別化・ブランドバランス |

**操作** — 点をクリックで展開／もう一度で収束、末端ノードで右パネルに本文と関連ノード、ドラッグで移動、ホイールで拡大、下部の凡例で領域をフォーカス、RESETで初期状態へ。

階層のつながりは実線、領域をまたぐ関連は点線で描かれる。全47ノード・70リンク。

## Concept Book の章立て

| # | Chapter | 内容 |
|---|---|---|
| I | Statement | まっすぐ進めなかった日々も、次の自分をつくる材料になる |
| II | Origin | 波打つ壁が、まっすぐな壁より強い理由 |
| III | The Editing Attitude | 統一するのは「憧れの内容」ではなく「扱う態度」 |
| IV | The Problem | 「自分を見ること」だけでは課金価値が生まれない |
| V | Longing | 憧れの「どこに」心が反応したのかを拾う |
| VI | The Style Book | その人自身から生まれるパーソナルな Style Book |
| VII | The Loop | 集める、つなぐ、返す、試す／Personal Context Graph |
| VIII | Wow Points | 課金価値が生まれる4つのポイント |
| IX | Conditions | 「価値観」を「自分を生かす条件」に落とす |
| X | Career as Entrance | キャリアを入口に。ただしキャリアジャーナルにはしない |
| XI | The Reader | まっすぐな成功ルートに乗れなかった人へ |
| XII | Promises | 約束しないもの／約束できるもの |
| XIII | Position | ジャーナリングでも自己分析でもキャリア診断でもない |
| XIV | Aesthetic | crincran自身が憧れられるブランドになること |
| XV | Business | 1,000人 × ¥500/月 |
| XVI | Words | ブランドコピー候補とブランド文章の核 |

## Design notes

- **Typography** — Bodoni Moda（欧文ディスプレイ）／ Noto Serif JP（和文見出し）／ Noto Sans JP（本文）
- **Color** — Graph は領域ごとの5色（思想・紫／プロダクト・青／ユーザー・緑／ブランド・赤／事業・琥珀）、Book はレンガ色 `#9a3f2c` を唯一のアクセントに
- **Motif** — Crinkle Crankle Wall の波形
- ライト／ダークモード両対応。モバイル幅でも横スクロールなし

## Status

`concept-development` — 検討段階の仮説を含み、今後変更される可能性があります。

---

*Your detours are part of the design.*
