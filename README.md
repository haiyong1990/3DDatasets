## Datasets

### Scene level

| Datasets      |#Scenes| #Rooms | #Frames | Annotated Structures |
|------------|---------|---------|---------|---------|
| [PlaneRCNN](https://github.com/NVlabs/planercnn)      | ~1,500 | ~1,500 | 100,000 (randomly sampled from 1 million) | planes |
| [Replica](https://github.com/facebookresearch/Replica-Dataset) | 18 | n/a | - | planes |
| [Wireframe](https://github.com/huangkuns/wireframe) | - | - | 5,462 | wireframe (2D) |
| [Wireframe Reconstruction](https://yichaozhou.com/publication/1811learning/) | synthetic and real images | - | - | wireframe (3D) |
| [SUN Primitive](http://3dvision.princeton.edu/projects/2012/SUNprimitive/) | - | - | 785 | cuboid, pyramid, cylinder, sphere, etc. |
| LSUN Room Layout | - | n/a | 5,396 | cuboid layout |
| [PanoContext](http://panocontext.cs.princeton.edu/) | - | n/a | 500 (pano) | cuboid layout |
| [LayoutNet](https://github.com/zouchuhang/LayoutNet) | - | n/a | 1,071 (pano) | cuboid layout |
| [MatterportLayout](https://github.com/ericsujw/Matterport3DLayoutAnnotation) | - | n/a | 2,295 (RGB-D pano) | Manhattan layout |
| [Floor-SP](https://github.com/woodfrog/floor-sp) | 100 | 707 | ~1500 (every scene has a set of RGB-D pano) | floorplan (with non-Manhattan structures) |
| [FloorNet](https://github.com/art-programmer/FloorNet) | ~150 | ~1000 | - | floorplan |
| [Raster-to-Vector](https://github.com/art-programmer/FloorplanTransformation) | 870 | - | - | floorplan |
| [3RScan](https://waldjohannau.github.io/RIO/) | 478 | - | - | objects |
| [Structured3D](https://structured3d-dataset.org/) | 3,500 | 21,835 | 196,515 | pritimitves (points/lines/planes) and relationships, 3D object instance bounding boxes|

### Object level

| Datasets      |#Images | #Categories | #3D models | Annotated Structures | Notes |
|------------|---------|---------|---------|---------|---------|
| [Keypoint-5](http://3dinterpreter.csail.mit.edu/) | 8,649 | 5 | - | keypoints | | 
| [IKEA Keypoints](http://3dinterpreter.csail.mit.edu/) | 759 | | 219 | keypoints | derived from [IKEA 3D](http://ikea.csail.mit.edu/) |
| [ANSI Mechanical Component](https://github.com/lingxiaoli94/SPFN) | - | 504 | 17,197 | plane, sphere, cylinder, cone, etc.| |
| [PartNet](https://cs.stanford.edu/%7Ekaichun/partnet/) | - | 24 | 26,671 | fine-grained, instance-level, and hierarchical 3D parts | derived from ShapeNet |
| [PartNet-Symh](https://github.com/FoggYu/PartNet_symh/) | - | 24 | 22,369 | Symmetry hierarchical 3D parts | derived from PartNet |
| [StructureNet](https://cs.stanford.edu/~kaichun/structurenet/) | - | 6 | - | Symmetry hierarchical 3D parts | derived from PartNet |

### Datasets examples
[PlaneRCNN](https://github.com/NVlabs/planercnn)

<div align="center">
<img src=figures/PlaneRCNN.jpg>
</div>

<div align="center">From left to right: input RGB image, planar segmentation, depthmap</div>

[Wireframe](https://github.com/huangkuns/wireframe)

<div align="center">
<img src=figures/Wireframe.jpg>
</div>

<div align="center">First row: manually labelled line segments. Second row: groundtruth junctions</div>

[Wireframe Reconstruction](https://yichaozhou.com/publication/1811learning/)

<div align="center">
<img src=figures/Wireframe_reconstruction.jpg>
</div>

<div align="center">From left column to right column: input image with groundtruth wireframes, predicted 3D wireframe and alternative view of the same image</div>

[SUN Primitive](http://3dvision.princeton.edu/projects/2012/SUNprimitive/)

<div align="center">
<img src=figures/SUN_Primitive.jpg>
</div>

<div align="center">Yellow: groundtruth, green: correct detection, red: false alarm</div>

LSUN Room Layout

<div align="center">
<img src=figures/LSUN_room.png>
</div>

<div align="center">From left right: input RGB image, room layout (corner-representation), room layout (segmentation-representation)</div>

[PanoContext](http://panocontext.cs.princeton.edu/)

<div align="center">
<img src=figures/PanoContext.jpg>
</div>

<div align="center">From left to right: a single-view panorama, object detection and 3D reconstruction</div>

[LayoutNet](https://github.com/zouchuhang/LayoutNet)

<div align="center">
<img src=figures/LayoutNet.jpg>
</div>

<div align="center">Orange lines: predicted layout, Green lines: groundtruth layout</div>

[Raster-to-Vector](https://github.com/art-programmer/FloorplanTransformation)

<div align="center">
<img src=figures/Raster_to_vector.jpg>
</div>

<div align="center">From left to right: an input floorplan image, reconstructed vector-graphics representation visualized by custom renderer, and a popup 3D model</div>

[Floor-SP](https://github.com/woodfrog/floor-sp)

<div align="center">
<img src=figures/Floor-SP.png>
</div>

<div align="center">From left to right: stitched RGB-D panorama of indoor scenes & top-view point density/normal map, vector-graphics floorplan with non-Manhattan structures</div>

[Structured3D](https://structured3d-dataset.org/)

<div align="center">
<img src=figures/Structured3D.jpg>
</div>

<div align="center">(a) house designs (b) ground truth 3D structure annotations (c) photo-realistic 2D images</div>

[Keypoint-5](http://3dinterpreter.csail.mit.edu/) and [IKEA Keypoints](http://3dinterpreter.csail.mit.edu/)

<div align="center">
<img src=figures/Keypoints_5_input.jpeg>
<img src=figures/Keypoints_5_label.jpeg>
</div>

<div align="center">Left: input image, right: labeled 2D keypoints</div>

[ANSI Mechanical Component](https://github.com/lingxiaoli94/SPFN)

<div align="center">
<img src=figures/ANSI.jpg>
</div>

<div align="center">Up to down: input point cloud and geometric primitives</div>

[PartNet](https://cs.stanford.edu/%7Ekaichun/partnet/)

<div align="center">
<img src=figures/PartNet.jpg>
</div>

<div align="center">From left column to right column:Three levels(from coarse to fine-grained) of segmentation annotations in the hierarchy,for three segmentation tasks</div>

[PartNet-Symh](https://github.com/FoggYu/PartNet_symh/)

<div align="center">
<img src=figures/PartNet_Symh.jpg>
</div>

<div align="center">Odd rows: groundtruth fine-grained segmentation results, even rows: prediction fine-grained segmentation results</div>

