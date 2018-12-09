# Ceegyresuarus

This is a personal deposit for computer graphics related resource.

---

## Topics

### Textures

* [DXT and BC Compressions](http://reedbeta.com/blog/understanding-bcn-texture-compression-formats/)

### Procedural Graphics

* [Signed Distance Functions](https://www.iquilezles.org/www/articles/distfunctions/distfunctions.htm)

* [Perlin Noise](http://flafla2.github.io/2014/08/09/perlinnoise.html)

### GPU

* [VSync](https://computergraphics.stackexchange.com/questions/2166/how-does-vsync-affect-fps-exactly-when-not-at-full-vsync-fps)

### Collision & Physics

* [GJK Algorithm](https://caseymuratori.com/blog_0003)

* [Separate Axis Theorem](https://gamedevelopment.tutsplus.com/tutorials/collision-detection-using-the-separating-axis-theorem--gamedev-169)

### Rendering

* [Variance Shadow Map](http://lousodrome.net/blog/light/2012/01/23/variance-shadow-maps/)

* [Spherical Harmonic Lighting](https://dickyjim.wordpress.com/2013/09/04/spherical-harmonics-for-beginners/)

* [Light Probe](https://computergraphics.stackexchange.com/questions/4164/what-are-spherical-harmonics-light-probes)

* [Volumetric Lighting](https://developer.nvidia.com/VolumetricLighting)

* [Volumetric Rendering](https://www.ea.com/frostbite/news/physically-based-unified-volumetric-rendering-in-frostbite)

* [Screen Space Deferred Decal](https://bartwronski.com/2015/03/12/fixing-screen-space-deferred-decals/)

### Programming

* [Memory Allocator](https://github.com/mtrebi/memory-allocators#build-instructions)

* [Streaming SIMD Extensions](http://sci.tuomastonteri.fi/programming/sse)

* [C++ Array Decay](https://www.geeksforgeeks.org/what-is-array-decay-in-c-how-can-it-be-prevented/)

* [C++ Pure Virtual Destructor](https://eli.thegreenplace.net/2010/11/13/pure-virtual-destructors-in-c)

* [Build a Heap in O(n) Time Complexity](https://stackoverflow.com/questions/9755721/how-can-building-a-heap-be-on-time-complexity)

### Rasterization

* [Homogeneous Division after Clip Space](https://stackoverflow.com/questions/41085117/why-does-gl-divide-gl-position-by-w-for-you-rather-than-letting-you-do-it-your)

* [Reversed Z Buffer](https://developer.nvidia.com/content/depth-precision-visualized)

* [A Trip Through the Graphics Pipeline](https://fgiesen.wordpress.com/2011/07/06/a-trip-through-the-graphics-pipeline-2011-part-6/)

### Tessellation

* [Tessellation Modes Quick Reference](http://reedbeta.com/blog/tess-quick-ref/)

### APIs

* [Mapping between HLSL and GLSL](https://anteru.net/blog/2016/mapping-between-hlsl-and-glsl/index.html)

* [Discriptor Binding in DX12 and Vulkan](https://www.gamedev.net/forums/topic/678860-descriptor-binding-dx12-and-vulkan/)

* [DX12 do's and don'ts](https://developer.nvidia.com/dx12-dos-and-donts)

* [DX12 root signature & Vulkan descriptor sets](https://gpuopen.com/performance-root-signature-descriptor-sets/)

* [Common HRESULT Values](https://docs.microsoft.com/en-us/windows/desktop/seccrypto/common-hresult-values)

* [Error codes that can be returned by a DXGI function](https://docs.microsoft.com/en-us/windows/desktop/direct3ddxgi/dxgi-error)

* [Windows 10 adds a border around a window](https://stackoverflow.com/questions/34139450/getwindowrect-returns-a-size-including-invisible-borders)

---

## Blogs and Websites

* https://pharr.org/matt/blog/

* http://erich.realtimerendering.com

* https://www.iquilezles.org

* https://herbsutter.com

* http://reedbeta.com

* https://bartwronski.com/

* http://fabiensanglard.net

* http://madebyevan.com/

* https://mynameismjp.wordpress.com

* https://prideout.net/blog/old/blog.html

* https://prideout.net/

* http://casual-effects.com/#blog

* http://taichi.graphics/

* http://www.ludicon.com/castano/blog

* http://efficientshading.com

* https://caseymuratori.com

* http://www.adriancourreges.com

* http://jpgrenier.org/index.html

* http://lousodrome.net/blog/light

* https://www.alanzucconi.com/tutorials/

* http://humus.name/index.php?page=News

* http://kesen.realtimerendering.com

* http://advances.realtimerendering.com/

---

## Assets

### Model

* http://casual-effects.com/data/

---

## Notes

### APIs

* [D3D use right multiply while OpenGL use left multiply.](https://docs.microsoft.com/en-us/windows/desktop/dxtecharts/the-direct3d-transformation-pipeline)

* [D3D use left hand coordinates while OpenGL use right hand coordinates by default.](https://docs.microsoft.com/en-us/windows/desktop/api/directxmath/nf-directxmath-xmmatrixlookatlh)

* [D3D texture start at top-left corner while OpenGL texture start from bottom-left corner.](https://docs.microsoft.com/en-us/windows/desktop/direct3d9/texture-coordinates)

* [D3D z value in NDC ranges from 0 to 1 while OpenGL z value in NDC ranges from -1 to 1 by default.](https://docs.microsoft.com/en-us/windows/desktop/direct3d9/projection-transform)

* [D3D12_RESOURCE_STATE_NON_PIXEL_SHADER_RESOURCE is actually NON_Pixel_Shader_SHADER_RESOURCE.](https://docs.microsoft.com/en-us/windows/desktop/api/d3d12/ne-d3d12-d3d12_resource_states)

### C & C++

* [Character literals are treated as int in C whereas char in C++.](https://www.geeksforgeeks.org/g-fact-54/)

* [Sizeof operator will generate 0 for an empty structure in C whereas 1 for an empty structure in C++.](https://www.geeksforgeeks.org/difference-c-structures-c-structures/)

* [Pass NULL as C++ function argument can lead to ambiguous function call when the function is overloaded to take int as argument.](https://www.geeksforgeeks.org/understanding-nullptr-c/)

* [C allows a void* pointer to be assigned to any pointer type without a cast, whereas C++ requires an explicit cast.](https://www.geeksforgeeks.org/g-fact-12-2/)

* [Virtual function can be inlined when called using the object of that class instead of base class reference or pointer.](https://www.geeksforgeeks.org/inline-virtual-function/)

* [Virtual functions can be private in C++.](https://www.geeksforgeeks.org/can-virtual-functions-be-private-in-c/)

* [C++ only allows static const integral members to be initialized inline before C++ 11.](https://stackoverflow.com/questions/225089/why-cant-we-initialize-members-inside-a-structure)
