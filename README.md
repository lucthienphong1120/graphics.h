# Setup

```
git clone https://github.com/lucthienphong1120/graphics.h
```

# Build

+ Run `setup.exe` with administrator permission, this will automatic configure the library
+ Or read and follow the instructions in `Setup_x64.txt` or `Setup_x32.txt` to configure manually

# How to use

+ open Dev-C++ 5.11, set compiler is "TDM-GCC 4.9.2 32-bit Release"
+ create graphics project to run every graphics file
+ link libraries to compiler options to run without project

```
-static-libgcc -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32
```
