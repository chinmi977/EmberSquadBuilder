# EmberSquadBuilder
Ember:Obsidian-Protocol Squad editor.

## Concept
no application server.  
work on smartphone Web browser.  

## Environment
- CSS Framework  
  [BULMA](https://bulma.io/)
- Server  
  any Web Servers.  
  currentry, work on github-pages.  

## Files
```
┬─ index.html
│    Main content.
├─ LabelDict.json
│    Language dictionary file for labels.
├─ LICENSE
│    LICENSE
├─ PartsData_RDL_en.json
│    RDL Parts data information file for English.
├─ PartsData_RDL_ja.json
│    RDL Parts data information file for Japanese.
├─ PartsData_RDL_zh-CN.json
│    RDL Parts data information file for Simplified Chinese.
├─ PartsData_RDL_zh-TW.json
│    RDL Parts data information file for Traditional Chinese.
│    This file is temporary. The content is the same as the English file.
└─ README.md
     This file.
```

## Parts Data File Naming Rule
PartsData_${Faction}_${Language}.json

Faction:[RDL|UN|GoF]  
Language:[en|ja|zh-CN|zh-TW]  
`zh-TW` is temporary.

## Parts Data
- Part Data RDL, UN
  https://discord.com/channels/972775718264135740/972779618375438336/1313034452846383155

## TODO
- Squad Member edit.
- Squad reset.
- When add memer, open current added.
- 'Tab Label' multi language.
- When change Language in "Squad" view, change parts glossary.
