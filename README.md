# Google Calendar Month for Rainmeter

Googleカレンダーの予定を月間表示するRainmeterスキンです。  
A Rainmeter skin that displays Google Calendar events in a monthly calendar view.

## 主な機能 / Features

- GoogleカレンダーのiCal連携 / Google Calendar iCal integration
- 月間カレンダー表示 / Monthly calendar view
- 先月・今月・来月への移動 / Navigate previous, current, and next month
- 1日に表示する予定数を1〜3件から選択可能 / Configurable 1–3 events displayed per day
- 予定表示数に応じてカレンダーの高さを自動調整 / Calendar height automatically adjusts to the selected event count
- 専用設定画面 / Dedicated settings screen
- タブ形式のコンパクトな設定画面 / Compact tab-based settings screen
- 低解像度PC向けのレイアウト / Improved layout for low-resolution displays
- カレンダー更新間隔を設定可能 / Configurable calendar update interval
- 予定色を文字背景として表示 / Optional event color backgrounds
- 予定色の背景表示をON/OFF可能 / Event color backgrounds can be enabled or disabled
- 複数日にまたがる予定を帯状に表示 / Multi-day events are displayed as continuous bands
- BYDAYを含む月次繰り返し予定に対応 / Improved monthly recurring event support including BYDAY
- 今日・明日の予定を音声読み上げ / Voice reading of today's and tomorrow's schedules
- Rainmeter起動時の予定読み上げ / Voice announcement on Rainmeter startup
- 定時読み上げを2件まで設定可能 / Up to 2 scheduled voice announcement times
- 読み上げ判定間隔を設定可能 / Configurable speech check interval
- 「予定はありません」の読み上げON/OFF / Optional "no events" voice announcement
- 多言語UI対応 / Multilingual UI support
  - 日本語 / Japanese
  - English
  - Français / French
  - Deutsch / German
- 選択中の設定を色で確認可能 / Selected settings are visually highlighted
- iCal URL未設定時は古い予定キャッシュを自動削除 / Cached events are automatically cleared when no iCal URL is configured

## 必要環境 / Requirements

- Windows 10 / 11
- Rainmeter 4.5 or later
- Windows Speech API (SAPI) for voice announcements

## インストール / Installation

1. Releasesから最新の `.rmskin` をダウンロード  
   Download the latest `.rmskin` from Releases.

2. ファイルをダブルクリックしてインストール  
   Double-click the file to install it.

3. カレンダーの「設定」を開く  
   Open the calendar settings.

4. Googleカレンダーの「iCal形式の非公開URL」を入力  
   Enter your Google Calendar private iCal URL.

5. 「保存して閉じる」を押す  
   Click `Save and Close`.

## Google Calendarの設定 / Google Calendar Setup

Google Calendarの設定画面から、使用するカレンダーの  
「カレンダーの統合」を開き、  
「iCal形式の非公開URL」をコピーしてスキンに設定してください。

Open Google Calendar settings, select the calendar you want to use,  
open **Integrate calendar**, and copy the  
**Secret address in iCal format** into the skin settings.

iCal URLが未設定の場合は、以前取得した予定データは自動的にクリアされます。

If no iCal URL is configured, previously cached calendar data is automatically cleared.

## 設定画面 / Settings

v1.1.2では設定画面を3つのタブに分割しました。

- 基本設定
- 読み上げ
- 定時読み上げ

Version 1.1.2 divides the settings screen into three tabs:

- Basic
- Speech
- Scheduled Speech

低解像度のノートPCなどでも設定しやすいよう、画面サイズをコンパクトにしています。

The settings screen has been made more compact for easier use on low-resolution displays.

## 表示予定数 / Events Per Day

1日に表示する予定数を以下から選択できます。

- 1件
- 2件
- 3件

初期値は1件です。

The number of events displayed per day can be selected from:

- 1 event
- 2 events
- 3 events

The default is 1 event per day.

選択した予定数に合わせて、カレンダー全体の高さも自動的に変更されます。

The calendar height automatically changes according to the selected number of events.

## 多言語表示 / Multilingual Interface

v1.1.2ではUIの多言語表示に対応しました。

対応言語:

- 日本語
- English
- Français
- Deutsch

Version 1.1.2 adds multilingual UI support.

Supported languages:

- Japanese
- English
- French
- German

ボタン、タブ、設定項目、説明文などは言語ファイルから読み込まれます。

Buttons, tabs, settings labels, and descriptions are loaded from language files.

## 音声読み上げ / Voice Announcements

Google Calendarの予定をWindowsの音声合成機能で読み上げることができます。

