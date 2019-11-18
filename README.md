# Curated List of 3D Morphable Model Software and Data
<p align="center">
<img src="images/MorphableModels.png" alt ="3D Morphable Models">
  </p>

The idea of this list is to collect shared data and algorithms around 3D Morphable Models. You are invited to contribute to this list by adding a pull request. The original list arised from the Dagstuhl seminar on 3D Morphable Models https://www.dagstuhl.de/19102 in March 2019.

# Morphable Models:
## Google Group
- Google group to help foster a research community interested in 3DMMs, share resources etc.: https://groups.google.com/forum/#!forum/3d-morphable-models
## Face Models:
- Basel Face Model 2009: http://faces.cs.unibas.ch/bfm/?nav=1-0&id=basel_face_model
- Basel Face Model 2017: http://faces.cs.unibas.ch/bfm/bfm2017.html
- Large Scale 3D Morphable Model: https://xip.uclb.com/i/healthcare_tools/LSFM.html
- Liverpool-York Head Model: https://www-users.cs.york.ac.uk/~nep/research/LYHM/ 
- Multilinear Autoencoder for 3D Face Model Learning: http://mae.gforge.inria.fr/ 
- Statistical 3D Shape Models of Human Faces: http://facepage.gforge.inria.fr/ 
- Surrey Face Model https://cvssp.org/facemodel
- Articulated Expressive Head Model (FLAME): http://flame.is.tue.mpg.de/
- Convolutional Mesh Autoencoder (CoMA): http://coma.is.tue.mpg.de/
## Body Models:
- A skinned Multi-Person Linear Model (SMPL): http://smpl.is.tue.mpg.de/
- Expressive Body Model - SMPL with articulated hands and expressive face (SMPL-X): https://smpl-x.is.tue.mpg.de/
- MPII Human Shape Model: http://humanshape.mpi-inf.mpg.de/ 
## Other Models:
- The York Ear Model: https://www-users.cs.york.ac.uk/~nep/research/YEM/
- SMALA Skinned Multi-Animal Linear Model of 3D Animal Shape http://smal.is.tue.mpg.de/

# Registration / model construction / alignment:
- Large Scale Facial Model (LSFM) pipeline: https://github.com/menpo/lsfm 
- Basel Face Registration pipeline: https://github.com/unibas-gravis/basel-face-pipeline 
- Shape-aware surface reconstruction based on a statistical shape model prior: https://github.com/fbernardpi/sparsePdmFitting
- Fast Linear Assignment Problem solver: https://de.mathworks.com/matlabcentral/fileexchange/48448-fast-linear-assignment-problem-using-auction-algorithm-mex
- NmfSync for making pairwise (partial) permutations cycle-consistent (relevant for multi-matching): https://github.com/fbernardpi/NmfSync
- Transformation Synchronisation method for making pairwise transformations cycle-consistent (e.g. for solving the Generalised - - Procrustes Problem, or general multi-image registration): https://sites.google.com/site/fbernardpi/code
- Learning linear shape deformations with local support: https://sites.google.com/site/fbernardpi/code

