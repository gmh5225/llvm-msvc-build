
# llvm-msvc-build

[![build](https://github.com/NewWorldComingSoon/llvm-msvc-build/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/NewWorldComingSoon/llvm-msvc-build/actions/workflows/build.yml)
[![GitHub license](https://img.shields.io/github/license/NewWorldComingSoon/llvm-msvc-build)](https://github.com/NewWorldComingSoon/llvm-msvc-build/blob/main/LICENSE)

[![Github All Releases](https://img.shields.io/github/downloads/NewWorldComingSoon/llvm-msvc-build/total.svg)](https://github.com/NewWorldComingSoon/llvm-msvc-build/releases) 
[![GitHub release](https://img.shields.io/github/release/NewWorldComingSoon/llvm-msvc-build.svg)](https://github.com/NewWorldComingSoon/llvm-msvc-build/releases) 

## What's llvm-msvc?
A project that forked LLVM focused on MSVC Compatibility.

## Features:
- SEH support.
- [Compatible with MSVC syntax as much as possible.](https://github.com/gmh5225/llvm-msvc-compatibility
)
- Windows Driver support.(Now only X64)
- [Intrinsic support.](https://github.com/gmh5225/LLVMIntrinsicRewrite)
- Naked X64 inline asm support.

## How to use llvm-msvc?
- Install Visual Studio 2015~2022(I suggest 2022) with WDK11.
- Install llvm-msvc in this repository (llvm-msvc_X86_64_installer.exe)
- Create your windows driver project and select "LLVM-MSVC_v143_KernelMode" as your platform toolset.
- Compile it.

If you have any questions about how to compile Windows Driver by llvm-msvc.

Please tell me or send [issues](https://github.com/NewWorldComingSoon/llvm-msvc-issues/issues)

We want to use llvm-msvc as comfortable as msvc.

Thank you

Here is an windows driver example: [[link]](https://github.com/gmh5225/LLVMWindowsDriverTest)

![image](https://github.com/NewWorldComingSoon/llvm-msvc-build/blob/main/LLVMDriverTest.png)

## Some discussions on UnknownCheats
https://www.unknowncheats.me/forum/general-programming-and-reversing/493547-using-llvm-msvc-compile-windows-driver.html

