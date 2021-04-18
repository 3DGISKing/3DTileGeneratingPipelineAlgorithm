# 3D Tile Generating Pipeline Algorithm

There are many 3d tile generators but the conversion process is still a black box to users.  
I started this project because I really wanted to know how they work under the hood.

## Pipeline Algorithm
### step1
Generate a density grid.

### step2
Subdivide a density grid and process it and get the hierarchical bounding box array.

## Open source 3d tile generators
- https://github.com/CesiumGS/3d-tiles-validator/tree/master/samples-generator
- https://github.com/PrincessGod/objTo3d-tiles
- https://github.com/saharilarshad/citygml-to-3dtiles
- https://github.com/saharilarshad/gltf-to-3dtiles
- https://github.com/fanvanzh/3dtiles
- https://github.com/Geodan/pg2b3dm
- https://github.com/daniel-hilton/gltf-b3dm-convertor

## References
- https://github.com/CesiumGS/3d-tiles/tree/master/specification  
- https://docs.opengeospatial.org/cs/18-053r2/18-053r2.html#27
- https://github.com/CesiumGS/3d-tiles/blob/master/3d-tiles-overview.pdf
- https://community.cesium.com/t/understanding-geometric-error/8480
- https://github.com/CesiumGS/3d-tiles/issues/162
- https://kb.orbitgt.com/204/technology/supported_formats/models/3dtiles
- https://cesium.com/blog/2017/03/30/spatial-subdivision/
- https://cesium.com/blog/2017/04/04/spatial-subdivision-in-practice/
- https://cesium.com/blog/2017/08/11/adaptive-subdivision-of-3d-tiles/
- https://community.safe.com/s/question/0D54Q000080hBIN/how-does-the-cesium-3d-tiles-writer-work