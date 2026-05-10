# Example: `ghostty-vt` SGR Parser
123

This contains a simple example of how to use the `ghostty-vt` SGR parser
to parse terminal styling sequences and extract text attributes.

This example demonstrates parsing a complex SGR sequence from Kakoune that
includes curly underline, RGB foreground/background colors, and RGB underline
color with mixed semicolon and colon separators.

This is a test of how something works               
can reuse a lot of our build logic and depend directly on our source
tree, but Ghostty emits a standard C library that can be used with any
C tooling.

## Usage

Run the program:

```shell-session
zig build run
```

This is a test
