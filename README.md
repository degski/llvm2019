# llvm2019
Allows the LLVM Compiler Toolchain (installed separately) to be used from within Visual Studio 2019 (only) to build C/C++ Projects.

~~This is a (slighly) modified version of the extension as published under [llvm-project](https://github.com/llvm/llvm-project) (folder llvm/tools/msbuild) for Visual Studio 2017.~~

This is the same code as the extension published under [llvm-project](https://github.com/llvm/llvm-project) (folder llvm/tools/msbuild) for Visual Studio 2017, but now for VS2019. It merges the code the original LLVM Compiler Toolchain extension with the structure of llvm2019.

Built with Visual Studio 2019 Community edition. Tested (very cursory) under Visual Studio 2019 Community only.

Inspired by:

* [LLVM Compiler Toolchain extension @ Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=LLVMExtensions.llvm-toolchain)
* [llvm2019 extension @ Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=MarekAniola.mangh-llvm2019)
* [Bug 42290 - LLVM Compiler Toolchain extension does not support Visual Studio 2019](https://bugs.llvm.org/show_bug.cgi?id=42290)
* [Microsoft/PTVS Build error: The specified InstallRoot value of 'VCTargets' is invalid for item #5243](https://github.com/Microsoft/PTVS/issues/5243)