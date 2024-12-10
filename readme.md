### How to run
```
standart run:
cargo run -- "nobody" poem.txt

run with case_insensitive:
IGNORE_CASE=1 cargo run -- to poem.txt

run with unicode_normalization:
IGNORE_CASE=1 cargo run -- cafe poem.txt
```

### How to test
```
cargo test

test fn search
```