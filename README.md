# Howler.js-test

## Front
### Howler-test.html
Howler.jsを使ってブラウザ内で音声の再生テスト
 - 画面クリックで再生

## back
動画抽出や音声抽出に必要なライブラリ
 - youtube-dl.exe
 - ffmpeg.exe

動画の抽出
``` youtube-dl https://www.youtube.com/watch?v=BMb5IetESGE&ab_channel=Ado -f mp4 ```
上記では不可。チャンネル名の左、&を消す。

 ``` youtube-dl https://www.youtube.com/watch?v=BMb5IetESGEab_channel=Ado -f mp4 ```
 これで動画の抽出を行える。

 音声の抽出
 ``` youtube-dl https://www.youtube.com/watch?v=BMb5IetESGEab_channel=Ado -x --audio-format mp3 ```
 &を消さなくてもいけるっぽいが、&を消さないとDLの速度が遅い。

 上記コマンドはライブラリがあるディレクトリで実行する。