# Merge Intervals
In this exercise your job is to merge the intervals, where some of them possibly overlapping.

## Inputs
The first line consists of 1 integer `N`.<br>
The next `N` lines each contains 2 numbers, `L` and `R`, representing an interval {`L`, `R`} with length `R - L + 1`. (`1 ≤ L ≤ R ≤ 2 𝖷 10<sup>9`)

## Outputs
The length of discrete boxes covered by the intervals.

## Sample Tests
**Input 1**
```
7
1 1
1 2
1 3
1 5
2 3
1 8
2 8
```
**Output 1**
```
8
```
## Subtasks
For all cases:<br>
1 <= N <= 1 𝖷 10<sup>8<br>

\# | Points | Constraints
--- | --- | ---
1 | 50 | N <= 1 𝖷 10<sup>4
2 | 50 | no additional constraint
