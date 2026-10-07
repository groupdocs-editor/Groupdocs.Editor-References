---
title: "FontStyle"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Definisce come il carattere deve essere stilizzato con una variante normale, corsiva o obliqua dalla sua famiglia di caratteri."
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

Definisce come il carattere deve essere stilizzato: un carattere normale, corsivo o obliquo dalla sua famiglia di caratteri.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Normal](#Normal) | Seleziona un carattere classificato come normale all'interno di una famiglia di caratteri. |
|
|  | [Italic](#Italic) | Seleziona un carattere classificato come corsivo. |
|
|  | [Oblique](#Oblique) | Seleziona un carattere classificato come obliquo. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica se questo font-style ha un valore iniziale (Normale) |
|
|  | [getValue()](#getValue--) | Restituisce un valore di questo stile di carattere come stringa |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Determina se questa istanza di font-style è uguale a quella specificata |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza di font-style è uguale a quella specificata non convertita |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Verifica se due valori "FontStyle" sono uguali |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | Verifica se due valori "FontStyle" non sono uguali |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | Cerca di riconoscere una parola chiave specificata come valore corretto della proprietà 'font-style' e la restituisce in caso di successo o NULL in caso di fallimento. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


Seleziona un carattere classificato come normale all'interno di una famiglia di caratteri. Valore iniziale.


### Italic {#Italic}
```
public static final FontStyle Italic
```


Seleziona un carattere classificato come corsivo. Se non è disponibile una versione corsiva del carattere, se ne utilizza una classificata come obliqua. Se nessuna delle due è disponibile, lo stile viene simulato artificialmente.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


Seleziona un carattere classificato come obliquo. Se non è disponibile una versione obliqua del carattere, se ne utilizza una classificata come corsiva. Se nessuna delle due è disponibile, lo stile viene simulato artificialmente.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica se questo font-style ha un valore iniziale (Normale)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Restituisce un valore di questo stile di carattere come stringa


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


Determina se questa istanza di font-style è uguale a quella specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Altra istanza di font-style |
|

**Returns:**
boolean - true se sono uguali, false altrimenti

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza di font-style è uguale a quella specificata non convertita


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza di font-style non castata, può essere null |
|

**Returns:**
boolean - true se sono uguali, false se non uguali, null o di altro tipo

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza


**Returns:**
int - Hash-code come intero con segno

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


Verifica se due valori "FontStyle" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Primo valore da verificare |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Secondo valore da verificare |
|

**Returns:**
boolean - true se sono uguali, false altrimenti

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


Verifica se due valori "FontStyle" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Primo valore da verificare |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Secondo valore da verificare |
|

**Returns:**
boolean - false se sono uguali, true altrimenti

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


Cerca di riconoscere una parola chiave specificata come valore corretto della proprietà 'font-style' e la restituisce in caso di successo o NULL in caso di fallimento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parola chiave | java.lang.String | Una parola chiave da analizzare |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | Risultato, se l'analisi è stata eseguita con successo, o #Normal.Normal altrimenti |
|

**Returns:**
boolean - true se l'analisi è stata eseguita con successo, false altrimenti

