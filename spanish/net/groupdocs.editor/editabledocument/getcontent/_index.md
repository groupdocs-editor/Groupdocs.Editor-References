---
title: "GetContent"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Devuelve el contenido completo del documento HTML como un flujo de bytes al escribir este contenido en el flujo especificado con la codificación de texto indicada"
type: docs
weight: 130
url: /es/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

Devuelve el contenido completo del documento HTML como un flujo de bytes al escribir este contenido en el flujo especificado con la codificación de texto indicada

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Parameter | Descripción |
| --- | --- |
| TStream | Cualquier implementación de Stream |
| storage | Flujo de bytes no nulo que admite escritura |
| encoding | Codificación de texto no nula, que debe aplicarse al escribir contenido de texto en el *storage* especificado |

### Valor devuelto

Instancia del *almacenamiento* especificado

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Alguno de los argumentos de entrada es nulo |
| ArgumentException | El flujo especificado no es escribible |

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

Devuelve el contenido completo del documento HTML como una cadena.

```csharp
public string GetContent()
```

### Valor devuelto

Cadena que contiene el contenido del documento HTML

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

Devuelve el contenido completo del documento HTML como una cadena, donde los enlaces a los recursos externos contienen la plantilla especificada con marcadores de posición.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| externalImagesTemplate | String | A través de este parámetro el usuario puede especificar una plantilla de cadena con un marcador de posición, que se aplicará a los enlaces de todas las imágenes externas en los elementos IMG, que estarán presentes en la cadena HTML resultante. Si es NULL o vacío, la plantilla no se añadirá y solo se presentarán los nombres de archivo puros en el marcado HTML resultante. Si la plantilla es inválida, se tratará como un prefijo, de modo que los nombres de archivo se concatenarán al final de la misma. |
| externalCssTemplate | String | A través de este parámetro se puede especificar una plantilla de cadena con un marcador de posición, que se añadirá a los enlaces de todas las hojas de estilo externas en los elementos LINK, que estarán presentes en la cadena HTML resultante. Si es NULL o está vacío, la plantilla no se añadirá y solo se mostrarán los nombres de archivo en el marcado HTML resultante. Si la plantilla es inválida, se tratará como un prefijo, de modo que los nombres de archivo se concatenarán al final de la misma. |

### Valor devuelto

Cadena que contiene el contenido del documento HTML con enlaces, ajustado a los recursos externos

### Ver también

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
