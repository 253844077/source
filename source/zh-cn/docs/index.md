title: 一级协议
---

## 开合窗帘(Curtain)

### 可操作数据点

open,close,pause,percent,speed,direction...

### 升级协议

#### 1、协议升级

``` bash
    {
        "cmdType":"update",
        "content":{
            "operation":{"attribute":"protocol","protocolVersion":"1.1"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
     }
```

#### 2、设备升级

``` bash
    {
        "cmdType":"update",
        "content":{
            "operation":{"attribute":"device","deviceVersion":"1.1"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

### 操作协议

#### 1、打开窗帘

``` bash
    {
        "cmdType":"control",
        "content":{
            "operation":{"attribute":"open","value":"open"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

#### 2、关闭窗帘

``` bash
    {
        "cmdType":"control",
        "content":{
            "operation":{"attribute":"close","value":"close"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

#### 3、暂停窗帘

``` bash
    {
        "cmdType":"control",
        "content":{
            "operation":{"attribute":"pause","value":"pause"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

#### 4、百分比打开

``` bash
    {
        "cmdType":"control",
        "content":{
            "operation":{"attribute":"percent","value":55}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

### 设置协议

1、设置速度

``` bash
    {
        "cmdType":"setup",
        "content":{
            "operation":{"attribute":"speed","value":2}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

2、反向

``` bash
    {
        "cmdType":"setup",
        "content":{
            "operation":{"attribute":"reverse","value":"reverse"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

### 查询协议

批量查询

1、查询窗帘控制属性值

``` bash
    {
        "cmdType":"query",
        "content":{
            "list":{"attribute":"control"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```

2、查询窗帘设置属性值

``` bash
    {
        "cmdType":"query",
        "content":{
            "list":{"attribute":"setup"}
        },
        " messageId:"7312dshfuijfsdfldals8312321"
    }
```


