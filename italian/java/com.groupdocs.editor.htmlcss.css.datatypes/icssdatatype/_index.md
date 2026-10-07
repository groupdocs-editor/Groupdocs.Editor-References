---
title: "ICssDataType"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Interfaccia comune per tutti i tipi di dati CSS utilizzati nelle proprietà CSS"
type: docs
weight: 15
url: /it/java/com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public interface ICssDataType extends System.IEquatable<ICssDataType>
```

Interfaccia comune per tutti i tipi di dati CSS, utilizzati nelle proprietà CSS

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [serializeDefault()](#serializeDefault--) | Dovrebbe restituire una rappresentazione stringa predefinita del valore corrente del |
tipo di dato
|
|  | [isDefault()](#isDefault--) | Dovrebbe definire se il valore corrente del tipo di dato è quello predefinito |
valore per questo specifico tipo di dato o meno
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


Dovrebbe definire se il valore corrente del tipo di dato è quello predefinito
valore per questo specifico tipo di dato o meno


**Returns:**
boolean -
