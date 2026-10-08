---
title: "MailMessageOutput"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Controla qué partes del mensaje de correo deben entregarse al procesamiento de salida"
type: docs
weight: 960
url: /es/net/groupdocs.editor.options/mailmessageoutput/
---
## MailMessageOutput enumeration

Controla qué partes del mensaje de correo deben entregarse al procesamiento de salida

```csharp
[Flags]
public enum MailMessageOutput
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | Ninguna de las partes del mensaje de correo electrónico será procesada |
| Body | `1` | Procesar el cuerpo del mensaje de correo |
| Subject | `2` | Procesar el asunto del mensaje de correo |
| Date | `4` | Procesar la fecha y hora en que se entregó el mensaje |
| To | `8` | Procesar todos los destinatarios del mensaje de correo |
| Cc | `10` | Procesar todos los destinatarios CC del mensaje de correo |
| Bcc | `20` | Procesar todos los destinatarios CCO del mensaje de correo |
| From | `40` | Procesar el remitente del mensaje de correo |
| Attachments | `80` | Procesar todos los archivos adjuntos del mensaje de correo |
| Metadata | `100` | Procesar todos los demás metadatos técnicos (sensibilidad, prioridad, codificación, MIME, X-Mailer, etc) |
| Common | `7B` | Salida común - cuerpo con todos los metadatos principales |
| All | `1FF` | Salida completa - cuerpo con todos los metadatos |

### Ver también

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
