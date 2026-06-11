# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Git Operations

This project uses GitHub for version control. Follow these rules on every code change:

1. Stage the changed files specifically (avoid `git add -A` or `git add .`)
2. Commit with a concise message describing the change
3. Push to GitHub immediately after every commit:
   ```
   git push origin <branch>
   ```

All code changes — including small fixes — must be pushed to GitHub before reporting the task as complete.

## Commit Message Style

Use short, imperative-mood messages in Japanese or English (match what the user uses). Example:

```
fix: タスクの削除ボタンが動作しない問題を修正
feat: タスクのステータス変更機能を追加
```
