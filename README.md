# Sounio Benchmarks

**55 benchmark problems** for the [Sounio programming language](https://github.com/Sounio-lang/sounio) — for evaluating LLM code generation quality.

## HumanEval-Sounio (50 problems)

Classic coding interview problems translated to idiomatic Sounio:

| Range | Topics |
|-------|--------|
| 001-010 | Two sum, FizzBuzz, string ops, Fibonacci, binary search, GCD, sieve |
| 011-020 | Sorting checks, merging, Roman numerals, balanced parens, spiral matrix |
| 021-030 | Determinant, median, moving average, histogram, Horner's method, numerical integration |
| 031-040 | Matrix multiply, Dutch flag, Boyer-Moore, stock profit, DP (stairs, robber, coins) |
| 041-050 | LIS, edit distance, unique paths, word break, set operations, inversions, permutations |

## Sounio-Specific Benchmarks (5 problems)

Problems that showcase Sounio's unique features:

| File | Feature |
|------|---------|
| sb_001 | GUM uncertainty propagation |
| sb_002 | Effect-tracked safe division |
| sb_003 | Higher-order function pipeline (map/filter/fold) |
| sb_004 | Running statistics accumulator (by-value struct update) |
| sb_005 | Enum state machine with match |

## Running

```bash
export SOUC=./path/to/souc-linux-x86_64-jit
export SOUNIO_STDLIB_PATH=./path/to/stdlib
bash run_bench.sh
```

## Results

All 55 problems pass `souc run` with exit code 0.

## License

See [Sounio main repository](https://github.com/Sounio-lang/sounio).
