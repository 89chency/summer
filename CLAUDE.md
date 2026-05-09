# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 專案概覽

**summer** — 鋼琴自學輔助工具。
目標：整理練習進度、簡譜分析、學習計畫追蹤，以 AI 輔助加速學習效率。

## 資料夾結構

```
summer/
  scripts/        # 自動化腳本（Python）
  output/         # 產出內容（練習報告、進度表）
  materials/      # 素材（影片參考、簡譜、音頻）← 不 commit
  templates/      # 範本檔案
```

## 工作流程

- **規劃**：CC 撰寫 `PLAN.md`，標記 `[Codex]` 任務交 Codex 執行
- **產出**：腳本 → GitHub；PDF / 報表 → Google Drive `G:\其他電腦\我的電腦\AI工作區\summer\`
- **進度筆記**：`~/OneDrive/Desktop/Obsidian/進度追蹤/summer.md`

## 技術棧（預期）

Python 為主要語言，常見套件：
- `anthropic` — Claude API 整合
- `pandas` / `openpyxl` — 練習紀錄整理
- `python-docx` — 報告生成

執行環境：Windows 11，PowerShell / Bash 均可。

## 常用指令

```powershell
pip install -r requirements.txt
python scripts/<script_name>.py
```
