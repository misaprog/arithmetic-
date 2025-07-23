# arithmetic
spam_amount = 0
ここでは spam_amount という変数に 0 を代入しています。

0 は数字ですね。

✅ type(spam_amount) の意味
type() は Python に「この変数（または値）のデータ型は何ですか？」と質問する関数です。

つまり：

python
コピーする
編集する
type(spam_amount)
は、

👉 「spam_amount って、どんな種類の値？」と聞いているのと同じです。

✅ 出力結果：int
python
コピーする
編集する
<class 'int'>
int は **"integer"（整数）**の略です。

つまり、spam_amount は整数型のデータだよとPythonが教えてくれています。

🧠 数値のデータ型にはどんなものがあるの？
データ型	説明	例
int	整数	1, 0, -100
float	小数	3.14, 0.5, -2.71
complex	複素数	2 + 3j（特殊な数学用途）

✅ 確認用の例（試してOK）
python
コピーする
編集する
x = 5
print(type(x))  # <class 'int'>

y = 3.14
print(type(y))  # <class 'float'>
🎯 まとめ
type() は「この値がどんな型か？」を確認する関数。

int は整数型。

Pythonは変数を自動で適切な型として認識してくれる（＝動的型付けと言います）。
