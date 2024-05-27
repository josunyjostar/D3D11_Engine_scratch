
## vcpkg install 
<pre>
cmd 실행
git clone https://github.com/microsoft/vcpkg
.\vcpkg\bootstrap-vcpkg.bat
.\vcpkg\vcpkg integrate install
</pre>
-------------
## vcpkg install list
-------------
<pre>
cmd에서 경로를 설치된 vcpkg로 옮긴다
vcpkg install assimp:x64-windows                                
vcpkg install directxmath:x64-windows                           
vcpkg install directxmesh:x64-windows                           
vcpkg install directxtex:x64-windows                            
vcpkg install directxtex[dx11]:x64-windows                      
vcpkg install directxtex[openexr]:x64-windows                   
vcpkg install directxtk:x64-windows                             
vcpkg install draco:x64-windows                                 
vcpkg install fp16:x64-windows                                  
vcpkg install glm:x64-windows                                   
vcpkg install imath:x64-windows                                 
vcpkg install imgui:x64-windows                                 
vcpkg install imgui[dx11-binding]:x64-windows                   
vcpkg install imgui[win32-binding]:x64-windows                  
vcpkg install kubazip:x64-windows                               
vcpkg install minizip:x64-windows                               
vcpkg install openexr:x64-windows                               
vcpkg install physx:x64-windows                                 
vcpkg install poly2tri:x64-windows                              
vcpkg install polyclipping:x64-windows                          
vcpkg install psimd:x64-windows                                 
vcpkg install pugixml:x64-windows                               
vcpkg install rapidjson:x64-windows                             
vcpkg install stb:x64-windows                                   
vcpkg install utfcpp:x64-windows                                
vcpkg install vcpkg-cmake-config:x64-windows                    
vcpkg install vcpkg-cmake-get-vars:x64-windows                  
vcpkg install vcpkg-cmake:x64-windows                           
vcpkg install zlib:x64-windows                               
</pre>
## vcpkg list version info
-------------
| branchname | version / date |  desc | 
|:------:|:---:|:---:|
|assimp:x64-windows                               |5.3.1#1            | The Open Asset import library|
|directxmath:x64-windows                          |2022-12-12         | DirectXMath SIMD C++ math library|
|directxmesh:x64-windows                          |2023-06-13         | DirectXMesh geometry processing library|
|directxtex:x64-windows                           |2023-09-01         | DirectXTex texture processing library|
|directxtex[dx11]:x64-windows                     |                   | Build with DirectX11 support|
|directxtex[openexr]:x64-windows                  |                   | Enable OpenEXR support|
|directxtk:x64-windows                            |2023-09-01#1       | A collection of helper classes for writing Direc...|
|draco:x64-windows                                |1.5.6              | A library for compressing and decompressing 3D g...|
|fp16:x64-windows                                 |2021-02-21#2       | Header-only library for conversion to/from half-...|
|glm:x64-windows                                  |2023-06-08         | OpenGL Mathematics (GLM)|
|imath:x64-windows                                |3.1.9#1            | Imath is a C++ and Python library of 2D and 3D v...|
|imgui:x64-windows                                |1.89.9             | Bloat-free Immediate Mode Graphical User interfa...|
|imgui[dx11-binding]:x64-windows                  |                   | Make available DirectX11 binding|
|imgui[win32-binding]:x64-windows                 |                   | Make available Win32 binding|
|kubazip:x64-windows                              |0.2.4              | A portable, simple zip library written in C|
|minizip:x64-windows                              |1.3#1              | Minizip zip file manipulation library|
|openexr:x64-windows                              |3.1.8              | OpenEXR is a high dynamic-range (HDR) image file...|
|physx:x64-windows                                |5.3.0              | The NVIDIA PhysX SDK is a scalable multi-platfor...|
|poly2tri:x64-windows                             |2020-07-21#3       | The Clipper library performs clipping and offset...|
|polyclipping:x64-windows                         |6.4.2#12           | The Clipper library performs clipping and offset...|
|psimd:x64-windows                                |2021-02-21#2       | Portable 128-bit SIMD intrinsics|
|pugixml:x64-windows                              |1.14               | Light-weight, simple and fast XML parser for C++...|
|rapidjson:x64-windows                            |2023-07-17         | A fast JSON parser/generator for C++ with both S...|
|stb:x64-windows                                  |2023-04-11#1       | public domain header-only libraries|
|utfcpp:x64-windows                               |3.2.5              | UTF-8 with C++ in a Portable Way|
|vcpkg-cmake-config:x64-windows                   |2022-02-06#1       |
|vcpkg-cmake-get-vars:x64-windows                 |2023-03-02         |
|vcpkg-cmake:x64-windows                          |2023-05-04         |
|zlib:x64-windows                                 |1.3                | A compression library|

