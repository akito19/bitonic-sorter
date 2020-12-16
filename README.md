# Bitonic Sorter

https://gihyo.jp/book/2019/978-4-297-10559-4

```
% cargo run --release --example benchmark 26
   Compiling bitonic-sorter v0.1.0 (/home/akito/playground/rust/bitonic-sorter)
    Finished release [optimized] target(s) in 0.68s
     Running `target/release/examples/benchmark 26`
sorting 67108864 integers (256) MB
cpu info: 6 physical cores, 6 logical cores
seq_sort: sorted 67108864 integers in 34.073724879 seconds
par_sort: sorted 67108864 integers in 6.682033903 seconds
speed up: 5.10x
```
