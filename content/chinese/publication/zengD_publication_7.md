+++
abstract = "We present an approach to simultaneously solve the two problems of face alignment and 3D face reconstruction from an input 2D face image of arbitrary poses and expressions. The proposed method iteratively and alternately applies two sets of cascaded regressors, one for updating 2D landmarks and the other for updating reconstructed poseexpression-normalized (PEN) 3D face shape. The 3D face shape and the landmarks are correlated via a 3D-to-2D mapping matrix. In each iteration, adjustment to the landmarks is firstly estimated via a landmark regressor, and this landmark adjustment is also used to estimate 3D face shape adjustment via a shape regressor. The 3D-to-2D mapping is then computed based on the adjusted 3D face shape and 2D landmarks, and it further refines the 2D landmarks. An effective algorithm is devised to learn these regressors based on a training dataset of pairing annotated 3D face shapes and 2D face images. Compared with existing methods, the proposed method can fully automatically generate PEN 3D face shapes in real time from a single 2D face image and locate both visible and invisible 2D landmarks. Extensive experiments show that the proposed method can achieve the state-of-the-art accuracy in both face alignment and 3D face reconstruction, and benefit face recognition owing to its reconstructed PEN 3D face shapes."
abstract_short = ""
date = "2016-10-01"
image_preview = ""
math = false
publication = "Proceedings of the 14th European Conference on Computer Vision (ECCV), Amsterdam, The Netherlands, October 2016"
publication_short = "ECCV2016"
selected = true
title = "Joint Face Alignment and 3D Face Reconstruction"
url_code = ""
url_dataset = ""
url_pdf = "https://www.danzeng.org/publications/2016ECCV.pdf"
url_project = ""
url_slides = ""
url_video = ""
[[authors]]
	name = "Feng Liu"

[[authors]]
	name = "Dan Zeng"

[[authors]]
	name = "Qijun Zhao"

+++