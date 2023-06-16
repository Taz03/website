---
title: MisplacedBreak
layout: article
---
<!-- Copyright 2023 The Go Authors. All rights reserved.
     Use of this source code is governed by a BSD-style
     license that can be found in the LICENSE file. -->

<!-- Code generated by generrordocs.go; DO NOT EDIT. -->

```
MisplacedBreak occurs when a break statement is not within a for, switch,
or select statement of the innermost function definition.

Example:
 func f() {
 	break
 }
```
