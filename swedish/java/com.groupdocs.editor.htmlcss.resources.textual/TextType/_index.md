---
title: "TextType"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar en stödbart textresurstyp"
type: docs
weight: 12
url: /sv/java/com.groupdocs.editor.htmlcss.resources.textual/texttype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class TextType implements IResourceType
```

Representerar en stödbart textresurstyp

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextType()](#TextType--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | Speciellt värde som markerar odefinierad, okänd eller ej stödjande text |
resurs
|
|  | [getCss()](#getCss--) | CSS-typ för den textuella resursen |
|
|  | [getXml()](#getXml--) | XML-typ för den textuella resursen |
|
|  | [getFormalName()](#getFormalName--) | Returnerar ett formellt namn för den här textuella resurstypen |
|
|  | [getFileExtension()](#getFileExtension--) | Filändelse (utan inledande punkt) för en viss text |
resurs
|
|  | [getMimeCode()](#getMimeCode--) | MIME-kod för en specifik textresurstyp |
|
|  | [equals(TextType other)](#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Bestämmer om detta objekt är lika med angiven "TextType" |
instans
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om detta objekt är lika med angivet okastat objekt, |
vilket förmodligen är en annan "TextType"-instans
|
|  | [op_Equality(TextType first, TextType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definierar om två specifika "TextType"-instanser är lika |
|
|  | [op_Inequality(TextType first, TextType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-) | Definierar om två specifika "TextType"-instanser inte är lika |
|
|  | [hashCode()](#hashCode--) | Returnerar en hashkod, som är ett konstant tal för detta specifika värde |
typ
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | Returnerar TextType‑värde, som motsvarar filnamnstillägg, som extraheras från angivet filnamn med filändelse eller ren filändelse |
|
### TextType() {#TextType--}
```
public TextType()
```


### getUndefined() {#getUndefined--}
```
public static TextType getUndefined()
```


Speciellt värde som markerar odefinierad, okänd eller ej stödjande text
resurs


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getCss() {#getCss--}
```
public static TextType getCss()
```


CSS-typ för den textuella resursen


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getXml() {#getXml--}
```
public static TextType getXml()
```


XML-typ för den textuella resursen


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


Returnerar ett formellt namn för den här textuella resurstypen


**Returns:**
java.lang.String
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


Filändelse (utan inledande punkt) för en viss text
resurs


**Returns:**
java.lang.String
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


MIME-kod för en specifik textresurstyp


**Returns:**
java.lang.String
### equals(TextType other) {#equals-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public final boolean equals(TextType other)
```


Bestämmer om detta objekt är lika med angiven "TextType"
instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Annan TextType‑instans som ska jämföras med denna för likhet |
|

**Returns:**
boolesk - Returnerar true om de är lika eller false om de är olika

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om detta objekt är lika med angivet okastat objekt,
vilket förmodligen är en annan "TextType"-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Annan TextType‑instans som är inbäddad i ett objekt |
|

**Returns:**
boolesk - Returnerar true om de är lika eller false om de är olika

### op_Equality(TextType first, TextType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Equality(TextType first, TextType second)
```


Definierar om två specifika "TextType"-instanser är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Första TextType‑instansen |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Andra TextType‑instansen |
|

**Returns:**
boolesk - Returnerar true om de är lika eller false om de är olika

### op_Inequality(TextType first, TextType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.textual.TextType-com.groupdocs.editor.htmlcss.resources.textual.TextType-}
```
public static boolean op_Inequality(TextType first, TextType second)
```


Definierar om två specifika "TextType"-instanser inte är lika


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | first | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Första TextType‑instansen |
|
|  | second | [TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) | Andra TextType‑instansen |
|

**Returns:**
boolesk - Returnerar true om de är olika eller false om de är lika

### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod, som är ett konstant tal för detta specifika värde
typ


**Returns:**
int - Signerat 4‑byte heltal. Returnerar 0 om detta objekt har standardvärde.

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static TextType parseFromFilenameWithExtension(String filename)
```


Returnerar TextType‑värde, som motsvarar filnamnstillägg, som extraheras från angivet filnamn med filändelse eller ren filändelse


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filnamn | java.lang.String | Filnamn med filändelse, kan vara relativ eller absolut sökväg, eller ren filändelse |
|

**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype) - Parsed TextType instance on success or TextType.Undefined on failure

