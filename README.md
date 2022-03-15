# window-manager
## 可変ウィンドウ時の座標計算簡易化クラス

可変ウィンドウ時は拡大縮小する場合、図形の座標も可変にする必要がありますが、

仮想ウィンドウ上の座標をx,y関数に通すことで座標を可変させられます

![image](https://user-images.githubusercontent.com/91818705/158425573-17ae9a25-db36-435f-a28c-59d3ffb678c6.png)

![image](https://user-images.githubusercontent.com/91818705/158425427-0c967ade-4549-42be-897a-10bae9208292.png)

- setWindow関数で初期ウィンドウ,仮想ウィンドウの幅高さを設定
- x,y関数で仮想ウィンドウの座標からメインウィンドウの座標へ変換