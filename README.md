# cmake-build

## Setup

### Debian/Ubuntu Packages

```
$ sudo apt install -y build-essential procps curl file git
```

### Homebrew packages

```
$ brew install llvm
$ brew install cmake
$ brew install clang-format
$ brew install conan
```

### .clang-format

```
$ clang-format -style=llvm -dump-config > .clang-format
```

---

## References

- [The place to find and share popular C/C++ Conan packages](https://conan.io/center/)
- [Master CMake for Cross-Platform C++ Project Building](https://www.udemy.com/course/master_cmake/)
- [Using clang-tidy and clang-format](https://linuxplumbersconf.org/event/7/contributions/803/attachments/660/1213/Using_clang-tidy_and_clang-format.pdf)
- [ttroy50.github.io/cmake-examples](https://github.com/ttroy50/cmake-examples)
- [CMake wrapper for conan C and C++ package manager](https://github.com/conan-io/cmake-conan)
- [Conan Cheat Sheet](https://docs.conan.io/en/latest/_images/conan-cheatsheet.png)
- [코난 C/C++ package manager](https://choiwooseok.github.io/cpp/package-manager/Conan-post/)
- [Linking Conan Include to VS Code](https://newbedev.com/linking-conan-include-to-vs-code)
- [c_cpp_properties.json reference](https://code.visualstudio.com/docs/cpp/c-cpp-properties-schema-reference)
