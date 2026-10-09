---
title: "LengthUnit"
second_title: "Node.js 用 GroupDocs.Editor (Java 経由) API リファレンス"
description: "サポートされているすべての長さ単位"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/lengthunit/
---
**Inheritance:**
java.lang.Object
```
public class LengthUnit
```

サポートされているすべての長さ単位


*** ** * ** ***

<https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units>

<br />


## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Unitless](#Unitless) | Unitless - 定義された長さ単位がありません。 |
|
|  | [Px](#Px) | ピクセル。 |
|
|  | [Em](#Em) | Em。 |
|
|  | [Ex](#Ex) | Ex（x 長さ）。 |
|
|  | [Cm](#Cm) | センチメートル。 |
|
|  | [Mm](#Mm) | ミリメートル。 |
|
|  | [In](#In) | インチ。 |
|
|  | [Pt](#Pt) | ポイント。 |
|
|  | [Pc](#Pc) | パイカ。 |
|
|  | [Ch](#Ch) | Ch。 |
|
|  | [Rem](#Rem) | Rem。 |
|
|  | [Vw](#Vw) | Vw - ビューポートの幅。 |
|
|  | [Vh](#Vh) | Vh - ビューポートの高さ。 |
|
|  | [Vmin](#Vmin) | Vmin。 |
|
|  | [Vmax](#Vmax) | Vmax。 |
|
|  | [Percent](#Percent) | この値は固定（外部）値に対して相対的で、文脈です |
依存。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getUnit()](#getUnit--) |  |
| [getUnits()](#getUnits--) |  |
### Unitless {#Unitless}
```
public static final int Unitless
```


単位なし - 定義された長さの単位がありません。デフォルト値。


### Px {#Px}
```
public static final int Px
```


ピクセル。表示デバイスに対して相対的です。画面表示の場合、通常は
ディスプレイのデバイスピクセル（ドット）1つです。


### Em {#Em}
```
public static final int Em
```


Em。 この単位は要素の計算されたフォントサイズを表します。


### Ex {#Ex}
```
public static final int Ex
```


Ex（x-長さ）。この単位は要素のx高さを表します
フォント。'x'文字を含むフォントでは、通常これは
フォントの小文字の高さです; 多くのフォントで 1ex \\u2248 0.5em です。


### Cm {#Cm}
```
public static final int Cm
```


Cm。1センチメートル（10ミリメートル）です。


### Mm {#Mm}
```
public static final int Mm
```


Mm。1ミリメートルです。


### In {#In}
```
public static final int In
```


In。1インチ（2.54センチメートル）です。


### Pt {#Pt}
```
public static final int Pt
```


Pt。1ポイントはインチの1/72、または0.353 mmです。


### Pc {#Pc}
```
public static final int Pc
```


Pc。1パイカ（12ポイント）です。


### Ch {#Ch}
```
public static final int Ch
```


Ch。 この単位は幅、より正確には前進幅を表します
測定値、文字グリフ '0'（ゼロ、Unicode文字 U+0030）の
要素のフォントです。


### Rem {#Rem}
```
public static final int Rem
```


Rem。 この単位はルート要素（例:
 \<html\> 要素のフォントサイズ）のフォントサイズに使用される場合
このルート要素では、初期値を表します。


### Vw {#Vw}
```
public static final int Vw
```


Vw - ビューポート幅。ビューポート幅の1/100です。


### Vh {#Vh}
```
public static final int Vh
```


Vh - ビューポート高さ。ビューポート高さの1/100です。


### Vmin {#Vmin}
```
public static final int Vmin
```


Vmin。高さと幅の最小値の1/100です
ビューポートの。


### Vmax {#Vmax}
```
public static final int Vmax
```


Vmax。高さと幅の最大値の1/100です
ビューポートの。


### Percent {#Percent}
```
public static final int Percent
```


この値は固定（外部）値に対して相対的で、文脈です
依存。1% = 外部値の 1/100。


### getUnit() {#getUnit--}
```
public static Integer[] getUnit()
```




**Returns:**
java.lang.Integer[]
### getUnits() {#getUnits--}
```
public static Map<Integer,String> getUnits()
```




**Returns:**
java.util.Map<java.lang.Integer,java.lang.String>
