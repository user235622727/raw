# RAW

    image/frame == RGBA == 32bit
    audio == U32 == 32bit

<a name="_toc"></a>TOC<br/>
<!-- items start --><!-- item start -->
<a href="#features">Features</a><br /><!-- item stop --><!-- item start -->
<a href="#download">Download</a><br /><!-- item stop --><!-- item start -->
<a href="#changes">Changes</a><br /><!-- item stop --><!-- item start -->
<a href="#screenshots">Screenshots</a><br /><!-- item stop --><!-- item start -->
<a href="#included">Included</a><br /><!-- item stop --><!-- item start -->
<a href="#dependencies">Dependencies</a><br /><!-- item stop --><!-- item start -->
<a href="#license">License</a><br /><!-- item stop --><!-- items stop -->

<a name="features"></a>
## Features

    - Minimal dependencies
    - Modular on file system level
    - Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface.

![images/Douglas_McIlroy_quote.jpg](images/Douglas_McIlroy_quote.jpg)
https://en.wikipedia.org/wiki/Unix_philosophy





<a href="#_toc">TOC</a>

<a name="download"></a>
## Download

[raw-0.1.zip](raw-0.1.zip)

<div class="code">

    Current version: 0.1

</div>





<a href="#_toc">TOC</a>

<a name="changes"></a>
## Changes

<div class="code">

    0.1 initial release

</div>





<a href="#_toc">TOC</a>

<a name="screenshots"></a>
## Screenshots

<img loading="lazy" src="images/screenshots/Untitled.png" width="100%" style="image-rendering:pixelated;" />

<img loading="lazy" src="images/screenshots/Untitled2.png" width="100%" style="image-rendering:pixelated;" />

<img loading="lazy" src="images/screenshots/Untitled3.png" width="100%" style="image-rendering:pixelated;" />

<img loading="lazy" src="images/workflow.png" width="100%" style="image-rendering:pixelated;" />

<img loading="lazy" src="images/workflow2.png" width="100%" style="image-rendering:pixelated;" />





<a href="#_toc">TOC</a>

<a name="included"></a>
## Included

    ./inputdev.sh
    ./inputdev.c
script to find input devices


    ./raw2uinput
playback recorded input using linux/kernel uinput


    ./raw2ff
gamepad rumble





<a href="#_toc">TOC</a>

<a name="dependencies"></a>
## Dependencies

