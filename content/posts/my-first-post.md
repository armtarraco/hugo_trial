---
title: "How to measure elapsed time with Ruby"
date: 2018-04-09T10:06:11+02:00
draft: true
---


```
starting = Process.clock_gettime(Process::CLOCK_MONOTONIC) # time consuming operation ending = Process.clock_gettime(Process::CLOCK_MONOTONIC) elapsed = ending - starting elapsed # => 9.183449000120163 secon
```
