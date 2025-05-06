# cs551-computer-graphics---homework-assignment-6---shaders-solved
**TO GET THIS SOLUTION VISIT:** [CS551 Computer Graphics – Homework Assignment 6 – Shaders Solved](https://www.ankitcodinghub.com/product/cs551-computer-graphics-homework-assignment-6-shaders-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97313&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS551 Computer Graphics - Homework Assignment 6 - Shaders Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<h2 dir="auto">Goals:</h2>
<ul dir="auto">
<li>
<p dir="auto">Understand how to program shaders that run on the GPU.

</li>
<li>
<p dir="auto">Become familiar with setting up a modern GPU drawing pipeline.

</li>
<li>
<p dir="auto">Understand cartoon shading.

</li>
<li>
<p dir="auto">Understand texture coordinates.

</li>
<li>
<p dir="auto">Understand normal mapping.

</li>
<li>
<p dir="auto">Understand cube maps.

</li>
<li>
<p dir="auto">(optional) Understand how to compute a tangent-space from texture coordinates.

</li>
</ul>
<h2 dir="auto"><a id="user-content-background" class="anchor" href="https://github.com/yig/graphics101-pipeline#background" aria-hidden="true"></a>Background</h2>
<ul dir="auto">
<li>Topics: The Graphics Pipeline, Viewing, Illumination, Texture Mapping, Meshes</li>
<li>Book (FoCG,4e): Chapter 17&nbsp;<em>Using Graphics Hardware</em>.</li>
<li>Video: “Lecture 8: The Graphics Pipeline” and “Lecture 9: Texture Mapping”, “Assignment 6: Shaders aka The Graphics Pipeline”, and “Assignment 6: Shaders addendum”</li>
<li>Quiz: Mesh Processing</li>
</ul>
<p dir="auto">(FoCG,4e is&nbsp;<em>Fundamentals of Computer Graphics (4th edition)</em>&nbsp;by Steve Marschner and Peter Shirley, 4th edition.)

<h2 dir="auto"><a id="user-content-getting-started--handing-in" class="anchor" href="https://github.com/yig/graphics101-pipeline#getting-started--handing-in" aria-hidden="true"></a>Getting Started &amp; Handing In:</h2>
<ul dir="auto">
<li>
<p dir="auto">Download or clone this code repository. I recommend cloning so you can easily integrate updates I release while you are working on the project. Don’t fork it on GitHub, or else your code will be visible to everyone.

</li>
<li>
<p dir="auto">Follow the instructions to install a working development environment:&nbsp;<a href="https://github.com/yig/graphics101">https://github.com/yig/graphics101</a>.

<ul dir="auto">
<li>
<p dir="auto">Optional: Install the&nbsp;<a href="https://www.glfw.org/" rel="nofollow">glfw</a>&nbsp;library for creating an OpenGL window. If you don’t install it this way, the&nbsp;<code>CMakeLists.txt</code>&nbsp;will download and compile&nbsp;<code>glfw</code>&nbsp;on the fly.

<ul dir="auto">
<li>
<p dir="auto">Mac with Homebrew package manager:&nbsp;<code>brew install glfw</code>.

</li>
<li>
<p dir="auto">Ubuntu Linux:&nbsp;<code>sudo apt-get install libglfw3-dev</code>.

</li>
<li>
<p dir="auto">Windows: It’s complicated. Just let the&nbsp;<code>CMakeLists.txt</code>&nbsp;compile it for you. If you really want to, you can use&nbsp;<a href="https://github.com/microsoft/vcpkg">vcpkg</a>. If you cloned&nbsp;<code>vcpkg</code>&nbsp;as&nbsp;<code>C:\src\vcpkg</code>:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>git clone https://github.com/microsoft/vcpkg
.\vcpkg\bootstrap-vcpkg.bat
.\vcpkg\vcpkg install glfw3
</code></pre>
</div>
<p dir="auto">if you are using a 64-bit Windows compiler toolchain, replace the last command with:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>.\vcpkg\vcpkg install glfw3:x64-windows
</code></pre>
</div>
<p dir="auto">and then copy the GLFW folder&nbsp;<code>vcpkg</code>&nbsp;installs to your&nbsp;<code>Program Files</code>&nbsp;or else add the following flag to your&nbsp;<code>cmake ..</code>:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>-DCMAKE_TOOLCHAIN_FILE=C:\src\vcpkg/scripts/buildsystems/vcpkg.cmake
</code></pre>
</div>
</li>
</ul>
</li>
</ul>
</li>
<li>
<p dir="auto">The code will be written in GLSL (OpenGL shading language) and C++. You are encouraged to write helper functions as you like.

</li>
<li>
<p dir="auto">There are separate downloads for three large examples. Unzip them and move the&nbsp;<code>head</code>,&nbsp;<code>lemon</code>, and&nbsp;<code>hercules</code>&nbsp;directories into your&nbsp;<code>pipeline/examples/</code>&nbsp;directory so that you end up with&nbsp;<code>pipeline/examples/head</code>,&nbsp;<code>pipeline/examples/lemon</code>, and&nbsp;<code>pipeline/examples/hercules</code>.

</li>
<li>
<p dir="auto">Copy the&nbsp;<code>mesh.cpp</code>‘s functions&nbsp;<code>computeNormals()</code>,&nbsp;<code>normalizingTransformation()</code>, and&nbsp;<code>applyTransformation()</code>&nbsp;from the&nbsp;<code>mesh.cpp</code>&nbsp;you wrote for the previous homework on&nbsp;<a href="https://github.com/yig/graphics101-meshes">meshes</a>. Don’t replace the&nbsp;<code>mesh.cpp</code>&nbsp;file with the one you previously wrote, because there’s a new function for this project and some functions aren’t needed (the half-edge support code is missing from this project). If you already turned in your&nbsp;<a href="https://github.com/yig/graphics101-meshes">meshes</a>&nbsp;homework, you can email us to request a guaranteed-correct version of&nbsp;<code>meshes.cpp</code>.

</li>
<li>
<p dir="auto">Build and run the code. The code should compile. When it runs, it will ask you to choose a JSON file specifying a scene. It can also be run as a command-line program taking a single argument, the path to the JSON file. That way you can specify a command-line argument in Qt Creator and simply run. Run these two JSON scene files to verify that everything is working. They don’t depend on any code you write:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  simplescene.json
  sphere.json
</code></pre>
</div>
<p dir="auto">You should see:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/simplescene.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/simplescene.png?w=980&amp;ssl=1" alt="simplescene.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/sphere-first.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/sphere-first.png?w=980&amp;ssl=1" alt="sphere.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">Once you add the missing code to&nbsp;<code>vao.cpp</code>,&nbsp;<code>sphere.json</code>&nbsp;will look as follows:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/sphere.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/sphere.jpg?w=980&amp;ssl=1" alt="sphere.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

</li>
<li>
<p dir="auto">Implement&nbsp;<code>vao.cpp</code>‘s&nbsp;<code>makeFromMesh()</code>&nbsp;to upload normals and texture coordinates to the GPU as per-vertex attributes. Create your vertex shader and fragment shaders for each shader. Modify the JSON scene files as needed. Tangent-space normal mapping will require you to modify additional C++ code (<code>mesh.cpp</code>‘s&nbsp;<code>computeTangentBitangent()</code>&nbsp;and&nbsp;<code>fancyscene.cpp</code>‘s&nbsp;<code>vaoFromOBJPath()</code>).

</li>
<li>
<p dir="auto">Build and run and test that it is working correctly. If you run the&nbsp;<code>pipeline</code>&nbsp;program with the&nbsp;<code>-h</code>&nbsp;or&nbsp;<code>--help</code>&nbsp;flag, you should see the following:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  Usage: ./pipeline [--width pixels] [--height pixels] [--screenshot path/to/save.png] [path/to/scene.json]
</code></pre>
</div>
</li>
<li>
<p dir="auto">Check your work with the&nbsp;<a href="https://github.com/yig/graphics101-pipeline-autograder">autograder</a>.

</li>
<li>
<p dir="auto">Here are the JSON scene files that will verify your output. Save screenshots by pressing the&nbsp;<code>s</code>&nbsp;key or by passing&nbsp;<code>--screenshot output.png</code>&nbsp;to the executable. Save a screenshot for each of the JSON scenes into an output subdirectory&nbsp;<code>screenshots</code>.

<ul dir="auto">
<li><code>phong_bunny.json</code></li>
<li><code>phong_sphere.json</code></li>
<li><code>cel_bunny.json</code></li>
<li><code>matcap_bunny.json</code></li>
<li><code>matcap_head.json</code></li>
<li><code>matcap_hercules.json</code></li>
<li><code>matcap_lemon.json</code></li>
<li><code>matcap_sphere.json</code></li>
<li><code>normalmap_cube.json</code></li>
<li><code>normalmap_head.json</code></li>
<li><code>normalmap_lemon.json</code></li>
<li><code>normalmap_hercules_bronze.json</code></li>
<li><code>normalmap_hercules_marble.json</code></li>
<li>… and any others that you make. You are required to make at least one (discussed below).</li>
</ul>
</li>
<li>
<p dir="auto">There is a cmake target&nbsp;<code>screenshots</code>&nbsp;that will do this for you, so you can just type&nbsp;<code>make screenshots</code>&nbsp;or&nbsp;<code>cmake --target screenshots --build .</code>&nbsp;in your&nbsp;<code>build</code>&nbsp;directory.

</li>
<li>
<p dir="auto">You will find reference output in the&nbsp;<code>examples/</code>&nbsp;directory. For each&nbsp;<code>&lt;filename&gt;.json</code>&nbsp;file, there is a&nbsp;<code>&lt;filename&gt;.png</code>&nbsp;screenshot taken from the default point of view.

</li>
<li>
<p dir="auto">Qt Creator has a great debugger for C++. For shaders, debugging is a bit trickier. When there is a GLSL error, you will see the shader code and the line number printed out to&nbsp;<em>Application Output</em>&nbsp;in Qt Creator.

</li>
<li>
<p dir="auto">Create a file named&nbsp;<code>Notes.txt</code>&nbsp;in the folder. Describe any known issues or extra features or things you attempted but did not finish. Name people in the class who deserve a star for helping you (not by giving your their code!).

</li>
<li>
<p dir="auto">When done, run the the&nbsp;<code>cpack</code>&nbsp;command from inside your build directory to generate an appropriate zip file of your&nbsp;<code>pipeline</code>&nbsp;project. The zip file it creates,&nbsp;<code>pipeline.zip</code>, will include the&nbsp;<code>screenshots</code>&nbsp;subdirectory and your&nbsp;<code>Notes.txt</code>&nbsp;file. It will ignore unneeded large and numerous directories (e.g.&nbsp;<code>build</code>,&nbsp;<code>examples/head</code>,&nbsp;<code>examples/hercules</code>,&nbsp;<code>examples/lemon</code>). Upload your&nbsp;<code>pipeline.zip</code>&nbsp;to Blackboard before the deadline.

</li>
<li>
<p dir="auto"><strong>THIS IS AN INDIVIDUAL, NOT A GROUP ASSIGNMENT. That means all code written for this assignment should be original! Although you are permitted to consult with each other while working on this assignment, code that is substantially the same will be considered cheating.</strong>&nbsp;In your&nbsp;<code>Notes.txt</code>, please note who deserves a star (who helped you with the assignment).

</li>
</ul>
<h2 dir="auto"><a id="user-content-overview" class="anchor" href="https://github.com/yig/graphics101-pipeline#overview" aria-hidden="true"></a>Overview:</h2>
<p dir="auto">In this assignment, you will be writing GLSL shaders. You will write a Phong shader (the same lighting model as in your ray tracer). You will implement reflections with a cube map. You will load high resolution normals from a texture and implement tangent-space normal mapping. (For this, you will also need to implement some additional mesh processing to create additional per-vertex attributes.) You will write a cartoon shader. For bonus, you can also write additional shaders and write OpenGL code to setup a different rendering pipeline. Your output will look like this:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/phong_bunny_norefract.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/phong_bunny_norefract.jpg?w=980&amp;ssl=1" alt="phong_bunny.json without refraction" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/phong_bunny_refract.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/phong_bunny_refract.jpg?w=980&amp;ssl=1" alt="phong_bunny.json with refraction" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/phong_sphere.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/phong_sphere.jpg?w=980&amp;ssl=1" alt="phong_sphere.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/cel_bunny.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/cel_bunny.jpg?w=980&amp;ssl=1" alt="cel_bunny.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/cel_sphere.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/cel_sphere.jpg?w=980&amp;ssl=1" alt="cel_sphere.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap_head.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap_head.jpg?w=980&amp;ssl=1" alt="matcap_head.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap_hercules.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap_hercules.jpg?w=980&amp;ssl=1" alt="matcap_hercules.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap_lemon.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap_lemon.jpg?w=980&amp;ssl=1" alt="matcap_lemon.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/normalmap_cube.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/normalmap_cube.jpg?w=980&amp;ssl=1" alt="normalmap_cube.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/normalmap_head.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/normalmap_head.jpg?w=980&amp;ssl=1" alt="normalmap_head.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/normalmap_hercules_bronze.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/normalmap_hercules_bronze.jpg?w=980&amp;ssl=1" alt="normalmap_hercules_bronze.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/normalmap_hercules_marble.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/normalmap_hercules_marble.jpg?w=980&amp;ssl=1" alt="normalmap_hercules_marble.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/normalmap_lemon.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/normalmap_lemon.jpg?w=980&amp;ssl=1" alt="normalmap_lemon.json" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<h2 dir="auto"><a id="user-content-rubric" class="anchor" href="https://github.com/yig/graphics101-pipeline#rubric" aria-hidden="true"></a>Rubric:</h2>
<ol dir="auto">
<li>
<p dir="auto"><strong>(40 points)</strong>&nbsp;Phong reflectance model. Your vertex shader only needs to transform the positions and normals. Your fragment shader is where the lighting is calculated. This is the same lighting model as you implemented for your ray tracer. However, you won’t be able to implement the global illumination terms the same way (shadow and reflection and refraction). In this assignment, you won’t be able to implement shadows at all. The simplified formula is:

<p dir="auto"><em>K<sub>R</sub>&nbsp;I<sub>R</sub>&nbsp;+ K<sub>T</sub>&nbsp;I<sub>T</sub>&nbsp;+ ∑<sub>L</sub>&nbsp;( K<sub>A</sub>&nbsp;I<sub>AL</sub>&nbsp;+ [ K<sub>D</sub>&nbsp;I<sub>L</sub>&nbsp;( N · L ) + K<sub>S</sub>&nbsp;I<sub>L</sub>&nbsp;( V · R )<sup>n</sup>&nbsp;] )</em>

<p dir="auto">Read on for details. In this assignment, all the parameters are stored as uniforms, which are global variables for shaders programs.&nbsp;<em>K<sub>A</sub></em>,&nbsp;<em>K<sub>S</sub></em>,&nbsp;<em>n</em>,&nbsp;<em>K<sub>R</sub></em>, and&nbsp;<em>K<sub>T</sub></em>&nbsp;refer to&nbsp;<code>material.color_ambient</code>,&nbsp;<code>material.color_specular</code>,&nbsp;<code>material.shininess</code>,&nbsp;<code>material.color_reflect</code>, and&nbsp;<code>material.color_refract</code>. If the boolean&nbsp;<code>material.use_diffuse_texture</code>&nbsp;is false, then&nbsp;<em>K<sub>D</sub></em>&nbsp;=&nbsp;<code>material.color_diffuse</code>. If&nbsp;<code>material.use_diffuse_texture</code>&nbsp;is true, use&nbsp;<em>K<sub>D</sub></em>&nbsp;=&nbsp;<code>material.color_diffuse</code>&nbsp;times the color stored in the texture map:&nbsp;<em>K<sub>D</sub></em>&nbsp;=&nbsp;<code>material.color_diffuse*texture( material.diffuse_texture, fTexCoord )</code>. The summation is over all&nbsp;<code>num_lights</code>&nbsp;of the&nbsp;<code>Light</code>&nbsp;structures;&nbsp;<em>I<sub>AL</sub></em>&nbsp;and&nbsp;<em>I<sub>L</sub></em>&nbsp;refer to&nbsp;<code>lights[i].color_ambient</code>&nbsp;and&nbsp;<code>.color</code>. The light&nbsp;<code>.position</code>&nbsp;should be interpreted as existing in eye-space, not world-space. See&nbsp;<em>Tips</em>&nbsp;below for converting between world and eye space.

<ul dir="auto">
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;Upload the normals and texture coordinates to the GPU as per-vertex attributes. To do this, you will implement&nbsp;<code>vao.cpp</code>‘s&nbsp;<code>makeFromMesh()</code>. You will see in that function how&nbsp;<code>mesh.positions</code>&nbsp;are uploaded. Do the same for&nbsp;<code>mesh.normals</code>&nbsp;and&nbsp;<code>mesh.texcoords</code>.

</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Vertex shader&nbsp;<code>phong.vs</code>. Use the provided uniforms&nbsp;<code>uProjectionMatrix</code>,&nbsp;<code>uViewMatrix</code>, and&nbsp;<code>uNormalMatrix</code>&nbsp;to transform the input world-space position&nbsp;<code>vPos</code>&nbsp;and normal&nbsp;<code>vNormal</code>&nbsp;into eye-space and pass them&nbsp;<em>out</em>&nbsp;to the fragment shader and set the output variable&nbsp;<code>gl_Position</code>. Pass the texture coordinate&nbsp;<code>vTexCoord</code>&nbsp;out unchanged.

<ul dir="auto">
<li>
<p dir="auto"><code>fPos</code>,&nbsp;<code>fNormal</code>, and&nbsp;<code>fTexCoord</code>&nbsp;are output variables, which is how you pass along this information to the fragment shader, which is where you do your lighting calculations. You can pass along&nbsp;<code>fPos</code>&nbsp;and&nbsp;<code>fNormal</code>&nbsp;in world-space or in eye-space, so long as you use a consistent space when you compute your lighting. (If you want to compute lighting in world-space, you will have to convert the light position and the eye position into world-space by multiplying them with&nbsp;<code>inverse(uViewMatrix)</code>.)

</li>
<li>
<p dir="auto"><code>uViewMatrix</code>&nbsp;is the matrix that converts a position in world-space into a position in eye-space:&nbsp;<code>uViewMatrix*p</code>&nbsp;converts&nbsp;<code>p</code>&nbsp;from world to eye-space.&nbsp;<code>uNormalMatrix</code>&nbsp;is the matrix that converts a normal from world-space to a normal in camera-space. It is equal to&nbsp;<code>transpose(inverse(mat3(uViewMatrix)))</code>.

</li>
<li>
<p dir="auto"><code>uProjectionMatrix</code>&nbsp;is the matrix that converts a position from camera-space to normalized-device coordinates.

</li>
<li>
<p dir="auto"><code>gl_Position</code>&nbsp;is the one variable you are required to assign in any vertex shader, so that the GPU knows which pixels are inside the triangle. You must set&nbsp;<code>gl_Position</code>&nbsp;to the position in normalized device coordinates.

</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(20 points)</strong>&nbsp;Fragment shader&nbsp;<code>phong.fs</code>. Implement ambient, diffuse, and specular illumination.

<ul dir="auto">
<li>
<p dir="auto"><strong>(2 points)</strong>&nbsp;Ambient lighting:&nbsp;<em>K<sub>A</sub>&nbsp;I<sub>AL</sub></em>.

</li>
<li>
<p dir="auto"><strong>(8 point)</strong>&nbsp;Diffuse lighting:&nbsp;<em>K<sub>D</sub>&nbsp;I<sub>L</sub>&nbsp;( N · L )</em>.&nbsp;<em>N</em>&nbsp;is the (normalized) surface normal vector and&nbsp;<em>L</em>&nbsp;is the (normalized) vector from the surface position to the light’s position. Note that if this dot product is negative, then the light is behind the surface and you should not add diffuse OR specular lighting.

</li>
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;Specular lighting: K<sub>S</sub>&nbsp;I<sub>L</sub>&nbsp;( V · R )<sup>n</sup>.&nbsp;<em>V</em>&nbsp;is the (normalized) vector from the surface position to the eye position. In eye-space the eye is located at the origin.&nbsp;<em>R</em>&nbsp;is the (normalized) direction from the light position to the surface position, reflected across the surface normal. The formula for reflecting a vector across another vector is given below under&nbsp;<em>Implementation Details</em>&nbsp;(or you can use the GLSL&nbsp;<code>reflect()</code>&nbsp;function). Note that if the dot product is negative, then the light is reflected away from the viewer and you should not add any specular lighting. (You can use max( 0, V · R) instead of an&nbsp;<code>if</code>&nbsp;statement if you desire.) Also note that if the dot product used for diffuse lighting is zero (the light is behind the surface), then you also should not add specular lighting.

</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(5 points)</strong>&nbsp;Implement reflections with a cube map (in the fragment shader) if&nbsp;<code>material.reflective</code>. Use the&nbsp;<em>world-space</em>&nbsp;reflected view direction as the parameter to the cube map:&nbsp;<code>texture( uEnvironmentTex, direction )</code>. The resulting color is&nbsp;<em>I<sub>R</sub></em>. If the direction you pass to the cube map is in eye-space, it’s as if the environment is rotating with the viewer, which means that the reflection will not change as you rotate the camera with the mouse.

</li>
<li>
<p dir="auto"><strong>(bonus 5 points)</strong>&nbsp;Implement refraction if&nbsp;<code>material.refractive</code>. Use the same cube map texture as in reflections to get&nbsp;<em>I<sub>T</sub></em>. You can get the refraction direction via the GLSL&nbsp;<code>refract()</code>&nbsp;function.

</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(30 points)</strong>&nbsp;Cel or toon shading. You only need to write a fragment shader&nbsp;<code>cel.fs</code>, since the same vertex shader as the one you wrote for Phong shading&nbsp;<code>phong.vs</code>&nbsp;can be re-used. Cel shading is the lighting effect used in games like&nbsp;<em>Zelda: Wind Waker</em>&nbsp;and&nbsp;<em>Breath of the Wild</em>,&nbsp;<em>Jet Set Radio</em>, and&nbsp;<em>Naruto Shippuden</em>. To achieve cel shading, we compute a scalar brightness value, round it to discrete levels, and then use that to scale the material color. The scalar brightness value&nbsp;<em>F</em>&nbsp;is computed with a simplified Phong reflectance in which no material colors&nbsp;<em>K</em>&nbsp;appear and the light color terms&nbsp;<em>I<sub>AL</sub></em>&nbsp;and&nbsp;<em>I<sub>L</sub></em>&nbsp;for&nbsp;<code>.color_ambient</code>&nbsp;and&nbsp;<code>.color</code>&nbsp;are simplified into scalar intensities:

<p dir="auto"><em>F = ∑<sub>L</sub>&nbsp;(I<sub>AL</sub>&nbsp;+ [I<sub>L</sub>&nbsp;( N · L ) + I<sub>L</sub>&nbsp;( V · R )<sup>n</sup>])</em>

<p dir="auto">Use the integer uniform&nbsp;<code>material.bands</code>&nbsp;to round&nbsp;<em>F</em>&nbsp;into discrete levels:&nbsp;<em>F<sub>discrete</sub></em>&nbsp;= min( floor(&nbsp;<em>F</em>&nbsp;*&nbsp;<em>F</em>&nbsp;*&nbsp;<code>material.bands</code>&nbsp;),&nbsp;<code>material.bands</code>&nbsp;– 1 )/(&nbsp;<code>material.bands</code>&nbsp;– 1). (Squaring&nbsp;<em>F</em>&nbsp;makes the bands more uniformly spaced.) The final color for a pixel is&nbsp;<em>K</em>&nbsp;*&nbsp;<em>F<sub>discrete</sub></em>, where&nbsp;<em>K</em>&nbsp;is the material color. If the boolean&nbsp;<code>material.use_diffuse_texture</code>&nbsp;is false, then&nbsp;<em>K</em>&nbsp;=&nbsp;<code>material.color</code>. If&nbsp;<code>material.use_diffuse_texture</code>&nbsp;is true, use&nbsp;<em>K</em>&nbsp;=&nbsp;<code>material.color</code>&nbsp;times the color stored in the texture map:&nbsp;<em>K</em>&nbsp;=&nbsp;<code>material.color*texture( material.diffuse_texture, fTexCoord )</code>. You will re-use your&nbsp;<code>phong.vs</code>&nbsp;and only write a different&nbsp;<code>cel.fs</code>.

</li>
<li>
<p dir="auto"><strong>(20 points + bonus 3 points)</strong>&nbsp;MatCaps with object-space normal mapping. You only need to write a fragment shader&nbsp;<code>matcap.fs</code>, since the same vertex shader as the one you wrote for Phong shading&nbsp;<code>phong.vs</code>&nbsp;can be re-used. A MatCap (Material Capture) is a delightfully simple and flexible technique to create realistic or artistic lighting for a shape. The idea is simple. Different points on a shape look different because the normals are different. Think about your Phong reflectance model. The material parameters and lights are shared by every point on the object. The vector&nbsp;<em>V</em>&nbsp;from the point to the eye varies slightly, but we could approximate this with a constant direction. This is all to say that the appearance of an object is almost entirely dependent on its normals in eye space. A MatCap is a lookup table from a normal to a color. A sphere has normals pointing in all directions. All we need to do is render a sphere and save its colors. To render, we just need to look up the color of the sphere with that normal. In fact, we only render the part of the shape we can see, so we only need to worry about front-facing normals (with&nbsp;<em>z</em>&gt;0 in eye-space). This gives us a very convenient way to store the lookup table:

</li>
</ol>
<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap-blue.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap-blue.png?w=980&amp;ssl=1" alt="matcap-blue.png" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">We store the front half of the sphere as a circle. To look up the color from the matcap, we just use the&nbsp;<em>x,y</em>&nbsp;component of the normal scaled and shifted to lie in the range [0,1]² instead of [-1,1]²:&nbsp;<code>color = texture( material.matcap_texture, n.xy*0.5 + 0.5 ).rgb</code>. We can create MatCaps any way we like. We can render a sphere with physically-based materials in a sophisticated lighting environment:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap-gold.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap-gold.png?w=980&amp;ssl=1" alt="matcap-gold.png" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>&nbsp;<a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap-lake.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap-lake.png?w=980&amp;ssl=1" alt="matcap-lake.png" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">We can also create an artistic sphere:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/docs/images/matcap-artred.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/docs/images/matcap-artred.png?w=980&amp;ssl=1" alt="matcap-artred.png" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<p dir="auto">Those MatCaps create the following bunnies:

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/examples/matcap_bunny-blue.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/examples/matcap_bunny-blue.png?resize=256%2C256&amp;ssl=1" width="256" height="256" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload" style="--smush-placeholder-width: 256px; --smush-placeholder-aspect-ratio: 256/256;"></a>

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/examples/matcap_bunny-gold.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/examples/matcap_bunny-gold.png?resize=256%2C256&amp;ssl=1" width="256" height="256" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload" style="--smush-placeholder-width: 256px; --smush-placeholder-aspect-ratio: 256/256;"></a>

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/examples/matcap_bunny-lake.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/examples/matcap_bunny-lake.png?resize=256%2C256&amp;ssl=1" width="256" height="256" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload" style="--smush-placeholder-width: 256px; --smush-placeholder-aspect-ratio: 256/256;"></a>

<p dir="auto"><a href="https://i0.wp.com/github.com/yig/graphics101-pipeline/blob/master/examples/matcap_bunny-artred.png?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/yig/graphics101-pipeline/raw/master/examples/matcap_bunny-artred.png?resize=256%2C256&amp;ssl=1" width="256" height="256" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload" style="--smush-placeholder-width: 256px; --smush-placeholder-aspect-ratio: 256/256;"></a>

<p dir="auto">You can see lots of MatCaps visualized on 3D shapes&nbsp;<a href="https://observablehq.com/@makio135/matcaps?ui=classic" rel="nofollow">here</a>.

<ul dir="auto">
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;In&nbsp;<code>matcap.fs</code>, set the output color to the color stored in the MatCap texture for the eye-space normal&nbsp;<code>fNormal</code>. If&nbsp;<code>material.use_diffuse_texture</code>, multiply the color by the diffuse texture color&nbsp;<code>texture( material.diffuse_texture, fTexCoord ).rgba</code>.

</li>
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;Object-space normal mapping. Texture resolution is typically much higher than vertex resolution. This is why we typically store colors in a texture map and not as vertex attributes. Along these same lines, we can store normals in a normal map in order to have render super-detailed surfaces. Normal maps are typically stored in tangent-space, which is substantially more difficult to implement. (Tangent-space normal mapping is described below for bonus points.) In&nbsp;<code>matcap.fs</code>, if&nbsp;<code>material.use_normal_map</code>, read the object-space normal from the texture via&nbsp;<code>texture( material.normal_map, fTexCoord ).rgb</code>. Normal components range from [-1,1], while colors range from [0,1], so each normal component is stored in the texture as&nbsp;<code>0.5*(n+1)</code>. Convert the color stored in the normalmap texture back to a normal via&nbsp;<code>2*color-1</code>. This normal is in object-space. Convert it to eye-space using&nbsp;<code>uNormalMatrix</code>&nbsp;and then use it instead of&nbsp;<code>fNormal</code>&nbsp;to read from the MatCap.

</li>
<li>
<p dir="auto"><strong>(bonus 3 points)</strong>&nbsp;Make your own MatCap! You can make a toon shader MatCap by taking a screenshot of a toon-shaded sphere. You can also make much cooler stuff. Have fun with this.

</li>
</ul>
<ol dir="auto" start="4">
<li>
<p dir="auto"><strong>(10 points)</strong>&nbsp;Be creative! Create a time-varying artistic shader of your own design. Make use of the uniform&nbsp;<code>uTime</code>, which stores the seconds since the program was launched. Declare it in your shader as&nbsp;<code>uniform float uTime;</code>&nbsp;Be sure to change&nbsp;<code>TimerMilliseconds</code>&nbsp;in the scene JSON file to something like 16 (which corresponds to 60 frames-per-second). See&nbsp;<code>sphere.vs</code>&nbsp;for an example.

</li>
<li>
<p dir="auto"><strong>(bonus 30 points)</strong>&nbsp;Normal mapping (<code>normalmap.vs</code>&nbsp;and&nbsp;<code>normalmap.fs</code>). This is an extension of your Phong reflectance model shader. With normal mapping, the texture stores a normal vector. Because lighting is entirely determined by the normal vector, high resolution normals make a surface look incredibly detailed. The normals in a normal maps are typically stored as vectors in the&nbsp;<em>tangent space</em>&nbsp;of the surface. This technique requires you to compute a “tangent frame” for each vertex (tangent and bitangent vectors to accompany the normal) and upload that to the GPU as additional attributes. To do this, you will implement&nbsp;<code>mesh.cpp</code>&nbsp;<code>computeTangentBitangent()</code>&nbsp;to compute the tangent frame and&nbsp;<code>fancyscene.cpp</code>&nbsp;<code>vaoFromOBJPath()</code>&nbsp;to upload the additional attributes to the GPU. (Computing and uploading this additional data for this shader won’t get in the way of the other shaders.) Each face has a well-defined tangent frame derived from the texture coordinates of its vertices; see the accompanying handout for details. Just like with per-vertex normals, you will pre-compute each face’s tangent frame vectors and average them at the vertices. In the vertex shader, you will convert the tangent and bitangent vectors from world-space to eye-space (using&nbsp;<code>uViewMatrix</code>) and pass them to the fragment shader. In the fragment shader, you will extract the tangent-space normal from the texture and convert it to world-space with the tangent frame matrix. That will be the normal you use for your lighting calculations. (You can reconstruct the tangent-frame matrix from the tangent, bitangent, and normal. Don’t forget to normalize them.) Implementation note: Normal components range from [-1,1], while colors range from [0,1], so each normal component is stored in the texture as&nbsp;<code>0.5*(n+1)</code>. Convert the color back to a normal via&nbsp;<code>2*color-1</code>.

<ul dir="auto">
<li>
<p dir="auto">For a deeper explanation of the coordinate systems involved in tangent-space normal mapping, see&nbsp;<a href="https://github.com/yig/graphics101-pipeline/blob/master/docs/tangent_space_normal_and_bump_mapping.pdf">this PDF</a>.

</li>
<li>
<p dir="auto">For a video explanation of normal mapping, see&nbsp;<a href="https://www.youtube.com/watch?v=yHzIx41eiD4" rel="nofollow">this YouTube video</a>.

</li>
</ul>
</li>
<li>
<p dir="auto"><strong>(bonus variable points):</strong>

<ul dir="auto">
<li>
<p dir="auto">Image Processing (blur, edge detect, etc.). Draw a full-screen textured square. Your vertex shader should pass along the position and texture coordinates, ignoring the view and projection transformations. Your fragment shader accesses the texture value at the pixel and at nearby pixels. You can use the GLSL function&nbsp;<code>textureSize( tex, 0 )</code>&nbsp;to get the texture width and height in pixels so that you can generate texture coordinates for the surrounding pixels.

</li>
<li>
<p dir="auto">Ray Tracer or Signed Distance Field renderer. Implement ray tracing or ray marching (as in some&nbsp;<a href="https://www.shadertoy.com/" rel="nofollow">ShaderToy</a>&nbsp;examples). Just like with Image Processing, the vertex shader does nothing. The fragment shader implements an entire ray tracer or ray marching. All geometry is specified via uniforms.

</li>
<li>
<p dir="auto">Animation. You can create a sequence of transformation matrices and interpolate between them (linearly or with an easing function). You can go further and implement linear blend skinning, in which there are multiple sequences of transformation matrices animating in parallel, and each vertex has a set of associated “skin” weights. The vertex is transformed by the weighted average transformation matrix. Some of the infrastructure for this is already implemented.

</li>
<li>
<p dir="auto">Ambient Occlusion. This provides a much more accurate surface ambient color&nbsp;<em>K<sub>A</sub></em>&nbsp;by computing the fraction of directions that are blocked by the mesh (a ray exiting the point with that direction would intersect the mesh). You can compute this in a pre-computation step or approximate it with a multi-pass shader. When computing it as a pre-process, you can store per-vertex attributes or a texture map.

</li>
<li>
<p dir="auto">Procedural textures. Generate a wood or marble color as a 3D function of position.

</li>
<li>
<p dir="auto">Geometry or tessellation shaders. We haven’t talked about these more exotic shaders, but the framework supports them.

</li>
<li>
<p dir="auto">Physically-Based Rendering. There are many ways to pursue this. Note that the&nbsp;<code>lemon</code>&nbsp;example comes with a gloss map.

</li>
<li>
<p dir="auto">Something else!

</li>
</ul>
</li>
</ol>
<h2 dir="auto"><a id="user-content-tips" class="anchor" href="https://github.com/yig/graphics101-pipeline#tips" aria-hidden="true"></a>Tips</h2>
<ul dir="auto">
<li>
<p dir="auto">If you see a blank screen (all background color and no shape), the problem is most likely in your vertex shader. This is assuming that your environment works (e.g. that&nbsp;<code>simplescene.json</code>&nbsp;and&nbsp;<code>sphere.json</code>&nbsp;produce the expected output).

</li>
<li>
<p dir="auto">The glm library is modeled after the OpenGL shading language GLSL. Anything involving&nbsp;<code>vec2</code>,&nbsp;<code>vec3</code>,&nbsp;<code>vec4</code>,&nbsp;<code>mat3</code>,&nbsp;<code>mat4</code>, etc. and virtually any GLSL functions should be accessible in C++ with the&nbsp;<code>glm::</code>&nbsp;prefix. There are many convenience constructors and math operations. Here is a nice reference:&nbsp;<a href="https://en.wikibooks.org/wiki/GLSL_Programming/Vector_and_Matrix_Operations" rel="nofollow">GLSL Programming: Vector and Matrix Operations</a>.

</li>
<li>
<p dir="auto">The GLSL (and glm) matrix constructors that take vectors use those vectors as the columns of the matrix, not the rows. (If you want to fill out the rows, fill out the columns and then call&nbsp;<code>transpose()</code>.) In fact, all matrix indexing uses column-then-row (column-major) ordering, which is different from what mathematicians do.

</li>
<li>
<p dir="auto">In C++ you can call the constructor of an object when you declare it, like so:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  vec4 foo( 1.0, 2.0, 3.0, 4.0 );
</code></pre>
</div>
<p dir="auto">GLSL does not allow this and you will get a compile error. Instead, you have to write:

<div class="snippet-clipboard-content notranslate position-relative overflow-auto">
<pre class="notranslate"><code>  vec4 foo = vec4( 1.0, 2.0, 3.0, 4.0 );
</code></pre>
</div>
</li>
<li>
<p dir="auto">Unless you assign a value, a local variable you declare will be uninitialized. While some implementations will initialize, for example,&nbsp;<code>vec3 foo;</code>&nbsp;to 0 by default, the GLSL specification does not require this. (The grader’s graphics driver will probably initialize to random values.) Manually initialize to 0,&nbsp;<code>vec3 foo = vec3(0);</code>, if that’s what you want.

</li>
<li>
<p dir="auto">There is a simple, sample 3D shader in&nbsp;<code>sphere.json</code>&nbsp;/&nbsp;<code>sphere.vs</code>&nbsp;/&nbsp;<code>sphere.fs</code>. (The simplest possible shader is in&nbsp;<code>simplescene.json</code>&nbsp;/&nbsp;<code>simplest.vs</code>&nbsp;/&nbsp;<code>simplest.fs</code>&nbsp;and is based off the&nbsp;<code>simplescene.h/cpp</code>&nbsp;C++ setup code.)

</li>
<li>
<p dir="auto">To convert a position from world-space to eye-space, left-multiply the provided uniform&nbsp;<code>uViewMatrix</code>&nbsp;by the position. To convert a normal from world-space to eye-space, use the provided uniform&nbsp;<code>uNormalMatrix</code>, which is the inverse-transpose of the upper-left 3×3 portion of&nbsp;<code>uViewMatrix</code>. To convert a position or direction from eye-to-world, use&nbsp;<code>inverse( uViewMatrix )</code>. To convert a direction (other than a normal) from eye-to-world, you can be more efficient and use&nbsp;<code>transpose( uNormalMatrix )</code>.

</li>
<li>
<p dir="auto">The GLSL function&nbsp;<code>texture(...)</code>, which loads a value from a texture, returns a&nbsp;<code>vec4</code>. Some overly permissive OpenGL drivers will allow you to use it as a&nbsp;<code>vec3</code>, but that behavior is wrong. Use&nbsp;<code>texture(...).rgb</code>&nbsp;to get the RGB components as a&nbsp;<code>vec3</code>&nbsp;or call&nbsp;<code>vec3(texture(...))</code>.

</li>
<li>
<p dir="auto">To reflect a (not necessarily normalized) vector&nbsp;<strong>v</strong>&nbsp;across a normalized vector&nbsp;<strong>n</strong>, the formula for the reflected vector&nbsp;<strong>r</strong>&nbsp;is&nbsp;<strong>r = v – 2(v·n)n</strong>.

<p dir="auto"><a href="https://github.com/yig/graphics101-pipeline/blob/master/docs/eqs/reflection.svg" target="_blank" rel="noopener noreferrer"><img decoding="async" data-src="https://github.com/yig/graphics101-pipeline/raw/master/docs/eqs/reflection.svg" alt="Illustration of a vector v reflected across a vector n" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

</li>
<li>
<p dir="auto">All of the required portions of the assignment can use the same C++ setup code (defined in&nbsp;<code>fancyscene.cpp</code>/<code>fancyscene.h</code>) and differ only in which shaders and uniforms are specified in the JSON file. (Only normal mapping requires you to modify some of the C++ setup code.)

</li>
<li>
<p dir="auto">You can achieve better code re-use in the shaders if you split them up. When you specify a shader in the JSON file, you can pass an array of file paths which will be concatenated together in sequence and then compiled. This allows you to write common helper functions in a&nbsp;<code>common.glsl</code>&nbsp;file if you so desire. The first line must always be a&nbsp;<code>#version</code>&nbsp;directive, so I often split my complex shaders into&nbsp;<code>[ shaderTop.vs, common.glsl, shaderBottom.vs ]</code>. It may also make sense to share a bottom but have different middles (e.g. normal mapping and Phong shading could share a bottom but have different middle files implementing an appropriate&nbsp;<code>get_normal()</code>&nbsp;function).

</li>
<li>
<p dir="auto">You can create your own C++ scene if you want to customize the camera or attributes. You will need to duplicate the scene class (<code>SimpleScene</code>&nbsp;or&nbsp;<code>FancyScene</code>) and register it with&nbsp;<code>pipelineguifactory.cpp</code>. For reference, you can see/study the simplest-possible OpenGL scene in&nbsp;<code>simplescene.h</code>&nbsp;and&nbsp;<code>simplescene.cpp</code>.

</li>
<li>
<p dir="auto">Almost everything in a JSON scene will live reload if using a&nbsp;<code>FancyScene</code>, including shaders, uniforms, and textures. The only property that will not live reload is&nbsp;<code>PipelineGUI</code>.

</li>
<li>
<p dir="auto">You can find lots of Creative Commons environment (cube) maps on the website of Emil Persson, aka Humus:&nbsp;<a href="http://www.humus.name/" rel="nofollow">http://www.humus.name</a>

</li>
<li>
<p dir="auto">You can find lots of MatCaps on this website:&nbsp;<a href="https://github.com/nidorx/matcaps">https://github.com/nidorx/matcaps</a>. You can see all the MatCaps nicely visualized here:&nbsp;<a href="https://observablehq.com/@makio135/matcaps?ui=classic" rel="nofollow">https://observablehq.com/@makio135/matcaps?ui=classic</a>

</li>
</ul>
