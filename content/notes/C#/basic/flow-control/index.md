---
title: Flow Control
weight: 30
menu:
  notes:
    name: Flow Control
    identifier: notes-csharp-basics-flow-control
    parent: notes-csharp-basics
    weight: 30
---

<!-- Condition -->
{{< note title="Condition">}}

```csharp
if day == "sunday" || day == "saturday" {
  rest()
} else if day == "monday" && isTired() {
  groan()
} else {
  work()
}
```

```csharp
if _, err := doThing(); err != nil {
  fmt.Println("Uh oh")
```

{{< /note >}}

<!-- Switch -->

{{< note title="Switch" >}}

```csharp
switch day {
  case "sunday":
    // cases don't "fall through" by default!
    fallthrough

  case "saturday":
    rest()

  default:
    work()
}
```

{{< /note >}}

<!-- Loop -->

{{< note title="Loop" >}}

```csharp
for count := 0; count <= 10; count++ {
  fmt.Println("My counter is at", count)
}
```

```csharp
entry := []string{"Jack","John","Jones"}
for i, val := range entry {
  fmt.Printf("At position %d, the character %s is present\n", i, val)
```

```csharp
n := 0
x := 42
for n != x {
  n := guess()
}
```

{{< /note >}}