# Ray Tracer

## An interactive Ray Tracer application build under an MVC architecture.

### The implementation contains the following features:
  1. Multithreaded image rendering.
  2. Rendering of circles, rectangles, cubes, spheres, toruses, cones, cylinders and triangles
  3. Rendering of two different textures (normal texture and checkered texture).
  4. Phong reflection model (Ambient Lighting + Diffuse Reflection + Specular Reflection) .
  5. Shininess -  Polished feeling of the surface of an object - and shadows.
  6. Super sampling - A method of anti-aliasing (spatial) used to remove harsh edges from the rendered image.
  7. Interractive GUI.

The application is launched from the `RayTracerApplication` located in the `utility` sub-package. Once the application has started proceed to http://localhost:8080.


## Model Values for a sample scene:
#### Sphere:
**Radius:** 10\
**Color:** any\
**Center Position:** {20,10,0}\
**Surface:** Normal\
**Reflection:** 60\
**Advanced settings are optional**

#### Plane:
**Width:** 70\
**Height:** 70\
**Color:** any\
**Center position:** {0,0,0}\
**Surface:** Checkers\
**Rotation:** {-90,0,0}\
**Reflection:** 50

#### Cube:
**Color:** any\
**Center position:** {-20,10,0}\
**Dimensions:** 20, 20, 20\
**Surface:** Normal\
**Rotation:** {0,1,0}\
**Reflection:** 50

#### Light:
**Color:** FFFFFFFF (white)\
**Direction:** {1,-20,1}


![alt text](https://github.com/AndreiIM/RayTracer/blob/master/Sphere_Cube.png "Sample Image")


