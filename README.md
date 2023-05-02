# Tenycircle.js-document
# ダウンロード
## githubから
ダウンロードして
```html
<script src="pass/to/Tenycircle.min.js"></script>
```
## cdnから
jsdeliverなどで
```html
<script src="https://cdn.jsdelivr.net/gh/Tenycircle-js/Tenycircle.js@main/TenyCircle.min.js"></script>
```
# 使用する方法
`$.メソッド名(引数)`

または

``` $.メソッド名`引数(文字のみ)` ```
# `$.`を省略
```javascript
with ($) {
  //コード
}
```
(推奨されません)
# 各メソッドの説明
# 以下、`$`を省略
## `$.id`メソッド
### 引数 １つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
id`id1`.innerHTML
```
## `$.class`メソッド
### 引数 １つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
class`class1`
```
## `$.name`メソッド
### 引数 １つ string | array
### 返り値 htmlElement | null
### 使用例
```javascript
name`name`
```
