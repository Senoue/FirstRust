# First Rust

## 1st Step

```
$ cd FirstRust
$ docker-compose up -d
$ docker exec -it firstrust_rust_1 bash
```

## 2nd Step

```
$ cargo new hello --bin
$ cd hello
$ cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.04s
     Running `target/debug/hello`
```

## 3rd Step

```
$ cd src/
$ rustc main.rs
$ ./main
$ Hello, world!
```
