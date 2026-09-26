# Conversation Flow

## 1. Start

ユーザーが音声で話し始める。

## 2. Intent detection

発話から現在の目的を推定する。

## 3. Prompt selection

現在のIntentと会話状態から次のPromptを選ぶ。

## 4. Voice response

質問を音声で返す。

## 5. State update

回答から出版企画の状態を更新する。

## 6. Loop

十分な情報が集まるまで質問・深掘り・リサーチを繰り返す。

## 7. Output

企画概要などの成果物に構造化する。

## 8. Save

Google Drive / GitHubなどへ保存する。

## Design rule

保存先やモデル選択はユーザーインターフェースから隠す。

ユーザーは「壁打ちして」「調べて」「保存して」と言うだけでよい。
