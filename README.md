# decimal-to-unicode

A simple Bash script that takes a base-10 number and returns the corresponding unicode character

## Example

```
  $  ./decimal_to_unicode.sh 232
  >  è
```


## Why?

I learned to type French using an English keyboard layout on Windows as a kid. Long ago I memorized the decimal value of the relevant accented characters. For example, to type "è" I would type ALT + 0232. This may sound tedious but it is actually not bad when you get used to it.

These days, I only type in French on IRC sometimes, and I just don't worry about accents. I suddenly have a need to write a more formal document in French. I would really like to be able to use my muscle memory while typing and enable something similar to ALT+0232 in my Linux environment.

I wasn't able to find anything, so I decided to make it. Unfortunately my desktop environment, Cinnamon, only seems to support fairly simple keyboard shortcuts; I can call a script on a specific key combo, but I can't seem to send the keypresses that follow as arguments.

Regardless, I hope that this Bash script will work as a core component of such a keyboard shortcut arrangement. I could also use 'xdotool' to emit the character to the window that has focus.

TL;DR: I like to procrastinate with style.
