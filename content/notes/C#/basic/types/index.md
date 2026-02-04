---
title: Basic Types
weight: 20
menu:
  notes:
    name: Basic Types
    identifier: notes-csharp-basics-types
    parent: notes-csharp-basics
    weight: 20
---
<!-- String Type -->
{{< note title="Strings" >}}
```csharp
str := "Hello"
```

Multiline string
```csharp
str := `Multiline
string`
```
{{< /note >}}

<!-- Number Types -->
{{< note title="Numbers" >}}
Typical types

```csharp
num := 3          // int
num := 3.         // float64
num := 3 + 4i     // complex128
num := byte('a')  // byte (alias for uint8)
```

Other Types

```csharp
var u uint = 7        // uint (unsigned)
var p float32 = 22.7  // 32-bit float
```

{{< /note >}}

<!----------- Arrays  ------>

{{< note title="Arrays" >}}

```csharp
// var numbers [5]int
numbers := [...]int{0, 0, 0, 0, 0}
```

{{< /note >}}

<!-- Pointers -->

{{< note size="medium" title="Pointers">}}

```csharp
func main () {
  b := *getPointer()
  fmt.Println("Value is", b)
```

```csharp
func getPointer () (myPointer *int) {
  a := 234
  return &a
```

```csharp
a := new(int)
*a = 234
```

Pointers point to a memory location of a variable. Go is fully garbage-collected.

{{< /note >}}

<!-- Type Conversion -->

{{< note title="Type Conversion" >}}

```csharp
i := 2
f := float64(i)
u := uint(i)
```

{{< /note >}}

<!-- Slice -->

{{< note title="Slice" >}}

```csharp
slice := []int{2, 3, 4}
```

```csharp
slice := []byte("Hello")
```

{{< /note >}}
