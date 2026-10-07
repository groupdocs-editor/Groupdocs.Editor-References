---
title: "EmailEditOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para editar documentos en los diferentes formatos de correo electrónico"
type: docs
weight: 14
url: /es/java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Permite especificar opciones personalizadas para editar documentos en los diferentes formatos de correo electrónico (email)

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EmailEditOptions()](#EmailEditOptions--) | Inicializa una nueva instancia de la clase [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), donde todas las opciones se establecen a sus valores predeterminados |
|
|  | [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Inicializa una nueva instancia de la clase [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) con |
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parámetro
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Permite controlar qué partes del mensaje de correo deben entregarse a la salida [EditableDocument](../../com.groupdocs.editor/editabledocument) y luego al HTML generado |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Permite controlar qué partes del mensaje de correo deben entregarse a la salida [EditableDocument](../../com.groupdocs.editor/editabledocument) y luego al HTML generado |
|
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Inicializa una nueva instancia de la clase [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions), donde todas las opciones se establecen a sus valores predeterminados


### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Inicializa una nueva instancia de la clase [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) con
MailMessageOutput
(#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput) parámetro


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mailMessageOutput | int | La salida del mensaje de correo, que también puede especificarse a través de la propiedad |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Permite controlar qué partes del mensaje de correo deben entregarse a la salida [EditableDocument](../../com.groupdocs.editor/editabledocument) y luego al HTML generado
Valor: enumeración con banderas que controla las partes del mensaje de correo que deben procesarse. El valor predeterminado es MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Permite controlar qué partes del mensaje de correo deben entregarse a la salida [EditableDocument](../../com.groupdocs.editor/editabledocument) y luego al HTML generado
Valor: enumeración con banderas que controla las partes del mensaje de correo que deben procesarse. El valor predeterminado es MailMessageOutput.All


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

