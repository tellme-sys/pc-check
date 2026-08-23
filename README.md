# PC Check

PC・周辺機器の基本動作を、ソフトウェアをインストールせずブラウザ上で確認できるWebツールです。

キーボード、マウス、モニター、ネットワーク、ゲームコントローラーなどの基本的な動作確認を、ブラウザ上で簡単に行えることを目的としています。

This is a web-based tool for checking the basic functionality of PCs and peripheral devices without installing additional software.

It provides simple browser-based checks for keyboards, mice, monitors, network responsiveness, game controllers, and related hardware.

## 公開サイト / Live Site

PC Check is available via GitHub Pages.

https://tellme-sys.github.io/pc-check/

## 主な機能 / Features

* PC・画面基本情報表示
  Basic PC and display information

* 日本語キーボード（JIS 109キー）チェック
  Japanese keyboard (JIS 109-key) check

* 英語キーボード（US 104キー）チェック
  English keyboard (US 104-key) check

* キーボードのチャタリング確認
  Keyboard chatter detection

* 60% / テンキーレス / フルキーボード表示切替
  60% / tenkeyless / full-size keyboard selection

* マウス動作チェック
  Mouse input check

* マウスのチャタリング確認
  Mouse chatter detection

* 左・右・中央クリック確認
  Left, right, and middle click check

* ホイール上下確認
  Mouse wheel up/down check

* 戻る・進むボタン確認
  Back and forward mouse button check

* モニター表示チェック
  Monitor display check

* 白・黒・赤・緑・青・グレー表示
  White, black, red, green, blue, and gray display tests

* グラデーション・格子・縞模様表示
  Gradient, checker, and stripe display tests

* 全画面モニターチェック
  Fullscreen monitor check

* モニター表示自動サイクル
  Automatic monitor color cycle

* ネットワーク応答時間チェック（概算）
  Approximate network response check

* ゲームコントローラーチェック
  Game controller check

* ボタン・十字キー・スティック入力確認
  Gamepad button, D-pad, and analog stick input check

* 日本語 / 英語表示切替
  Japanese / English interface switching

* 総合結果表示
  Overall result summary

## 推奨環境 / Recommended Environment

**Google Chrome 最新版**を推奨します。

Chromium系ブラウザでも基本的な機能を利用できます。

一部の高度な機能では、ブラウザの対応状況によって動作が制限される場合があります。

**The latest version of Google Chrome is recommended.**

Basic functionality should also work in other Chromium-based browsers.

Some advanced features may be limited depending on browser support.

## キーボードチェックについて / Keyboard Check

キーボードチェック中は、対応しているChrome環境で一部のブラウザショートカットキーの通常動作を一時的に抑制します。

チェック終了後は通常の動作に戻ります。

物理的に反応しないキーは、ブラウザへ入力信号自体が届かないため自動検出できません。

キーを一通り押した後、白いまま残っているキーがないか確認してください。

During the keyboard check, supported Chrome environments may temporarily suppress some browser shortcut behavior.

Normal keyboard behavior is restored when the check ends.

A physically unresponsive key cannot be automatically detected because no input signal reaches the browser.

After testing, check whether any keys remain white.

## チャタリング判定について / Chattering Detection

短時間に異常な連続入力が検出された場合、チャタリングの可能性を表示します。

ただし、結果だけでハードウェア故障を確定するものではありません。

複数回チェックして再現性を確認してください。

If abnormal repeated input is detected within a short period, the tool may indicate possible chattering.

This result alone does not confirm a hardware fault.

Please repeat the check several times to confirm whether the issue is reproducible.

## ネットワークチェックについて / Network Check

ネットワークチェックは、ブラウザからHTTPS通信を行い、その往復時間を利用して通信の応答性を概算します。

OSの `ping` コマンドと同じ測定ではありません。

また、回線速度そのものを測定する機能ではありません。

The network check estimates responsiveness using HTTPS request round-trip times from the browser.

It is not equivalent to the operating system's `ping` command.

It also does not measure actual connection bandwidth.

## 注意事項 / Disclaimer

このサイトは、ブラウザ上で取得可能な情報や入力イベントを利用した簡易動作チェックツールです。

PCや周辺機器の故障、正常性、性能を完全に診断または保証するものではありません。

ブラウザ、OS、接続機器、セキュリティ設定などによって、一部の機能が利用できない場合があります。

This site provides basic functionality checks using information and input events available through the web browser.

It does not provide a complete diagnosis or guarantee the condition, performance, or reliability of PCs or peripheral devices.

Some features may be unavailable depending on the browser, operating system, connected hardware, or security settings.

## 開発状況 / Development Status

現在開発中です。

機能や表示内容は今後変更される場合があります。

Currently under development.

Features and interface details may change in future versions.
