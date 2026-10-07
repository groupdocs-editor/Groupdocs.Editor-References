---
title: "FontSize"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta una dimensione del carattere come unità speciale o valore di lunghezza che specifica la dimensione del carattere, storicamente la larghezza della M maiuscola."
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

Rappresenta una dimensione del carattere come unità speciale o valore di lunghezza, che specifica la dimensione del carattere (storicamente la larghezza della lettera maiuscola \"M\").

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Medium](#Medium) | Dimensione media. |
|
|  | [XxSmall](#XxSmall) | La absolute-size molto piccola |
|
|  | [XSmall](#XSmall) | La absolute-size piccola mediocre |
|
|  | [Small](#Small) | La absolute-size piccola normale |
|
|  | [Large](#Large) | La absolute-size grande normale |
|
|  | [XLarge](#XLarge) | La absolute-size grande mediocre |
|
|  | [XxLarge](#XxLarge) | La absolute-size molto grande |
|
|  | [Larger](#Larger) | Relative-size più grande - il font sarà più grande rispetto al font-size dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave absolute-size sopra. |
|
|  | [Smaller](#Smaller) | Relative-size più piccolo - il font sarà più piccolo rispetto al font-size dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave absolute-size sopra. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isInitial()](#isInitial--) | Indica se questa font-size ha un valore iniziale (Medium) |
|
|  | [getValue()](#getValue--) | Restituisce un valore di questa font-size come stringa |
|
|  | [isLengthDefined()](#isLengthDefined--) | Indica se questa font-size è definita con un valore [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | Un valore di lunghezza, se questa font-size è stata definita con esso, altrimenti viene lanciata un'eccezione |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | Indica se questa font-size è definita con una dimensione assoluta come parola chiave, basata sulla dimensione del carattere predefinita dell'utente (che è medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | Indica se questa font-size è definita con una dimensione relativa come parola chiave. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Determina se questa istanza di font-size è uguale a quella specificata |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa istanza di font-size è uguale a quella specificata non convertita |
|
|  | [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Verifica se due valori "FontSize" sono uguali |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | Verifica se due valori "FontSize" non sono uguali |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Crea una font-size da una lunghezza specificata |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | Tenta di riconoscere una parola chiave specificata come valore di parola chiave corretto di 'font-size' e la restituisce in caso di successo o NULL in caso di fallimento. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


Dimensione media. Valore iniziale.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


La absolute-size molto piccola


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


La absolute-size piccola mediocre


### Small {#Small}
```
public static final FontSize Small
```


La absolute-size piccola normale


### Large {#Large}
```
public static final FontSize Large
```


La absolute-size grande normale


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


La absolute-size grande mediocre


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


La absolute-size molto grande


### Larger {#Larger}
```
public static final FontSize Larger
```


Relative-size più grande - il font sarà più grande rispetto al font-size dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave absolute-size sopra.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


Relative-size più piccolo - il font sarà più piccolo rispetto al font-size dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave absolute-size sopra.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


Indica se questa font-size ha un valore iniziale (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


Restituisce un valore di questa font-size come stringa


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


Indica se questa font-size è definita con un valore [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


Un valore di lunghezza, se questa font-size è stata definita con esso, altrimenti viene lanciata un'eccezione


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


Indica se questa font-size è definita con una dimensione assoluta come parola chiave, basata sulla dimensione del carattere predefinita dell'utente (che è medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


Indica se questa font-size è definita con una dimensione relativa come parola chiave. Il carattere sarà più grande o più piccolo rispetto alla dimensione del carattere dell'elemento genitore, approssimativamente secondo il rapporto usato per separare le parole chiave di dimensione assoluta.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


Determina se questa istanza di font-size è uguale a quella specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Altra istanza di font-size |
|

**Returns:**
boolean - true se sono uguali, false altrimenti

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa istanza di font-size è uguale a quella specificata non convertita


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza di font-size non convertita, può essere null |
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

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


Verifica se due valori "FontSize" sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Primo valore da verificare |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Secondo valore da verificare |
|

**Returns:**
boolean - true se sono uguali, false altrimenti

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


Verifica se due valori "FontSize" non sono uguali


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Primo valore da verificare |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Secondo valore da verificare |
|

**Returns:**
boolean - false se sono uguali, true altrimenti

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


Crea una font-size da una lunghezza specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Un valore di lunghezza, non può essere senza unità o negativo |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


Tenta di riconoscere una parola chiave specificata come valore di parola chiave corretto di 'font-size' e la restituisce in caso di successo o NULL in caso di fallimento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parola chiave | java.lang.String | Una parola chiave da analizzare |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | Risultato, l'analisi è stata eseguita con successo, altrimenti #Medium.Medium |
|

**Returns:**
boolean - true se l'analisi è stata eseguita con successo, false altrimenti

