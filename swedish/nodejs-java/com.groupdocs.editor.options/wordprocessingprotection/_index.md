---
title: "WordProcessingProtection"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Inkapslar dokumentskyddsalternativ för WordProcessing-dokumentet som genereras från HTML"
type: docs
weight: 46
url: /sv/nodejs-java/com.groupdocs.editor.options/wordprocessingprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingProtection
```

Inkapslar dokumentskyddsalternativ för WordProcessing-dokumentet,
som genereras från HTML

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WordProcessingProtection()](#WordProcessingProtection--) | Parameterlös konstruktor - alla parametrar har standardvärden |
|
|  | [WordProcessingProtection(int protectionType, String password)](#WordProcessingProtection-int-java.lang.String-) | Tillåter att ange alla parametrar vid klassinstansiering |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Tillåter att ange en skyddstyp för dokumentet. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Tillåter att ange en skyddstyp för dokumentet. |
|
|  | [getPassword()](#getPassword--) | Lösenordet för att skydda dokumentet med. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Lösenordet för att skydda dokumentet med. |
|
| [convertToAsposeWords(int protectionType)](#convertToAsposeWords-int-) |  |
### WordProcessingProtection() {#WordProcessingProtection--}
```
public WordProcessingProtection()
```


Parameterlös konstruktor - alla parametrar har standardvärden


### WordProcessingProtection(int protectionType, String password) {#WordProcessingProtection-int-java.lang.String-}
```
public WordProcessingProtection(int protectionType, String password)
```


Tillåter att ange alla parametrar vid klassinstansiering


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | protectionType | int | Ange skyddstypen för dokumentet |
|
|  | lösenord | java.lang.String | Ange skyddslösenordet |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Tillåter att ange en skyddstyp för dokumentet. Som standard är den satt till att inte
skydda dokumentet alls.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Tillåter att ange en skyddstyp för dokumentet. Som standard är den satt till att inte
skydda dokumentet alls.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Lösenordet för att skydda dokumentet med. Om null eller tom sträng -
kommer skyddet inte att tillämpas på dokumentet.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Lösenordet för att skydda dokumentet med. Om null eller tom sträng -
kommer skyddet inte att tillämpas på dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### convertToAsposeWords(int protectionType) {#convertToAsposeWords-int-}
```
public static int convertToAsposeWords(int protectionType)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| protectionType | int |  |

**Returns:**
int
