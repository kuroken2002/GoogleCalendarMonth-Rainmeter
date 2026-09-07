# Google Calendar Month for Rainmeter

Googleカレンダーの予定を月間表示するRainmeterスキンです。  
A Rainmeter skin that displays Google Calendar events in a monthly calendar view.

## 主な機能 / Features

- GoogleカレンダーのiCal連携 / Google Calendar iCal integration
- 月間カレンダー表示 / Monthly calendar view
- 先月・今月・来月への移動 / Navigate previous, current, and next month
- 日本語表示対応 / Japanese display support
- 1日最大3件の予定を表示 / Displays up to 3 events per day

## 必要環境 / Requirements

- Windows 10 / 11
- Rainmeter 4.5 or later

## インストール / Installation

1. Releasesから最新の `.rmskin` をダウンロード  
   Download the latest `.rmskin` from Releases.
2. ファイルをダブルクリックしてインストール  
   Double-click the file to install it.
3. 「iCal設定」を押す  
   Click `iCal設定` (iCal Settings).
4. Googleカレンダーの「iCal形式の非公開URL」を入力  
   Enter your Google Calendar private iCal URL.
5. スキンを再読み込み  
   Refresh the skin.

## Google Calendarの設定 / Google Calendar Setup

Google Calendarの設定画面から、使用するカレンダーの
「カレンダーの統合」を開き、
「iCal形式の非公開URL」をコピーしてスキンに設定してください。

Open Google Calendar settings, select the calendar you want to use,
open **Integrate calendar**, and copy the
**Secret address in iCal format** into the skin settings.

## プライバシー / Privacy

Googleカレンダーの非公開iCal URLは、GitHubや作者には送信されません。  
利用者自身のパソコン内の `Variables.inc` に保存されます。

Your private Google Calendar iCal URL is not sent to GitHub or the author.  
It is stored locally in `Variables.inc` on your PC.

## Version

Latest: **v1.0.1**

### v1.0.1

- 作者情報を統一 / Updated author metadata
- Version情報を修正 / Fixed version information
- `Variables.inc` のコメント表記を修正 / Fixed comments in `Variables.inc`

## Beta version available

v1.1.0-beta.1 is now available.

- 今日・明日の予定の音声読み上げ
- 定時読み上げ
- Rainmeter起動時の読み上げ
- 専用設定画面
- カレンダー更新間隔の設定
- 読み上げ判定間隔の設定
  
This beta adds schedule voice reading, scheduled announcements, and a dedicated settings screen.

## Author
## Rainmeter Forum

Discussion, feedback and support are available on the official Rainmeter Forum.

[Google Calendar Month v1.0.1 - Rainmeter Forums](https://forum.rainmeter.net/viewtopic.php?t=46019)
**kuroken2002**
