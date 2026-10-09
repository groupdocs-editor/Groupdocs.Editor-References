---
title: "EmailSaveOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de correo electrónico"
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.editor.options/emailsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class EmailSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar documentos de correo electrónico (email)

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [EmailSaveOptions()](#EmailSaveOptions--) | Inicializa una nueva instancia de la clase [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), donde todas las opciones se establecen en sus valores predeterminados |
|
|  | [EmailSaveOptions(int mailMessageOutput)](#EmailSaveOptions-int-) | Inicializa una nueva instancia de la clase [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) con |
MailMessageOutput
parámetro (#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput)
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMailMessageOutput()](#getMailMessageOutput--) | Permite controlar qué partes del mensaje de correo deben entregarse al documento de correo de salida, que será generado y guardado con el método [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
|  | [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Permite controlar qué partes del mensaje de correo deben entregarse al documento de correo de salida, que será generado y guardado con el método [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-) |
|
### EmailSaveOptions() {#EmailSaveOptions--}
```
public EmailSaveOptions()
```


Inicializa una nueva instancia de la clase [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions), donde todas las opciones se establecen en sus valores predeterminados


### EmailSaveOptions(int mailMessageOutput) {#EmailSaveOptions-int-}
```
public EmailSaveOptions(int mailMessageOutput)
```


Inicializa una nueva instancia de la clase [EmailSaveOptions](../../com.groupdocs.editor.options/emailsaveoptions) con
MailMessageOutput
parámetro (#getMailMessageOutput.getMailMessageOutput/#setMailMessageOutput.setMailMessageOutput)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | mailMessageOutput | int | La salida del mensaje de correo, que también puede especificarse a través de la propiedad |
|

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Permite controlar qué partes del mensaje de correo deben entregarse al documento de correo de salida, que será generado y guardado con el método [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Valor: enumeración con banderas que controla las partes del mensaje de correo que deben procesarse. El valor predeterminado es MailMessageOutput.All


**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Permite controlar qué partes del mensaje de correo deben entregarse al documento de correo de salida, que será generado y guardado con el método [Editor.save(EditableDocument,Stream,ISaveOptions)](../../com.groupdocs.editor/editor#save-EditableDocument-Stream-ISaveOptions-)
Valor: enumeración con banderas que controla las partes del mensaje de correo que deben procesarse. El valor predeterminado es MailMessageOutput.All


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

