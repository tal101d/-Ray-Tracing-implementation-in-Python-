The majority of the code consists of computations in Linear Algebra, combined with principles from Physics, to provide approximations of scene colors. External libraries were solely integrated to expedite calculations.

Scenes can be constructed manually by composing a text document, which is subsequently processed by the code to recognize pertinent objects and interpret the entire scene.

The code exhibits the capability to depict cubes, spheres, and planes. It employs the Phong model to define material properties, involving calculations for Ambient, Diffuse, and Specular components to predict object colors.

Furthermore, the code possesses the ability to generate renderings within a specified recursion depth, dictating how many times a ray can bounce before termination. This extends to rendering transparent and semi-transparent objects.

The code also incorporates the Soft Shadows technique, which is resource-intensive yet affords heightened realism. This technique involves casting a grid of rays for each light source to estimate the light received from non-negligible volume light sources at a given point.

A sample render output:![Rendered Scene](https://github.com/tal101d/-Ray-Tracing-implementation-in-Python-/assets/116706412/c83a5e9a-7643-483f-8969-4a3f47411842)





