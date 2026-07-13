# TELEPHOTONE -テレフォトン

Visible-Light Instrument ── LIDI Standard / by TELEPHONOVISION

画面の発光の強さ(輝度)で音高を送る可視光楽器。型式 TPV-04。

- `index.html` ── 楽器本体(送信部+受信部)
- `tester.html` ── 輝度階調テスター(開発工程1・実効分解能計測ユニット)

## 使い方
1. 送信端末・受信端末それぞれで https://teletone.github.io を開く
2. 主電源を入れる
3. 送信側: WINDOW → CAL LIGHT → TRANSMIT → 鍵盤演奏(またはAUTO PLAY)
4. 受信側: RECEIVE → ROIを発光面に合わせ CAL LIGHTの発光中に CAPTURE

カメラは https 経由でのみ動作します(GitHub Pagesはhttps標準)。

前作: [MABATAKI SIGNAL (TPV-03)](https://mabatakisignal.github.io/)