# Data / 3D scans:
## Faces:
- BU-3DFE, BU-4DFE: http://www.cs.binghamton.edu/~lijun/Research/3DFE/3DFE_Analysis.html
- The Headspace dataset: https://www-users.cs.york.ac.uk/~nep/research/Headspace/
- The UoY 3D face dataset https://www-users.cs.york.ac.uk/~nep/research/UoYfaces/
- CoMA 3D face dataset (registrations): http://coma.is.tue.mpg.de/
- D3DFACS dataset: [raw scan data](https://www.cs.bath.ac.uk/~dpc/D3DFACS/), [Registrations](http://flame.is.tue.mpg.de/)
- FaceCap dataset: http://gvv.mpi-inf.mpg.de/projects/FaceCap/
- MonFaceCap: http://gvv.mpi-inf.mpg.de/projects/MonFaceCap/ 
- Parametric Face Image Generator: https://github.com/unibas-gravis/parametric-face-image-generator
- VOCASET speech-4D head scan dataset: https://voca.is.tue.mpg.de/
- Speech-driven 3D Facial Motion Database (S3DFM): http://groups.inf.ed.ac.uk/trimbot2020/DYNAMICFACES/index.html
- The Florence 2D/3D hybrid face dataset: http://www.micc.unifi.it/vim/3dfaces-dataset/

## Bodies:
- A Model of Dynamic Human Shape in Motion:  http://dyna.is.tue.mpg.de 
- In the wild 3D pose dataset with ground truth: http://virtualhumans.mpi-inf.mpg.de/3DPW
- Human3.6m - 3.6 million 3D poses from 11 actors and in 17 scenarios: http://vision.imar.ro/human3.6m
- CAESAR body measurements database: https://store.sae.org/caesar/ 
- People in clothing scans: http://buff.is.tue.mpg.de
- Unite the People dataset: http://up.is.tuebingen.mpg.de
- Data from the GVV group: http://gvvperfcapeva.mpi-inf.mpg.de/
  - MuCo-3DHP: http://gvv.mpi-inf.mpg.de/projects/SingleShotMultiPerson/
  - MuPoTS-3D: http://gvv.mpi-inf.mpg.de/projects/SingleShotMultiPerson/
  - MonoPerfCap: http://gvv.mpi-inf.mpg.de/projects/wxu/MonoPerfCap/
  - IntrinsicMoCap: https://download.mpi-inf.mpg.de/projects/IntrinsicMoCap/
  - MPI-INF-3DHP: http://gvv.mpi-inf.mpg.de/3dhp-dataset/  
  - MARCOnI: http://marconi.mpi-inf.mpg.de/
  - EgoCap: http://gvv.mpi-inf.mpg.de/projects/EgoCap/
  - MPII Human Shape: http://humanshape.mpi-inf.mpg.de/
  - BinoCap: http://gvv.mpi-inf.mpg.de/projects/BinoCap/
  - Inertial Depth Tracker Dataset: http://gvvperfcapeva.mpi-inf.mpg.de/public/InertialDepthTracker/index.php 
  - Performance Capture from Sparse Multi-view Video: http://resources.mpi-inf.mpg.de/perfcap/ 
  - Performance Capture of Interacting Characters with Handheld Kinects: http://gvvperfcapeva.mpi-inf.mpg.de/public/KinectsMocap/ 

##  Other Data:
- 3D people in clothing from video: https://graphics.tu-bs.de/people-snapshot
- The York 3D Ear dataset: https://www-users.cs.york.ac.uk/~nep/research/YEM/ 
- Estimation of Human Body Shape in Motion with Wide Clothing: http://dressedhuman.gforge.inria.fr/ 

# Model adaptation to images or videos:
## Faces:
- 3D Morphable Model fitting using edge features: https://github.com/waps101/3DMM_edges 
- Basic 3D Morphable Model fitting: https://github.com/anhttran/3dmm_basic
- A lightweight 3D Morphable Model fitting library: https://github.com/patrikhuber/eos 
- Probabilistic Fitting: https://github.com/unibas-gravis/scalismo-faces 
- Deep Neural Network parameter regression: https://talhassner.github.io/home/publication/2017_CVPR
- Expression-Net: https://github.com/fengju514/Expression-Net
- Face-Pose-Net: https://github.com/fengju514/Face-Pose-Net
- Shape-Net: https://github.com/anhttran/3dmm_cnn
- Extreme 3D Face Reconstruction: https://github.com/anhttran/extreme_3d_faces
- FLAME fitting: [Chumpy-based framework](https://github.com/Rubikplayer/flame-fitting), [Tensorflow-based framework](https://github.com/TimoBolkart/TF_FLAME) 
- 3D face shape and expression regression network (RingNet): https://github.com/soubhiksanyal/RingNet
- Joint 3D Face Reconstruction and Dense Alignment with Position Map Regression Network https://github.com/YadiraF/PRNet
- Unrestricted Facial Geometry Reconstruction Using Image-to-Image Translation https://github.com/matansel/pix2vertex
- 3D Morphable Models as Spatial Transformer Networks https://github.com/anilbas/3DMMasSTN
- Large Pose 3D Face Reconstruction from a Single Image via Direct Volumetric Regression https://github.com/AaronJackson/vrn
- Accurate 3D Face Reconstruction with Weakly-Supervised Learning: From Single Image to Image Set https://github.com/microsoft/Deep3DFaceReconstruction
- Facial Detail synthesis https://github.com/apchenstu/Facial_Details_Synthesis

## Other"
- Three-D Safari https://github.com/silviazuffi/smalst

### Benchmarks:
- “not quite in-the-wild” (NoW) Challenge (3D face reconstruction from images benchmark): https://ringnet.is.tue.mpg.de

## Bodies:
- 3D pose and shape (Neural Body Fitter): https://github.com/mohomran/neural_body_fitting
- Expressive Body Capture: 3D Hands, Face, and Body from a Single Image (SMPLify-X): https://github.com/vchoutas/smplify-x

# Illumination Models:
- Basel Illumination Prior 2017: http://gravis.dmi.unibas.ch/PMM/data/bip/

# Tutorials:
- Statistical Shape Modelling: https://gravis.dmi.unibas.ch/PMM/lectures/ssm/
- Probabilistic Fitting: https://gravis.dmi.unibas.ch/PMM/lectures/fitting/ 
- Semantic Morphable Model: https://gravis.dmi.unibas.ch/PMM/lectures/segmentation/ 

# Web services:
- Photo-realistic Face Manipulation: https://face-morpher.scalismo.org/
- 3D Face Reconstruction from a Single Image: https://cvl-demos.cs.nott.ac.uk/vrn/
