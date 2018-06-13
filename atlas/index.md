---
layout: default
title: Atlases
permalink: /atlases/
order: 5
---

General introduction:
---

Below introduces a white matter atlas containing 800 fiber clusters (FCs) generated from 100 Human Connectome Project (HCP) subjects provided by the O'Donnell Research Group (ORG).

-- ORG-800FC-100HCP

* An anatomically curated white matter atlas to enable consistent white matter tract parcellation across different populations (Zhang, et al, 2018).
* Including information from 100 subjects (healthy adults from the [Human Connectome Project](https://www.humanconnectome.org)).
* Leveraging a well-established data-driven fiber clustering pipeline via the [whitematteranalysis](http://github.com/SlicerDMRI/whitematteranalysis) package, including groupwise tractography registration (O’Donnell et al., 2012) and groupwise spectral clustering of tractography (O’Donnell and Westin, 2007; O’Donnell et al., 2017).
* A total of 256 white matter structures are annotated in the proposed atlas, including 58 deep white matter tracts, plus 198 short and medium range superficial fiber clusters, plus potential false positive connections.
* First Glance:
	- Whole brain fiber cluster atlas (800 fiber clusters)
      <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLww-JBrXO084AJN_nEZI838rFzwCaWGTY&index=0" frameborder="0" allowfullscreen="1" showinfo="1" rel="0"></iframe>
    - Annotated anatomical fiber tracts (58 deep white matter tracts and 198 superficial fiber clusters organized into 16 categories according to the brain lobes they connect)
      <iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLww-JBrXO084AJN_nEZI838rFzwCaWGTY&index=1" frameborder="0" allowfullscreen="1" showinfo="2" rel="0"></iframe>

Usage:
---
* Atlas download and visualization: 
	* For initially viewing the atlas, the minimal software dependency is needed (Only [Python 2.7.X](https://www.python.org/downloads/)).
	* Instructions for downloading and visualizing the atlas can be found [here](https://github.com/SlicerDMRI/ORG-Atlases#org-atlases).
	

* Subject-specific tractography parcellation:
	* This allows the users to apply the atlas to perform white matter parcellation on their own tractography data.
	* For this aim, the atlas needs to be used along with the computation tools provided in the [whitematteranalysis](http://github.com/SlicerDMRI/whitematteranalysis) package. (Make sure install whitematteranalysis first, following the instructions [here](https://github.com/SlicerDMRI/whitematteranalysis#whitematteranalysis)).
	* The atlas can also be downloaded via whitematteranalysis, following the instructions [here](<https://github.com/SlicerDMRI/whitematteranalysis/wiki/2b)-Downloading-a-Preprovided-Anatomically-Curated-Parcellation-Atlas>).
	* Instructions for applying the downloaded atlas for subject-specific tractography parcellation can be found [here](<https://github.com/SlicerDMRI/whitematteranalysis/wiki/2c)-Running-the-Clustering-Pipeline-to-Cluster-a-Single-Subject-from-the-Atlas>). 


References
---
- (Zhang, et al, 2018) Zhang, F., Wu, Y., Norton, I., Rathi, Y., Makris, N., O’Donnell, L.J., 2018. An anatomically curated fiber clustering white matter atlas for consistent white matter tract parcellation across the lifespan. NeuroImage, 2018.
- (O’Donnell et al., 2017) O’Donnell, L. J., Suter, Y., Rigolo, L., Kahali, P., Zhang, F., Norton, I., Albi, A., Olubiyi, O., Meola, A., Essayed, W. I., Unadkat, P., Ciris, P. A., Wells III, W. M., Rathi, Y., Westin, C.-F., Golby, A. J., 2017. Automated white matter fiber tract identification in patients with brain tumors. NeuroImage: Clinical 13, 138–153.
- (O’Donnell et al., 2012) O’Donnell, L. J., Wells III, W. M., Golby, A. J., Westin, C.-F., 2012. Unbiased groupwise registration of white matter tractography. In: International Con- ference on Medical Image Computing and Computer-Assisted Intervention (MICCAI). pp. 123–130.
- (O’Donnell and Westin, 2007) O’Donnell, L. J., Westin, C.-F., 2007. Automatic tractography segmentation using a high-dimensional white matter atlas. IEEE Transactions on Medical Imaging 26 (11), 1562–1575.

