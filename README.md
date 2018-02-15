
# Hidden-in-RedPackage
[这段代码](https://github.com/Oslomayor/Hidden-in-RedPackage/blob/master/sorce.html) 藏了8个数字密码，支付宝口令红包

### 1.参考资料

2016 年的解析 [程序员红包解析](https://www.jianshu.com/p/b1d9180bae35)

一段 JSON

```json
<script type="text/inject-data">%7B%22uid%22%3A%22165580424%22%2C%22procedure%22%3A%22right*3%22%7D</script>
```

在线解析 [bejson](http://www.bejson.com/)

得到

```js
< script type = "text/inject-data" > {
	"uid": "165580424",
	"procedure": "right*3"
} < /script>
```

**165580424** 右移3位，得到密码 **20697553**

### 2. 
