---
title: "FontWeight"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "La proprietà Font-weight imposta il peso o il grassetto del carattere."
type: docs
weight: 12
url: /it/java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

La proprietà Font-weight imposta il peso (o il grassetto) del carattere. I pesi disponibili dipendono dalla famiglia di caratteri attualmente impostata.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Lighter](#Lighter) | Un peso del carattere relativo più leggero rispetto all'elemento genitore |
|
|  | [Bolder](#Bolder) | Un peso del carattere relativo più pesante rispetto all'elemento genitore |
|
|  | [Normal](#Normal) | Peso del carattere normale. |
|
|  | [Bold](#Bold) | Peso del carattere grassetto. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica se questa font-size ha un valore iniziale (Medium) |
|
|  | [getNumber()](#getNumber--) | Restituisce un numero - valore intero compreso tra 1 e 1000, inclusi, che descrive il grassetto del carattere, oppure genera un'eccezione, se il grassetto corrente non è assoluto, ma relativo |
|
|  | [isAbsolute()](#isAbsolute--) | Indica se questa istanza di font-weight memorizza un valore assoluto del peso (grassetto) del carattere, come numero intero |
|
|  | [isRelative()](#isRelative--) | Indica se questa istanza di font-weight memorizza un valore relativo del peso (grassetto) del carattere - rispetto al grassetto dell'elemento genitore |
|
|  | [getValue()](#getValue--) | Restituisce il valore di questo font-weight come stringa |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Determina se le istanze specificate di FontWeight sono uguali |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza di FontWeight è uguale a quella specificata non castata |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Verifica se due valori \"FontWeight\" sono uguali |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | Verifica se due valori \"FontWeight\" non sono uguali |
|
|  | [fromNumber(int number)](#fromNumber-int-) | Crea un font-weight da un numero specificato |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | Tenta di analizzare una stringa specificata e restituisce un'istanza valida di FontWeight in caso di successo |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


Un peso del carattere relativo più leggero rispetto all'elemento genitore


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


Un peso del carattere relativo più pesante rispetto all'elemento genitore


### Normal {#Normal}
```
public static final FontWeight Normal
```


Peso del carattere normale. Uguale a 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


Peso del carattere grassetto. Uguale a 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica se questa font-size ha un valore iniziale (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


Restituisce un numero - valore intero compreso tra 1 e 1000, inclusi, che descrive il grassetto del carattere, oppure genera un'eccezione, se il grassetto corrente non è assoluto, ma relativo


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Indica se questa istanza di font-weight memorizza un valore assoluto del peso (grassetto) del carattere, come numero intero


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Indica se questa istanza di font-weight memorizza un valore relativo del peso (grassetto) del carattere - rispetto al grassetto dell'elemento genitore


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Restituisce il valore di questo font-weight come stringa


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


Determina se le istanze specificate di FontWeight sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Altra istanza di FontWeight per verificare l'uguaglianza |
|

**Returns:**
boolean - true se sono uguali, false se sono diversi

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza di FontWeight è uguale a quella specificata non castata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza di FontWeight non castata, può essere null |
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

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


Verifica se due valori \"FontWeight\" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Primo valore da verificare |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Secondo valore da verificare |
|

**Returns:**
boolean - true se sono uguali, false altrimenti

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


Verifica se due valori \"FontWeight\" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Primo valore da verificare |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Secondo valore da verificare |
|

**Returns:**
boolean - false se sono uguali, true altrimenti

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


Crea un font-weight da un numero specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | number | int | Intero senza segno, deve rientrare nell'intervallo [1..1000] |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


Tenta di analizzare una stringa specificata e restituisce un'istanza valida di FontWeight in caso di successo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | input | java.lang.String | Stringa di input da analizzare |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | Valore FontWeight valido in caso di successo o #Normal.Normal in caso di fallimento |
|

**Returns:**
boolean - Successo (true) o fallimento (false) dell'analisi

