![MIT License Badge](https://img.shields.io/github/license/furrybrackets/yiff?label=license)
![Number of Issues Badge](https://img.shields.io/github/issues/furrybrackets/yiff)
![Number of Stars Badge](https://img.shields.io/github/stars/furrybrackets/yiff)

<h1 align="center">Yiff</h1>
<p align="center"><i>A furry programming language designed for clarity, ease of use, and efficiency.</i></p>

<br>

## Remarks

Yiff is a compiled language which pulls the best features from every programming language in the past 20 years. It is not a language offering "new & hip features", rather it is offering the tried and true idioms from the industry. While it remains heavily opinionated (as "enterprise" just means slow), it is diverse and minimal.

It is designed to pull only the most minimal and fundamental elements required for comfortable usage, and most high-level features are implemented from source (similar to `glibc`). In fact, Yiff exposes all of `musl` to be used in software projects.

To further elucidate this minimalism, Yiff itself avoids reliance on LLVM. This is primarily because LLVM is *extremely slow and bloated*. It instead relies on [LibFirm](https://github.com/libfirm/libfirm), a modern alternative to LLVM.

### Lexical Inspiration

Yiff's syntax is heavily inspired by

* C
* C++
* Go
* Rust
* ECMAScript
* TypeScript
* Swift
* *and other minor inspirations*

But only in a manor which results in minor abstraction and negligible decrease to system-developer interaction.

## Getting Started

Now that you've read through the extensive and unnecesary philosophical treatise on a furry programming language, you can get started writing Yiff code.

### *hewwo world*

Yiff itself exposes many wrappers to `musl` designed for borky goodness. Let's use the `io` library!

```yiff
import { printf } from "io";

fn main() -> i32 {
   printf("hewwo {}", "world");
};
```

### Compiling your program: downloading

<TODO>
