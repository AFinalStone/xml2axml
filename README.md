# xml2axml

[xml2axml.jar](out/artifacts/xml2axml_jar/xml2axml.jar)

支持二进制类型的AXML和文本类型的AXML进行相互转换（xml2axml.jar）

* 【encode】把文本类型的AndroidManifest.xml转化为二进制类型的AndroidManifest.xml

```
java -jar xml2axml e [AndroidManifest-readable-in.xml] [AndroidManifest-bin-out.xml]
```

* 【decode】把二进制类型的AndroidManifest.xml转化为文本类型的AndroidManifest.xml

```
java -jar xml2axml d [AndroidManifest-bin-in.xml] [AndroidManifest-readable-out.xml]
```

参考的原项目地址：https://github.com/l741589/xml2axml
