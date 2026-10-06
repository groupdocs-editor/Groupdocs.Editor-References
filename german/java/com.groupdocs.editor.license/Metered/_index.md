---
title: "Meterbasiert"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Methoden zum Anwenden einer meterbasierten Lizenz bereit."
type: docs
weight: 11
url: /de/java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Stellt Methoden zum Anwenden einer [Metered](../https://purchase.groupdocs.com/faqs/licensing/metered) Lizenz bereit.

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aktiviert das Produkt mit meterbasierten Schlüsseln. |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Ruft die Menge der verarbeiteten MB ab. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Ruft die Anzahl der verbrauchten Credits ab. |
|
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Aktiviert das Produkt mit meterbasierten Schlüsseln.


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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | publicKey | java.lang.String | Der öffentliche Schlüssel. |
|
|  | privateKey | java.lang.String | Der private Schlüssel. |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ruft die Menge der verarbeiteten MB ab.


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


Ruft die Anzahl der verbrauchten Credits ab.


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
java.math.BigDecimal - Anzahl der bereits verbrauchten Credits

