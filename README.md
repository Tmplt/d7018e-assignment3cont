# Embedded decryption

## Building
```
$ xargo build [--target ...] [--release]
```

## Results
Decrypting the string "abc" in debug took 7079 cycles vs. release which took 552 cycles.
The cycle decrease is possible in release because of zero-cost abstractions.
