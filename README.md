# Hello World in All Major Languages

This collection contains "Hello, World!" programs written in 20+ major programming languages, demonstrating how to print output in each language.

## How to Run Each Language

### Python
```bash
python hello.py
```
**Requirements:** Python 3.x installed

### JavaScript (Node.js)
```bash
node hello.js
```
**Requirements:** Node.js installed

### Java
```bash
javac hello.java
java hello
```
**Requirements:** JDK (Java Development Kit) installed

### C++
```bash
g++ hello.cpp -o hello
./hello
```
**Requirements:** GCC compiler or any C++ compiler installed

### C
```bash
gcc hello.c -o hello
./hello
```
**Requirements:** GCC compiler or any C compiler installed

### C#
```bash
csc hello.cs
./hello.exe
```
**Requirements:** .NET SDK or Mono installed

### Go
```bash
go run hello.go
```
**Requirements:** Go installed

### Rust
```bash
rustc hello.rs -o hello
./hello
```
**Requirements:** Rust toolchain installed

### PHP
```bash
php hello.php
```
**Requirements:** PHP installed

### Ruby
```bash
ruby hello.rb
```
**Requirements:** Ruby installed

### Swift
```bash
swift hello.swift
```
**Requirements:** Swift compiler installed

### TypeScript
```bash
npx ts-node hello.ts
```
or first compile then run with Node:
```bash
tsc hello.ts
node hello.js
```
**Requirements:** Node.js and TypeScript installed

### R
```bash
Rscript hello.r
```
or run in R interpreter:
```R
source("hello.r")
```
**Requirements:** R installed

### Perl
```bash
perl hello.pl
```
**Requirements:** Perl installed

### Lua
```bash
lua hello.lua
```
**Requirements:** Lua installed

### Kotlin
```bash
kotlinc hello.kt -include-runtime -d hello.jar
java -jar hello.jar
```
**Requirements:** Kotlin compiler installed

### Scala
```bash
scalac hello.scala
scala HelloKt
```
**Requirements:** Scala and Java installed

### Julia
```bash
julia hello.jl
```
**Requirements:** Julia installed

### Elixir
```bash
elixir hello.exs
```
**Requirements:** Elixir installed

### Haskell
```bash
ghc hello.hs -o hello
./hello
```
**Requirements:** GHC (Glasgow Haskell Compiler) installed

## Installation Summary by OS

### Windows
- **Python:** Download from python.org or use `choco install python`
- **Node.js:** Download from nodejs.org or use `choco install nodejs`
- **Java:** Download from oracle.com/java or use `choco install jdk`
- **C++/C:** Install Visual Studio with C++ tools or MinGW
- **Go:** Download from golang.org or use `choco install golang`
- **Rust:** Download from rustup.rs
- **Ruby:** Download from rubyinstaller.org or use `choco install ruby`
- **PHP:** Download from php.net or use `choco install php`
- **Others:** Use Chocolatey package manager for easy installation

### macOS
Most languages available via Homebrew:
```bash
brew install python node java go rust ruby php perl lua
```

### Linux (Ubuntu/Debian)
```bash
sudo apt update
sudo apt install python3 nodejs default-jdk g++ gcc gcc-c++ rustc ruby php perl lua
```

## Summary

| Language | File | Interpreter | Compiled |
|----------|------|-------------|----------|
| Python | hello.py | ✓ | ✗ |
| JavaScript | hello.js | ✓ | ✗ |
| Java | hello.java | ✗ | ✓ |
| C++ | hello.cpp | ✗ | ✓ |
| C | hello.c | ✗ | ✓ |
| C# | hello.cs | ✗ | ✓ |
| Go | hello.go | ✓* | ✓ |
| Rust | hello.rs | ✗ | ✓ |
| PHP | hello.php | ✓ | ✗ |
| Ruby | hello.rb | ✓ | ✗ |
| Swift | hello.swift | ✓* | ✓ |
| TypeScript | hello.ts | ✗ | ✓ |
| R | hello.r | ✓ | ✗ |
| Perl | hello.pl | ✓ | ✗ |
| Lua | hello.lua | ✓ | ✗ |
| Kotlin | hello.kt | ✗ | ✓ |
| Scala | hello.scala | ✗ | ✓ |
| Julia | hello.jl | ✓ | ✗ |
| Elixir | hello.exs | ✓ | ✗ |
| Haskell | hello.hs | ✗ | ✓ |

*Go and Swift support both interpreted (via `go run` and `swift`) and compiled modes
