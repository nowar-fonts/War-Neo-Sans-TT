# Archived

Official WotLK classic is coming with modern typographical technique. The OpenType/TT variant is no longer needed.

# War Neo Sans (OpenType/TT)

War Neo Sans, font packs for _World of Warcraft_ and _WoW Classic_ that support all client languages. War Sans is subsetted [Nowar Neo Sans](https://github.com/nowar-fonts/Nowar-Neo-Sans).

## Character Set

* WoWG (WoW Global)
  + covers all characters allowed in WoW character names;
  + supports commonly used characters in Latin, Cyrillic, Greek scripts, and Chinese, Japanese, Korean languages.
* WoWC (WoW Chinese), subset of WoWG
  + covers all characters allowed in Latin and Cyrillic character names, and almost all characters in Chinese character names (except non-radical characters in URO+);
  + supports commonly used characters in Latin, Cyrillic, Greek scripts, and Chinese, Japanese languages.

## Download the Fonts

[Latest release at GitHub](https://github.com/nowar-fonts/War-Neo-Sans-TT/releases)

Mirrors: [Gitee (release repo)](https://gitee.com/nowar-fonts/War-Neo-Sans-TT)

War Neo Sans is shipped in 4 weights and 7 regional variants, with several features.

### Weights

* 300: Light
* 400: Regular
* 500: Medium
* 700: Bold

### Regional Variants

Bliz and Neut are “standard variants” with regional Chinese character orthographies. Character set: WoWG.

|      | European and 한국어 | 简体中文       | 繁體中文 | Note                                       |
| ---- | ------------------- | -------------- | -------- | ------------------------------------------ |
| Bliz | Mainland China (UI) | Mainland China | Taiwan   | Acts like WoW’s default fallback setting.  |
| Neut | Classical (UI)      | Mainland China | Taiwan   | Prefers classical orthography on fallback. |

CL is the “classical variant” with classical Chinese character orthography (aka Kāngxī Dictionary forms). Character set: WoWG.

|    | European and 한국어 | 中文      |
| -- | ------------------- | --------- |
| CL | Classical (UI)      | Classical |

PSimp and PSimpChat are special variants for 繁體中文 that remap traditional Chinese character to simplified ones. Character set: WoWG.

| | Common Fonts | 繁體中文 Text, Combat and Tooltip Fonts | 繁體中文 Chat Fonts | European, 简体中文 and 한국어 |
| --------- | ----------------------------- | ------------------------- | ------------------------- | --- |
| PSimp     | Mainland China (UI, Remapped) | Mainland China (Remapped) | Mainland China            | N/A |
| PSimpChat | Mainland China (UI, Remapped) | Mainland China (Remapped) | Mainland China (Remapped) | N/A |

GBK and Big5 are “subset variants”, which are designed for 简体中文 and 繁體中文 respectively, and occupy less disk space. Character set: WoWC.

|      | Common Fonts        | 简体中文       | 繁體中文 | European and 한국어 |
| ---- | ------------------- | -------------- | -------- | ------------------- |
| GBK  | Mainland China (UI) | Mainland China | N/A      | N/A                 |
| Big5 | Taiwan (UI)         | N/A            | Taiwan   | N/A                 |

* European: English, Español (AL), Português, Deutsch, Español (EU), Français, Italiano, and Русский.
* UI: Ambiguous punctations are treated as Western; CJK puctations are half-width.
* Common fonts: `FRIZQT__` and `ARIALN`, which are hard-coded in some addons.

### Features

| Tag | Name        | Description                                                            |
| --- | ----------- | ---------------------------------------------------------------------- |
| OSF | Oldstyle    | Oldstyle (non-lining), propotional figure.                             |
| RP  | Roleplaying | `丶` (U+4E36) is mapped to the same glyph as `·` (U+00B7, MIDDLE DOT). |
| SC  | Smallcaps   | Small capitals for Latin.                                              |

Pre-built feature variants: `Bliz,OSF`, `Bliz,RP`, `Bliz,SC`.

## How to Build

Same as [Nowar Sans](https://github.com/nowar-fonts/Nowar-Sans#how-to-build). Note that you don’t need Source Han Sans files (they are already included in the repo).

## Credit

Latin, Greek and Cyrillic characters are from [Roboto](https://github.com/google/roboto) by Google.

CJK Ideographs, Kana and Hangul are from [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) by Adobe.

The traditional Chinese to simplified Chinese conversion table is from [Open Chinese Convert project](https://github.com/BYVoid/OpenCC).
