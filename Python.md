# Python

## 网络

Q 如何对abc%进行urlencode? urlenncode之后值是什么？

A quote_plus('abc%'), 'abc%25'。quote_plus对于数字和字母以及'_.-'不会进行编码，其他都会将其转化为某种编码，目前大多是utf-8编码。

Q 如何访问www.baidu.com？

A r = requests.get('http://www.baidu.com')

Q 如何访问www.baidu.com? 加上参数a=b

A params={'a':'b'}; r = request.get('http://www.baidu.com', params)

Q 如何获取图片？

A 图片需要按照二进制的方式进行保存。保存r.content即可。

Q 如何发起post请求

A r = requests.post(url, params)



