---
title: "TextDecorationLineType"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta i tipi di linea di decorazione del testo: underline, underscore, overline e line-through (barrato)"
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

Rappresenta i tipi di linea di decorazione del testo: sottolineatura (underscore), sovralineatura e barratura (strikethrough).

<br />

*** ** * ** ***

Struct immutabile. Simile a https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [None](#None) | Non produce alcuna decorazione del testo. |
|
|  | [Underline](#Underline) | Ogni riga di testo è sottolineata. |
|
|  | [Overline](#Overline) | Ogni riga di testo ha una linea sopra di essa. |
|
|  | [LineThrough](#LineThrough) | Ogni riga di testo ha una linea al centro. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica se questa istanza ha un valore iniziale \\u2014 Nessuno |
|
|  | [isUnderline()](#isUnderline--) | Indica se la sottolineatura (underscore) è abilitata |
|
|  | [isOverline()](#isOverline--) | Indica se la sovralineatura è abilitata |
|
|  | [isLineThrough()](#isLineThrough--) | Indica se la barratura (strikethrough) è abilitata |
|
|  | [getValue()](#getValue--) | Restituisce un valore di tutti i flag di questa istanza come testo |
|
|  | [toString()](#toString--) | Restituisce un valore di tutti i flag di questa istanza come testo |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Indica se questa istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) è uguale a quella specificata |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | Indica se questa istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) è uguale a quella specificata non convertita |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash di questa istanza |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Verifica se due valori "TextDecorationLineType" sono uguali |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Verifica se due valori "TextDecorationLineType" non sono uguali |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | Crea e restituisce un'istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) con flag, definiti dai parametri specificati |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | Tenta di analizzare una stringa specificata e restituisce un'istanza valida di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Combina (unisce) due tipi di linea specificati e produce un nuovo tipo di linea risultante, in cui i flag sono uniti (unione) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Sottrae il secondo tipo di linea specificato dal primo tipo di linea specificato e produce un nuovo tipo di linea risultante, in cui sono presenti solo i flag del primo operando che non si trovano nel secondo operando (differenza) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | Restituisce l'intersezione tra il primo e il secondo tipo di linea, dove sono abilitati solo i flag che sono abilitati simultaneamente in entrambi gli operandi. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | Converti un byte specifico (ottetto a 8 bit) al corrispondente [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), lancia un'eccezione se il cast è non valido |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


Non produce alcuna decorazione del testo. Valore iniziale.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


Ogni riga di testo è sottolineata.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


Ogni riga di testo ha una linea sopra di essa.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


Ogni riga di testo ha una linea al centro.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica se questa istanza ha un valore iniziale \\u2014 Nessuno


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


Indica se la sottolineatura (underscore) è abilitata


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


Indica se la sovralineatura è abilitata


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


Indica se la barratura (strikethrough) è abilitata


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Restituisce un valore di tutti i flag di questa istanza come testo


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Restituisce un valore di tutti i flag di questa istanza come testo


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


Indica se questa istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) è uguale a quella specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Altra istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
boolean -  true  se sono uguali,  false  altrimenti

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Indica se questa istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) è uguale a quella specificata non convertita


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | java.lang.Object | Altra istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), convertita in oggetto |
|

**Returns:**
boolean -  true  se sono uguali,  false  altrimenti

### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash di questa istanza


**Returns:**
int - Codice hash intero con segno

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


Verifica se due valori "TextDecorationLineType" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primo operando da verificare |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Secondo operando da verificare |
|

**Returns:**
boolean -  true  se sono uguali,  false  altrimenti

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


Verifica se due valori "TextDecorationLineType" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primo operando da verificare |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Secondo operando da verificare |
|

**Returns:**
boolean -  true  se sono diversi,  false  altrimenti

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


Crea e restituisce un'istanza di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) con flag, definiti dai parametri specificati


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | isUnderline | boolean | Determina se un flag di sottolineatura è abilitato o meno |
|
|  | isOverline | boolean | Determina se un flag di sovralineatura è abilitato o meno |
|
|  | isLineThrough | boolean | Determina se un flag di barrato è abilitato o meno |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


Tenta di analizzare una stringa specificata e restituisce un'istanza valida di [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | input | java.lang.String | Stringa di input |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Risultato. Se l'analisi non è valida, è un valore #None.None |
|

**Returns:**
boolean -  true  se l'analisi ha avuto successo,  false  in caso di errore

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


Combina (unisce) due tipi di linea specificati e produce un nuovo tipo di linea risultante, in cui i flag sono uniti (unione)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primo operando di tipo linea |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Secondo operando di tipo linea |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


Sottrae il secondo tipo di linea specificato dal primo tipo di linea specificato e produce un nuovo tipo di linea risultante, in cui sono presenti solo i flag del primo operando che non si trovano nel secondo operando (differenza)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primo operando di tipo linea |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Secondo operando di tipo linea |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


Restituisce un'intersezione tra i primi e i secondi tipi di linea, dove sono abilitati solo quei flag che sono abilitati simultaneamente in entrambi gli operandi. Ha la priorità più alta tra tutti gli operatori (superiore a unione e differenza)


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Primo operando di tipo linea |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | Secondo operando di tipo linea |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


Converti un byte specifico (ottetto a 8 bit) al corrispondente [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype), lancia un'eccezione se il cast è non valido


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | ottetto | byte | Un ottetto a 8 bit (bitfield), dove i primi 5 bit sono zero, mentre gli ultimi 3 indicano flag |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
