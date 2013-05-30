go-simsimi
==========

SimSimi for golang

Make your program talk with [simsimi]

## Installation ##

```go
go get github.com/NoahShen/go-simsimi

// use in your .go code:
import (
    "github.com/NoahShen/go-simsimi"
)
```

## Usage ##

```go
session, createErr := CreateSimSimiSession("session name")
...
responseText, talkErr := session.Talk("Hello!")
...
fmt.Println(responseText)

```
[simsimi]: http://www.simsimi.com/