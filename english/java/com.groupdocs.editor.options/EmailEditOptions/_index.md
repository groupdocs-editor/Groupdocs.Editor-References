---
title: EmailEditOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for editing documents in the different electronic mail email formats
type: docs
weight: 13
url: /java/com.groupdocs.editor.options/emaileditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class EmailEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents in the different electronic mail (email) formats
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailEditOptions()](#EmailEditOptions--) | Initializes a new instance of the [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) class, where all options are set to their default values |
| [EmailEditOptions(int mailMessageOutput)](#EmailEditOptions-int-) | Initializes a new instance of the [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) class with  MailMessageOutput (\#getMailMessageOutput.getMailMessageOutput/\#setMailMessageOutput.setMailMessageOutput) parameter |
## Methods

| Method | Description |
| --- | --- |
| [getMailMessageOutput()](#getMailMessageOutput--) | Allows to control which parts of the mail message should be delivered to the output [EditableDocument](../../com.groupdocs.editor/editabledocument) and then to the emitted HTML |
| [setMailMessageOutput(int value)](#setMailMessageOutput-int-) | Allows to control which parts of the mail message should be delivered to the output [EditableDocument](../../com.groupdocs.editor/editabledocument) and then to the emitted HTML |
### EmailEditOptions() {#EmailEditOptions--}
```
public EmailEditOptions()
```


Initializes a new instance of the [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) class, where all options are set to their default values

### EmailEditOptions(int mailMessageOutput) {#EmailEditOptions-int-}
```
public EmailEditOptions(int mailMessageOutput)
```


Initializes a new instance of the [EmailEditOptions](../../com.groupdocs.editor.options/emaileditoptions) class with  MailMessageOutput (\#getMailMessageOutput.getMailMessageOutput/\#setMailMessageOutput.setMailMessageOutput) parameter

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mailMessageOutput | int | The mail message output, which also can be specified through the property |

### getMailMessageOutput() {#getMailMessageOutput--}
```
public final int getMailMessageOutput()
```


Allows to control which parts of the mail message should be delivered to the output [EditableDocument](../../com.groupdocs.editor/editabledocument) and then to the emitted HTML

Value: Flagged enum that controls the parts of the mail message, which should be processed. Default value is  MailMessageOutput.All 

**Returns:**
int
### setMailMessageOutput(int value) {#setMailMessageOutput-int-}
```
public final void setMailMessageOutput(int value)
```


Allows to control which parts of the mail message should be delivered to the output [EditableDocument](../../com.groupdocs.editor/editabledocument) and then to the emitted HTML

Value: Flagged enum that controls the parts of the mail message, which should be processed. Default value is  MailMessageOutput.All 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

