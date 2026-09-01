# ShapeSpaceSurvey

This is the suppoerting information of the paper: "Learning the Geometry of Data: \\A Mathematical Review of Shape Space Analysis", by Gary P. T. Choi, Khanh Dao Duc, Shira Faigenbaum-Golovin, Karen Habermann, Emmanuel Hartman, Christoph von Tycowicz, Chi Zhang, Wenjun Zhao, Felix Zhou


A central objective of machine learning is to identify structure and patterns in data. Advances in data acquisition have increasingly produced datasets whose observations possess rich geometric form, giving rise to shape spaces that encode variability in object geometry. Such datasets arise across a wide range of disciplines, including biology, medicine, anthropology, and computer vision, where subtle geometric differences often carry important scientific information. Traditional machine learning methods, however, are frequently ill-equipped to account for the nonlinear geometric structure underlying these data. This survey synthesizes a rapidly growing body of work on shape space analysis, which provides a mathematical and computational framework for the study of geometric data. Drawing on ideas from differential geometry, statistics, and machine learning, we organize the literature around a common analytical pipeline: shape representation and parameterization, the rigorous construction of robust geodesic metrics, statistical analysis on shape spaces, and geometry-aware learning methods. We discuss how these tools enable the characterization of shape variability, the comparison of geometric objects, and the analysis of structural trajectories across populations and time. To illustrate the breadth of the field, we highlight applications spanning multiple scales of biological organization, including studies of subcellular morphology and primate tooth evolution. Across these and many other domains, researchers face common challenges arising from complex, nonlinear, and often unaligned geometric variation. The review concludes by identifying key theoretical and computational challenges, as well as emerging opportunities driven by increasingly large and diverse geometric datasets.


A wide range of problems in shape space have been studied - each motivated by the specific challenges posed by particular datasets (see Section \ref{sec:datasets}). We aimed to provide an extensive list of the existing tools for others to apply them easily. However, the breadth of available methodological tools is far too extensive to be exhaustively covered in this paper. In particular, the rapidly growing body of machine learning–based approaches has produced a long and continually expanding list of relevant contributions. Rather than attempting an incomplete survey, we decided to maintain a more comprehensive and regularly updated list of related methods and references in a dedicated GitHub repository.

A living index of available tools and resources. Last updated: Sep 1 2026.

# Shape space tools

