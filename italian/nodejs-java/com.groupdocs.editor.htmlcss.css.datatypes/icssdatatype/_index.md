---
title: "ICssDataType"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Interfaccia comune per tutti i tipi di dati CSS utilizzati nelle proprietà CSS"
type: docs
weight: 15
url: /it/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Interfaccia comune per tutti i tipi di dati CSS, che sono usati nelle proprietà CSS

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Dovrebbe restituire una rappresentazione stringa predefinita del valore corrente del |
tipo di dato
|
|  | [isDefault()](#isDefault--) | Deve definire se il valore corrente del tipo di dato è quello predefinito |
valore per questo tipo di dato specifico o meno
|
### serializeDefault() {#serializeDefault--}
```
public abstract String serializeDefault()
```


Dovrebbe restituire una rappresentazione stringa predefinita del valore corrente del
tipo di dato


**Returns:**
java.lang.String -
### isDefault() {#isDefault--}
```
public abstract boolean isDefault()
```


Deve definire se il valore corrente del tipo di dato è quello predefinito
valore per questo tipo di dato specifico o meno


**Returns:**
boolean -
