---
title: "Metered"
second_title: "GroupDocs.Editor for Java API संदर्भ"
description: "Metered लाइसेंस को लागू करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

[Metered](../https://purchase.groupdocs.com/faqs/licensing/metered) लाइसेंस को लागू करने के लिए मेथड्स प्रदान करता है।

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Metered()](#Metered--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered कुंजियों के साथ उत्पाद को सक्रिय करता है। |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | प्रोसेस किए गए MBs की मात्रा प्राप्त करता है। |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | उपयोग किए गए क्रेडिट्स की गिनती प्राप्त करता है। |
|
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered कुंजियों के साथ उत्पाद को सक्रिय करता है।


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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | publicKey | java.lang.String | सार्वजनिक कुंजी। |
|
|  | privateKey | java.lang.String | निजी कुंजी। |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


प्रोसेस किए गए MBs की मात्रा प्राप्त करता है।


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


उपयोग किए गए क्रेडिट्स की गिनती प्राप्त करता है।


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
java.math.BigDecimal - पहले उपयोग किए गए क्रेडिट्स की गिनती

