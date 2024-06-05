---
title: Metered
second_title: GroupDocs.Editor for Node.js via Java API Reference
description: Provides methods for applying  Metered license.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods for applying [Metered][] license.

--------------------

**Learn more**

 *  More about licensing: [GroupDocs Licensing FAQ][]
 *  More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/editor/java/licensing-and-subscription/
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methods

| Method | Description |
| --- | --- |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activates product with Metered keys. |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Retrieves amount of MBs processed. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves count of credits consumed. |
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activates product with Metered keys.

--------------------

> ```
> Following example demonstrates how to activate product with Metered keys.
>  
>  String publicKey = "Public Key";
>  String privateKey = "Private Key";
>  Metered metered = new Metered();
>  metered.setMeteredKey(publicKey, privateKey);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | The public key. |
| privateKey | java.lang.String | The private key. |

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Retrieves amount of MBs processed.

--------------------

> ```
> Following example demonstrates how to retrieve amount of MBs processed.
>   
>   String publicKey = "Public Key";
>   String privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.setMeteredKey(publicKey, privateKey);
>   double mbProcessed = metered.getConsumptionQuantity();
> ```

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Retrieves count of credits consumed.

--------------------

> ```
> Following example demonstrates how to retrieve count of credits consumed.
>   
>   String publicKey = "Public Key";
>   String privateKey = "Private Key";
> 
>   Metered metered = new Metered();
>   metered.setMeteredKey(publicKey, privateKey);
>   double creditsConsumed = metered.getConsumptionCredit();
> ```

**Returns:**
double - Count of already used credits
