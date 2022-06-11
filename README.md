### xterm-256color-na

`xterm-256color-na` compiles and installs these `xterm-256color` terminfo
database entries, which have been modified to not save and restore the
screen on application startup and shutdown.

| TERM | description |
|------|-------------|
|xterm-256color-na|no alternate screen|
|xterm-256color-na-1002|no alternate screen, pressed mouse motions|
|xterm-256color-na-1003|no alternate screen, all mouse motions|

#### Installation

    $ bash xterm-256color-na

#### Usage Example

    $ export TERM=xterm-256color-na-1002

#### See Also

* https://stackoverflow.com/questions/29020638/which-term-to-use-to-have-both-256-colors-and-mouse-move-events-in-python-curse
* https://invisible-island.net/xterm/terminfo-contents.html
