+++
title = "AR image generation using view-dependent geometry modification and texture mapping"
date = 2015-06-01
authors = ["Yuta Nakashima", "Yusuke Uno", "Norihiko Kawai", "Tomokazu Sato", "Naokazu Yokoya"]
publication_types = ["2"]
abstract = "Augmented reality (AR) applications often require virtualized real objects, i.e., virtual objects that are built based on real objects and rendered from an arbitrary viewpoint. In this paper, we propose a method for real object virtualization and AR image generation based on view-dependent geometry modification and texture mapping. The proposed method is a hybrid of model- and image-based rendering techniques that uses multiple input images of the real object as well as the object’s three-dimensional (3D) model obtained by an automatic 3D reconstruction technique. Even with state-of-the-art technology, the reconstructed 3D model’s accuracy can be insufficient, resulting in such visual artifacts as false object boundaries. The proposed method generates a depth map from a 3D model of a virtualized real object and expands its region in the depth map to remove the false object boundaries. Since such expansion reveals the background pixels in the input images, which is particularly undesirable for AR applications, we preliminarily extract object regions and use them for texture mapping. With our GPU implementation for real-time AR image generation, we experimentally demonstrated that using expanded geometry reduces the number of required input images and maintains visual quality."
featured = false
publication = "*Virtual Reality*"
tags = ["Augmented reality", "Free-viewpoint image generation", "View-dependent geometry modification", "View-dependent texture mapping"]
url_pdf = "https://doi.org/10.1007/s10055-015-0259-3"
doi = "10.1007/s10055-015-0259-3"
+++

