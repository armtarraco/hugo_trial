---
title: How to measure elapsed time with Ruby
date: 2018-04-09 10:06:11 +0200

---
```
starting = Process.clock_gettime(Process::CLOCK_MONOTONIC) # time consuming operation ending = Process.clock_gettime(Process::CLOCK_MONOTONIC) elapsed = ending - starting elapsed # => 9.183449000120163 secon
```
