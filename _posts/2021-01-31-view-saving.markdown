---
layout: post
title:  "View saving"
categories: android
---

If you change view state (translation, color etc.), it doesn't mean that these changes will be recovered after activity recreation.
Certain view states will be recovered (text for EditText, RadioButton state etc.). But only if these view have id.

[example][example]

[example]: https://github.com/theManWithoutQualities/view-saving
