# MELSEC PLC Intelligent Unit I/O Signal Assignment

## Overview

This repository manages I/O signal assignment information for Mitsubishi Electric MELSEC PLC Intelligent Units. It provides device assignments and comments for input/output devices (X/Y) in both Japanese and English, serving as a reference for PLC programming.

## Supported Units

This project supports communication units, data logging units, and other intelligent units from the iQ-R series.

## CSV File Format

Each CSV file contains the following format:

| Column | Description |
|---|---|
| Device | Device number (X00, Y00, etc.) |
| Comment | Device function description |

### Input Device (X) Examples
- `X00` - Unit error
- `X01` - Local data link status
- `X0F` - Unit ready

### Output Device (Y) Examples
- `Y00` - Use prohibit
- `Y17` - ERR LED turn-off request

## Usage

### 1. File Selection
Select the CSV file corresponding to your intelligent unit.

### 2. Data Reference
- **Japanese version**: `*_Japanese.csv`
- **English version**: `*_English.csv`

### 3. PLC Programming Applications
- I/O signal assignment verification
- Device comment configuration
- Communication status monitoring program creation
- Error handling program implementation
- Communication parameter setup
- Data link status monitoring

## Important Notes

- I/O signal assignments may vary depending on unit configuration and firmware version
- Please refer to the corresponding unit manual for actual usage
- Use this repository information as reference material and consult the latest manual for actual system design

---

# MELSEC PLC インテリユニット 入出力信号割り付け

## 概要

このリポジトリは、三菱電機MELSEC PLCのインテリユニット（Intelligent Unit）の入出力信号割り付け情報を管理するためのプロジェクトです。

各インテリユニットの入出力デバイス（X/Y）の割り付けとコメントを日本語・英語で提供し、PLCプログラミング時の参考資料として活用できます。

## 対応ユニット

iQ-R シリーズの通信ユニット、データログユニット、その他のインテリユニットに対応しています。

## CSVファイル形式

各CSVファイルは以下の形式で構成されています：

| 列 | 説明 |
|---|---|
| Device | デバイス番号（X00, Y00等） |
| コメント | デバイスの機能説明 |

### 入力デバイス（X）の例
- `X00` - ユニット異常
- `X01` - 自局データリンク状態
- `X0F` - ユニットレディ

### 出力デバイス（Y）の例
- `Y00` - 使用禁止
- `Y17` - ERR LED消灯要求

## 使用方法

### 1. ファイルの選択
使用するインテリユニットに対応するCSVファイルを選択してください。

### 2. データの参照
- **日本語版**: `*_Japanese.csv`
- **英語版**: `*_English.csv`

### 3. PLCプログラミングでの活用
- 入出力信号の割り付け確認
- デバイスコメントの設定
- 通信状態監視プログラムの作成
- エラー処理プログラムの実装
- 通信パラメータの設定
- データリンク状態の監視

## 注意事項

- 各ユニットの入出力信号割り付けは、ユニットの設定やファームウェアバージョンによって異なる場合があります
- 実際の使用時は、該当するユニットのマニュアルも併せてご確認ください
- 本リポジトリの情報は参考資料としてご利用いただき、実際のシステム設計時は最新のマニュアルをご確認ください

