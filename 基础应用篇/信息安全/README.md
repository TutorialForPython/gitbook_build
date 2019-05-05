# 摘要加密与数字签名

python标准库`hashlib`和`hmac`提供了基本的摘要算法.在python3.6中还新增了一个标准库`secrets `用于生成用于加密的随机数据.

而加密和签名算法则需要第三方工具如`PyCrypto`,`itsdangerous`支持.


## 更新信息

+ 2019-05-05

    + '加密算法'更新了ECC和RSA的算法部分
    + '数字签名'新增了JWT相关内容