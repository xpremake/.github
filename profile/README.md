# xpremake is NOT Premake

If you are looking for Premake, be it the latest version or the older iterations of Premake:

* [premake organization](https://github.com/premake/)
  * [premake/premake-core](https://github.com/premake/premake-core)
  * [premake/premake-4.x](https://github.com/premake/premake-4.x)

## What's this then, you ask?

_This_ is an attempt of leveraging Zig as drop-in replacement C compiler and creating a hybrid of Premake 4.x and Premake 5.x.

In particular the 4.x version will be what originated as a yak shaving project for WinDirStat: my fork of Premake 4.x.

PS: The purpose of using Zig is _also_ to enable Linux builds with the widest possible compatibility across glibc, obviating the need for other hacks that can achieve the same (or using musl-libc).
