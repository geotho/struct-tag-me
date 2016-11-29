# Struct-Tag-Me: append JSON struct tags to Go structs

## What?
Convert this:
```go
type Foo struct {
  AThing            string
  AnotherThing      int
  AnotherOtherThing string
}
```

into this:

```go
type Foo struct {
  AThing            string `json:"aThing,omitempty"`
  AnotherThing      int    `json:"anotherThing,omitempty"`
  AnotherOtherThing string `json:"anotherOtherThing,omitempty"`
}
```

## Usage:
Go here: [https://geotho.github.io/struct-tag-me/](https://geotho.github.io/struct-tag-me/)

## Bugs:
You'll have to `gofmt` it yourself.