<div class="code">

    ldd ./raw2image ./p8png2raw ./raw2speaker ./gl2raw ./xmp2raw ./raw2oss ./raw2x264 ./gme2raw ./raw2x11 ./raw2alsa ./capture2raw ./raw2fb ./raw2uinput ./ttf2raw ./raw2chafa ./alsa2raw ./input2raw ./raw2ansi ./raw2ff ./image2raw
    ./raw2image:
        linux-vdso.so.1 (0x00007fa25e547000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fa25e309000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fa25e549000)
    ./p8png2raw:
        linux-vdso.so.1 (0x00007f735bef3000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f735bc9f000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f735bef5000)
    ./raw2speaker:
        linux-vdso.so.1 (0x00007fa4e0f24000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fa4e0d04000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fa4e0f26000)
    ./gl2raw:
        linux-vdso.so.1 (0x00007f0ecb4c9000)
        libGLESv2.so.2 => /lib/x86_64-linux-gnu/libGLESv2.so.2 (0x00007f0ecb48d000)
        libEGL.so.1 => /lib/x86_64-linux-gnu/libEGL.so.1 (0x00007f0ecb477000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f0ecb281000)
        libGLdispatch.so.0 => /lib/x86_64-linux-gnu/libGLdispatch.so.0 (0x00007f0ecb1c8000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f0ecb4cb000)
    ./xmp2raw:
        linux-vdso.so.1 (0x00007f05d75f5000)
        libxmp.so.4 => /lib/x86_64-linux-gnu/libxmp.so.4 (0x00007f05d752d000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f05d7337000)
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007f05d7247000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f05d75f7000)
    ./raw2oss:
        linux-vdso.so.1 (0x00007f9936054000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f9935e34000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f9936056000)
    ./raw2x264:
        linux-vdso.so.1 (0x00007fcdb812d000)
        libx264.so.165 => /lib/x86_64-linux-gnu/libx264.so.165 (0x00007fcdb7e00000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fcdb7c0a000)
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007fcdb7b1a000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fcdb812f000)
    ./gme2raw:
        linux-vdso.so.1 (0x00007fbfa8ef6000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fbfa8cd6000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fbfa8ef8000)
    ./raw2x11:
        linux-vdso.so.1 (0x00007eff62ab5000)
        libX11.so.6 => /lib/x86_64-linux-gnu/libX11.so.6 (0x00007eff62943000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007eff6274d000)
        libxcb.so.1 => /lib/x86_64-linux-gnu/libxcb.so.1 (0x00007eff62722000)
        /lib64/ld-linux-x86-64.so.2 (0x00007eff62ab7000)
        libXau.so.6 => /lib/x86_64-linux-gnu/libXau.so.6 (0x00007eff6271d000)
        libXdmcp.so.6 => /lib/x86_64-linux-gnu/libXdmcp.so.6 (0x00007eff62715000)
    ./raw2alsa:
        linux-vdso.so.1 (0x00007ff0f071e000)
        libasound.so.2 => /lib/x86_64-linux-gnu/libasound.so.2 (0x00007ff0f05ab000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007ff0f03b5000)
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007ff0f02c5000)
        /lib64/ld-linux-x86-64.so.2 (0x00007ff0f0720000)
    ./capture2raw:
        linux-vdso.so.1 (0x00007fcea1ca3000)
        libX11.so.6 => /lib/x86_64-linux-gnu/libX11.so.6 (0x00007fcea1b31000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fcea193b000)
        libxcb.so.1 => /lib/x86_64-linux-gnu/libxcb.so.1 (0x00007fcea1910000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fcea1ca5000)
        libXau.so.6 => /lib/x86_64-linux-gnu/libXau.so.6 (0x00007fcea190b000)
        libXdmcp.so.6 => /lib/x86_64-linux-gnu/libXdmcp.so.6 (0x00007fcea1903000)
    ./raw2fb:
        linux-vdso.so.1 (0x00007fb499981000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fb499761000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fb499983000)
    ./raw2uinput:
        linux-vdso.so.1 (0x00007fea5963e000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fea5941e000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fea59640000)
    ./ttf2raw:
        linux-vdso.so.1 (0x00007fb40367e000)
        libfreetype.so.6 => /lib/x86_64-linux-gnu/libfreetype.so.6 (0x00007fb403581000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fb40338b000)
        libz.so.1 => /lib/x86_64-linux-gnu/libz.so.1 (0x00007fb40336b000)
        libbz2.so.1.0 => /lib/x86_64-linux-gnu/libbz2.so.1.0 (0x00007fb403358000)
        libpng16.so.16 => /lib/x86_64-linux-gnu/libpng16.so.16 (0x00007fb403320000)
        libbrotlidec.so.1 => /lib/x86_64-linux-gnu/libbrotlidec.so.1 (0x00007fb403310000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fb403680000)
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007fb403220000)
        libbrotlicommon.so.1 => /lib/x86_64-linux-gnu/libbrotlicommon.so.1 (0x00007fb4031fd000)
    ./raw2chafa:
        linux-vdso.so.1 (0x00007f461a0b6000)
        libchafa.so.0 => /usr/local/lib/libchafa.so.0 (0x00007f461a016000)
        libglib-2.0.so.0 => /lib/x86_64-linux-gnu/libglib-2.0.so.0 (0x00007f4619eba000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f4619cc4000)
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007f4619bd4000)
        libmvec.so.1 => /lib/x86_64-linux-gnu/libmvec.so.1 (0x00007f4619adb000)
        libatomic.so.1 => /lib/x86_64-linux-gnu/libatomic.so.1 (0x00007f4619ace000)
        libpcre2-8.so.0 => /lib/x86_64-linux-gnu/libpcre2-8.so.0 (0x00007f4619a1f000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f461a0b8000)
    ./alsa2raw:
        linux-vdso.so.1 (0x00007eff0cbe4000)
        libasound.so.2 => /lib/x86_64-linux-gnu/libasound.so.2 (0x00007eff0ca71000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007eff0c87b000)
        libm.so.6 => /lib/x86_64-linux-gnu/libm.so.6 (0x00007eff0c78b000)
        /lib64/ld-linux-x86-64.so.2 (0x00007eff0cbe6000)
    ./input2raw:
        linux-vdso.so.1 (0x00007f1e7479f000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f1e74579000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f1e747a1000)
    ./raw2ansi:
        linux-vdso.so.1 (0x00007fd0657a9000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fd065588000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fd0657ab000)
    ./raw2ff:
        linux-vdso.so.1 (0x00007f9d77b5f000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007f9d7793f000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f9d77b61000)
    ./image2raw:
        linux-vdso.so.1 (0x00007fcbfe4bf000)
        libc.so.6 => /lib/x86_64-linux-gnu/libc.so.6 (0x00007fcbfe281000)
        /lib64/ld-linux-x86-64.so.2 (0x00007fcbfe4c1000)

</div>





<a href="#_toc">TOC</a>

<a name="license"></a>
## License

<div class="code">

    RAW
    
    Copyright (C) 1999-2025 NoisyB
    
    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; either version 2 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 675 Mass Ave, Cambridge, MA 02139, USA.

</div>





<a href="#_toc">TOC</a>

