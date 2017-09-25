## extract formdata

適用在處理要送 "https://course.nctu.edu.tw/index.asp" 的 formdata 資料。
將 "https://portal.nctu.edu.tw/portal/relay.php?D=cos" 出來的 HTML 處理成 url 格式，

### 如何安裝

先裝 node.js

安裝 dependencies
```sh
npm install
```

pipe 要 parse 的 HTML 進去
```sh
echo HTML | node extractFormdata.js
```
