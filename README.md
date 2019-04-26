# VAD
VAD (Voice Activity Detection) tool 

-- Sorry! Currently Japanese only --

VAD 20190426版
 (vad20190426.tar.gz)
 2019/4/26 修正版（speech_msecの未定義でのエラーが発生する現象への修正版）

配布物の説明<p>
[0] 概要<br>
　本ツールは、音声ファイル内の音声区間を検出し、その音声区間の開始時刻や
音声区間長を算出するプログラムです。動作確認環境は以下です。
<ul>
<li> CentOS 5、6</li>
<li> gcc-4.7.3/lib64</li>
<li> python-2.7.3</li>
</ul>

[1] ディレクトリ構成<br>
　vad20160115.tar.gzを解凍すると作成される20160115以下の構成

　doc/        NICTmmcv(VADの実行ファイル）の入出力フォーマットに関する
              ドキュメント。

　model/      NICTmmcvの実行に必要なモデル一式。

　src/        NICTmmcv、および、サンプルスクリプトで使用する
              framesync2txtのソースがあります。

　vad_script/ VADサンプルスクリプト。
              NICTmmcvを使用して、与えられた音声ファイルリストに対し、
              音声区間検出を実行し、検出した音声区間を表示するサンプル
              スクリプトがあります。

[2] コンパイル/インストール方法<br>
  src/000INSTALL.txtを参照してください。

[3] VADサンプルスクリプトの実行<br>
  vad_script/000README.txtを参照してください。

[4] ライセンス<br>
  本ツールは修正版BSDライセンスにて配布いたします。

-以上
