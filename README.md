# Programming language benchmarks

## Opinions

- Reaction to "1 billion nested loop iterations" (2024-12-05) https://x.com/cmuratori/status/1864546805150830878

> This is not a useful "nested loop" benchmark as it warrants - it's actually an integer division benchmark.
> Can it give you a vague sense of how insane the looping overhead is in many modern languages? Sure. Can it actually tell you how good a reasonable language is at loops? It cannot.
> The reason for this is that the loop body consists entirely of a carried dependency on a modulus. This effectively limits the loop to scalar execution, and to several-cycle throughput.

- Language Performance Comparisons Are Junk (2024-12-20) https://www.youtube.com/watch?v=RrHGX1wwSYM

- Reaction to Levenshtein distance "Bouncing balls" https://x.com/cmuratori/status/1870199185972347274
> Please stop creating microbenchmarks without analysis. If you haven't read the assembly for each run, you have no idea what you're actually benchmarking. This creates a lot of work for people like me who have to clean up the wave of misunderstandings. It is very frustrating.

> They cannot be improved. This is not an appropriate use of microbenchmarking, full stop.

> The point is that microbenchmarks test other things than what they claim, so without the analysis, you draw the wrong conclusion.

> The entire exercise seems in bad faith.

- Why I Hate Language Benchmarks (2024-01-22) https://www.gingerbill.org/article/2024/01/22/comparing-language-benchmarks/

## Hall of shame

The Original "Bouncing balls" that triggered me to start this list:

- 1 billion nested loop iterations https://github.com/bddicken/languages

> The Original "Bouncing balls" https://x.com/BenjDicken/status/1861072804239847914

> The Sliding lines https://x.com/BenjDicken/status/1863977678690541570

> The Levenshtein distance "Bouncing balls" https://x.com/BenjDicken/status/1869412072318283783

## The Usual Suspects

- The Computer Language Benchmarks Game https://benchmarksgame-team.pages.debian.net/benchmarksgame/

> Measured : Which programming language is fastest?

> https://en.wikipedia.org/wiki/The_Computer_Language_Benchmarks_Game

- Programming Language Benchmarks https://github.com/hanabi1224/Programming-Language-Benchmarks

> It's inspired by Benchmarks Game, some of the benchmark problems and implementation are borrowed from it.
> https://programming-language-benchmarks.vercel.app

- comparing the execution speeds of various programming languages https://github.com/jabbalaci/SpeedTests

- Prime Number Projects in C#/C++/Python https://github.com/PlummersSoftwareLLC/Primes

> E00: Software Drag Racing: C++ vs C# vs Python - Which Will Win? https://youtu.be/D3h62rgewZM

- Some benchmarks of different languages https://github.com/kostya/benchmarks

- Benchmark for interpreted languages implementations. https://github.com/kostya/jit-benchmarks

- Rust scripting languages benchmark  https://github.com/khvzak/script-bench-rs

- A programming language benchmark https://github.com/attractivechaos/plb2

- Data Processing benchmark featuring Rust, Go, Swift, Zig, Julia etc. https://github.com/jinyus/related_post_gen

- Benchmark for interpreted languages https://github.com/Airsequel/interpreted-languages-benchmark

- Microbenchmarks comparing the Julia Programming language with other languages https://github.com/JuliaLang/Microbenchmarks

- A simple web benchmark of C++, Crystal, Go, Java, Node.js, PHP, Python, Rust and Scala. https://github.com/nuald/simple-web-benchmark

- Benchmark some scientific computations for various languages & libraries https://github.com/Axect/Scientific_Bench

## Real Jobs

- The One Billion Row Challenge https://www.morling.dev/blog/one-billion-row-challenge/

## Self track

- How has PyPy performance evolved over time? https://speed.pypy.org/

- YJIT Benchmarks https://speed.yjit.org/

- Performance Tracking for Zig https://github.com/ziglang/gotta-go-fast

## Surely You're Joking, Mr.

- FizzBuzz Enterprise Edition is a no-nonsense implementation of FizzBuzz made by serious businessmen for serious business purposes.
https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition

