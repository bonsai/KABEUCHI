# Recap

Last session: 2026-09-27

## 状態（次回の出発点）

KABEUCHI を「壁打ちという**器官**」として定義し直した。プロダクトではなく、
4つの器官（ブレスト／壁打ち／グリル／詰める）の一つ、という位置づけ。

判断の軸は **温度**：

| 器官 | 温度 | 問い | 持ち帰るもの |
|---|---|---|---|
| ブレスト | 42℃ | 聞かない | 大量の未加工 |
| 壁打ち | 38℃ | ほんとにそうなのか | 気づく |
| グリル | 15℃ | 前提は間違っていないか | 食べれる状態 |
| 詰める | 15℃ | 一問ずつ | 順序と仕様 |

壁打ちの目的は成果物ではなく **気づく**（話手側の変化）。
機構は `why_speaking_changes_thinking`：話した語は他人の記憶に入り、改竄できない
→ 自己監視が物理的に不可能になる。だから「一人で考える」で代替できない。

## 今セッションの完了（証拠）

### bonsai/KABEUCHI（push 済 `c4b6a97..db82cc4`）
- `workflow/old-work.yaml` — commit `5cba5d2`
  昔の仕事の工程（receive→carry→recall→speak→write→sort→decide→drop）、
  発生4場所（仕事/馬上/トイレ/風呂）、器官4つ、planner の5工程、
  `vocations`（pdm_editor / idol_producer）、`why_speaking_changes_thinking`。
- `skills/brainstorm/SKILL.md` — commit `ac41c88`
  42℃の器官。`disable-model-invocation: true`。混同表つき。
- `essays/essay-bad-wallbounce-partner.md` — commit `db82cc4`（1258字）
  日本語版エッセイ。`~/essays/` にも同内容。

### bonsai/ask（push 済 `41f4bc7..8b7ef6b`）
- `question-forms.md` — commits `813e143`, `014c7d9`
  質問の型10（数を出す／今を問う／否定を問う／由来／場面／決定者／最後の一歩／
  沈黙／復唱／推奨しない）+ anti-forms 7 + 温度の軸。
  **README の Skill Protocol step 5 `Choose` は型カタログ不在だった** → 埋めた。
  step 4 `Detect` は 15℃ の動作だと README に注記。
- `essay-a-good-question-is-a-closed-door.md` — commits `522f35e`, `8b7ef6b`（724 words）
  英語版エッセイ。

## ブロッカー・保留

- **Deleuze の ask パターンが未着手。** ユーザーの最後の依頼。
  `README.md` の `## Philosopher / Thinker Patterns`（Socrates/Plato/Wittgenstein の
  3人）に追加する。Deleuze は **存在論的問いではなく条件的問い**（「それを可能にしている
  条件は？」）を立てる型なので、既存3人（well-formed）と違い **崩す型** に属する。
  → 前セッションで見つけた「崩す型の思想家が1人もいない」穴を、Deleuze がちょうど埋める。
- `skills/kabeuchi/SKILL.md` の constraint `C5 Remain domain-agnostic` が
  `vocations`（職種依存）と矛盾したまま。消すか core 4条に絞るか未決定。
- `old-work.yaml` の rules は重複6組を数えた。4条への畳み込みは提案のみで未適用。
- `old-work.yaml` の `mirror_do_not_interrogate` と、エッセイの「崩す型」が
  整合するか未検証（復唱は前段か代替か）。

## 次の一手（優先順）

1. `bonsai/ask` に **Deleuze** を Thinker Patterns に追加（形式: `aware/notice/ask/follow-up/behavior`）。
   条件的問い・本質の拒否・「誰が決める？」という裁定者への疑い・問いの退行的性質。
2. `skills/kabeuchi/SKILL.md` の `C5` を core 4条に絞り、型依存は plugin へ。
3. `old-work.yaml` の rules 10 → 4 へ畳む（`stay_at_38` / `do_not_judge` /
   `ask_only_what_changes_understanding` / `keep_proportional`）。
4. 復唱と崩す型の関係を決めて `old-work.yaml` の rule 5 を修正。

## 数量メモ

- エッセイ: 日本語 1258字 / 英語 724 words
- 質問の型: 10 + anti-forms 7
- 器官: 4（42/38/15/15℃）
- コミット: KABEUCHI 3件 / ask 4件（すべて push 済）
- 未コミット: なし（両 repo とも clean）
