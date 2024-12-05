# 追加演習

教材の練習問題の追加演習
完成した場合、担当者に問題にRVすること

RVでは、自身の書いた疑似言語を口頭で説明する。
<div style="page-break-before:always"></div>

## 問題10 偶数判定
引数が`整数型:x`の入力に対して、その値が偶数であれば`true`、そうでなければ`false`を戻り値として返す`関数isEven`を疑似言語で作成せよ。

---

```
[プログラム]
  〇論理型:isEven(整数型:x)
    //続きを以下に記載すること
```


<div style="page-break-before:always"></div>


## 問題20 最大値

引数が`整数型:x,y,z`の入力に対して、最大の値を戻り値として返す`関数max`を疑似言語で作成せよ。

---

```
[プログラム]
  〇整数型:max(整数型:x,整数型:y,整数型:z)
    //続きを以下に記載すること
```

<div style="page-break-before:always"></div>


## 問題30 配列からの最大値

引数が`整数型配列:numArray`の入力に対して、最大の値を戻り値として返す`関数maxFromArray`を疑似言語で作成せよ。このとき、整数型配列は一次元配列とする。

---

```
[プログラム]
  〇整数型:maxFromArray(整数型配列:numArray)
    //続きを以下に記載すること
```

<div style="page-break-before:always"></div>


## 問題30 FizzBuzz

1から1000までの数を以下のルールに従って文字列を出力するプログラムを作成せよ。

ルール:
- 数が3の倍数であれば"Fizz"を出力する。
- 数が5の倍数であれば"Buzz"を出力する。
- 数が3と5両方の倍数であれば"FizzBuzz"を出力する。
- それ以外の数の場合、数値をそのまま出力する。

出力例：`1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz 16 …… `

```
[プログラム]
  //続きを以下に記載すること
```

<div style="page-break-before:always"></div>



## 問題40 再帰関数

以下の関数subProgramが定義されている。
```
[プログラム]
  〇整数型:subProgram(整数型:n)
    if (n < 1)
      return n
    else
      return subProgram(n-1)
    endif
```

`subProgram(10)`の結果となる整数値を回答せよ。

<div style="page-break-before:always"></div>


## 問題50 ソート

引数が`整数型配列:numArray`の入力に対して、**降順**にして並び替えた整数型配列を戻り値として返す`関数descendingOrderSort`を疑似言語で作成せよ。このとき、整数型配列は一次元配列とする。

```
[プログラム]
  〇整数descendingOrderSort型配列:(整数型配列:numArray)
    //続きを以下に記載すること
```


<div style="page-break-before:always"></div>


