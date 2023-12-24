---
title: For Loop with Index
weight: 1
description: >
  Use Docsy's Hugo shortcodes to quickly build site pages.
---

## for example 1

test

{{< tabpane langEqualsHeader=true >}}

{{< tab "C" >}}
#include <stdio.h>
#include <stdlib.h>

int main(void)
{
  puts("Hello World!");
  return EXIT_SUCCESS;
}
{{< /tab >}}

{{< tab "C++" >}}
#include <iostream>

int main()
{
  std::cout << "Hello World!" << std::endl;
}
{{< /tab >}}

{{< tab "Go" >}}
package main
import "fmt"
func main() {
  fmt.Printf("Hello World!\n")
}
{{< /tab >}}

{{< /tabpane >}}

Hi

<br/>

{{< tabpane langEqualsHeader=true >}}
{{< tab "C" >}}
test Hello World!!
{{< /tab >}}
{{< tab "C++" >}}
Hello World!!
{{< /tab >}}
{{< tab "Go" >}}
Hello World!!
{{< /tab >}}
{{< /tabpane >}}

test

Hi

## for example 2

test 1

test 2