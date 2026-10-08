---
title: "FontType"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en stödbar teckensnittstyp"
type: docs
weight: 360
url: /sv/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Representerar en stödbar teckensnittstyp

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Representerar en EOT (Embedded OpenType)-teckensnittstyp |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Representerar en OTF (OpenType Font)-teckensnittstyp |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | Representerar ett TrueType Collection (TTC)-teckensnitt |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Representerar en TTF (TrueType Font)-teckensnittstyp |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Speciellt värde, som markerar odefinierad, okänd eller ej stödd teckensnittresurs |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Representerar en WOFF (Web Open Font Format)-teckensnittstyp |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Representerar en WOFF2 (Web Open Font Format version 2)-teckensnittstyp |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Returnerar ett CSS-kompatibelt namn för denna teckensnittstyp, som används i @font-face-regeln |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Filnamnstillägg (utan punkttecken) för denna teckensnittstyp |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Typsnittformat för @font-face-format |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Returnerar ett formellt namn för den här typsnittstypen |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | MIME-kod för en viss typsnittstyp |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Returnerar den första typsnittstypen från den angivna mängden som inte är ett \"Undefined\"-värde, annars \"Undefined\"-typsnittstyp (när alla objekt är \"Undefined\") |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Returnerar ett FontType‑värde som motsvarar det angivna CSS‑kompatibla namnet på typsnittstypen |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Returnerar ett FontType‑värde som motsvarar filnamnstillägget som extraheras från det angivna filnamnet |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Returnerar ett FontType‑värde som motsvarar den angivna MIME‑koden |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Bestämmer om detta objekt är lika med den angivna \"FontType\"‑instansen |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Bestämmer om detta objekt är lika med det angivna okastade objektet, som sannolikt är en annan \"FontType\"‑instans |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Returnerar en hashkod som är ett konstant tal för denna specifika värdetyp |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Kontrollerar om två \"FontType\"‑värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Kontrollerar om två \"FontType\"‑värden inte är lika |

### Se även

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
