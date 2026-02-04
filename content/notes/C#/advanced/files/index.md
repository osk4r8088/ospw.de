---
title: File Manipulation
weight: 40
menu:
  notes:
    name: File Manipulation
    identifier: notes-csharp-advanced-files
    parent: notes-csharp-advanced
    weight: 10
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