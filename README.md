# number patterns

A few years ago I noticed some patterns. I thought I'd document them.

<img align="center" width="120" src="svg/0.svg"/>

## reading directions:

|     |                                                                             |                                                                             |                                                                             |
| --- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
|     | 1: <img align="center" width="120" src="svg/reading-direction/1-or-2.svg"/> | 2: <img align="center" width="120" src="svg/reading-direction/1-or-2.svg"/> | 3: <img align="center" width="120" src="svg/reading-direction/3-or-6.svg"/> |
|     | 4: <img align="center" width="120" src="svg/reading-direction/4-or-7.svg"/> | 5: <img align="center" width="120" src="svg/reading-direction/5.svg"/>      | 6: <img align="center" width="120" src="svg/reading-direction/3-or-6.svg"/> |
|     | 7: <img align="center" width="120" src="svg/reading-direction/4-or-7.svg"/> | 8: <img align="center" width="120" src="svg/reading-direction/8-or-9.svg"/> | 9: <img align="center" width="120" src="svg/reading-direction/8-or-9.svg"/> |

## multiplication and addition tables:

|                                                      |                                                                 |                                                                 |                                                                 |
| ---------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------- |
| 0: <img align="center" width="120" src="svg/0.svg"/> | 1: <img align="center" width="120" src="svg/1.svg"/>            | 2: <img align="center" width="120" src="svg/monochrome/2.svg"/> | 3: <img align="center" width="120" src="svg/monochrome/3.svg"/> |
|                                                      | 4: <img align="center" width="120" src="svg/monochrome/4.svg"/> | 5: <img align="center" width="120" src="svg/monochrome/5.svg"/> | 6: <img align="center" width="120" src="svg/monochrome/6.svg"/> |
|                                                      | 7: <img align="center" width="120" src="svg/monochrome/7.svg"/> | 8: <img align="center" width="120" src="svg/monochrome/8.svg"/> | 9: <img align="center" width="120" src="svg/monochrome/9.svg"/> |

## or:

|                                                      |                                                      |                                                      |                                                      |
| ---------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| 0: <img align="center" width="120" src="svg/0.svg"/> | 1: <img align="center" width="120" src="svg/1.svg"/> | 2: <img align="center" width="120" src="svg/2.svg"/> | 3: <img align="center" width="120" src="svg/3.svg"/> |
|                                                      | 4: <img align="center" width="120" src="svg/4.svg"/> | 5: <img align="center" width="120" src="svg/5.svg"/> | 6: <img align="center" width="120" src="svg/6.svg"/> |
|                                                      | 7: <img align="center" width="120" src="svg/7.svg"/> | 8: <img align="center" width="120" src="svg/8.svg"/> | 9: <img align="center" width="120" src="svg/9.svg"/> |

## or:

(rotate to put the number at the top of the "page")

|                                                      |                                                                |                                                                |                                                                |
| ---------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |
| 0: <img align="center" width="120" src="svg/0.svg"/> | 1: <img align="center" width="120" src="svg/1.svg"/>           | 2: <img align="center" width="120" src="svg/2.svg"/>           | 3: <img align="center" width="120" src="svg/rotations/3.svg"/> |
|                                                      | 4: <img align="center" width="120" src="svg/rotations/4.svg"/> | 5: <img align="center" width="120" src="svg/5.svg"/>           | 6: <img align="center" width="120" src="svg/rotations/6.svg"/> |
|                                                      | 7: <img align="center" width="120" src="svg/rotations/7.svg"/> | 8: <img align="center" width="120" src="svg/rotations/8.svg"/> | 9: <img align="center" width="120" src="svg/rotations/9.svg"/> |

## # = last digit:

<img align="center" width="120" src="svg/last-digit.svg"/>

## darker square = +10: (and # = last digit)

<img align="center" width="120" src="svg/+10.svg"/>

- The # = the last digit in the number. Landing on a darker square = +10.
- For example, 7 x 5 = 35: last digit is 5, and landing on 3 dark squares = +30.

## example sequence for 7:

<img align="center" width="120" src="svg/rotations/7.svg"/> , or alternatively: <img align="center" width="120" src="svg/7.svg"/> and <img align="center" width="120" src="svg/reading-direction/4-or-7.svg"/>

last digits: 74185296307418529630...

| 7   | 4   | 1   | 8   | 5   | 2   | 9   | 6   | 3   | 0   | 7   | 4   | 1   | 8   | 5   | 2   | 9   | 6   | 3   | 0   | ... |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     | +10 | +10 |     | +10 | +10 |     | +10 | +10 | +10 |     | +10 | +10 |     | +10 | +10 |     | +10 | +10 | +10 | ... |

= 7, 14, 21, 28, 35, 42, 49, 56, 63, 70, ...

it also continues past 7 x 10, because of the modulo nature of the patterns

## visual patterns:

just 4 rules:

- **0:** do nothing.

  <img align="center" src="svg/0.svg"/>

- **odd:** read the "number pad" like a book (the nominal number should be at the top of the "page"), and every "step" on a darker square = +10.

  <img align="center" src="svg/reading-direction/1-or-2.svg"/><img align="center" src="svg/1.svg"/>

- **even:** read the "number pad" like a book (the nominal number should be at the top of the "page"), but "step" on every other like a "checkerboard" pattern, and every "step" _**on**_ a darker square = +10.

  <img align="center" src="svg/reading-direction/1-or-2.svg"/><img align="center" src="svg/2.svg"/>

- **5:** move like a chess knight in "J" shaped jumps, but _**not**_ in "L" shaped jumps, and every "step" on a darker square = +10.

  <img align="center" src="svg/reading-direction/5.svg"/><img align="center" src="svg/5.svg"/>

then you get the:

```text
x times tables
+ addition tables
```

and you could also reverse the patterns to get:

```text
/ = reverse of x pattern
- = reverse of + pattern
```
