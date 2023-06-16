---
title: MisplacedContinue
layout: article
---
<!-- Copyright 2023 The Go Authors. All rights reserved.
     Use of this source code is governed by a BSD-style
     license that can be found in the LICENSE file. -->

<!-- Code generated by generrordocs.go; DO NOT EDIT. -->

```
MisplacedContinue occurs when a continue statement is not within a for
loop of the innermost function definition.

Example:
 func sumeven(n int) int {
 	proceed := func() {
 		continue
 	}
 	sum := 0
 	for i := 1; i {{raw "<"}}= n; i++ {
 		if i % 2 != 0 {
 			proceed()
 		}
 		sum += i
 	}
 	return sum
 }
```
