# adguardhome针对互联网工作者的允许列表

互联网工作者需要使用公众号后台、百度统计后台等，而面向普通用户的列表都是宁可错杀原则都给屏蔽了，这对开发人员和运营人员造成不小的困扰。这个列表可以避免这些问题。

**普通用户非运营工作者、开发者请勿使用，以免失去屏蔽效果**

## 添加方法

在adguardhome中的「过滤器」->「DNS允许列表」添加下面地址

```
https://raw.githubusercontent.com/zhheo/adguardhome-developer-allowlist/main/allowlist.txt
```

如果无法读取，可以使用能够访问的cdn获取列表。

```
https://cdn1.tianli0.top/gh/zhheo/adguardhome-developer-allowlist@main/allowlist.txt
```

## 适用范围

仅适用于中国大陆
