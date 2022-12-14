# github.com/andrietri/go-lib

## Usage

### Initialize your module

```
$ go mod init example.com/my-golib-demo
```

### Get the go-lib module

Note that you need to include the **v** in the version tag.

```
$ go get github.com/andrietri/go-lib@v0.1.0
```

```go
package main

import (
    "fmt"

    "github.com/andrietri/go-lib"
)

func main() {
    fmt.Println(golib.Add(2,3))
    fmt.Println(golib.Subtract(2,3))
}
```

## Testing

```
$ go test
```