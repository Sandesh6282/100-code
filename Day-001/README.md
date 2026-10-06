# Day 1 — Palindrome Checker

## Problem

Check whether a given string reads the same forwards and backwards.

## Examples

| Input | Output |
|---|---|
| `madam` | `True` |
| `hello` | `False` |
| `racecar` | `True` |

## Approach

I reverse the string using Python slicing:

```python
text[::-1]
