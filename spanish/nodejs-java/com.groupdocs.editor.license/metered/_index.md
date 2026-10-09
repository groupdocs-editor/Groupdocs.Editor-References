---
title: "Metered"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Proporciona métodos para aplicar la licencia Metered."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.editor.license/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Proporciona métodos para aplicar la licencia [Metered](../https://purchase.groupdocs.com/faqs/licensing/metered).

<br />

*** ** * ** ***

**Learn more**

* More about licensing: [GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing)
* More about GroupDocs.Editor licensing:[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/editor/java/licensing-and-subscription/)

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [Metered()](#Metered--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activa el producto con claves Metered. |
|
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la cantidad de MB procesados. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Recupera el recuento de créditos consumidos. |
|
### Metered() {#Metered--}
```
public Metered()
```


### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activa el producto con claves Metered.


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | publicKey | java.lang.String | La clave pública. |
|
|  | privateKey | java.lang.String | La clave privada. |
|

### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Recupera la cantidad de MB procesados.


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


Recupera el recuento de créditos consumidos.


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
java.math.BigDecimal - Cantidad de créditos ya utilizados

