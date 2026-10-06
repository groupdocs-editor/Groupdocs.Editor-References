---
title: "计量"
second_title: "GroupDocs.Editor for Java API 参考"
description: "提供用于应用 Metered 许可证的方法。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供用于应用 [Metered](../https://purchase.groupdocs.com/faqs/licensing/metered) 许可证的方法。

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 使用 Metered 密钥激活产品。 |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | 检索已处理的 MB 数量。 |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | 检索已消耗的积分数量。 |
|
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


使用 Metered 密钥激活产品。


*** ** * ** ***

> ```
>  Following example demonstrates how to activate product with Metered keys.
>   String publicKey = "Public Key";
>  String privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.setMeteredKey(publicKey, privateKey);
>  
>  
> ```

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | publicKey | java.lang.String | 公钥。 |
|
|  | privateKey | java.lang.String | 私钥。 |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


检索已处理的 MB 数量。


*** ** * ** ***

> ```
>   Following example demonstrates how to retrieve amount of MBs processed.
>     String publicKey = "Public Key";
>   String privateKey = "Private Key";
>
>   Metered metered = new Metered();
>   metered.setMeteredKey(publicKey, privateKey);
>   double mbProcessed = metered.getConsumptionQuantity();
>  
>  
> ```

<br />



**Returns:**
java.math.BigDecimal
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


检索已消耗的积分数量。


*** ** * ** ***

> ```
>   Following example demonstrates how to retrieve count of credits consumed.
>     String publicKey = "Public Key";
>   String privateKey = "Private Key";
>
>   Metered metered = new Metered();
>   metered.setMeteredKey(publicKey, privateKey);
>   double creditsConsumed = metered.getConsumptionCredit();
>  
>  
> ```

<br />



**Returns:**
java.math.BigDecimal - 已使用积分的计数

