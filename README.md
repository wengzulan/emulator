# emulator

Allows you to partly emulate an Android native library.<br>

This is an educational project to learn more about the ELF file format and [Unicorn](https://github.com/unicorn-engine/unicorn).


## Usage

Simple tests under src/test directory

## Features
- Emulation of the JNI Invocation API so JNI_OnLoad can be called.
- Support JavaVM, JNIEnv.
- Emulation of syscalls instruction.
- Support ARM32 and ARM64 bit ELF.
- Inline hook, thanks HookZz.
- Import hoo, thanks xHook.
- Support simple debugger.

## Thanks
- [unicorn](https://github.com/unicorn-engine/unicorn)
- [keystone](https://github.com/keystone-engine/keystone)
- [capstone](https://github.com/aquynh/capstone)
- [HookZz](https://github.com/jmpews/HookZz)
- [xHook](https://github.com/iqiyi/xHook)
