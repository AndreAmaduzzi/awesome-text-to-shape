# Awesome Text-to-Shape
A collection of resources on text-to-shape tasks.

## Overview
This repository collects works which connect text to 3D data. Overall, this collection is organized as follows. _If you find some works which are missing, feel free to raise an issue or create a pull request. Contributions in any form are strongly appreciated._
* Text-driven Shape Generation
  * Point cloud
  * Voxel
  * Mesh
  * Neural Field
* Text-driven Shape Manipulation
  * Point cloud
  * Voxel
  * Mesh
  * Neural Field
* Datasets
* Evaluation Metrics
* Surveys 

## Text-driven Shape Generation
The methods which are able to generate 3D data from text can be categorized by the representation they use.

### Point Cloud
* **Point-E: A System for Generating 3D Point Clouds from Complex Prompts**
  
  [ArXiv 2022](https://arxiv.org/abs/2212.08751) | [Code](https://github.com/openai/point-e)

* **Neural Shape Compiler: a unified framework for transforming between text, point cloud and program**

  [ArXiv 2022](https://arxiv.org/abs/2212.12952) | [Code](https://github.com/tiangeluo/ShapeCompiler) | [Project](https://tiangeluo.github.io/projectpages/shapecompiler.html)

### Voxel
* **Text2Shape: Generating Shapes from Natural Language by Learning Joint Embeddings**
  
  [ArXiv 2018](https://arxiv.org/abs/1803.08495) | [Code](https://github.com/kchen92/text2shape/) | [Project](http://text2shape.stanford.edu/)

* **Clip-Forge**

  [CVPR 2022](https://arxiv.org/abs/2110.02624) | [Code](https://github.com/AutodeskAILab/Clip-Forge)
  
* **Towards Implicit Text-Guided 3D Shape Generation**
  
  [CVPR 2022](https://arxiv.org/abs/2203.14622) | [Code](https://github.com/liuzhengzhe/Towards-Implicit-Text-Guided-Shape-Generation)

### Mesh
* **ShapeCrafter: A Recursive Text-Conditioned 3D Shape Generation Model**

  [ArXiv 2022](https://arxiv.org/abs/2207.09446) | [Code](https://github.com/FreddieRao/ShapeCrafter) | [Project](https://ivl.cs.brown.edu/#/projects/shapecrafter)

* **AutoSDF: Shape Priors for 3D Completion, Reconstruction and Generation**

  [CVPR 2022](https://arxiv.org/abs/2203.09516) | [Code](https://github.com/yccyenchicheng/AutoSDF/) | [Project](https://yccyenchicheng.github.io/AutoSDF/) 

* **ISS: Image as stepping stone for Text-Guided 3D Shape Generation**

  [ArXiv 2022](https://arxiv.org/abs/2209.04145)
  
* **Neural Wavelet-domain Diffusion for 3D Shape Generation, Inversion, and Manipulation**  

  [SIGGRAPH Asia 2022](https://arxiv.org/pdf/2302.00190.pdf)
  
* **Magic3D: High-Resolution Text-to-3D Content Creation**

  [ArXiv 2022](https://arxiv.org/abs/2211.10440) | [Project](https://deepimagination.cc/Magic3D/)

### Neural Radiance Fields
* **Zero-Shot Text-Guided Object Generation with Dream Fields**

   [CVPR 2022](https://arxiv.org/pdf/2112.01455.pdf) | [Code](https://github.com/google-research/google-research/tree/master/dreamfields) | [Project](https://ajayj.com/dreamfields)

* **DreamFusion: Text-to-3D using 2D Diffusion**

  [ArXiv 2022](https://arxiv.org/abs/2209.14988) | [Project](https://dreamfusion3d.github.io/)
 
* **Dream3D: Zero-Shot Text-to-3D Synthesis Using 3D Shape Prior and Text-to-Image Diffusion Models**

  [ArXiv 2022](https://arxiv.org/abs/2212.14704) | [Project](https://bluestyle97.github.io/dream3d/)

* **Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields** 
 
  [ArXiV 2023](https://arxiv.org/pdf/2305.11588.pdf)

## Other tasks
* **CLIP2Point: Transfer CLIP to Point Cloud Classification with Image-Depth Pre-training**

  [ArXiv 2022](https://arxiv.org/pdf/2210.01055.pdf) | [Project](https://github.com/tyhuang0428/CLIP2Point)


## Datasets
* **Text2Shape: Generating Shapes from Natural Language by Learning Joint Embeddings**
  
  [Web page](http://text2shape.stanford.edu/) |  [Shapenet website](https://shapenet.org/)

## Evaluation Metrics
* **ShapeGlot: Learning Language for Shape Differentiation**

  [ICCV 2019](https://arxiv.org/pdf/1905.02925.pdf) | [Code](https://github.com/optas/shapeglot) | [Project](https://ai.stanford.edu/~optas/shapeglot/)

* **CLIP-Similarity**: described in [ShapeCrafter](https://arxiv.org/abs/2207.09446)
