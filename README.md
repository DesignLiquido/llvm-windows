# llvm-windows

This project builds LLVM binary for our [`llvm-bindings`](https://github.com/DesignLiquido/llvm-bindings) package, regarding Windows requirements. It just takes too long to build LLVM on Windows, so we need to have pre-built binaries for our build pipelines.

## Usage

```sh
git tag llvmorg-<version> master
git push origin tag llvmorg-<version>
```
