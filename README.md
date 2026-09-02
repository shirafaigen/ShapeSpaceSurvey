# ShapeSpaceSurvey

This is the suppoerting information of the paper: "Learning the Geometry of Data: A Mathematical Review of Shape Space Analysis", by Gary P. T. Choi, Khanh Dao Duc, Shira Faigenbaum-Golovin, Karen Habermann, Emmanuel Hartman, Christoph von Tycowicz, Chi Zhang, Wenjun Zhao, Felix Zhou


A central objective of machine learning is to identify structure and patterns in data. Advances in data acquisition have increasingly produced datasets whose observations possess rich geometric form, giving rise to shape spaces that encode variability in object geometry. Such datasets arise across a wide range of disciplines, including biology, medicine, anthropology, and computer vision, where subtle geometric differences often carry important scientific information. Traditional machine learning methods, however, are frequently ill-equipped to account for the nonlinear geometric structure underlying these data. This survey synthesizes a rapidly growing body of work on shape space analysis, which provides a mathematical and computational framework for the study of geometric data. Drawing on ideas from differential geometry, statistics, and machine learning, we organize the literature around a common analytical pipeline: shape representation and parameterization, the rigorous construction of robust geodesic metrics, statistical analysis on shape spaces, and geometry-aware learning methods. We discuss how these tools enable the characterization of shape variability, the comparison of geometric objects, and the analysis of structural trajectories across populations and time. To illustrate the breadth of the field, we highlight applications spanning multiple scales of biological organization, including studies of subcellular morphology and primate tooth evolution. Across these and many other domains, researchers face common challenges arising from complex, nonlinear, and often unaligned geometric variation. The review concludes by identifying key theoretical and computational challenges, as well as emerging opportunities driven by increasingly large and diverse geometric datasets.


A wide range of problems in shape space have been studied - each motivated by the specific challenges posed by particular datasets (see Section \ref{sec:datasets}). We aimed to provide an extensive list of the existing tools for others to apply them easily. However, the breadth of available methodological tools is far too extensive to be exhaustively covered in this paper. In particular, the rapidly growing body of machine learning–based approaches has produced a long and continually expanding list of relevant contributions. Rather than attempting an incomplete survey, we decided to maintain a more comprehensive and regularly updated list of related methods and references in a dedicated GitHub repository.

A living index of available tools and resources. Last updated: Sep 1 2026.

# Shape space tools

