# lter Example:Nice Numbers
## Nice Numbers
** Definition: ** A nice number doesn't have 98, 99 , 01, or 02 among its digits and 00 can only be followed by more 0's.
These numbers are nice enough already and unaffected: 755 2859 45622895
Implement nice, which takes a positive integer n. It returns the nearest nice number to n
- For numbers that end in 98 or 99 or 01 or 02, round to the nearest 100.
- Look for 98 or 99 or 01 or 02 among the digits that aren't at the end.
