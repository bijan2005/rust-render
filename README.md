# rust-render
A raytracing 3D renderer written in Rust.

### Checklist of features

This list may be changed or extended in the future.

- [x] Raytracing camera
  - [x] Camera struct
  - [x] Ray creation code
- [x] Object code architecture
- [x] Sphere objects
  - [x] Sphere struct
  - [x] Sphere intersection test
  - [x] Sphere normal generation
  - [x] Color mapping on spheres
- [x] Plane objects
  - [x] Plane struct
  - [x] Plane intersection test
  - [x] Color mapping on planes
- [x] Triangle objects
  - [x] Triangle struct
  - [x] Triangle intersection test
  - [x] Triangle normal generation
  - [x] Color mapping on triangles
  - [x] Triangle mesh struct
  - [x] Triangle mesh intersection test
- [x] Bounding spheres
- [ ] Direct lighting
  - [ ] Point light sources
    - [x] Point source struct
    - [x] Point source illuminance test
    - [x] Hard shadows
    - [ ] Soft shadows
  - [ ] ~~Light-emitting surfaces~~
- [ ] Indirect lighting
  - [ ] Reflection
    - [ ] Perfectly reflective objects
    - [ ] Diffuse reflection
    - [ ] Roughness
  - [ ] Transparency
    - [ ] Simple transparency
    - [ ] Refraction
