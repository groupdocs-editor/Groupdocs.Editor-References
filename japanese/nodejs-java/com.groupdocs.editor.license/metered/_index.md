---
title: "従量課金"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "従量課金ライセンスを適用するためのメソッドを提供します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

従量課金ライセンスを適用するためのメソッドを提供します。[従量課金](../https://purchase.groupdocs.com/faqs/licensing/metered)

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metered()](#Metered--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 従量課金キーで製品を有効化します。 |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | 処理された MB の量を取得します。 |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | 消費されたクレジット数を取得します。 |
|
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


従量課金キーで製品を有効化します。


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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | publicKey | java.lang.String | 公開キーです。 |
|
|  | privateKey | java.lang.String | プライベートキーです。 |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


処理された MB の量を取得します。


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


消費されたクレジット数を取得します。


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
java.math.BigDecimal - 既に使用されたクレジットの数

