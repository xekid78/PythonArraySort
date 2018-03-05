# PythonArraySort
配列のソート

## 処理
配列をsorted関数を使ってソートします。

## コード
```
numbers = [3,6,1,2,5,4]

print(numbers)
print()

print("*** 昇順 ***")
print(sorted(numbers))
print()

print("*** 降順 ***")
print(sorted(numbers,  reverse = True))
```

## 出力結果  
```
[3, 6, 1, 2, 5, 4]

*** 昇順 ***
[1, 2, 3, 4, 5, 6]

*** 降順 ***
[6, 5, 4, 3, 2, 1]
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Python 3.6.4 |
