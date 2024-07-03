Complex Puzzle

Your task is to find a secret message. The message is written on a paper with ink-drops. The ink used is special, so it is visible through the paper.

In the below input, the `#` represents an ink-drop and a `.` represents an empty space.
```
..#..#..............
.#.....#.....#......
.......#.....#....##
............#######.
....................
.......#.....#....##
#...................
....................
...................#
....#...........#...
```

You can find the secret message by folding the paper twice in the exact middle: once horizontally and once vertically.

The above paper has length of 20 characters and width of 10 characters (20x10).
So when you fold the above paper with vertical axis in the middle, your paper looks like this (10x10):
```
..#..#....
.#....##..
##....##..
.#######..
..........
##....##..
#.........
..........
#.........
...##.....
```

And when you fold the above paper with horizontal axis in the middle, your paper looks like this (10x5):
```
..####....
##....##..
##....##..
########..
##....##..
```

And the secret message is revealed, which is `A`.
