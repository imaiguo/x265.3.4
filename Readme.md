

## build with MSVC

设置编译环境

```bash
> git tag 3.4
> vcvars64
> set Path=D:\devtools\nasm-2.16.01;%Path%
> cd source
> mkdir build & cd build
> cmake .. -G Ninja -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\x265.3.4
> cmake .. -G Ninja -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=D:\devtools\x265.3.4
```
