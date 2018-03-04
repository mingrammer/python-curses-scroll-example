# Python Curses Scroll Example

I'll introduce how to implement the scroll and paging in Python curses.

## What is purpose?

Scroll and paging are little a bit cumbersome to implement with curses. So, I'd like to share the code snippets to help for building the scroll and paging feature for your TUI based application.

## Key Idea

The key idea is simple. The idea is that compare the length of item list and current cursor position, then just calculate the next cursor position. Of course, there are some exceptions such as scroll overflow we must deal with.

## Scroll Demo

[Scroll implementation](/tui.py#L86-L110)

[![Scroll In Python Curses](https://asciinema.org/a/166994.png)](https://asciinema.org/a/166994)

## Paging Demo

[Paging implementation](/tui.py#L112-L132)

[![Paging In Python Curses](https://asciinema.org/a/166995.png)](https://asciinema.org/a/166995)