---
title: "FontStyle"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Definieert hoe het lettertype moet worden gestyled met een normale, cursieve of schuine vorm uit zijn font-family."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Definieert hoe het lettertype moet worden gestyled met: een normale, cursieve of schuine stijl uit zijn lettertypefamilie.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Normal](#Normal) | Selecteert een lettertype dat als normaal is geclassificeerd binnen een font-family. |
|
|  | [Italic](#Italic) | Selecteert een lettertype dat als cursief is geclassificeerd. |
|
|  | [Oblique](#Oblique) | Selecteert een lettertype dat als schuin is geclassificeerd. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [isInitial()](#isInitial--) | Geeft aan of deze font-style een initiële waarde heeft (Normaal) |
|
|  | [getValue()](#getValue--) | Retourneert een waarde van deze font-style als een string. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Bepaalt of deze font-style instantie gelijk is aan de opgegeven. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of deze font-style instantie gelijk is aan de opgegeven niet-gecastte. |
|
|  | [hashCode()](#hashCode--) | Retourneert een hashcode voor deze instantie. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Controleert of twee "FontStyle" waarden gelijk zijn. |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Controleert of twee "FontStyle" waarden niet gelijk zijn. |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Probeert een opgegeven trefwoord te herkennen als een juiste trefwoordwaarde van 'font-style' en retourneert het bij succes of NULL bij falen. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Selecteert een lettertype dat als normaal is geclassificeerd binnen een font-family. Initiële waarde.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Selecteert een lettertype dat als cursief is geclassificeerd. Als er geen cursieve versie van het lettertype beschikbaar is, wordt er in plaats daarvan een als schuin geclassificeerd gebruikt. Als geen van beide beschikbaar is, wordt de stijl kunstmatig gesimuleerd.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Selecteert een lettertype dat als schuin is geclassificeerd. Als er geen schuine versie van het lettertype beschikbaar is, wordt er in plaats daarvan een als cursief geclassificeerd gebruikt. Als geen van beide beschikbaar is, wordt de stijl kunstmatig gesimuleerd.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Geeft aan of deze font-style een initiële waarde heeft (Normaal)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Retourneert een waarde van deze font-style als een string.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Bepaalt of deze font-style instantie gelijk is aan de opgegeven.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Andere font-style instantie |
|

**Returns:**
boolean - true als ze gelijk zijn, false anders

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of deze font-style instantie gelijk is aan de opgegeven niet-gecastte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | obj | java.lang.Object | Andere niet-gecastte font-style instantie, kan null zijn |
|

**Returns:**
boolean - true als ze gelijk zijn, false als ze niet gelijk zijn, null of van een ander type

### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor deze instantie.


**Returns:**
int - Hash-code als een ondertekend geheel getal

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Controleert of twee "FontStyle" waarden gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Eerste waarde om te controleren |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Tweede waarde om te controleren |
|

**Returns:**
boolean - true als ze gelijk zijn, false anders

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Controleert of twee "FontStyle" waarden niet gelijk zijn.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Eerste waarde om te controleren |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Tweede waarde om te controleren |
|

**Returns:**
boolean - false als ze gelijk zijn, true anders

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Probeert een opgegeven trefwoord te herkennen als een juiste trefwoordwaarde van 'font-style' en retourneert het bij succes of NULL bij falen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | trefwoord | java.lang.String | Een trefwoord om te parseren |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Resultaat, als parseren succesvol was, of #Normal.Normal anders |
|

**Returns:**
boolean - true als parseren succesvol was, false anders

