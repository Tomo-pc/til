# PHP基礎

## echo
phpでの「echo」とはrubyでいう「puts」である。

## 「文字列」と「数値」
rubyと同じく、'Hello World'のようにクォーテーションで囲んだものが文字列となり、<br>
  １や3.14のように囲まないものが数値となる。

## 変数

### 変数の定義
- 頭に「$」記号をつけることによって変数を定義する。
- 「$変数名 = 値;」で様々な値を変数に入れることが出来る。
- 文字列の場合は、「$変数名　= '値';」である。
- 呼び出す時は、「echo $値」とする。

### 変数の更新
#### 文字列の更新
例）<br>
$fruit = 'りんご';　 ←定義<br>
$fruit = 'みかん'; ←更新<br>
となる。
#### 数値の更新
例)<br>
$x = 5;　←定義<br>
$x += 3; ←定義した値に３を足して再定義（更新）<br>
上記のように、「$x = $x + 3」を「$x += 3」に省略できる。

### 文字の連結
- 「.」をつけることによって文字の連結ができる。
- $値.'値'; で文字の連結ができる。
#### 省略化
「.=」でも同じように連結される。
