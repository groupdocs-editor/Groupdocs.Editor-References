---
title: PresentationSaveOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for generating and saving Presentation PowerPoint-compatible documents
type: docs
weight: 32
url: /java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Allows to specify custom options for generating and saving Presentation (PowerPoint-compatible) documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationSaveOptions()](#PresentationSaveOptions--) | This parameterless constructor creates a new instance of PresentationSaveOptions with PPTX output format (can be modified then through  OutputFormat (\#getOutputFormat.getOutputFormat/\#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property) |
| [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Creates a new instance of PresentationSaveOptions with specified mandatory Presentation output format, while all other parameters are default |
## Methods

| Method | Description |
| --- | --- |
| [getPassword()](#getPassword--) | Allows to specify, modify and obtain the password, which will be used for encoding the resultant Presentation document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Allows to specify, modify and obtain the password, which will be used for encoding the resultant Presentation document. |
| [getSlideNumber()](#getSlideNumber--) | Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior). |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior). |
| [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int)) property, or it should be injected between existing slide and previous one, without replacing its content. |
| [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int)) property, or it should be injected between existing slide and previous one, without replacing its content. |
| [getOutputFormat()](#getOutputFormat--) | Allows to specify a Presentation format, which will be used for saving the document |
| [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Allows to specify a Presentation format, which will be used for saving the document |
| [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Allows to specify an array with 1-based numbers of slides that should be deleted from the presentation during its saving, in case when the edited slide is inserted into existing presentation. |
| [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Allows to specify an array with 1-based numbers of slides that should be deleted from the presentation during its saving, in case when the edited slide is inserted into existing presentation. |
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


This parameterless constructor creates a new instance of PresentationSaveOptions with PPTX output format (can be modified then through  OutputFormat (\#getOutputFormat.getOutputFormat/\#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)

### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Creates a new instance of PresentationSaveOptions with specified mandatory Presentation output format, while all other parameters are default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Mandatory output format, in which the Presentation document should be saved |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Allows to specify, modify and obtain the password, which will be used for encoding the resultant Presentation document. By default is NULL - password will not be set. Set to NULL or empty string in order to remove the password, if it was set previously.

**Returns:**
java.lang.String - 
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Allows to specify, modify and obtain the password, which will be used for encoding the resultant Presentation document. By default is NULL - password will not be set. Set to NULL or empty string in order to remove the password, if it was set previously.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior). Slide number is a 1-based number of a slide in the presentation, loaded in the Editor class. If it is 0 (default value), the new presentation will be created with single edited slide. If it is greater or lesser then zero, and there is valid presentation, loaded in the Editor class, the edited slide, stored inside input EditableDocument instance, will be inserted into this presentation.

--------------------

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
> ```

--------------------

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (\#getInsertAsNewSlide.getInsertAsNewSlide/\#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Allows to insert edited slide into existing presentation instead of creating a new single-slide presentation (default behavior). Slide number is a 1-based number of a slide in the presentation, loaded in the Editor class. If it is 0 (default value), the new presentation will be created with single edited slide. If it is greater or lesser then zero, and there is valid presentation, loaded in the Editor class, the edited slide, stored inside input EditableDocument instance, will be inserted into this presentation.

--------------------

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
> ```

--------------------

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (\#getInsertAsNewSlide.getInsertAsNewSlide/\#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int)) property, or it should be injected between existing slide and previous one, without replacing its content. By default is false \\u2014 existing slide will be replaced. This property is ignored, if value of  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int)) property is set to '0'.

--------------------

By default slide is replaced. This means that if given presentation has 5 slides, and  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int))=4, then 4th slide will be replaced with the new edited slide, while the total amount of slides in presentation (5) will remain untouched. However, if value of this property is set to  *true* , the new edited slide will be injected as 4th slide, and all subsequent slides wil be shifter to the end: "old" 4th slide becomes 5th, and 5th becomes 6th, and the total amount of slides in presentation will be incremented by one and equal to 6.

**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Boolean flag, which specifies whether edited slide should replace the existing slide in original presentation on the position, specified by the  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int)) property, or it should be injected between existing slide and previous one, without replacing its content. By default is false \\u2014 existing slide will be replaced. This property is ignored, if value of  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int)) property is set to '0'.

--------------------

By default slide is replaced. This means that if given presentation has 5 slides, and  SlideNumber (\#getSlideNumber.getSlideNumber/\#setSlideNumber(int).setSlideNumber(int))=4, then 4th slide will be replaced with the new edited slide, while the total amount of slides in presentation (5) will remain untouched. However, if value of this property is set to  *true* , the new edited slide will be injected as 4th slide, and all subsequent slides wil be shifter to the end: "old" 4th slide becomes 5th, and 5th becomes 6th, and the total amount of slides in presentation will be incremented by one and equal to 6.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Allows to specify a Presentation format, which will be used for saving the document

--------------------

Output format is usually set in the constructor of this class, because it is mandatory. This property allows to obtain or modify the output format later, when instance of [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) class was already created.

**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Allows to specify a Presentation format, which will be used for saving the document

--------------------

Output format is usually set in the constructor of this class, because it is mandatory. This property allows to obtain or modify the output format later, when instance of [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) class was already created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Allows to specify an array with 1-based numbers of slides that should be deleted from the presentation during its saving, in case when the edited slide is inserted into existing presentation.When the edited slide is saved not as a new single-slide presentation (default behavior), but instead is saved into an existing presentation (using \#getSlideNumber().getSlideNumber() / \#setSlideNumber(int).setSlideNumber(int)), it is also possible to delete some particular slides from this presentation by specifying their numbers in this array. By default this array is  null  \\u2014 no slides will be deleted. However, when this array is non-null and non-empty, and it contains at least one valid slide number, after the output Presentation document is generated with the content of the edited slide, the slides with specified numbers will be deleted from the presentation right before writing its content to the output stream or file. Slide numbers in this array are 1-based, not 0-based. Invalid numbers (less than 1 or greater than the total number of slides) will be ignored.

**Returns:**
int[] - Array of 1-based slide numbers to delete, or  null  if nothing should be deleted.
### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Allows to specify an array with 1-based numbers of slides that should be deleted from the presentation during its saving, in case when the edited slide is inserted into existing presentation.Slide numbers in this array are 1-based. Invalid numbers will be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | Array of 1-based slide numbers to delete (may be  null  or empty). |