Google Calendar events can be read aloud using Windows speech synthesis.

設定可能な項目:

- Rainmeter起動時の読み上げ
- 今日 / 明日の予定
- 定時読み上げ1
- 定時読み上げ2
- 読み上げ判定間隔
- 予定がない場合の読み上げ

Available options include:

- Voice announcement on Rainmeter startup
- Today's or tomorrow's schedule
- Scheduled announcement 1
- Scheduled announcement 2
- Speech check interval
- Optional "no events" announcement

今日 / 明日などの選択中の項目は、設定画面上で色分けして表示されます。

Selected options such as Today / Tomorrow are visually highlighted in the settings screen.

## 予定色 / Event Colors

Google Calendarの予定色を、予定文字の背景色として表示できます。

背景色表示は設定画面からON/OFFを切り替えられるため、  
デスクトップの雰囲気に合わせて表示方法を選択できます。

Google Calendar event colors can be used as text backgrounds.

The color background display can be enabled or disabled in the settings,  
allowing you to choose a style that matches your desktop.

## 複数日予定 / Multi-day Events

複数日にまたがる予定は、日付をまたいで連続した帯として表示されます。

Events spanning multiple days are displayed as continuous bands across dates.

## プライバシー / Privacy

Googleカレンダーの非公開iCal URLは、GitHubや作者には送信されません。  
利用者自身のパソコン内に保存されます。

Your private Google Calendar iCal URL is not sent to GitHub or the author.  
It is stored locally on your PC.

## Version

Latest: **v1.1.2**

### v1.1.2

#### New features / 新機能

- 設定画面を3タブ構成に変更
- 低解像度PC向けに設定画面をコンパクト化
- 1日に表示する予定数を1〜3件から選択可能
- 予定表示数に合わせてカレンダーの高さを自動変更
- 多言語UIに対応
  - 日本語
  - English
  - Français
  - Deutsch
- 選択中の予定表示数を色で表示
- 選択中の表示言語を色で表示
- 読み上げ対象の今日 / 明日を色で表示
- 予定表示数の初期値を1件に変更

- Added a three-tab settings screen
- Added a compact settings layout for low-resolution displays
- Added selectable 1–3 events per day
- Calendar height now adjusts automatically to the selected event count
- Added multilingual UI support
  - Japanese
  - English
  - French
  - German
- Selected event count is visually highlighted
- Selected display language is visually highlighted
- Selected Today / Tomorrow speech target is visually highlighted
- Default events per day changed to 1

#### Improvements / 改善

- フランス語・ドイツ語など長い文字列に合わせて設定画面の配置を調整
- タブの選択状態を色で分かりやすく表示
- 設定項目の選択状態を統一した配色で表示

- Improved settings layout for longer French and German text
- Active tabs are now visually highlighted
- Selected settings use a consistent highlight style

#### Fixes / 修正

- iCal URLが空の場合でも、以前取得した予定が表示され続ける問題を修正
- iCal URL未設定時に古い予定キャッシュを自動的にクリアするよう変更

- Fixed an issue where previously downloaded events could remain visible when the iCal URL was empty
- Cached calendar data is now automatically cleared when no iCal URL is configured

### v1.1.1

#### New features / 新機能

- 予定の色を文字の背景色として表示
- 予定色の背景表示ON/OFF設定を追加
- 複数日にまたがる予定を帯状に表示
- 専用設定画面
- 今日・明日の予定の音声読み上げ
- Rainmeter起動時の読み上げ
- 定時読み上げ
- 更新間隔・読み上げ判定間隔の設定

- Added event color backgrounds
- Added an ON/OFF setting for event color backgrounds
- Added band-style display for multi-day events
- Added a dedicated settings screen
- Added voice reading of today's and tomorrow's schedules
- Added startup voice announcements
- Added scheduled voice announcements
- Added configurable calendar update and speech check intervals

#### Fixes / 修正

- BYDAYを使用した月次繰り返し予定が誤った日付に表示される問題を修正
- 例: `RRULE:FREQ=MONTHLY;BYDAY=4WE` が毎月第4水曜日として正しく表示されるよう修正

- Fixed monthly recurring events using BYDAY being displayed on the wrong date
- Example: `RRULE:FREQ=MONTHLY;BYDAY=4WE` now correctly displays the 4th Wednesday of each month

## Rainmeter Forum

Discussion, feedback and support are available on the official Rainmeter Forum.

[Google Calendar Month - Rainmeter Forums](https://forum.rainmeter.net/viewtopic.php?t=46019)

## Author

**kuroken2002**
