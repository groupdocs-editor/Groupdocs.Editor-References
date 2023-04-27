---
title: TextDecorationLineType
second_title: GroupDocs.Editor for .NET API Reference
description: Represents types of the text decoration line underline underscore overline and linethrough strikethrough
type: docs
weight: 320
url: /net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Represents types of the text decoration line: underline (underscore), overline, and line-through (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Properties

| Name | Description |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Indicates whether this instance has an initial value — None |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Indicates whether line-through (strikethrough) is enabled |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Indicates whether overline is enabled |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Indicates whether underline (underscore) is enabled |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Returns a value of all flags in this instance as text |

## Methods

| Name | Description |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Creates and returns a [`TextDecorationLineType`](../textdecorationlinetype) instance with flags, defined by the specified parameters |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Indicates whether this [`TextDecorationLineType`](../textdecorationlinetype) instance is equal to specified uncasted |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Indicates whether this [`TextDecorationLineType`](../textdecorationlinetype) instance is equal to specified |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Returns a hash-code of this instance |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Returns a value of all flags in this instance as text |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Tries to parse a specified string and return a valid [`TextDecorationLineType`](../textdecorationlinetype) instance |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Combines (merges) two specified line types and produces new resultant line type, where flags are merged (union) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Returns an intersection between first and second line types, where only those flags are enabled, which are enabled simultaneously in both operands. Has the highest priority between all operators (higher then union and difference) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Checks whether two "TextDecorationLineType" values are equal |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Casts specific Byte (8-bit octet) to the corresponding [`TextDecorationLineType`](../textdecorationlinetype), throws exception if casting is invalid (2 operators) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Checks whether two "TextDecorationLineType" values are not equal |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Subtracts second specified line type from the first specified line type and produces new resultant line type, where are present only those flags from the first operand, which are not found in the second operand (difference) |

## Fields

| Name | Description |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Each line of text has a line through the middle. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Produces no text decoration. Initial value. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Each line of text has a line above it. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Each line of text is underlined. |

### Remarks

Immutable struct. Similar to the https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### See Also

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
