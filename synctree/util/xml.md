# Xml

## ● Xml Encode

       입력된 데이터를 XML 형태로 변환할 때 사용

![](../../.gitbook/assets/image%20%28204%29.png)

### ● 예문

![](../../.gitbook/assets/image%20%28388%29.png)

![](../../.gitbook/assets/image%20%28408%29.png)

![](../../.gitbook/assets/image%20%28384%29.png)

### ● 결과

```text
{
  "result": {
    "xmlEncode": "<?xml version=\"1.0\" encoding=\"UTF-8\"?>\n<root><test1>test1</test1><test2>test2</test2></root>\n"
  }
}
```

## ● Xml Decode

        XML형태의 데이터를 decode된 데이터로 변환할 때 사용

![](../../.gitbook/assets/image%20%28101%29.png)

### ● 예문

![](../../.gitbook/assets/image%20%28401%29.png)

![](../../.gitbook/assets/image%20%28403%29.png)

![](../../.gitbook/assets/image%20%28409%29.png)

### ● 결과

```text
{
  "result": {
    "xmlDecode": {
      "root": {
        "test1": "test1",
        "test2": "test2"
      }
    }
  }
}
```

