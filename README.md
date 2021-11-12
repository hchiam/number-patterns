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

|                                                      |                                                      |                                                      |                                                      |
| ---------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| 0: <img align="center" width="120" src="svg/0.svg"/> | 1: <img align="center" width="120" src="svg/1.svg"/> | 2: <img align="center" width="120" src="svg/2.svg"/> | 3: <img align="center" width="120" src="svg/3.svg"/> |
|                                                      | 4: <img align="center" width="120" src="svg/4.svg"/> | 5: <img align="center" width="120" src="svg/5.svg"/> | 6: <img align="center" width="120" src="svg/6.svg"/> |
|                                                      | 7: <img align="center" width="120" src="svg/7.svg"/> | 8: <img align="center" width="120" src="svg/8.svg"/> | 9: <img align="center" width="120" src="svg/9.svg"/> |

## or:

|                                                      |                                                                                       |                                                                                       |                                                                                        |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| 0: <img align="center" width="120" src="svg/0.svg"/> | 1: <img align="center" width="120" src="svg/1.svg"/>                                  | 2: <img align="center" width="120" src="svg/2.svg"/>                                  | 3: <img align="center" width="120" src="svg/3.svg" style="transform:rotate(-90deg)"/>  |
|                                                      | 4: <img align="center" width="120" src="svg/4.svg"  style="transform:rotate(90deg)"/> | 5: <img align="center" width="120" src="svg/5.svg"/>                                  | 6: <img align="center" width="120" src="svg/6.svg"  style="transform:rotate(-90deg)"/> |
|                                                      | 7: <img align="center" width="120" src="svg/7.svg"  style="transform:rotate(90deg)"/> | 8: <img align="center" width="120" src="svg/8.svg" style="transform:rotate(180deg)"/> | 9: <img align="center" width="120" src="svg/9.svg" style="transform:rotate(180deg)"/>  |

## last digit = #:

<img align="center" width="120" src="svg/last-digit.svg"/>

## +10: (and last digit = #)

<img align="center" width="120" src="svg/+10.svg"/>

- The # = the last digit in the number. Landing on a darker square = +10.
- For example, 7 x 5 = 35: last digit is 5, and landing on 3 dark squares = +30.

## example sequence:

7: last digits: 74185296307418529630...

| 7   | 4   | 1   | 8   | 5   | 2   | 9   | 6   | 3   | 0   | 7   | 4   | 1   | 8   | 5   | 2   | 9   | 6   | 3   | 0   | ... |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|     | +10 | +10 |     | +10 | +10 |     | +10 | +10 | +10 |     | +10 | +10 |     | +10 | +10 |     | +10 | +10 | +10 | ... |

## visual patterns:

just 4 rules:

- **0:** do nothing.
- **odd:** read the "number pad" like a book (the nominal number should be at the top of the "page"), and every "step" on a darker square = +10.
- **even:** read the "number pad" like a book (the nominal number should be at the top of the "page"), but "step" on every other like a "checkerboard" pattern, and every "step" _**on**_ a darker square = +10.
- **5:** move like a chess knight in "J" shaped jumps, but _**not**_ in "L" shaped jumps, and every "step" on a darker square = +10.
