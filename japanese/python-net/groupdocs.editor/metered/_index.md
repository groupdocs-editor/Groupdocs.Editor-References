---
title: "Metered クラス"
second_title: "GroupDocs.Editor for Python via .NET API References"
description: 
type: docs
url: /ja/python-net/groupdocs.editor/metered/
is_root: false
weight: 110
---


## Metered class

従量課金（使用量に応じた支払い）ライセンスを管理します。

Metered ライセンスは実際の使用量に基づいて請求されます（通常はページまたは
処理されたドキュメント）。公開/非公開キーのペアを一度だけ設定します
アプリケーションの起動時に、ラッパーは使用状況を GroupDocs に報告します
バックグラウンドでライセンスサーバーに

Metered 型は次のメンバーを公開します:

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_consumption_credit](/editor/python-net/groupdocs.editor/metered/get_consumption_credit/) | 現在のキーに対する残りのメータークレジットを返します。 |
| [get_consumption_quantity](/editor/python-net/groupdocs.editor/metered/get_consumption_quantity/) | これまでに消費された合計メーター量を返します。 |
| [set_metered_key](/editor/python-net/groupdocs.editor/metered/set_metered_key/#public_key-private_key) | 指定された公開/非公開キーのペアでメーター課金を有効化します。 |

### 参照
* module [`groupdocs.editor`](/editor/python-net/groupdocs.editor/)
