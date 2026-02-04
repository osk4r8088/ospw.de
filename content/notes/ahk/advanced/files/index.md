---
title: File Manipulation
weight: 40
menu:
  notes:
    name: File Manipulation
    identifier: notes-ahk-advanced-files
    parent: notes-ahk-advanced
    weight: 10
---

<!-- Condition -->
{{< note title="Condition">}}

```ahk
if day == "sunday" || day == "saturday" {
  rest()
} else if day == "monday" && isTired() {
  groan()
} else {
  work()
}
```

```ahk
if _, err := doThing(); err != nil {
  fmt.Println("Uh oh")
```

{{< /note >}}