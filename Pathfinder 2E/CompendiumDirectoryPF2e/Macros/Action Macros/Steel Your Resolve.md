---
title: "Steel Your Resolve"
icon: ":file-question:"
aliases: "Steel Your Resolve"
foundryId: Compendium.pf2e.action-macros.Macro.oxowCzHbxSGOWRke
tags:
  - Macro
---

# Steel Your Resolve
![[icons/svg/dice-target.svg|150]]

```Macro
author: 7rBRoXLPb5I767rN
command: |-
  const tokens = canvas.tokens.controlled;
  if (tokens.length != 1) {
      ui.notifications.error(`You must select one pc token`);
  } else {
      game.pf2e.actions.steelYourResolve({ actors: [token.actor ?? actor].filter((actor) => actor !== null) });
  }
img: icons/svg/dice-target.svg
name: Steel Your Resolve
scope: global
type: script
flags: {}
folder: null
_stats:
  systemId: null
  systemVersion: null
  coreVersion: null
  createdTime: null
  modifiedTime: null
  lastModifiedBy: null
```
