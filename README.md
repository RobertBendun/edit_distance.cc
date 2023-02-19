# Edit distance for C++

Implementation of [Levenshtein distance](https://en.wikipedia.org/wiki/Levenshtein_distance) in C++.

Supports C++20 ranges and iterators as input.

## Use

```cpp
static_assert(edit_distance(
  std::string_view("kitten"),
  std::string_view("sitting")) == 3);
```
