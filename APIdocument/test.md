---
title: material
---
### 接口说明
- 输出所有可以借用的物资，包括他的数目，所属，简介等

### 接口地址
```bash
http://yb.upc.edu.cn:8086/material
- 请求方法：Get
- 返回：json
```

### 接口限制
- 授权需要：否
- 访问权限：无限制
- 频次限制：无限制
### 注意事项
- 需要你先授权
- 还有什么其他的要求以后会补上
### 请求参数
- 无
### 成功返回
    [
    {
      "id":1,
      "name":"名字",
      "organization":"易班",
      "description":"描述",
      "number":2,
      "totalNumber":2,
      "status":true
      }
      ......
      //可以有多个数据
      ]
### 错误返回
    {
      "code":-1,
      "message":"没有登陆"
    }
#### 反馈
- [欢迎您和我们联系]:https://github.com/upcyiban
