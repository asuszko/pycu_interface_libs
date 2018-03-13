# pycu_interface_libs

Precompiled shared libraries for [pycu_interface](https://github.com/asuszko/pycu_interface). Due to the current limitations of my graphics hardware available, I am only able to test out the following compiled shared libraries for Windows: sm_30 and sm_50, and for Linux: sm_30. However, historically speaking, when older compute architectures were tested functional, this translated into newer compilations working out of the box, as [CUDA is backwwards compatible](http://docs.nvidia.com/cuda/pascal-compatibility-guide/index.html) down to version 30.

## Setup

Copy the content of the latest compute version supported by your hardware (for example, sm_50) into the pycu_interface root folder. Test using the sample scripts found in the [pycu_interface samples directory](https://github.com/asuszko/pycu_interface/tree/master/samples).

## License
 
The MIT License (MIT)

Copyright (c) 2018 Arthur Suszko (art.suszko@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
