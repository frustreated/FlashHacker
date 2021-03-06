# FlashHacker

FlashHacker is an ActionScript Bytecode instrumentation framework. The RABCDasm tool is used for disassembling and assembling of ActionScript Bytecode. FlashHacker uses Bytecode disassembly to inject various instrumentation instructions. This is very useful when you work with malicious Flash files.

The whole concept was introduced in my previous presentation at ShmooCon 2012
   http://www.shmoocon.org/2012/presentations/Jeong_Wook_Oh_AVM%20Inception%20-%20ShmooCon2012.pdf

## Prerequisites
* PySide: https://pypi.python.org/pypi/PySide (pip install -U PySide on Windows)
* Graphviz 2.x: http://graphviz.org/ (included in the distribution)
* RABCDasm binaries: https://github.com/CyberShadow/RABCDAsm/releases (included in the distribution)

## How to use
Download whole source tree and run "python FlashHacker.py" and it will pop up GUI. You can load a swf file and add instrumentation you want and save it as a new file. You can also use FlashManipulation.py to use script based approach, but it is still under testing. You can run the instrumented SWF file with debug version of Adobe Flash Player with provided mm.cfg under Environment folder and you will get useful debug log. Please be aware that the limitation of maximum Flash execution of 30 seconds exists. For more details on how the debug version of Adobe Flash works, please read https://helpx.adobe.com/flash-player/kb/configure-debugger-version-flash-player.html.

## LICENSE
Copyright (c) 2015, Jeong Wook Oh
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
   * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
   * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
   * Neither the name of the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

