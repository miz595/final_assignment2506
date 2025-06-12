# 講義書き起こし修正AI

本ツールは、Gemini APIとGoogle Colabを使って、講義の書き起こしテキストを自動で修正し、スライドの専門用語に合わせて表記を統一するものです。

## 使い方
1. Google Colabでノートブック（.ipynb）を開く
2. pptxファイル（slide.pptx）をアップロード
3. 書き起こしファイル（transcript.txt）をアップロード
4. セルを上から順番に実行
5. 出力ファイル（transcript_fixed.txt）をダウンロード

## 必要なもの
- google-generativeai
- python-pptx

## 注意
- GeminiのAPIキーはColabのシークレット機能で管理してください
