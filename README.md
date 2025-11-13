# Advanced Git Activity!

This is a real repository of a small C++ program, but it's content is mostly
irrelevant. Your task it to (optionally) group up and complete the following
tasks. This IS a competition with everyone else in the room!

1. Remove ALL swear words in the Git commit history to make this repo super
   professional!
2. `EVIL_FILE` was introduced in some commit and we need to remove it, but you
   MUST use a fixup commit that 'fixes' the commit that introduced it
   - HINT: Use `git bisect` to find the offending commit
3. There's a commit called 'wip', which isn't a very helpful message. Squash
   this commit into the one that comes after it.

If you finish all of these and you think you're the first to do so, have us
check and we will verify your work!

> The original README is preserved below, but it's not important. You do not
> need to run the program for this workshop.

---
# REPO'S ORIGINAL README BELOW
simple C++ implementation of the doomsday algorithm.

Building:
```sh
make
```

Usage:
```
Usage: ./build/doomsday [-h|--help] mm/dd/yyyy

This program calculates the day of the week that (nearly) any date falls on.
It uses the Doomsday rule derived by John Conway. For more information, see
the Wikipedia article on the topic : https://en.wikipedia.org/wiki/Doomsday_rule
```

This was one of my first coding projects, came back a few years later to clean
it up.
