---
layout: note
title:
tags: 
source:
compiler:
category:
---

# to change extensions for a bunch of files at once

```
@ECHO OFF
PUSHD .
FOR /R %%d IN (.) DO (
cd "%%d"
IF EXIST *.CERMTXT (
REN *.CERMTXT *.MD
)
)
POPD
```

save as .bat and run
