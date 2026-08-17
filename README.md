# Leetcode-training

Java submission snippets for LeetCode practice. Each file keeps the LeetCode problem number/title header and defines the method expected by the online judge.

## Current solution index

This table indexes only the files currently in this repository; it does not claim complete topic or LeetCode coverage.

| Problem | File | Entry method | Main idea visible in the current code |
| --- | --- | --- | --- |
| 1. Two Sum | [`1.two-sum.java`](1.two-sum.java) | `twoSum` | Nested index scan |
| 2. Add Two Numbers | [`2.add-two-numbers.java`](2.add-two-numbers.java) | `addTwoNumbers` | Linked-list traversal with carry |
| 50. Pow(x, n) | [`50.pow-x-n.java`](50.pow-x-n.java) | `myPow` | Binary exponentiation with a widened exponent |
| 66. Plus One | [`66.plus-one.java`](66.plus-one.java) | `plusOne` | Right-to-left carry handling |
| 383. Ransom Note | [`383.ransom-note.java`](383.ransom-note.java) | `canConstruct` | Character counts in a `HashMap` |
| 412. Fizz Buzz | [`412.fizz-buzz.java`](412.fizz-buzz.java) | `fizzBuzz` | Divisibility checks |
| 485. Max Consecutive Ones | [`485.max-consecutive-ones.java`](485.max-consecutive-ones.java) | `findMaxConsecutiveOnes` | Running and maximum counters |
| 876. Middle of the Linked List | [`876.middle-of-the-linked-list.java`](876.middle-of-the-linked-list.java) | `middleNode` | Store nodes, then select the midpoint |
| 977. Squares of a Sorted Array | [`977.squares-of-a-sorted-array.java`](977.squares-of-a-sorted-array.java) | `sortedSquares` | Square in place, then sort |
| 1089. Duplicate Zeros | [`1089.duplicate-zeros.java`](1089.duplicate-zeros.java) | `duplicateZeros` | Shift array suffixes in place |
| 1295. Find Numbers with Even Number of Digits | [`1295.find-numbers-with-even-number-of-digits.java`](1295.find-numbers-with-even-number-of-digits.java) | `findNumbers` | Count digits with `Math.log10` |
| 1342. Number of Steps to Reduce a Number to Zero | [`1342.number-of-steps-to-reduce-a-number-to-zero.java`](1342.number-of-steps-to-reduce-a-number-to-zero.java) | `numberOfSteps` | Repeated parity-based reduction |
| 1480. Running Sum of 1d Array | [`1480.running-sum-of-1-d-array.java`](1480.running-sum-of-1-d-array.java) | `runningSum` | Prefix sum |
| 1672. Richest Customer Wealth | [`1672.richest-customer-wealth.java`](1672.richest-customer-wealth.java) | `maximumWealth` | Row sums and maximum tracking |

## How to use the files

Open a file and submit its `Solution` implementation through the matching LeetCode problem page. The linked-list problems rely on LeetCode's supplied `ListNode` definition, which remains as a comment in each snippet.

These are raw online-judge submissions rather than a standalone Java application:

- there is no Gradle/Maven build, package structure, test suite, or `main` method;
- the repository does not pin a Java/JDK version;
- most files define the same package-private class name, `Solution`, so they are not intended to be compiled together;
- filenames follow LeetCode tooling conventions rather than Java public-class naming conventions.

No claim is made here about completeness, optimality, or correctness beyond preserving and indexing the code currently present.
