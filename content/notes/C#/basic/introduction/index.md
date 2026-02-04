---
title: Introduction
weight: 10
menu:
  notes:
    name: Introduction
    identifier: notes-csharp-basics-intro
    parent: notes-csharp-basics
    weight: 10
---
<!-- A Sample Program -->
{{< note title="Hello World">}}
A sample go program is show here.
  
```csharp
package main

import "fmt"

func main() {
  message := greetMe("world")
  fmt.Println(message)
}

func greetMe(name string) string {
  return "Hello, " + name + "!"
}
```

Run the program as below:

```bash
$ go run hello.go
```
{{< /note >}}

<!-- Declaring Variables -->

{{< note title="Variables" >}}
**Normal Declaration:**
```csharp
var msg string
msg = "Hello"
```

---

**Shortcut:**
```csharp
msg := "Hello"
```
{{< /note >}}


<!-- Declaring Constants -->

{{< note title="Constants" >}}
```csharp
const Phi = 1.618
```
{{< /note >}}