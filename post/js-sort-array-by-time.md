---
title: "Js Sort Array By Time"
date: 2017-07-13T15:15:28+08:00
draft: true
categories:
 - 技术文章
---

js sort array by time

```
array.sort(function(a,b){
  return new Date(b.date) - new Date(a.date);
});

```