| <div style="width: 20px;">Name</div> | Short description | Ref. | Link|
| :--- | :--- |--- |--- |
|SlicerSALT | disseminating advanced shape methodology, quantitative analysis of shapes | [^1]|  [link](https://www.kitware.com/slicersalt-3-0-released/)|
|Geomstats | computations, statistics, and machine learning on nonlinear manifolds using Riemannian geometry | [^2]| [link](https://geomstats.github.io)|
|SAMS | Software for the Analysis and Mapping of Surfaces |[^13]| [link](https://github.com/RRavier/SAMS/tree/master)|
|Neuroimaging software | There are about 600 tools designed for different datasets, and tasks starting from segmentation, to shape analysis, and time domain analysis | [^3] |[link](https://www.nitrc.org/)|
|LDDMM registration | Registration developed for cortical areas|[^4] | | [link](https://bitbucket.org/laurent_younes/pylddmm/src/master/}|
|SlicerMorph | SlicerMorph streamlines digital morphology research by enabling effortless data import, visualization, measurement, annotation, and geometric morphometric analysis on 3D data, including volumetric scans (CTs and MRs) and 3D surface scans, all within the 3D Slicer application | [^5] |[link](https://slicermorph.github.io)|
|geomorph | Widely used R package for multivariate analysis with shape data | [^6]| | [link](https://cran.r-project.org/web/packages/geomorph/)|
|MorphoJ | GUI platform for multivariate analysis with shape data, such as partial least squares, asymmetry and quantitative genetics | [^7]| |[link](https://morphometrics.uk/MorphoJ_page.html)|
|Morpho | R package for multivariate analysis with shape data, including discriminant analysis, polygon model deformation, permutation tests, detection of outliers, sliding semi-landmarks, in- and export of models  | [^8]| |[link](https://cran.r-project.org/web/packages/Morpho/index.html)|
|CT-Surfacing | Segment and create 3D models using a medical CT scanner | [^9]| |[link](https://github.com/jwcalder/CT-Surfacing)|
|Virtual Goniometer| measuring angles on 3D models | [^10], [^11]| [link](https://amaaze.umn.edu/software), [link](https://github.com/oneil571/AMAAZE-MCT-Processing)|
|Auto3dgm | Alignment of 3D shapes, by matching their PCA principal axis, and applying  minimum spanning tree on the shape distances | [^12]| [link](https://github.com/ToothAndClaw/Auto3dgm_Python)|
|Morphomatics | Riemannian shape spaces and geometric machine learning
|BioEncoder | supervised metric learning | [^23]| [link](https://github.com/agporto/BioEncoder)|
|ALPACA | Fast landmark transfer from a 3D model and its associated landmark set to target 3D model | [^21], [^22]| [link](https://github.com/SlicerMorph/SlicerMorph)|
|DeepBryo  | Deep learning-based morphometric characterization of cheilostome bryozoans | [^20]| [link](https://github.com/agporto/DeepBryo)|
|ML - MORPH  | Landmarking at low cost | [^19]| [link](https://github.com/agporto/ml-morph)|
|APPENDOMETER | morphometric characterization of Drosophila leg | [^18]|  [link](https://github.com/agporto/Appendometer)|
|Cell Geometry | comparison of biological cell shapes | [^17]|  [link](https://github.com/geometric-intelligence/cellgeometry/tree/main/cells/streamlit)|
|u-unwrap3D |  map 3D surface and volume data into different representations | [^16]|  [link](https://github.com/DanuserLab/u-unwrap3D)|
|u-Signal3D | morphology-invariant analysis of molecular organization | [^15]|  [link](https://github.com/DanuserLab/u-signal3D)|
|u-Shape3D | 3D Morphological Motif Detection |[^14]|  [link](https://github.com/DanuserLab/u-shape3D)|

[^1]: Vicory, Jared, Ye Han, Juan Carlos Prieto, David Allemang, Mathieu Leclercq, Connor Bowley, Harald Scheirich et al. "SlicerSALT: from medical images to quantitative insights of anatomy." In International Workshop on Shape in Medical Imaging, pp. 201-210. Cham: Springer Nature Switzerland, 2023.

[^2]: Miolane, Nina, Nicolas Guigui, Alice Le Brigant, Johan Mathe, Benjamin Hou, Yann Thanwerdas, Stefan Heyder et al. "Geomstats: A python package for riemannian geometry in machine learning." Journal of Machine Learning Research 21, no. 223 (2020): 1-9.

[^3]: Luo, Xiao-zhong James, David N. Kennedy, and Zohara Cohen. "Neuroimaging informatics tools and resources clearinghouse (NITRC) resource announcement." (2009): 55-56.

[^4]:Younes, Laurent, Kwame S. Kutten, and J. Tilak Ratnanather. "Normal and equivolumetric coordinate systems for cortical areas." MethodsX 12 (2024): 102689.


[^5]:Rolfe, Sara, Steve Pieper, Arthur Porto, Kelly Diamond, Julie Winchester, Shan Shan, Henry Kirveslahti, Doug Boyer, Adam Summers, and A. Murat Maga. "SlicerMorph: An open and extensible platform to retrieve, visualize and analyse 3D morphology." Methods in Ecology and Evolution 12, no. 10 (2021): 1816-1825.

[^6]:Baken, Erica K., Michael L. Collyer, Antigoni Kaliontzopoulou, and Dean C. Adams. "geomorph v4. 0 and gmShiny: Enhanced analytics and a new graphical interface for a comprehensive morphometric experience." Methods in Ecology and Evolution 12, no. 12 (2021): 2355-2363.

[^7]:Klingenberg, Christian Peter. "MorphoJ: an integrated software package for geometric morphometrics." Molecular ecology resources 11, no. 2 (2011): 353-357.

[^8]:Schlager, Stefan. "Morpho and Rvcg–shape analysis in R: R-packages for geometric morphometrics, shape analysis and surface manipulations." In Statistical shape and deformation analysis, pp. 217-256. Academic Press, 2017.

[^9]:Yezzi-Woodley, Katrina E., Jeff W. Calder, Mckenzie Sweno, Chloe Siewert, and Peter J. Olver. "The Batch Artifact Scanning Protocol: A new method using computed tomography (CT) to rapidly create three-dimensional models of objects from large collections en masse." Advances in Archaeological Practice 13, no. 4 (2025): 546-566.
[^10]: Yezzi-Woodley, Katrina, Jeff Calder, Peter J. Olver, Paige Cody, Thomas Huffstutler, Alexander Terwilliger, J. Anne Melton, Martha Tappen, Reed Coil, and Gilbert Tostevin. "The Virtual Goniometer: A new method for measuring angles on 3D models of fragmentary bone and lithics: demonstrating a new method for measuring angles on archaeological materials using fragmentary bone." Archaeological and Anthropological Sciences 13, no. 7 (2021): 1-16.
[^11]:O'Neill, Riley CW, Katrina Yezzi-Woodley, Jeff Calder, and Peter J. Olver. "En masse scanning and automated surfacing of small objects using Micro-CT." arXiv preprint arXiv:2410.07385 (2024).
[^12]:Boyer, Doug M., Jesus Puente, Justin T. Gladman, Chris Glynn, Sayan Mukherjee, Gabriel S. Yapuncich, and Ingrid Daubechies. "A new fully automated approach for aligning and comparing shapes." The Anatomical Record 298, no. 1 (2015): 249-276.
[^13]:Ravier, Robert J. "Eyes on the Prize: Improved Biological Surface Registration via Forward Propagation." arXiv preprint arXiv:1812.10592 (2018).

[^14]: Driscoll, Meghan K., Erik S. Welf, Andrew R. Jamieson, Kevin M. Dean, Tadamoto Isogai, Reto Fiolka, and Gaudenz Danuser. "Robust and automated detection of subcellular morphological motifs in 3D microscopy images." Nature methods 16, no. 10 (2019): 1037-1044.
[^15]: Mazloom-Farsibaf, Hanieh, Qiongjing Zou, Rebecca Hsieh, Gaudenz Danuser, and Meghan K. Driscoll. "Cellular harmonics for the morphology-invariant analysis of molecular organization at the cell surface." Nature computational science 3, no. 9 (2023): 777-788.
[^16]:Zhou, Felix Y., Virangika K. Wimalasena, Qiongjing Zou, Andrew Weems, Gabriel M. Gihana, Edward Jenkins, Bingying Chen et al. "Surface-guided computing to quantify dynamic interactions between cell morphology and molecular signals in 3D." bioRxiv (2023): 2023-04.
[^17]:Li, Wanxin, Ashok Prasad, Nina Miolane, and Khanh Dao Duc. "Using a Riemannian elastic metric for statistical analysis of tumor cell shape heterogeneity." In International Conference on Geometric Science of Information, pp. 583-592. Cham: Springer Nature Switzerland, 2023.
[^18]:Rossoni, Daniela M., Connor Murray, Arthur Porto, and David Houle. "Appendometer: A system for simultaneous, high-throughput morphometry of Drosophila legs and wings." BioRxiv (2025): 2025-01.
[^19]:Porto, Arthur, and Kjetil L. Voje. "ML‐morph: A fast, accurate and general approach for automated detection and landmarking of biological structures in images." Methods in Ecology and Evolution 11, no. 4 (2020): 500-512.
[^20]:Di Martino, Emanuela, Björn Berning, Dennis P. Gordon, Piotr Kuklinski, Lee Hsiang Liow, Mali H. Ramsfjell, Henrique L. Ribeiro et al. "DeepBryo: A web app for AI‐assisted morphometric characterization of cheilostome bryozoans." Limnology and Oceanography: Methods 21, no. 9 (2023): 542-551.
[^21]:Rolfe, Sara, Steve Pieper, Arthur Porto, Kelly Diamond, Julie Winchester, Shan Shan, Henry Kirveslahti, Doug Boyer, Adam Summers, and A. Murat Maga. "SlicerMorph: An open and extensible platform to retrieve, visualize and analyse 3D morphology." Methods in Ecology and Evolution 12, no. 10 (2021): 1816-1825.
[^22]:Porto, Arthur, Sara Rolfe, and A. Murat Maga. "ALPACA: a fast and accurate computer vision approach for automated landmarking of three‐dimensional biological structures." Methods in Ecology and Evolution 12, no. 11 (2021): 2129-2144.
[^23]: Lürig, Moritz D., Emanuela Di Martino, and Arthur Porto. "BioEncoder: A metric learning toolkit for comparative organismal biology." Ecology Letters 27, no. 8 (2024): e14495.
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
