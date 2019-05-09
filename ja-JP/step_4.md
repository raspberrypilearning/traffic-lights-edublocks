## LEDの制御

1. デスクトップからEduBlocksを開きます。

2. **gpiozero**をクリックします。ドロップダウンで、**一般**をクリックします。 `をgpiozero import *`からドラッグしてください。ワークスペースにブロックします。
    
    ![](images/edublocks1.png)

3. **出力**をクリックします。ドロップダウン**gpiozero** **LED**をクリックします。 `led = LED（ピン）`インポートブロックの下のワークスペースにブロックします。 変数の名前を`led`から変更します。 `赤`と変更`ピン` | `22`に移動します。

4. `led.on`でドラッグしてください。ブロックし、前のブロックの下にドッキングします。 `on`を変更してください。 `blink`にドロップダウンします。 コードブロックは次のようになります。
    
    ![](images/edublocks2.png)

5. 今すぐ**Run**をクリックします。ボタンを押してコードを実行します。 赤いLEDが点滅するはずです。

6. 他の2つのライトを導入するためにいくつかのLEDブロックを追加し、それらを異なる速度で点滅させます：
    
    ![](images/edublocks3.png)

7. コードをもう一度実行すると、3つのライトが異なる速度で点滅していることがわかります。

8. 大きい数字でライトを点滅させるのが遅くなると、どの数字が速くなるでしょうか？ あなたのライトが速く点滅するようにしてください。