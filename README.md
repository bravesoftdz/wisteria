# 藤 -Resizer-

複数の画像を一括して拡大・縮小します.
サイズを指定した後に画像ファイルをウインドウにドラッグするだけなので非常に手軽です.
また、複数の画像を含むフォルダ自体をドラッグすることも可能です.
ファイル名は生成規則を使って自動的に付ける事が出来ます.
3-lobed Lanczos-windowed sinc 補間法で拡大・縮小を行うので最高品質の画像を得ることが出来ます.
HTML を自動生成する機能もあるので、サムネイル付きでウェブに画像を載せるといった用途にも便利です.

本ソフトウェアを利用するためには、以下の事項についての知識及び理解が必要です.

- zipファイルとその解凍方法
- パスと拡張子
- ドラッグ操作

実行ファイルの存在するディレクトリに ini ファイルを作成するので、Vista 以降の場合は Program Files ディレクトリ配下には実行ファイルを配置しないでください.

## 動作確認例がある環境

- Windows XP
- Windows 7 (32bit/64bit)
- Windows 8 (32bit/64bit)
- Windows 10 (64bit)

## 動作不具合の確認例がある環境

- 無し

## 注意

- 実行ファイル(及びショートカット)ではなく、起動したウインドウへ D&D してください.

## 各メジャーバージョンの機能比較表

項目                              |2.x         |3.x (32bit) |3.x (64bit) |4.x
----------------------------------|------------|------------|------------|------------
バイナリサイズ                    |○          |△          |×          |×
標準での読込対応画像形式数        |× (IL)     |○ (WIC)    |○ (WIC     |○ (WIC)
Susie プラグイン対応              |○          |○          |○          |○
AtoB Converter プラグイン対応     |○          |○          |×          |○
JPEG サブサンプリング無効圧縮対応 |○          |○          |○          |×
並列処理対応                      |×          |○          |○          |○
タスクバーでの進捗表示            |×          |○          |○          |○
High DPI 対応                     |×          |×          |×          |○
参考: ビルドに使う Delphi の版数  |Delphi 2007 |Delphi XE2  |Delphi XE2  |Delphi 10.2
