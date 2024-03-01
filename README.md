# Hello, COBOL

[![macOS](https://img.shields.io/badge/macOS-Sonoma-black)](https://developer.apple.com/macos/sonoma/)
[![cobol](https://img.shields.io/badge/cobol-v3.2-black)](https://docs.scala-lang.org/scala3/new-in-scala3.html)

## Installation

https://formulae.brew.sh/formula/gnucobol

```
brew search cobol
```

install you find formulae. 

```
brew install gnucobol
```

```
% cobol -v
cobc (GnuCOBOL) 3.2.0
Built     Jul 28 2023 18:42:18	Packaged  Jul 28 2023 17:02:56 UTC
C version "Apple LLVM 15.0.0 (clang-1500.0.40.1)"
loading standard configuration file 'default.conf'
cobc: error: no input files
```

## Compile

```
cobc -x -o hello_world hello_world.cbl
```

## Run

```
./hello_world
```

## Guides

https://gnucobol.sourceforge.io/guides.html
