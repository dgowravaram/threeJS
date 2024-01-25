# threeJS

- npm init vite > select framework + jS/TS
- npm install three
- npm run dev to serve app locally

in index.html:
- add canvas tag for threeJS scene in body before script
- in style sheet fixed positioning

in main.js
- import threeJS. need 3 objects: scene, camera, renderer
- scene = container that holds objects, cameras, lights
- camera = to look @ things inside scene; most common = perspective camera
    - PerspectiveCamera(fieldOfView, aspectRatio, viewFrustrum)
- renderer = render graphics

create new torus object: 
- geometry: {x, y, z} points that make up shape
- material: wrapping paper for geometry
- mesh: construct shape w/ geomtery + material

no need to constantly recall render method, create game loop (recursive function for infinite loop of rendering) - animate()
