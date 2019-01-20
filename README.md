# Ceegyresuarus

This is a personal deposit for computer graphics related resource.

---

## I.Topics

### 1.Textures

* [DXT and BC Compressions](http://reedbeta.com/blog/understanding-bcn-texture-compression-formats/)

* [D3D11 Texture Format and Feature Support](https://docs.microsoft.com/en-us/windows/desktop/direct3ddxgi/format-support-for-direct3d-11-0-feature-level-hardware)

### 2.Procedural Graphics

* [Signed Distance Functions](https://www.iquilezles.org/www/articles/distfunctions/distfunctions.htm)

* [Perlin Noise](http://flafla2.github.io/2014/08/09/perlinnoise.html)

* [Simplex Noise](http://staffwww.itn.liu.se/~stegu/simplexnoise/simplexnoise.pdf)

### 3.Hardware

* [DXGI Flip Model & BlkBlt Model](https://docs.microsoft.com/en-us/windows/desktop/direct3ddxgi/dxgi-flip-model)

* [VSync](https://computergraphics.stackexchange.com/a/2296)

* [Cache Coherency](https://fgiesen.wordpress.com/2014/07/07/cache-coherency/)

* [Asynchronous Timewarp on Oculus Rift](https://developer.oculus.com/blog/asynchronous-timewarp-on-oculus-rift/)

* [WDDM](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/windows-vista-display-driver-model-design-guide) & [XDDM](https://docs.microsoft.com/en-us/windows-hardware/drivers/display/windows-2000-display-driver-model-design-guide)

### 4.Math & Physics

* [GJK Algorithm](https://caseymuratori.com/blog_0003)

* [Separate Axis Theorem](https://gamedevelopment.tutsplus.com/tutorials/collision-detection-using-the-separating-axis-theorem--gamedev-169)

* [The Jacobi and Gauss-Seidel Iterative Methods](https://www3.nd.edu/~zxu2/acms40390F12/Lec-7.3.pdf)

### 5.Rendering

#### Shadow Mapping

* [Variance Shadow Map](http://lousodrome.net/blog/light/2012/01/23/variance-shadow-maps/)

* [Cascaded Shadow Map (Parallel Split Shadow Map)](https://developer.download.nvidia.com/SDK/10.5/opengl/src/cascaded_shadow_maps/doc/cascaded_shadow_maps.pdf)

* [Sparse Shadow Tree](https://www.activision.com/cdn/research/SparseShadowTree.pdf)

#### Anti-Aliasing

* [Subpixel Morphological Anti-Aliasing](http://www.iryoku.com/smaa/)

* [FXAA](https://developer.download.nvidia.com/assets/gamedev/files/sdk/11/FXAA_WhitePaper.pdf)

* [Deferred MSAA](https://docs.nvidia.com/gameworks/content/gameworkslibrary/graphicssamples/d3d_samples/antialiaseddeferredrendering.htm)

#### Volumetric Rendering

* [Real-Time Volumetric Rendering by Patapom](https://patapom.com/topics/Revision2013/Revision%202013%20-%20Real-time%20Volumetric%20Rendering%20Course%20Notes.pdf)

* [Volumetric Lighting](https://developer.nvidia.com/VolumetricLighting)

* [Physically Based Sky, Atmosphere & Cloud Rendering](https://www.ea.com/frostbite/news/physically-based-sky-atmosphere-and-cloud-rendering)

* [Siggraph 2015 EA Volumetric Rendering](https://www.ea.com/frostbite/news/physically-based-unified-volumetric-rendering-in-frostbite)

#### Misc.

* [Spherical Harmonic Lighting](https://dickyjim.wordpress.com/2013/09/04/spherical-harmonics-for-beginners/)

* [Light Probe](https://computergraphics.stackexchange.com/questions/4164/what-are-spherical-harmonics-light-probes)

* [Screen Space Deferred Decal](https://bartwronski.com/2015/03/12/fixing-screen-space-deferred-decals/)

* [Premultiplied-Alpha](https://blogs.msdn.microsoft.com/shawnhar/2009/11/06/premultiplied-alpha/)

* [A Particle System Example](http://alextardif.com/Particles.html)

* [Tessellation Modes Quick Reference](http://reedbeta.com/blog/tess-quick-ref/)

* [CDLOD Terrain](https://github.com/fstrugar/CDLOD)

### 6.Programming

* [Memory Allocator](https://github.com/mtrebi/memory-allocators#build-instructions)

* [Streaming SIMD Extensions](http://sci.tuomastonteri.fi/programming/sse)

* [C++ Array Decay](https://www.geeksforgeeks.org/what-is-array-decay-in-c-how-can-it-be-prevented/)

* [C++ Pure Virtual Destructor](https://eli.thegreenplace.net/2010/11/13/pure-virtual-destructors-in-c)

* [Build a Heap in O(n) Time Complexity](https://stackoverflow.com/questions/9755721/how-can-building-a-heap-be-on-time-complexity)

* [Difference between VERIFY and ASSERT](https://stackoverflow.com/questions/2642424/is-verify-a-good-practice-in-c-coding)

* [Initialization in C++](https://mikelui.io/2019/01/03/seriously-bonkers.html)

* [Writing Main Function in an Array](http://jroweboy.github.io/c/asm/2015/01/26/when-is-main-not-a-function.html)

* [Floating Point Math](https://randomascii.wordpress.com/category/floating-point/)

* [A Matter of Precision](http://tomforsyth1000.github.io/blog.wiki.html#%5B%5BA%20matter%20of%20precision%5D%5D)

### 7.Rasterization

* [Homogeneous Division after Clip Space](https://stackoverflow.com/questions/41085117/why-does-gl-divide-gl-position-by-w-for-you-rather-than-letting-you-do-it-your)

* [Reversed Z Buffer](https://developer.nvidia.com/content/depth-precision-visualized)

* [A Trip Through the Graphics Pipeline](https://fgiesen.wordpress.com/2011/07/06/a-trip-through-the-graphics-pipeline-2011-part-6/)

### 8.APIs

* [Mapping between HLSL and GLSL](https://anteru.net/blog/2016/mapping-between-hlsl-and-glsl/index.html)

* [Discriptor Binding in DX12 and Vulkan](https://www.gamedev.net/forums/topic/678860-descriptor-binding-dx12-and-vulkan/)

* [DX12 do's and don'ts](https://developer.nvidia.com/dx12-dos-and-donts)

* [DX12 root signature & Vulkan descriptor sets](https://gpuopen.com/performance-root-signature-descriptor-sets/)

* [Difference between DX12 & Vulkan command queues](https://www.gamedev.net/forums/topic/700092-directx-12-command-queues/?do=findComment&comment=5396143)

* [Common HRESULT Values](https://docs.microsoft.com/en-us/windows/desktop/seccrypto/common-hresult-values)

* [Error codes that can be returned by a DXGI function](https://docs.microsoft.com/en-us/windows/desktop/direct3ddxgi/dxgi-error)

* [Windows 10 adds a border around a window](https://stackoverflow.com/questions/34139450/getwindowrect-returns-a-size-including-invisible-borders)

* [Direct3D 11 Debug API Tricks](https://seanmiddleditch.com/direct3d-11-debug-api-tricks/)

---

## II.Blogs and Websites

* https://www.jendrikillner.com/post/

* https://pharr.org/matt/blog/

* http://erich.realtimerendering.com

* https://www.iquilezles.org

* https://herbsutter.com

* http://reedbeta.com

* https://bartwronski.com/

* http://fabiensanglard.net

* http://madebyevan.com/

* https://mynameismjp.wordpress.com

* http://eelpi.gotdns.org/blog.wiki.html

* https://randomascii.wordpress.com/

* http://c0de517e.blogspot.com/

* https://blog.demofox.org/

* http://alextardif.com/index.html

* https://blogs.msdn.microsoft.com/shawnhar/

* https://prideout.net/blog/old/blog.html

* https://prideout.net/

* http://casual-effects.com/#blog

* http://taichi.graphics/

* http://www.ludicon.com/castano/blog

* http://efficientshading.com

* https://raytracey.blogspot.com/

* https://caseymuratori.com

* http://www.adriancourreges.com

* http://jpgrenier.org/index.html

* http://lousodrome.net/blog/light

* https://www.alanzucconi.com/tutorials/

* http://humus.name/index.php?page=News

* http://kesen.realtimerendering.com

* http://advances.realtimerendering.com/

---

## III.Assets

### Books

* http://www.realtimerendering.com/books.html

* https://ebookfoundation.github.io/free-programming-books/free-programming-books.html

* [Physically Based Rendering: From Theory To Implementation Third Edition](http://www.pbr-book.org/)

* [Linux Device Drivers Third Edition](https://lwn.net/Kernel/LDD3/)

* [Ray Tracing in One Weekend](http://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf)

* [Ray Tracing: The Next Week](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20The%20Next%20Week.pdf)

* [Ray Tracing: The Rest of Your Life](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20the%20Rest%20of%20Your%20Life.pdf)

### 3D Models

* http://casual-effects.com/data/

### Tools

* [UIforETW](https://randomascii.wordpress.com/2015/09/24/etw-central/)

---

## IV.Notes

### Rendering

* [Parallel Split Shadow Map is the academic name for Cascaded Shadow Map](https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch10.html)

### Direct3D & OpenGL

* [D3D use right multiply while OpenGL use left multiply.](https://docs.microsoft.com/en-us/windows/desktop/dxtecharts/the-direct3d-transformation-pipeline)

* [D3D use left hand coordinates while OpenGL use right hand coordinates by default.](https://docs.microsoft.com/en-us/windows/desktop/api/directxmath/nf-directxmath-xmmatrixlookatlh)

* [D3D texture start at top-left corner while OpenGL texture start from bottom-left corner.](https://docs.microsoft.com/en-us/windows/desktop/direct3d9/texture-coordinates)

* [D3D z value in NDC ranges from 0 to 1 while OpenGL z value in NDC ranges from -1 to 1 by default.](https://docs.microsoft.com/en-us/windows/desktop/direct3d9/projection-transform)

* [D3D12_RESOURCE_STATE_NON_PIXEL_SHADER_RESOURCE is actually NON Pixel Shader SHADER RESOURCE. It's for VS, HS, DS and GS.](https://docs.microsoft.com/en-us/windows/desktop/api/d3d12/ne-d3d12-d3d12_resource_states)

* [D3D SV_Position.w is w while gl_FragCoord.w is 1/w.](https://www.gamedev.net/forums/topic/698741-w-component-of-sv_positiongl_fragcoord/?tab=comments#comment-5397351)

* [D3D12 unnamed command queue being released while still in use by the GPU](https://www.gamedev.net/forums/topic/700769-d3d12-unnamed-command-queue-being-final-released-while-still-in-use-by-the-gpu/?tab=comments#comment-5399076)

* [D3D9 specify back buffer counts](https://docs.microsoft.com/en-us/windows/desktop/direct3d9/d3dpresent-parameters) while [D3D11 specify buffer counts](https://docs.microsoft.com/en-us/windows/desktop/api/dxgi/ns-dxgi-dxgi_swap_chain_desc)

### C & C++

* [Character literals are treated as int in C whereas char in C++.](https://www.geeksforgeeks.org/g-fact-54/)

* [Sizeof operator will generate 0 for an empty structure in C whereas 1 for an empty structure in C++.](https://www.geeksforgeeks.org/difference-c-structures-c-structures/)

* [Pass NULL as C++ function argument can lead to ambiguous function call when the function is overloaded to take int as argument.](https://www.geeksforgeeks.org/understanding-nullptr-c/)

* [C allows a void* pointer to be assigned to any pointer type without a cast, whereas C++ requires an explicit cast.](https://www.geeksforgeeks.org/g-fact-12-2/)

* [Virtual function can be inlined when called using the object of that class instead of base class reference or pointer.](https://www.geeksforgeeks.org/inline-virtual-function/)

* [Virtual functions can be private in C++.](https://www.geeksforgeeks.org/can-virtual-functions-be-private-in-c/)

* [C++ only allows static const integral members to be initialized inline before C++ 11.](https://stackoverflow.com/questions/225089/why-cant-we-initialize-members-inside-a-structure)
