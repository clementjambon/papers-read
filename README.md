# Papers I read
This repo is regularly updated with the papers I read so far.

I also maintain lists of:
* [articles I read](articles-read.md)
* [videos I watched](videos-watched.md)
* [books I read](books-read.md)

Categories are:
* [Machine Learing](#machine-learning)
    * [Optimization](#optimization)
    * [Graphs](#graphs)
    * [NLP](#nlp)
    * [Object detection/segmentation](#object-detection/segmentation)
    * [Transformers](#transformers)
    * [Generative Models](#generative-models)
* [Topological Data Analysis](#topological-data-analysis)
* [Optimal Transport](#optimal-transport)
* [Computer Vision](#computer-vision-)
    * [Geometry](#geometry)
    * [Scene Representation](#scene-representation)
    * [SLAM](#slam)
    * [Structure from Motion](#structure-from-motion)
    * [Image search](#image-search)
    * [Image processing](#image-processing)
    * [Descriptors](#descriptors)
    * [Graph cuts](#graph-cuts)
    * [Computational Photography](#computational-photography)
* [Applied Mathematics](#applied-mathematics-)
    * [Dimension reduction](#dimension-reduction)
* [Similarity Search](#similarity-search)
* [Computer Graphics](#computer-graphics)
    * [Compression](#compression)
    * [Geometry Processing](#geometry-processing)
    * [Signed Distance Fields](#signed-distance-fields)
    * [Procedural Generation](#procedural-generation)
    * [Shading](#shading)
## Machine Learning
### Optimization
- Nitish Srivastava, Geoffrey Hinton, Alex Krizhevsky, Ilya Sutskever, Ruslan Salakhutdinov. "Dropout: A Simple Way to Prevent Neural Networks from Overfitting". Journal of Machine Learning Research 2014; 15(56):1929-1958.
- Sebastian Ruder. (2017). An overview of gradient descent optimization algorithms. 

### Graphs
- T. N. Kipf, M. Welling. "Semi-Supervised Classification With Graph Convolutional Networks". ICLR 2017.
- Aditya Grover and Jure Leskovec. 2016. Node2vec: Scalable Feature Learning for Networks. In Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD '16). Association for Computing Machinery, New York, NY, USA, 855–864. DOI:https://doi.org/10.1145/2939672.2939754
- William L. Hamilton, Rex Ying, and Jure Leskovec. 2017. Inductive representation learning on large graphs. In Proceedings of the 31st International Conference on Neural Information Processing Systems (NIPS'17). Curran Associates Inc., Red Hook, NY, USA, 1025–1035.
- Petar Veličković, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Liò, & Yoshua Bengio. (2018). Graph Attention Networks. 

### NLP
- Tomas Mikolov, Kai Chen, Greg Corrado, Jeffrey Dean. Efficient Estimation of Word Representations in Vector Space. 
- Tomas Mikolov, Quoc V. Le, & Ilya Sutskever. (2013). Exploiting Similarities among Languages for Machine Translation. 
- Alexis Conneau, Douwe Kiela, Holger Schwenk, Loic Barrault, & Antoine Bordes. (2018). Supervised Learning of Universal Sentence Representations from Natural Language Inference Data.
- Reimers, N., & Gurevych, I. (2019). Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks. In Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing. Association for Computational Linguistics.

### Object detection/segmentation
- Ross Girshick. (2015). Fast R-CNN. 
- Shaoqing Ren, Kaiming He, Ross Girshick, & Jian Sun. (2016). Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks. 
- Kaiming He, Georgia Gkioxari, Piotr Dollár, & Ross Girshick. (2018). Mask R-CNN. 

### Transformers
- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A., Kaiser, & Polosukhin, I. (2017). Attention is All you Need. In Advances in Neural Information Processing Systems. Curran Associates, Inc..

### Generative Models
- Diederik P Kingma, & Max Welling. (2014). Auto-Encoding Variational Bayes. 
- Thomas Kipf, Elise van der Pol, & Max Welling. (2020). Contrastive Learning of Structured World Models.
- Ian Goodfellow. (2017). NIPS 2016 Tutorial: Generative Adversarial Networks.  
- David Ha and Jürgen Schmidhuber (2018). World Models. CoRR, abs/1803.10122.

## Topological Data Analysis
- Mathieu Carrière, Steve Y. Oudot, and Maks Ovsjanikov. 2015. Stable topological signatures for points on 3D shapes. In Proceedings of the Eurographics Symposium on Geometry Processing (SGP '15). Eurographics Association, Goslar, DEU, 1–12. DOI:https://doi.org/10.1111/cgf.12692
- Yuhei Umeda, Time Series Classification via Topological Data Analysis, Transactions of the Japanese Society for Artificial Intelligence, 2017, Volume 32, Issue 3, Pages D-G72_1-12

## Optimal Transport
- Marco Cuturi. 2013. Sinkhorn distances: lightspeed computation of optimal transport. In Proceedings of the 26th International Conference on Neural Information Processing Systems - Volume 2 (NIPS'13). Curran Associates Inc., Red Hook, NY, USA, 2292–2300.

## Computer vision 👀
### Geometry
- Hartley Richard I., 1998, Minimizing algebraic error, Phil. Trans. R. Soc. A.3561175–1192, http://doi.org/10.1098/rsta.1998.0216

### Scene representation
- Ben Mildenhall and Pratul P. Srinivasan and Matthew Tancik and Jonathan T. Barron and Ravi Ramamoorthi and Ren Ng. "NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis". CoRR 2020; abs/2003.08934.
- Jianxiong Shen, Adria Ruiz, Antonio Agudo, & Francesc Moreno-Noguer. (2021). Stochastic Neural Radiance Fields: Quantifying Uncertainty in Implicit 3D Representations.
- Towaki Takikawa and Joey Litalien, Kangxue Yin, Karsten Kreis, Charles Loop, Derek Nowrouzezahrai, Alec Jacobson, Morgan McGuire, & Sanja Fidler (2021). Neural Geometric Level of Detail: Real-time Rendering with Implicit 3D Shapes.
- Sitzmann, V., Martel, J., Bergman, A., Lindell, D., & Wetzstein, G. (2020). Implicit Neural Representations with Periodic Activation Functions. In Proc. NeurIPS.
- Jeong Joon Park and Peter Florence and Julian Straub and Richard A. Newcombe and Steven Lovegrove (2019). DeepSDF: Learning Continuous Signed Distance Functions for Shape Representation. CoRR, abs/1901.05103.
- Lindell, D., Van Veen, D., Park, J., & Wetzstein, G. (2021). BACON: Band-limited coordinate networks for multiscale scene representation.
- Sitzmann, V., Zollhöfer, M., & Wetzstein, G. (2019). Scene Representation Networks: Continuous 3D-Structure-Aware Neural Scene Representations. In Advances in Neural Information Processing Systems.
- Sitzmann, V., Chan, E., Tucker, R., Snavely, N., & Wetzstein, G. (2020). MetaSDF: Meta-Learning Signed Distance Functions. In Proc. NeurIPS.

### SLAM
- R. Mur-Artal, J. M. M. Montiel and J. D. Tardós, "ORB-SLAM: A Versatile and Accurate Monocular SLAM System," in IEEE Transactions on Robotics, vol. 31, no. 5, pp. 1147-1163, Oct. 2015, doi: 10.1109/TRO.2015.2463671.
- R. Mur-Artal and J. D. Tardós, "ORB-SLAM2: An Open-Source SLAM System for Monocular, Stereo, and RGB-D Cameras," in IEEE Transactions on Robotics, vol. 33, no. 5, pp. 1255-1262, Oct. 2017, doi: 10.1109/TRO.2017.2705103.
- Campos, C, Elvira, R, Rodriguez, J, M. Montiel, J, D. Tardos, J. "ORB-SLAM3: An Accurate Open-Source Library for Visual, Visual–Inertial, and Multimap SLAM". IEEE Transactions on Robotics 2021:1–17.
- Bescos, B, Facil, J, Civera, J, Neira, J. "DynaSLAM: Tracking, Mapping, and Inpainting in Dynamic Scenes". IEEE Robotics and Automation Letters 2018; 3(4):4076–4083.
- Sumikura, S, Shibuya, M, Sakurada, K. "OpenVSLAM". Proceedings of the 27th ACM International Conference on Multimedia 2019.

### Structure from Motion
- J. L. Schönberger and J. Frahm, "Structure-from-Motion Revisited," 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2016, pp. 4104-4113, doi: 10.1109/CVPR.2016.445.

### Image search
- A. Torii, J. Sivic, M. Okutomi and T. Pajdla, "Visual Place Recognition with Repetitive Structures," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 37, no. 11, pp. 2346-2359, 1 Nov. 2015, doi: 10.1109/TPAMI.2015.2409868.
- H. Jégou, M. Douze, C. Schmid and P. Pérez, "Aggregating local descriptors into a compact image representation," 2010 IEEE Computer Society Conference on Computer Vision and Pattern Recognition, 2010, pp. 3304-3311, doi: 10.1109/CVPR.2010.5540039.
- R. Arandjelovic and A. Zisserman, "All About VLAD," 2013 IEEE Conference on Computer Vision and Pattern Recognition, 2013, pp. 1578-1585, doi: 10.1109/CVPR.2013.207.
- Delhumeau, J, Gosselin, PH, Jégou, H, Pérez, "Revisiting the VLAD image representation". In ACM Multimedia 2013.
- E. Spyromitros-Xioufis, S. Papadopoulos, I. Y. Kompatsiaris, G. Tsoumakas and I. Vlahavas, "A Comprehensive Study Over VLAD and Product Quantization in Large-Scale Image Retrieval," in IEEE Transactions on Multimedia, vol. 16, no. 6, pp. 1713-1728, Oct. 2014, doi: 10.1109/TMM.2014.2329648.

### Image processing
- P. Burt and E. Adelson, "The Laplacian Pyramid as a Compact Image Code," in IEEE Transactions on Communications, vol. 31, no. 4, pp. 532-540, April 1983, doi: 10.1109/TCOM.1983.1095851.
- A. A. Efros and T. K. Leung, "Texture synthesis by non-parametric sampling," Proceedings of the Seventh IEEE International Conference on Computer Vision, 1999, pp. 1033-1038 vol.2, doi: 10.1109/ICCV.1999.790383.
- Brown and Lowe, "Recognising panoramas," Proceedings Ninth IEEE International Conference on Computer Vision, 2003, pp. 1218-1225 vol.2, doi: 10.1109/ICCV.2003.1238630.

### Descriptors
- David G. Lowe. Distinctive Image Features from Scale-Invariant Keypoints.
- Krystian Mikolajczyk, Cordelia Schmid. Scale & affine invariant interest point detectors. International Journal of Computer Vision, Springer Verlag, 2004, 60 (1), pp.63--86.
- E. Rublee, V. Rabaud, K. Konolige and G. Bradski, "ORB: An efficient alternative to SIFT or SURF," 2011 International Conference on Computer Vision, 2011, pp. 2564-2571, doi: 10.1109/ICCV.2011.6126544. 

### Graphc cuts
- H. Ishikawa, "Exact optimization for Markov random fields with convex priors" in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 25, no. 10, pp. 1333-1336, Oct. 2003, doi: 10.1109/TPAMI.2003.1233908.

### Computational Photography
- Samuel W. Hasinoff, Dillon Sharlet, Ryan Geiss, Andrew Adams, Jonathan T. Barron, Florian Kainz, Jiawen Chen, and Marc Levoy. 2016. Burst photography for high dynamic range and low-light imaging on mobile cameras. ACM Trans. Graph. 35, 6, Article 192 (November 2016), 12 pages. DOI:https://doi.org/10.1145/2980179.2980254

## Applied Mathematics 📐
- Keener, J. "The Perron–Frobenius Theorem and the Ranking of Football Teams". SIAM Review 1993; 35(1):80-93.
- Joan Solà, Jeremie Deray, Dinesh Atchuthan. A micro Lie theory for state estimation in robotics.
- Martin A. Fischler and Robert C. Bolles. 1981. "Random sample consensus: a paradigm for model fitting with applications to image analysis and automated cartography". Commun. ACM 24, 6 (June 1981), 381–395. DOI:https://doi.org/10.1145/358669.358692
- Stephen Boyd, Neal Parikh, Eric Chu, Borja Peleato, and Jonathan Eckstein. 2011. Distributed Optimization and Statistical Learning via the Alternating Direction Method of Multipliers. 3, 1 (January 2011), 1–122. DOI:https://doi.org/10.1561/2200000016

### 3D geometry
- K. S. Arun, T. S. Huang and S. D. Blostein, "Least-Squares Fitting of Two 3-D Point Sets," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. PAMI-9, no. 5, pp. 698-700, Sept. 1987, doi: 10.1109/TPAMI.1987.4767965.

### Dimension reduction
- R. Hadsell, S. Chopra and Y. LeCun, "Dimensionality Reduction by Learning an Invariant Mapping," 2006 IEEE Computer Society Conference on Computer Vision and Pattern Recognition (CVPR'06), 2006, pp. 1735-1742, doi: 10.1109/CVPR.2006.100.
- Joshua B. Tenenbaum, Vin de Silvaand John C. Langford, "A Global Geometric Framework for Nonlinear Dimensionality Reduction", Science, 22 Dec 2000, Vol 290, Issue 5500, pp. 2319-2323, DOI: 10.1126/science.290.5500.2319
- Sam T. Roweis and Lawrence K. Saul, "Nonlinear Dimensionality Reduction by Locally Linear Embedding", Science, 22 Dec 2000, Vol 290, Issue 5500, pp. 2323-2326, DOI: 10.1126/science.290.5500.2323
- M. Aharon, M. Elad and A. Bruckstein, "K-SVD: An algorithm for designing overcomplete dictionaries for sparse representation," in IEEE Transactions on Signal Processing, vol. 54, no. 11, pp. 4311-4322, Nov. 2006, doi: 10.1109/TSP.2006.881199.

## Similarity search
- H. Jégou, M. Douze and C. Schmid, "Product Quantization for Nearest Neighbor Search," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 33, no. 1, pp. 117-128, Jan. 2011, doi: 10.1109/TPAMI.2010.57.
- Ulrike von Luxburg. (2007). "A Tutorial on Spectral Clustering." 

## Computer Graphics

### Compression
- Schuster, K, Trettner, P, Schmitz, P, Schakib, J, Kobbelt, LCompression and Rendering of Textured Point Clouds via Sparse Coding. In High-Performance Graphics - Symposium Papers 2021 . The Eurographics Association.

### Geometry Processing
- Meyer, A. 2003. Discrete Differential-Geometry Operators for Triangulated 2-Manifolds. In Visualization and Mathematics III (pp. 35–57). Springer Berlin Heidelberg.
- Olga Sorkine and Marc Alexa. 2007. As-rigid-as-possible surface modeling. In Proceedings of the fifth Eurographics symposium on Geometry processing (SGP '07). Eurographics Association, Goslar, DEU, 109–116.
- Hsueh-Ti Derek liu and Alec Jacobson. 2019. Cubic stylization. ACM Trans. Graph. 38, 6, Article 197 (November 2019), 10 pages. DOI:https://doi.org/10.1145/3355089.3356495
- Y. Lipman, O. Sorkine, D. Cohen-Or, D. Levin, C. Rossi and H. P. Seidel, "Differential coordinates for interactive mesh editing," Proceedings Shape Modeling Applications, 2004., 2004, pp. 181-190, doi: 10.1109/SMI.2004.1314505.
- Mathieu Desbrun, Mark Meyer, Peter Schröder, and Alan H. Barr. 1999. Implicit fairing of irregular meshes using diffusion and curvature flow. In Proceedings of the 26th annual conference on Computer graphics and interactive techniques (SIGGRAPH '99). ACM Press/Addison-Wesley Publishing Co., USA, 317–324. DOI:https://doi.org/10.1145/311535.311576
- O. Sorkine, D. Cohen-Or, Y. Lipman, M. Alexa, C. Rössl, and H.-P. Seidel. 2004. Laplacian surface editing. In Proceedings of the 2004 Eurographics/ACM SIGGRAPH symposium on Geometry processing (SGP '04). Association for Computing Machinery, New York, NY, USA, 175–184. DOI:https://doi.org/10.1145/1057432.1057456
- Fernando de Goes and Alonso Martinez. 2019. Mesh wrap based on affine-invariant coordinates. In ACM SIGGRAPH 2019 Talks (SIGGRAPH '19). Association for Computing Machinery, New York, NY, USA, Article 4, 1–2. DOI:https://doi.org/10.1145/3306307.3328162
- Mullen, P., De Goes, F., Desbrun, M., Cohen-Steiner, D. and Alliez, P. (2010), Signing the Unsigned: Robust Surface Reconstruction from Raw Pointsets. Computer Graphics Forum, 29: 1733–1741. doi: 10.1111/j.1467-8659.2010.01782.x 
- Wardetzky, M., Mathur, S., Kaelberer, F., & Grinspun, E. (2007). Discrete Laplace operators: No free lunch. In Geometry Processing. The Eurographics Association.
- Kohlbrenner, M., Finnendahl, U., Djuren, T., & Alexa, M. (2021). Gauss Stylization: Interactive Artistic Mesh Modeling based on Preferred Surface Normals. Computer Graphics Forum.
- Hsueh-Ti Derek Liu, & Alec Jacobson. (2021). Normal-Driven Spherical Shape Analogies. 

### Signed Distance Fields
- Hart, J. Sphere tracing: a geometric method for the antialiased ray tracing of implicit surfaces. The Visual Computer 12, 527–545 (1996). https://doi.org/10.1007/s003710050084
- M. W. Jones, J. A. Baerentzen and M. Sramek, "3D distance fields: a survey of techniques and applications," in IEEE Transactions on Visualization and Computer Graphics, vol. 12, no. 4, pp. 581-599, July-Aug. 2006, doi: 10.1109/TVCG.2006.56.
- Sarah F. Frisken, Ronald N. Perry, Alyn P. Rockwood, and Thouis R. Jones. 2000. Adaptively sampled distance fields: a general representation of shape for computer graphics. In Proceedings of the 27th annual conference on Computer graphics and interactive techniques (SIGGRAPH '00). ACM Press/Addison-Wesley Publishing Co., USA, 249–254. DOI:https://doi.org/10.1145/344779.344899
- T. Bastos and W. Celes, "GPU-accelerated Adaptively Sampled Distance Fields," 2008 IEEE International Conference on Shape Modeling and Applications, 2008, pp. 171-178, doi: 10.1109/SMI.2008.4547967.

### Procedural Generation
- Yoav I. H. Parish and Pascal Müller. 2001. Procedural modeling of cities. In Proceedings of the 28th annual conference on Computer graphics and interactive techniques (SIGGRAPH '01). Association for Computing Machinery, New York, NY, USA, 301–308. DOI:https://doi.org/10.1145/383259.383292
- Guoning Chen, Gregory Esch, Peter Wonka, Pascal Müller, and Eugene Zhang. 2008. Interactive procedural street modeling. ACM Trans. Graph. 27, 3 (August 2008), 1–10. DOI:https://doi.org/10.1145/1360612.1360702

### Shading
- Barla, P., Thollot, J., & Markosian, L. (2006). X-Toon: An extended toon shader. In International Symposium on Non-Photorealistic Animation and Rendering (NPAR'06). ACM.
- Snyder, J. (1996). Area Light Sources for Real-Time Graphics.
- Eric Heitz, Jonathan Dupuy, Stephen Hill, and David Neubelt. 2016. Real-time polygonal-light shading with linearly transformed cosines. ACM Trans. Graph. 35, 4, Article 41 (July 2016), 8 pages. DOI:https://doi.org/10.1145/2897824.2925895
  