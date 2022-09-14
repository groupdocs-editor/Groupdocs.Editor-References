---
title: PresentationEditOptions
second_title: GroupDocs.Editor for Java API Reference
description: Allows to specify custom options for editing documents of all supportable Presentation PowerPoint-compatible formats
type: docs
weight: 31
url: /java/com.groupdocs.editor.options/presentationeditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class PresentationEditOptions implements IEditOptions
```

Allows to specify custom options for editing documents of all supportable Presentation (PowerPoint-compatible) formats
## Constructors

| Constructor | Description |
| --- | --- |
| [PresentationEditOptions()](#PresentationEditOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSlideNumber()](#getSlideNumber--) | Allows to specify the slide numbers, which should be opened for editing |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Allows to specify the slide numbers, which should be opened for editing |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the hidden slides should be included or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the hidden slides should be included or not. |
### PresentationEditOptions() {#PresentationEditOptions--}
```
public PresentationEditOptions()
```


### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Allows to specify the slide numbers, which should be opened for editing

--------------------

Slide number is a zero-based index of a slide, that allows to specify and select one particular slide from a presentation to edit. If lesser then 0, the first slide will be selected (same as SlideNumber = 0). If greater then amount of all slides in presentation, the last slide will be selected. If input presentation contains only single slide, this option will be ignored, and this single slide will be edited. If trying to open for editing a hidden slide, while  ShowHiddenSlides ([\#getShowHiddenSlides](../../null/\#getShowHiddenSlides)/[\#setShowHiddenSlides(boolean)](../../null/\#setShowHiddenSlides-boolean-)) option is set to 'false', the exception will be thrown.

**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Allows to specify the slide numbers, which should be opened for editing

--------------------

Slide number is a zero-based index of a slide, that allows to specify and select one particular slide from a presentation to edit. If lesser then 0, the first slide will be selected (same as SlideNumber = 0). If greater then amount of all slides in presentation, the last slide will be selected. If input presentation contains only single slide, this option will be ignored, and this single slide will be edited. If trying to open for editing a hidden slide, while  ShowHiddenSlides ([\#getShowHiddenSlides](../../null/\#getShowHiddenSlides)/[\#setShowHiddenSlides(boolean)](../../null/\#setShowHiddenSlides-boolean-)) option is set to 'false', the exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifies whether the hidden slides should be included or not. Default is false - hidden slides are not shown and exception will be thrown while trying to edit them.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the hidden slides should be included or not. Default is false - hidden slides are not shown and exception will be thrown while trying to edit them.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

