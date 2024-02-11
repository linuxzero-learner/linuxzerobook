---
title: "My First Post"
date: 2024-02-11T03:48:32+08:00
# bookComments: false
# bookSearchExclude: false
---
dqwerqrw
r
qwr
q
fsdf
sdf
sd
f
sdf
sdf

阿斯顿
```mermaid
gantt
    dateFormat MM-DD
    axisFormat %m-%d
    tickInterval 1day
    section Section
    +1 : a1, 02-01 , 5d
    3 : a2, 02-06 , 1d
    2 : a2, 02-07 , 1d
    1 : a2, 02-08 , 1d
    0 : a2, 02-09 , 1d
```
{{ if .Page.Store.Get "hasMermaid" }}
  <script type="module">
    import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.esm.min.mjs';
    mermaid.initialize({ startOnLoad: true });
  </script>
{{ end }}
