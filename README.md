# ruby_grammar：rubyの基本文法などをまとめたもの

* if文の基本の書き方
 ```
 if x > 10 
  x = x + 1
 end
 ```

* 後置ifの書き方
```
x += 1 if x > 10
```

* ifの条件分岐
```
if x > 10
  x += 1
elsif x == 10
  x += 2
else
 x += 3
end
```

* 繰り返しのeach文
```
numbers.each do |number|
  puts number
end
```

* 配列:複数オブジェクトの代入 (0から始まるインデックス番号が振られている)
```
Names = ["Lalisa", "Rose"]
puts names[0,1]
```

* ハッシュ：複数の値をキーと関連付けて管理する方法。nameやageがキー、=>以下が値にあたる。
```
user = {"name" => Rose, "age" => 27}
puts user["name"]
```

* メソッドの定義
```
def 任意のメソッド名
  任意の処理
end
```


