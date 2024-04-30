# Instructions

Write a function to convert from normal numbers to Roman Numerals.

The Romans were a clever bunch.
They conquered most of Europe and ruled it for hundreds of years.
They invented concrete and straight roads and even bikinis.
One thing they never discovered though was the number zero.
This made writing and dating extensive histories of their exploits slightly more challenging, but the system of numbers they came up with is still in use today.
For example the BBC uses Roman numerals to date their programs.

The Romans wrote numbers using letters - I, V, X, L, C, D, M; notice these letters have lots of straight lines and are hence easy to hack into stone tablets.

```text
 1  => I
10  => X
 7  => VII
```

The maximum number supported by this notation is 3,999.

Wikipedia says: Modern Roman numerals [...] are written by expressing each digit separately starting with the left most digit and skipping any digit with a value of zero.

To see this in practice, consider the example of 1990.

In Roman numerals 1990 is MCMXC:

```text
 1000 => M
  900 => CM
+  90 => XC
----- => -----
 1990 => MCMXC
```

2008 is written as MMVIII:

```text
 2000 => MM
+   8 => VIII
----- => ------
 2008 => MMVIII
```

Learn more about [Roman numerals on Wikipedia][roman-numerals].

[roman-numerals]: https://wiki.imperivm-romanvm.com/wiki/Roman_Numerals