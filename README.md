# examples-fl-chart
Flutter&thinsp;のグラフ用パッケージ&thinsp;[<ins>FL Chart</ins>](https://github.com/imaNNeo/fl_chart)&thinsp;の公式サンプルのWeb用テスト

- 公式リポジトリから用いたもの

  - examples&thinsp;フォルダ（プラットフォームは&thinsp;Web&thinsp;用だけ）

  - パッケージ最新版のソース

    - examples&thinsp;のうち&thinsp;Gauge Chart&thinsp;が、[<ins>pub.dev</ins>](https://pub.dev/packages/fl_chart)&thinsp;にある最新版 `1.2.0` に含まれていないため

- 動作確認環境

  ```
  $ flutter doctor
  Doctor summary (to see all details, run flutter doctor -v):
  [✓] Flutter (Channel stable, 3.44.0, on macOS 26.5 25F71 darwin-x64, locale en-JP)
  ...
  [✓] Chrome - develop for the web
  ```

- 起動時のメモ

  ```
  $ flutter run -d chrome
  Resolving dependencies...
  Downloading packages...
    cli_util 0.4.2 (0.5.1 available)
    go_router 16.3.0 (17.2.3 available)
    google_fonts 6.3.3 (8.1.0 available)
    image 4.8.0 (4.9.0 available)
    matcher 0.12.19 (0.12.20 available)
    meta 1.18.0 (1.18.2 available)
    package_info_plus 9.0.1 (10.1.0 available)
    package_info_plus_platform_interface 3.2.1 (4.1.0 available)
    test_api 0.7.11 (0.7.12 available)
    vector_math 2.2.0 (2.3.0 available)
    win32 5.15.0 (6.3.0 available)
    xml 6.6.1 (7.0.1 available)
  Got dependencies!
  12 packages have newer versions incompatible with dependency constraints.
  Try `flutter pub outdated` for more information.
  Launching lib/main.dart on Chrome in debug mode...
  Waiting for connection from debug service on Chrome...             26.6s

  Flutter run key commands.
  r Hot reload. 🔥🔥🔥
  R Hot restart.
  h List all available interactive commands.
  d Detach (terminate "flutter run" but leave application running).
  c Clear the screen
  q Quit (terminate the application on the device).
  ```

- 起動時の&thinsp;Chrome&thinsp;画面

  <img height=256 src="">
  TODO: ↑ 画像挿入

<br>

---
