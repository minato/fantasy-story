# キャラクター設定

このディレクトリには、物語に登場する人物やキャラクターの詳細な設定が格納されています。

## 含まれる内容

- キャラクターの基本情報（名前、年齢、外見など）
- 背景（生い立ち、家族関係など）
- 性格と動機
- 能力や特技
- 所持品や装備
- 関係する他のキャラクターとの繋がり
- キャラクターの成長や変化

## ディレクトリ構成

- `heroes/` - 主人公や英雄的な役割を持つキャラクター
- `witches/` - 八大魔女や魔女として登場するキャラクター

## キャラクターシート形式

各キャラクターのファイルは以下のような形式で記述することを推奨します：

```markdown
# キャラクター名

![キャラクター画像があれば]()

## 基本情報
- **種族:** 
- **年齢:** 
- **性別:** 
- **職業/役割:** 

## 外見
（外見の詳細な説明）

## 性格
（性格や行動パターンの説明）

## 背景
（生い立ちや歴史）

## 能力と特技
（特殊能力や得意なことの説明）

## 関連キャラクター
- [関連キャラクター名](../path/to/character.md) - 関係性の説明

## 登場する物語
- [物語タイトル](../../stories/path/to/story.md)
```