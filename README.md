# ai-dotfiles

Claude Code と GitHub Copilot の個人設定置き場。

## セットアップ

`.claude/` と `.copilot/` をホームディレクトリにコピーする。
- Mac: `/Users/ユーザー名/`
- Windows: `C:\Users\ユーザー名\`

## Claude Code

`.claude/skills/` にカスタムスキルを配置。チャットでスキル名を入力して呼び出す。

```
/my-impl
```

## GitHub Copilot

`.copilot/agents/` にカスタムエージェントを配置。VS Code の Copilot Chat で `/agent` と入力し、エージェントを選択して呼び出す。

```
/agent → my-impl を選択
```
