---
title: "ILoadOptions"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Interfaccia comune per tutte le classi di opzioni responsabili del caricamento di documenti di diversi formati"
type: docs
weight: 57
url: /it/nodejs-java/com.groupdocs.editor.options/iloadoptions/
---```
public interface ILoadOptions
```

Common interface for all option classes, responsible for loading documents of
different type formats

## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | In implementing class should allow to set a password for the encoded
password-protected document.
 |
| [setPassword(String value)](#setPassword-java.lang.String-) | In implementing class should allow to set a password for the encoded
password-protected document.
 |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


In implementing class should allow to set a password for the encoded
password-protected document. By default password is not used - string has
a NULL value.


**Returns:**
java.lang.String - 
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


In implementing class should allow to set a password for the encoded
password-protected document. By default password is not used - string has
a NULL value.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

