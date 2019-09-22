# Fork of fatih/color with enhancements for 256-color palette

See github.com/fatih/color for more information.

## Examples

### 256 color palette

See [https://en.wikipedia.org/wiki/ANSI_escape_code#8-bit] for color codes.

```go
col := color.New256(color.Fg256(208), color.Bg256(52)).Add(color.Underline)
col.Println("Prints bright orange underlined text on dark red background.")
```

## Credits

 * [Fatih Arslan](https://github.com/fatih)
 * Windows support via @mattn: [colorable](https://github.com/mattn/go-colorable)

## License

The MIT License (MIT) - see [`LICENSE.md`](https://github.com/mkke/color/blob/master/LICENSE.md) for more details

