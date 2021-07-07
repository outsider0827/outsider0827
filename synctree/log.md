# Log

## ● Info

        info 레벨의 로그를 서버에 기록할 때 사용

![](../.gitbook/assets/image%20%28243%29.png)

### ● 예문

![](../.gitbook/assets/image%20%28401%29.png)

![](../.gitbook/assets/image%20%28383%29.png)

### ● 결과

```text
{
  "result": "resultData"
}

// Console 

[YY.MM.DD hh:mm:ss] [INFO] Info Message
```

## ● Debug

        info 레벨의 로그를 서버에 기록할 때 사용

![](../.gitbook/assets/image%20%28306%29.png)

### ● 예문

![](../.gitbook/assets/image%20%28417%29.png)

![](../.gitbook/assets/image%20%28408%29.png)

### ● 결과

```text
{
  "result": "resultData"
}

// Console 

[YY.MM.DD hh:mm:ss] [DEBUG] request:{"request":{"header":{"X-SYNCTREE-PLAN-ENVIRONMENT":"dev","X-SYNCTREE-REVISION-ID":"e19666876544e44b69bd8fc4c2bad6523d7ae66b1ba049b0014ebb3fe6e8876e","X-SYNCTREE-BIZUNIT-VERSION":"1.0","X-SYNCTREE-PLAN-ID":"33b859014cf93e29f4206620353f24b43fdbf6c2be7c2c9f94829a10f37f4626","X-SYNCTREE-PLAN-TEST-MODE":"bizunit","CONTENT-TYPE":"application\/json","USER-AGENT":"GuzzleHttp\/6.2.1 curl\/7.58.0 PHP\/7.3.19-1+ubuntu18.04.1+deb.sury.org+1","X-AMZN-TRACE-ID":"Root=1-6018ee65-602172e07f00b1e323928c74","HOST":"seoul.synctreengine.com:8443","X-FORWARDED-PORT":"8443","X-FORWARDED-PROTO":"https","X-FORWARDED-FOR":"13.209.187.36","CONTENT-LENGTH":"0"},"body":[]}}
```

## ● Error

        info 레벨의 로그를 서버에 기록할 때 사용

![](../.gitbook/assets/image%20%28262%29.png)

### ● 예문

![](../.gitbook/assets/image%20%28403%29.png)

![](../.gitbook/assets/image%20%28429%29.png)

### ● 결과

```text
{
  "result": "resultData"
}

// Console 

[YY.MM.DD hh:mm:ss] [ERROR] Error Message
```

