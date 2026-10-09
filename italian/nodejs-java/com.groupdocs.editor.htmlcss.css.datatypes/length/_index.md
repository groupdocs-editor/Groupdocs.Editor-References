---
title: "Length"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta un valore di lunghezza CSS in qualsiasi unità supportata, inclusa la percentuale e il tipo senza unità."
type: docs
weight: 12
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

Rappresenta un valore di lunghezza CSS in qualsiasi unità supportata, inclusa la percentuale
e tipo senza unità. I valori possono essere interi o float, negativi, zero e
positivi. Struttura immutabile.

*** ** * ** ***


Questo tipo copre i seguenti tipi di dati CSS:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Length()](#Length--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | Zero intero senza unità - valore predefinito, identico al valore predefinito senza parametri |
costruttore
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | Crea e restituisce un'istanza del tipo Length con il numero float specificato |
e unità
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | Crea e restituisce un'istanza del tipo Length con il numero double specificato |
e unità
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | Crea e restituisce un'istanza del tipo Length a partire da un intero specificato |
numero e unità
|
|  | [isUnitlessZero()](#isUnitlessZero--) | Determina se questa istanza è uno zero senza unità o meno. |
|
|  | [isDefault()](#isDefault--) | Indica se questa istanza di Length ha un valore predefinito \u2014 senza unità |
zero.
|
|  | [getUnitType()](#getUnitType--) | Restituisce il tipo di unità di questa istanza di Length. |
|
|  | [isInteger()](#isInteger--) | Indica se il valore numerico di questa istanza di Length era |
originariamente specificato e memorizzato come numero intero (INT32)
|
|  | [isFloat()](#isFloat--) | Indica se il valore numerico di questa istanza di Length era |
originariamente specificato e memorizzato come numero a virgola mobile (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | Restituisce un valore numerico a virgola mobile dell'istanza Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | Restituisce un valore numerico intero di questa istanza Length, se è |
memorizzato internamente come intero, o genera un'eccezione, se era
originariamente memorizzato come numero a virgola mobile.
|
|  | [isAbsolute()](#isAbsolute--) | Ottiene se la lunghezza è fornita in unità assolute. |
|
|  | [isRelative()](#isRelative--) | Ottiene se la lunghezza è fornita in unità relative. |
|
|  | [isZero()](#isZero--) | Determina se il valore numerico di questa lunghezza è un numero zero |
|
|  | [isNegative()](#isNegative--) | Determina se il valore numerico di questa lunghezza è un numero negativo |
|
|  | [isPositive()](#isPositive--) | Determina se il valore numerico di questa lunghezza è un numero positivo |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | Il valore ha tipo senza unità, ma non è zero - positivo o negativo |
number
|
|  | [toPixel()](#toPixel--) | Converte la lunghezza in un numero di pixel, se possibile. |
|
|  | [to(int unit)](#to-int-) | Converte la lunghezza nell'unità specificata, se possibile. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | Restituisce una rappresentazione stringa di questa lunghezza nel tipo di unità specificato. |
|
|  | [serializeDefault()](#serializeDefault--) | Restituisce una rappresentazione stringa di questa lunghezza nella sua forma nativa originale |
forma (come è memorizzata), senza convertire il valore della lunghezza in un'altra
unità di misura
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Definisce se questo valore è uguale all'altra lunghezza specificata |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina se questa lunghezza è uguale all'oggetto specificato |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | Moltiplica la Length fornita per il fattore specificato |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Verifica l'uguaglianza delle due lunghezze fornite. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | Verifica la disuguaglianza delle due lunghezze fornite. |
|
|  | [hashCode()](#hashCode--) | Calcola e restituisce un hash-code di questa istanza di Length combinando |
hash-code del valore e del tipo unit
|
|  | [deepClone()](#deepClone--) | Restituisce una copia completa di questa istanza di Length |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | Prova a analizzare il nome dell'unità specificato e restituisce il valore corrispondente di un |
Enum Unit.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | Prova a analizzare una stringa specificata come valore Length, includendo il suo |
valore numerico e nome dell'unità
|
|  | [parse(String input)](#parse-java.lang.String-) | Analizza e restituisce la stringa specificata come valore Length, includendo il suo |
valore numerico e nome dell'unità, oppure genera un'eccezione in caso di errore
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


Zero intero senza unità - valore predefinito, identico al valore predefinito senza parametri
costruttore


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


Crea e restituisce un'istanza del tipo Length con il numero float specificato
e unità


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | \>Qualsiasi numero float (FP32) |
|
|  | unità | int | Qualsiasi tipo di unità valido |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


Crea e restituisce un'istanza del tipo Length con il numero double specificato
e unità


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Qualsiasi numero double (FP64), che verrà convertito in float (FP32) |
|
|  | unità | int | Qualsiasi tipo di unità valido |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


Crea e restituisce un'istanza del tipo Length a partire da un intero specificato
numero e unità


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Qualsiasi numero intero |
|
|  | unità | int | Qualsiasi tipo di unità valido |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


Determina se questa istanza è zero senza unità o meno. Zero senza unità
è il valore predefinito di questo tipo. Stesso della proprietà IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


Indica se questa istanza di Length ha un valore predefinito \u2014 senza unità
zero. Stesso della proprietà IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


Restituisce il tipo di unità di questa istanza di Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


Indica se il valore numerico di questa istanza di Length era
originariamente specificato e memorizzato come numero intero (INT32)


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


Indica se il valore numerico di questa istanza di Length era
originariamente specificato e memorizzato come numero a virgola mobile (FP32)


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


Restituisce un valore numerico float dell'istanza Length. Non genera mai un
eccezione - converte il valore Integer in Float se necessario.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


Restituisce un valore numerico intero di questa istanza Length, se è
memorizzato internamente come intero, o genera un'eccezione, se era
originariamente memorizzato come numero a virgola mobile.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


Ottiene se la lunghezza è fornita in unità assolute. Una tale lunghezza può essere
convertita in pixel.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Ottiene se la lunghezza è fornita in unità relative. Una tale lunghezza non può essere
convertita in pixel.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


Determina se il valore numerico di questa lunghezza è un numero zero


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


Determina se il valore numerico di questa lunghezza è un numero negativo


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


Determina se il valore numerico di questa lunghezza è un numero positivo


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


Il valore ha tipo senza unità, ma non è zero - positivo o negativo
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


Converte la lunghezza in un numero di pixel, se possibile. Se l'attuale
unità è relativa, verrà sollevata un'eccezione.


**Returns:**
float - Il numero di pixel rappresentato dalla lunghezza corrente.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


Converte la lunghezza nell'unità specificata, se possibile. Se l'attuale o
l'unità specificata è relativa, verrà sollevata un'eccezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | unità | int | L'unità a cui convertire. |
|

**Returns:**
float - Il valore nell'unità specificata della lunghezza corrente.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


Restituisce una rappresentazione stringa di questa lunghezza nel tipo di unità specificato.
Il valore numerico sarà convertito in corrispondenza del cambiamento del tipo di unità.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | unità | int | Unità specificata, a cui questa istanza dovrebbe essere convertita prima di serializzare in stringa. Deve essere valida. Non può essere senza unità. |
|

**Returns:**
java.lang.String - Rappresentazione stringa

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


Restituisce una rappresentazione stringa di questa lunghezza nella sua forma nativa originale
forma (come è memorizzata), senza convertire il valore della lunghezza in un'altra
unità di misura


**Returns:**
java.lang.String - Istanza stringa

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


Definisce se questo valore è uguale all'altra lunghezza specificata


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Altra istanza del tipo Length |
|

**Returns:**
boolean - True se uguale, altrimenti false

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se questa lunghezza è uguale all'oggetto specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Altra istanza del tipo Length, che è incapsulata in System.Object o in qualsiasi altro tipo astratto o interfaccia |
|

**Returns:**
boolean - True se uguale, altrimenti false

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


Moltiplica la Length fornita per il fattore specificato


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - moltiplicando |
|
|  | fattore | int | Intero arbitrario - fattore |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


Verifica l'uguaglianza delle due lunghezze fornite.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'operando di lunghezza sinistro. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'operando di lunghezza destro. |
|

**Returns:**
boolean - True se entrambe le lunghezze sono uguali, altrimenti false.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


Verifica la disuguaglianza delle due lunghezze fornite.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'operando di lunghezza sinistro. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | L'operando di lunghezza destro. |
|

**Returns:**
boolean - True se entrambe le lunghezze non sono uguali, altrimenti false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcola e restituisce un hash-code di questa istanza di Length combinando
hash-code del valore e del tipo unit


**Returns:**
int - Numero intero

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


Restituisce una copia completa di questa istanza di Length


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


Prova a analizzare il nome dell'unità specificato e restituisce il valore corrispondente di un
Enum Unit. Restituisce LengthUnit.Unitless se non riesce a trovare un LengthUnit appropriato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | unitName | java.lang.String | Stringa, che rappresenta il nome di un'unità |
|

**Returns:**
int - Valore dell'enum Unit in ogni caso, LengthUnit.Unitless quando non si trova un'unità appropriata

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


Prova a analizzare una stringa specificata come valore Length, includendo il suo
valore numerico e nome dell'unità


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | input | java.lang.String | Stringa di input, che dovrebbe essere analizzata |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Parametro di output, che contiene il risultato dell'analisi. Se l'analisi non ha successo, contiene un valore predefinito di Length \\u2014 zero senza unità. |
|

**Returns:**
boolean - True se l'analisi ha successo, false se non ha successo

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


Analizza e restituisce la stringa specificata come valore Length, includendo il suo
valore numerico e nome dell'unità, oppure genera un'eccezione in caso di errore


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | input | java.lang.String | Stringa di input, che dovrebbe essere analizzata |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

