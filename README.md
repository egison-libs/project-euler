# Utility Functions to solve Project Euler

## Usage

```
% egison -l lib/math/project-euler.egi
> (num-to-digits 12345)
{1 2 3 4 5}
> (digits-to-num {1 2 3 4 5})
12345
```

## Function List

### `sum-of-positive-divisors`

```
> (sum-of-positive-divisors 3)
4     ; 1+3
> (sum-of-positive-divisors 12)
28    ; 1+2+3+4+6+12
```
### `sum-of-proper-divisors`

```
> (sum-of-proper-divisors 3)
1
(sum-of-proper-divisors 12)
16    ; 1+2+3+4+6
```

### `num-to-digits`

```
> (num-to-digits 12345)
{1 2 3 4 5}
```

### `digits-to-num`

```
> (digits-to-num {1 2 3 4 5})
12345
```

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
