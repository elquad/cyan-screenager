# Screenager

Screenager is the funny short name for hacky screen manager for manual screen rotation on convertible laptop Acer Chromebook R11 (Cyan). It consists of two shell scripts I stolen from the Internet and a horrible python wrapper application that sits on your system tray. You can choose from five modes of operation:

- laptop mode
- tablet mode with screen oriented as if you were in laptop mode
- tablet mode with screen turned left
- tablet mode with screen turned right
- tablet mode with screen turned upside down

The icon on systray rotates itself as you change the mode. If you feel the icons don't suit your needs, replace them (the icons/ directory). The sources are quite trivial, you should be able to change stuff easily.

Keyboard and touchpad are disabled during tablet mode. Virtual keyboard emulator "onboard" is started in tablet mode and killed in laptop mode.

Requirements: python, python-wxtools, onboard

