#Useful Public webAPI collected
> not sure it will works when you check it since some of these API are not real public.

#IP

http://pv.sohu.com/cityjson

- req
```
GET method
```
- res
```
var returnCitySN = {"cip": "123.456.789.123", "cid": "310000", "cname": "上海市"};
```


#reqbody

http://httpbin.org/anything

- req
```
any method
```
- res
```
{
  "args": {}, 
  "data": "", 
  "files": {}, 
  "form": {}, 
  "headers": {
    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9", 
    "Accept-Encoding": "gzip, deflate", 
    "Accept-Language": "en,zh-CN;q=0.9,zh;q=0.8", 
    "Host": "httpbin.org", 
    "Upgrade-Insecure-Requests": "1", 
    "User-Agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/80.0.3987.122 Safari/537.36 OPR/67.0.3575.53", 
    "X-Amzn-Trace-Id": "Root=1-5f15c02f-a5ea8df8c76369abcdd12cb4"
  }, 
  "json": null, 
  "method": "GET", 
  "origin": "180.169.137.171", 
  "url": "http://httpbin.org/anything"
}
```