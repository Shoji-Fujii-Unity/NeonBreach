# NEON BREACH: 次元回廊 / Dimension Corridor

Three.js を使ったブラウザ向け 3D ファーストパーソン・シューティングゲームです。  
PC とスマートフォンで動作し、横長画面前提でプレイできるよう設計されています。

---

## Contents / 目次

- [日本語](#日本語)
- [English](#english)
- [简体中文](#简体中文)

---

## 日本語

### 概要

NEON BREACH: 次元回廊は、ローカルな `index.html` をそのまま開いてプレイできる 3D FPS です。  
インストール不要で、ブラウザだけで動作します。

### 推奨環境

- PC: Chrome / Edge / Firefox / Safari の最新バージョン
- スマホ: iPhone / Android の WebView 系ブラウザ

### 遊び方

1. `index.html` をブラウザで開く
2. 画面を横長に表示する
3. 必要に応じて全画面表示にする
4. メニューからゲームを開始する

### PC での操作

- `W` / `A` / `S` / `D`: 移動
- マウス: 視点操作
- クリック: 射撃
- `Shift`: ダッシュ
- `Esc`: 一時停止

### スマホでの操作

- 左スティック: 移動
- 右側のドラッグ: 視点操作
- 右下の `FIRE` ボタン: 射撃

### サウンド

- メニューから On / Off を切り替え可能
- 効果音は Web Audio API で生成しています

### 多言語対応

このゲームは次の言語に対応しています。

- 日本語
- English
- 简体中文

言語はメニューのドロップダウンから切り替えられます。

### セーブデータ

ローカルストレージに次の情報を保存します。

- 解放済みステージ
- 総スコア
- 総キル数
- 選択中の言語
- サウンド設定

セーブデータ名は `neon_breach_save_v1` です。

### ゲーム内容

- ステージは 12 本
- 敵の種類は多め
- ボスの種類は多め
- 敵を倒すとアイテムを落とすことがある
- ステージ内にもアイテムが配置される

### アイテム

取得できるアイテム:

- 回復パック
- シールドセル
- 加速コア
- 連射ブースター

### 敵について

敵は常にプレイヤーの方を向きます。  
また、敵には多彩なデザインと行動パターンを用意しています。

### 壁の処理について

ステージの通路は外側に出られないように完全に閉じられています。  
プレイヤーが虚空へ出ることはありません。

### ファイル構成

このプロジェクトは単一ファイルで動作します。

- `index.html`
- `README.md`

### 既知の注意

- 縦画面では横画面になるよう案内を表示します
- 一部のブラウザではセーブデータの保存が制限される場合があります
- 端末性能によっては動作が重くなることがあります

---

## English

### Overview

NEON BREACH: Dimension Corridor is a browser-based 3D FPS built with Three.js.  
It can run on both PC and mobile devices, and is designed for landscape screens.

### Supported Environments

- PC: latest Chrome, Edge, Firefox, Safari
- Mobile: modern mobile browsers

### How to Play

1. Open `index.html` in a browser
2. Rotate your device to landscape
3. Optional: enter fullscreen
4. Start the game from the menu

### Controls on PC

- `W` / `A` / `S` / `D`: move
- Mouse: aim
- Click: shoot
- `Shift`: dash
- `Esc`: pause

### Controls on Mobile

- Left stick: move
- Drag on the right side: aim
- `FIRE` button: shoot

### Audio

- Audio can be toggled On / Off from the menu
- Sound effects are generated with the Web Audio API

### Languages

The game supports these languages:

- 日本語
- English
- 简体中文

You can change the language from the menu.

### Save Data

The game saves the following data to local storage:

- unlocked stages
- total score
- total kills
- selected language
- audio setting

Save key: `neon_breach_save_v1`

### Game Content

- 12 stages
- many enemy types
- many boss types
- enemies may drop items
- items are also placed inside stages

### Items

Collectible items:

- health pack
- shield cell
- speed core
- rapid booster

### Enemies

Enemies always face the player.  
They also have detailed designs and different behaviors.

### Walls

Corridor walls are closed on all sides.  
The player cannot walk into empty space outside the stage.

### Project Structure

This project works as a single file.

- `index.html`
- `README.md`

### Notes

- A prompt is shown in portrait orientation
- Some browsers may restrict local storage
- Performance may vary depending on device capability

---

## 简体中文

### 概述

NEON BREACH: 次元回廊 是一个使用 Three.js 制作的浏览器 3D 第一人称射击游戏。  
可在 PC 和智能手机上运行，并适配横屏操作。

### 推荐环境

- PC: Chrome / Edge / Firefox / Safari 最新版
- 手机: iPhone / Android 现代浏览器

### 开始游戏

1. 用浏览器打开 `index.html`
2. 将设备横屏
3. 可选：进入全屏
4. 从菜单开始游戏

### PC 操作

- `W` / `A` / `S` / `D`：移动
- 鼠标：视角控制
- 点击：射击
- `Shift`：冲刺
- `Esc`：暂停

### 手机操作

- 左侧摇杆：移动
- 右侧拖动：视角控制
- 右下 `FIRE` 按钮：射击

### 音效

- 可在菜单中切换 On / Off
- 音效由 Web Audio API 生成

### 多语言支持

游戏支持以下语言：

- 日本語
- English
- 简体中文

语言可在菜单中切换。

### 存档

游戏会在本地存储中保存以下信息：

- 已解锁关卡
- 总分
- 总击杀数
- 当前语言
- 音效设置

存档键名：`neon_breach_save_v1`

### 游戏内容

- 共 12 个关卡
- 大量敌人种类
- 大量 Boss 种类
- 击杀敌人可能掉落道具
- 场景中也会放置道具

### 道具

可拾取道具：

- 生命恢复包
- 护盾单元
- 加速核心
- 连射强化器

### 敌人

敌人会始终面向玩家。  
敌人拥有丰富的外观设计和行动方式。

### 墙壁

通道墙壁完全封闭。  
玩家不会走出关卡进入虚空。

### 文件结构

本项目的运行只需以下文件：

- `index.html`
- `README.md`

### 注意事项

- 竖屏时会提示切换横屏
- 部分浏览器可能限制本地存储
- 设备性能不同会影响运行效果