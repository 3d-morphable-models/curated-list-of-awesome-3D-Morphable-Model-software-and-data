# Curated List of Awesome 3D Morphable Model Software and Data
![3D Morphable Models](images/MorphableModels.png "3D Morphable Models")
The idea of this list is to collect shared data and algorithms around 3D Morphable Models. You are invited to contribute to this list by adding a pull request. The original list arised from the Dagstuhl seminar on 3D Morphable Models https://www.dagstuhl.de/19102 in March 2019.
# Morphable Models:
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
- MPII Human Shape Model: http://humanshape.mpi-inf.mpg.de/ 
## Other Models:
- The York Ear Model: https://www-users.cs.york.ac.uk/~nep/research/YEM/

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
- The Headspace dataset: https://www-users.cs.york.ac.uk/~nep/research/Headspace/
- The UoY 3D face dataset https://www-users.cs.york.ac.uk/~nep/research/UoYfaces/
- CoMA 3D face dataset (registrations): http://coma.is.tue.mpg.de/
- D3DFACS registrations: http://flame.is.tue.mpg.de/
- FaceCap dataset: http://gvv.mpi-inf.mpg.de/projects/FaceCap/
- MonFaceCap: http://gvv.mpi-inf.mpg.de/projects/MonFaceCap/ 

## Bodies:
- A Model of Dynamic Human Shape in Motion:  http://dyna.is.tue.mpg.de 
- In the wild 3D pose dataset with ground truth: http://virtualhumans.mpi-inf.mpg.de/3DPW
- CAESAR body measurements database: https://store.sae.org/caesar/ 
- People in clothing scans: http://buff.is.tue.mpg.de
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
- A lightweight 3D Morphable Model fitting library: https://github.com/patrikhuber/eos 
- Probabilistic Fitting: https://github.com/unibas-gravis/scalismo-faces 
## Bodies:
- 3D pose and shape (Neural Body Fitter): https://github.com/mohomran/neural_body_fitting

# Illumination Models:
- Basel Illumination Prior 2017: http://gravis.dmi.unibas.ch/PMM/data/bip/

# Tutorials:
- Statistical Shape Modelling: https://gravis.dmi.unibas.ch/PMM/lectures/ssm/
- Probabilistic Fitting: https://gravis.dmi.unibas.ch/PMM/lectures/fitting/ 
- Semantic Morphable Model: https://gravis.dmi.unibas.ch/PMM/lectures/segmentation/ 

# Web services:
- Photo-realistic Face Manipulation: https://face-morpher.scalismo.org/ 
