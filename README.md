# Multi-Object-Tracking-Paper-List
Multi-object tracking is a deeply explored computer version problem. This is a paper list for multi-object-tracking.
## Datasets
[PETS2009](http://www.cvg.reading.ac.uk/PETS2009/a.html) : An old dataset.<br>
[KITTI-Tracking](http://www.cvlibs.net/datasets/kitti/eval_tracking.php) : multi-person or multi-car tracking dataset.<br>
[MOT dataset](https://motchallenge.net/) : A dataset for multi-person detection and tracking, mostly used.<br>
[UA-DETRAC](http://detrac-db.rit.albany.edu/) : A dataset for multi-car detection and tracking. <br>
## Evaluation Metric
**CLEAR MOT** : Bernardin, K. & Stiefelhagen, R. "Evaluating Multiple Object Tracking Performance: The CLEAR MOT Metric" [[paper]](https://cvhci.anthropomatik.kit.edu/images/stories/msmmi/papers/eurasip2008.pdf)<br>
**IDF1** : Ristani, E., Solera, F., Zou, R., Cucchiara, R. & Tomasi, C. "Performance Measures and a Data Set for Multi-Target, Multi-Camera Tracking" [[paper]](https://users.cs.duke.edu/~ristani/bmtt2016/ristani2016MTMC.pdf)<br>
## Open Source
### Batch
**IOU** : E. Bochinski, V. Eiselein, T. Sikora. "High-Speed Tracking-by-Detection Without Using Image Information" [[paper]](http://elvera.nue.tu-berlin.de/files/1517Bochinski2017.pdf) [[code]](https://github.com/bochinski/iou-tracker/) In International Workshop on Traffic and Street Surveillance for Safety and Security at IEEE AVSS 2017, 2017. <br>
**NMGC-MOT** Andrii Maksai, Xinchao Wang, Franc¸ois Fleuret, and Pascal Fua "Non-Markovian Globally Consistent Multi-Object Tracking
" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Maksai_Non-Markovian_Globally_Consistent_ICCV_2017_paper.pdf)[[code]](https://github.com/maksay/ptrack_cpp) In ICCV 2017<br>
**D2T** Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman, "Detect to Track and Track to Detect" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Feichtenhofer_Detect_to_Track_ICCV_2017_paper.pdf) [[code]](https://github.com/feichtenhofer/Detect-Track) In ICCV 2017<br>
**H2T** : Longyin Wen, Wenbo Li, Junjie Yan, Zhen Lei, Dong Yi, Stan Z. Li. "Multiple Target Tracking Based on Undirected Hierarchical Relation Hypergraph," [[paper]](http://www.cbsr.ia.ac.cn/users/lywen/papers/CVPR2014_HyperGraphMultiTargetsTracker.pdf) [[code]](http://www.cbsr.ia.ac.cn/users/lywen/) IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2014.<br>
**LDCT** : F. Solera, S. Calderara, R. Cucchiara "Learning to Divide and Conquer for Online Multi-Target Tracking" [[paper]](http://ieeexplore.ieee.org/document/7410854/) [[code page 1]](https://github.com/francescosolera/LDCT) [[code page 2]](http://imagelab.ing.unimore.it/imagelab/researchActivity.asp?idActivity=09) In Proceedings of International Converence on Computer Vision (ICCV), Santiago Cile, Dec 12-18, 2015<br>
**CEM** : Anton Milan, Stefan Roth, Konrad Schindler "Continuous Energy Minimization for Multi-Target Tracking" [[paper]](http://www.milanton.de/files/pami2014/pami2014-anton.pdf) [[code]](http://www.milanton.de/contracking/) in pami 2014<br>
**OPCNF** : Chari, Visesh and Lacoste-Julien, Simon and Laptev, Ivan and Sivic, Josef "On Pairwise Costs for Network Flow Multi-Object Tracking" [[paper]](https://arxiv.org/abs/1408.3304) [[code]](http://www.di.ens.fr/willow/research/flowtrack/) In CVPR 2015<br>
**KSP** : J. Berclaz, F. Fleuret, E. Türetken and P. Fua "Multiple Object Tracking using K-Shortest Paths Optimization" [[paper]](https://cvlab.epfl.ch/files/content/sites/cvlab2/files/publications/publications/2011/BerclazFTF11.pdf) [[code]](https://cvlab.epfl.ch/software/ksp)  IEEE Transactions on Pattern Analysis and Machine Intelligence, 2011.<br>
**GMCP** : Amir Roshan Zamir, Afshin Dehghan, and Mubarak Shah "GMCP-Tracker: Global Multi-object Tracking Using Generalized Minimum Clique Graphs" [[paper]](http://crcv.ucf.edu/papers/eccv2012/GMCP-Tracker_ECCV12.pdf) [[code]](http://crcv.ucf.edu/projects/GMCP-Tracker/) European Conference on Computer Vision (ECCV), 2012.<br>
### Online
**MOT-RNN** : Anton Milan, Seyed Hamid Rezatofighi, Anthony Dick, Konrad Schindler, Ian Reid "Online Multi-target Tracking using Recurrent Neural Networks"[[paper]](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking.pdf) [[code]](https://bitbucket.org/amilan/rnntracking) In AAAI 2017.<br>
**DeepSort** : Wojke, Nicolai and Bewley, Alex and Paulus, Dietrich "Simple Online and Realtime Tracking with a Deep Association Metric" [[paper]](https://arxiv.org/abs/1703.07402) [[code]](https://github.com/nwojke/deep_sort) In ICIP 2017<br>
**Sort** : Bewley, Alex and Ge, Zongyuan and Ott, Lionel and Ramos, Fabio and Upcroft, Ben "Simple Online and Realtime Tracking"[[paper]](https://arxiv.org/abs/1602.00763) [[code]](https://github.com/abewley/sort) In ICIP 2016.<br>
**MDP** : Yu Xiang, Alexandre Alahi, and Silvio Savarese "Learning to Track: Online Multi-Object Tracking by Decision Making
" [[paper]](http://openaccess.thecvf.com/content_iccv_2015/papers/Xiang_Learning_to_Track_ICCV_2015_paper.pdf) [[code]](http://cvgl.stanford.edu/projects/MDP_tracking/) In International Conference on Computer Vision (ICCV), 2015 <br>
**CMOT** : S. H. Bae and K. Yoon. "Robust online multi-object tracking based on tracklet confidence and online discriminative appearance learning" [[paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Bae_Robust_Online_Multi-Object_2014_CVPR_paper.pdf) [[code]](https://cvl.gist.ac.kr/project/cmot.html) In CVPR 2014<br> 
**RCMSS** : Mohamed A. Naiel1, M. Omair Ahmad, M.N.S. Swamy, Jongwoo Lim, and Ming-Hsuan Yang "Online Multi-Object Tracking Via 
Robust Collaborative Model and Sample Selection"[[paper]](https://users.encs.concordia.ca/~rcmss/include/Papers/CVIU2016.pdf) [[code]](https://users.encs.concordia.ca/~rcmss/) Computer Vision and Image Understanding 2016 <br>
**MHT-DAM** : Chanho Kim, Fuxin Li, Arridhana Ciptadi, James M. Rehg "Multiple Hypothesis Tracking Revisited"[[paper]](https://www.cc.gatech.edu/~ckim314/papers/MHTR_ICCV2015.pdf) [[code]](rehg.org/mht/) In ICCV 2015<br>
**OMPTTH** : Jianming Zhang, Liliana Lo Presti and Stan Sclaroff, "Online Multi-Person Tracking by Tracker Hierarchy," [[paper]]() [[code]](http://cs-people.bu.edu/jmzhang/tracker_hierarchy/Tracker_Hierarchy.htm) Proc. Int. Conf. on Advanced Video and Signal Based Surveillance (AVSS), 2012.<br>
**SMOT** : C. Dicle, O. Camps, M. Sznaier. "The Way They Move: Tracking Targets with Similar Appearance" [[paper]](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Dicle_The_Way_They_2013_ICCV_paper.pdf) [[code]](https://bitbucket.org/cdicle/smot) In ICCV, 2013.<br>
**HAF** : Ju, Jaeyong, et al. "Online Multi-Object Tracking based on Hierarchical Association Framework." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition Workshops. 2016. [[paper]](http://openaccess.thecvf.com/content_cvpr_2016_workshops/w20/papers/Ju_Online_Multi-Object_Tracking_CVPR_2016_paper.pdf) In CVPR, 2016w<br>
**RAN** : Fang K, Xiang Y, Savarese S. Recurrent Autoregressive Networks for Online Multi-Object Tracking[J]. arXiv preprint arXiv:1711.02741, 20 [[paper]](https://arxiv.org/pdf/1711.02741.pdf) In WACV 2018<br>
## Private Detection
**POI** : F. Yu, W. Li, Q. Li, Y. Liu, X. Shi, J. Yan. "POI: Multiple Object Tracking with High Performance Detection and Appearance Feature" [[paper]](https://arxiv.org/pdf/1610.06136.pdf) [[detection]](https://drive.google.com/open?id=0B5ACiy41McAHMjczS2p0dFg3emM) In BMTT, SenseTime Group Limited, 2016<br>
## New papers
### CVPR2017
Eldar Insafutdinov, Mykhaylo Andriluka, Leonid Pishchulin, Siyu Tang, Evgeny Levinkov, Bjoern Andres, Bernt Schiele "Art Track: Articulated Multi-Person Tracking in the Wild" [[paper]](https://arxiv.org/abs/1612.01465)<br>
Manmohan Chandraker, Paul Vernaza, Wongun Choi, Samuel Schulter "Deep Network Flow for Multi-Object Tracking" [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Schulter_Deep_Network_Flow_CVPR_2017_paper.pdf)<br>
Jeany Son, Mooyeol Baek, Minsu Cho, and Bohyung Han, "Multi-Object Tracking with Quadruplet Convolutional Neural Networks" [[paper]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Son_Multi-Object_Tracking_With_CVPR_2017_paper.pdf)<br>
### ICCV2017
A. Sadeghian, A. Alahi, S. Savarese, Tracking The Untrackable: Learning To Track Multiple Cues with Long-Term Dependencies [[paper]](https://arxiv.org/abs/1701.01909)<br>
Andrii Maksai, Xinchao Wang, Franc¸ois Fleuret, and Pascal Fua "Non-Markovian Globally Consistent Multi-Object Tracking
" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Maksai_Non-Markovian_Globally_Consistent_ICCV_2017_paper.pdf)[[code]](https://github.com/maksay/ptrack_cpp)<br>
Christoph Feichtenhofer, Axel Pinz, Andrew Zisserman, "Detect to Track and Track to Detect" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Feichtenhofer_Detect_to_Track_ICCV_2017_paper.pdf) [[code]](https://github.com/feichtenhofer/Detect-Track)<br>
Qi Chu, Wanli Ouyang,  Xiaogang Wang, Bin Liu, Nenghai Yu "Online Multi-Object Tracking Using CNN-Based Single Object Tracker With Spatial-Temporal Attention Mechanism" [[paper]](http://openaccess.thecvf.com/content_ICCV_2017/papers/Chu_Online_Multi-Object_Tracking_ICCV_2017_paper.pdf)<br>