| <div style="width: 20px;">Name</div> | Short description | Ref. | Link|
| :--- | :--- |--- |--- |
|SlicerSALT | disseminating advanced shape methodology, quantitative analysis of shapes | [^1]|  [link](https://www.kitware.com/slicersalt-3-0-released/)|
|Geomstats | computations, statistics, and machine learning on nonlinear manifolds using Riemannian geometry | \cite{Geomstats)| [link](https://geomstats.github.io)|
|SAMS | Software for the Analysis and Mapping of Surfaces | \cite{ravier2018algorithms)| [link](https://github.com/RRavier/SAMS/tree/master)|
|Neuroimaging software | There are about 600 tools designed for different datasets, and tasks starting from segmentation, to shape analysis, and time domain analysis | \cite{luo2009neuroimaging)|[link](https://www.nitrc.org/)|
|LDDMM registration | Registration developed for cortical areas| \cite{younes2024normal)| | [link](https://bitbucket.org/laurent_younes/pylddmm/src/master/}|
|SlicerMorph | SlicerMorph streamlines digital morphology research by enabling effortless data import, visualization, measurement, annotation, and geometric morphometric analysis on 3D data, including volumetric scans (CTs and MRs) and 3D surface scans, all within the 3D Slicer application | \cite{rolfe_slicermorph_2021)| |[link](https://slicermorph.github.io)|
|geomorph | Widely used R package for multivariate analysis with shape data | \cite{adams_geomorph_2021)| |[link](https://cran.r-project.org/web/packages/geomorph/index.html)|
|MorphoJ | GUI platform for multivariate analysis with shape data, such as partial least squares, asymmetry and quantitative genetics | \cite{klingenberg_morphoj_2011)| |[link](https://morphometrics.uk/MorphoJ_page.html)|
|Morpho | R package for multivariate analysis with shape data, including discriminant analysis, polygon model deformation, permutation tests, detection of outliers, sliding semi-landmarks, in- and export of models  | \cite{)| |[link](https://cran.r-project.org/web/packages/Morpho/index.html)|
|CT-Surfacing | Segment and create 3D models using a medical CT scanner | \cite{yezzi2022batch)| |[link](https://github.com/jwcalder/CT-Surfacing)|
|Virtual Goniometer| measuring angles on 3D models | \cite{yezzi2020virtual, o2024masse)| [link](https://amaaze.umn.edu/software), [link](https://github.com/oneil571/AMAAZE-MCT-Processing)|
|Auto3dgm | Alignment of 3D shapes, by matching their PCA principal axis, and applying  minimum spanning tree on the shape distances | \cite{boyer2015new)| [link](https://github.com/ToothAndClaw/Auto3dgm_Python)|
|Morphomatics | Riemannian shape spaces and geometric machine learning
|BioEncoder | supervised metric learning | \cite{x)| [link](https://github.com/agporto/BioEncoder)|
|ALPACA | Fast landmark transfer from a 3D model and its associated landmark set to target 3D model | \cite{x)| [link](https://github.com/SlicerMorph/SlicerMorph)|
|DeepBryo  | Deep learning-based morphometric characterization of cheilostome bryozoans | \cite{x)| [link](https://github.com/agporto/DeepBryo)|
|ML - MORPH  | Landmarking at low cost | \cite{x)| [link](https://github.com/agporto/ml-morph)|
|APPENDOMETER | morphometric characterization of Drosophila leg | \cite{x)|  [link](https://github.com/agporto/Appendometer)|
|Cell Geometry | comparison of biological cell shapes | \cite{li2023using)|  [link](https://github.com/geometric-intelligence/cellgeometry/tree/main/cells/streamlit)|
|u-unwrap3D |  map 3D surface and volume data into different representations | \cite{zhou2023surface)|  [link](https://github.com/DanuserLab/u-unwrap3D)|
|u-Signal3D | morphology-invariant analysis of molecular organization | \cite{mazloom2023cellular)|  [link](https://github.com/DanuserLab/u-signal3D)|
|u-Shape3D | 3D Morphological Motif Detection | \cite{driscoll2019robust)|  [link](https://github.com/DanuserLab/u-shape3D)|

[^1]:\cite{vicory2023slicersalt)
<!--

Additional code:


 %   \item Code and dataset for cancer cell shape analysis using SRV metric: https://osf.io/vbwra/ Ref: W. Li, A. Prasad, N. Miolane, K. Dao Duc (2023),
%``Using a Riemannian elastic metric for statistical analysis of tumor cell shape heterogeneity'',
%In: Nielsen, F., Barbaresco, F. (eds) Geometric Science of Information. GSI 2023. Lecture Notes in Computer Science, vol 14072.
%Springer, Cham. [link](https://doi.org/10.1007/978-3-031-38299-4_60}

%[link](https://github.com/geometric-intelligence/cellgeometry/tree/main/cells/streamlit}

%\item u-Unwrap3D ([link](https://github.com/DanuserLab/u-unwrap3D}, [link](https://www.biorxiv.org/content/10.1101/2023.04.12.536640v2})

%u-Signal3D ([link](https://github.com/DanuserLab/u-signal3D}, [link](https://www.nature.com/articles/s43588-023-00512-4})

%u-Shape3D ([link](https://github.com/DanuserLab/u-shape3D}, [link](https://www.nature.com/articles/s41592-019-0539-z})

\item [link](https://github.com/GitBoSun/ARAPReg} ( ARAPReg: An As-Rigid-As Possible Regularization Loss for Learning Deformable Shape Generators. ICCV 2021)
[link](https://github.com/yanghtr/GenCorres} (will be updated soon. GenCorres: Consistent Shape Matching via Coupled Implicit-Explicit Shape Generative Models. under review for ICLR 2024)

\item [link](https://sayanmuk.github.io/}
\item [link](https://github.com/sshanshans/ariaDNE_code}

\item [link](https://toothandclaw.github.io/}
\item [link](https://morphomatics.github.io/}
\item [link](https://geomstats.github.io/}
\item [link](https://www.math.cuhk.edu.hk/~ptchoi/}

\item [link](https://bitbucket.org/laurent_younes/py-lddmm/src/master/	}
\item https://github.com/awesomelistsio/awesome-ai-research-papers
-->
