
>参考的原项目地址：https://github.com/hzw1199/xml2axml  
**当AndroidManifest.xml中要进行UTF-8编码的修改的时候，原项目会出现乱码、加解密异常，本项目主要是为了解决这个问题**

# xml2axml

[xml2axml.jar](out/artifacts/xml2axml_jar)

支持二进制类型的AXML和文本类型的AXML进行相互转换（xml2axml.jar）

* 【encode】把文本类型的AndroidManifest.xml转化为二进制类型的AndroidManifest.xml

```
java -jar xml2axml e [AndroidManifest-readable-in.xml] [AndroidManifest-bin-out.xml]
```

* 【decode】把二进制类型的AndroidManifest.xml转化为文本类型的AndroidManifest.xml

```
java -jar xml2axml d [AndroidManifest-bin-in.xml] [AndroidManifest-readable-out.xml]
```

#### 注意事项

> 如果明文AndroidManifest.xml转二进制AndroidManifest.xml之后
> 重新打包签名失败，可以先解密，修改axml内容，再加密，解密，再加密；再重新打包签名


