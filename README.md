Usage:

```go
import (
    "github.com/yuin/goldmark"
    "github.com/zenarvus/goldmark-bettermedia"
)

var htmlConverter = goldmark.New(
	goldmark.WithExtensions(bettermedia.BetterMedia),
)
```
