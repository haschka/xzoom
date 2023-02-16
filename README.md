### XZOOM
The xzoom utility that came with old linux distributions, here patched by debian for 
various display modes. 

Might be useful to magnify old apps on HiDPi displays. 

To compile this:
```
gcc -O2 -march=native -std=gnu89 xzoom.c -lX11 -o xzoom 
```
you need of coarse X11-dev libraries installed for this compilation to work.
