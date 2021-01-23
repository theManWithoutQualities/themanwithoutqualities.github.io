---
layout: post
title:  "Testing coroutines"
categories: coroutines
---

To test coroutines you shoud wrap your code in runBlocking.
And catch CancellationException if need

[example][example]

[example]: https://github.com/theManWithoutQualities/coroutines/blob/master/app/src/test/java/com/example/coroutinesfun/FunTest.kt
