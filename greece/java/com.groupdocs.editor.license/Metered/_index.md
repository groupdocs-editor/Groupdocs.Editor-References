---
title: "Μετρημένο"
second_title: "Αναφορά API του GroupDocs.Editor για Java"
description: "Παρέχει μεθόδους για την εφαρμογή της άδειας Μετρημένου."
type: docs
weight: 11
url: /el/java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για την εφαρμογή της άδειας [Μετρημένο](../https://purchase.groupdocs.com/faqs/licensing/metered).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ενεργοποιεί το προϊόν με κλειδιά Μετρημένου. |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Ανακτά το ποσό των επεξεργασμένων MB. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Ανακτά τον αριθμό των καταναλωμένων πόντων. |
|
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ενεργοποιεί το προϊόν με κλειδιά Μετρημένου.


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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | publicKey | java.lang.String | Το δημόσιο κλειδί. |
|
|  | privateKey | java.lang.String | Το ιδιωτικό κλειδί. |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ανακτά το ποσό των επεξεργασμένων MB.


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


Ανακτά τον αριθμό των καταναλωμένων πόντων.


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
java.math.BigDecimal - Αριθμός ήδη χρησιμοποιημένων πόντων

